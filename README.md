# gaikwad_nellis_reproduction
 Revised Reproduction Package for Gaikwad and Nellis (2021) 
 
`revised_reproduction_package_for_gaikwad_nellis(2021)` contains all the files for the reproduction package. 
- `dataverse_files` is the folder with the data sets and code required to produce the tables and figures in the main paper and online appendix.
  - `supplementary-information` contains the code for cleaning the data and producing all the tables and figures in the main paper and online appendix.
    - In order to run the file, we had to make the following changes to the `supplementary_information` file as well as two associated data sets: 
      - Remove kableExtra from package installation and install separately after installing "systemfonts" binary version (reflected in the version history of the `supplementary_information` file).
      - Install `hutilscpp` package to make the `squish` function work.
      - Make sure to comment out any install.package commands before running.
      - Fix unicode errors (U+2032) and (U+2212) in `exhibit-registration-worldwide.xlsx` and `exhibit-literature-review.xlsx` to prevent LaTeX compilation errors. 
      - Fix "squish" function in the following way: `t1_experiment_df %,>% mutate(b_income_000_OUTLIER_FIXED = (squish(t1_experiment_df$b_income, a = 1000, b = 30000)/1000), b_income_000 = b_income/1000)`

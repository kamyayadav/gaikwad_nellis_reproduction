Readme for:

"Overcoming the Political Exclusion of Migrants: Theory and Experimental Evidence from India"

Nikhar Gaikwad, Columbia University
Gareth Nellis, University of California, San Diego

April 2021

# Contents

- supplementary-information.Rmd: Script to generate tables, figures, and appendix
- supplementary-information.pdf: Pdf output that results from running supplementary-information.Rmd 
- data-csds-delhi-2015.csv: Data to produce Online Appendix Table A18; recoded variables based on proprietary data from the Centre for the Study of Developing Societies
- data-election-results.csv: Data to produce Online Appendix Figure A13
- data-ihds2.csv: Data to produce results in Online Appendix Section E; original data available from https://www.icpsr.umich.edu/web/DSDR/studies/36151
- data-processing-times.csv: Data to produce results in Online Appendix Section P
- data-t1-experiment-df.Rds: Field experiment data, treatment 1
- data-t2-experiment-df.Rds: Field experiment data, treatment 2
- data-wvs-voter-turnout.xlsx: Data to produce Online Appendix Table A2
- exhibit-delhi-voting-patterns.xlsx: Data to produce Online Appendix Table A40
- exhibit-ihds2-vars.xlsx: Data to produce Online Appendix Table A17
- exhibit-indexes.xlsx: Data to produce Online Appendix Table A25
- exhibit-literature-review.xlsx: Data to produce Online Appendix Table A3
- exhibit-registration-worldwide.xlsx: Data to produce Online Appendix Table A1
- exhibit-survey-questions.xlsx: Data to produce Online Appendix Table A24
- irb-columbia: IRB approval notice, Columbia University
- irb-morsel: IRB approval notice, Morsel Research and Development
- irb-ucsd: IRB approval notice, University of California, San Diego
- pic-del-map.pdf: Data to produce Online Appendix Figure A14
- pic-fieldteam.png: Data to produce Online Appendix Figure A3
- pic-form-6-p1.pdf: Data to produce Online Appendix Figure A1
- pic-form-6-p2.pdf: Data to produce Online Appendix Figure A1
- pic-form-7-p1.pdf: Data to produce Online Appendix Figure A2
- pic-form-7-p2.pdf: Data to produce Online Appendix Figure A2
- pic-luc-map.pdf: Data to produce Online Appendix Figure A15
- pic-offices.png: Data to produce Online Appendix Figure A4
- pic-t2-block-design.pdf: Data to produce Online Appendix Figure A9
- pic-t2-email.pdf: Data to produce Online Appendix Figure A7
- pic-t2-letter.pdf: Data to produce Online Appendix Figure A6
- pic-t2-whatsapp.pdf: Data to produce Online Appendix Figure A8
- pic-voter-id.png": Data to produce Online Appendix Figure A5

# Instructions for running the code

- Open supplementary-information.Rmd in RStudio.
- Click "Knit" to compile to pdf. This will produce the tables and figures for the main text, as well as the online appendix.
- Alternatively, click "Run all code chunks" to produce the results in the R environment.

# R packages

All analysis was performed in R version 4.0.5 (2021-03-31), running under Windows 10 x64 (build 19041). 

The following R packages were employed to generate the results:

 [1] knitr_1.31           
 [2] gridExtra_2.3        
 [3] splitstackshape_1.4.8
 [4] lubridate_1.7.10     
 [5] ggthemes_4.2.4       
 [6] scales_1.1.1         
 [7] ggpubr_0.4.0         
 [8] car_3.0-10           
 [9] carData_3.0-4        
[10] lfe_2.8-6            
[11] Matrix_1.3-2         
[12] stargazer_5.2.2      
[13] rio_0.5.26           
[14] magrittr_2.0.1       
[15] kableExtra_1.3.4     
[16] forcats_0.5.1        
[17] stringr_1.4.0        
[18] dplyr_1.0.5          
[19] purrr_0.3.4          
[20] readr_1.4.0          
[21] tidyr_1.1.3          
[22] tibble_3.1.0         
[23] ggplot2_3.3.3        
[24] tidyverse_1.3.0      
[25] DeclareDesign_0.26.0 
[26] estimatr_0.30.2      
[27] fabricatr_0.14.0     
[28] randomizr_0.20.0     
[29] tinytex_0.31  
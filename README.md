# SOCCER22
This repository contains all relevant scripts from the research project **"Success-Score in Professional Soccer – Is there a sweet spot in the analysis of space and ball control?"** by me David Brinkjans and my fellow colleagues. This project was part of my work at the Institute of Exercise Training and Sport Informatics at the German Sport University Cologne. <br>

Data can unfortunately not be made publicly available. Please be aware that the code does not work without the correct data within a folder structure that resembles the one used within these scripts. An adaptation of the code to similar data should be possible with basic Python skills based on my comments. <br>

Success-Scores have been calculated via SOCCER© - a match analysis tool developed by Jürgen Perl (Perl et al., 2013). An implementation of the Success-Score via Python or similar programming languages is also possible based on the formula provided in the manuscript and will be included in the future. <br>
Data was made available to us in the required format, so this repository will not include any data parsing steps that would parse position data into the SOCCER©-format. The parsing procedures required are available in the repository for the more recent project SOCCER23 (https://github.com/DavidB1999/SOCCER23). Feel free to check that out as well. <br>


This folder contains the following Jupyter Notebooks: <br>

*01_txt_to_csv.ipynb* -  converting the Success-Score data from txt to csv and into an format that is easier to handle <br>

*02_minus_to_zero.ipynb* -  converting all Success-Scores <0 to 0 <br>

*03_percentile_calculation.ipynb* - sorting into percentile groups <br>

*04_goals.ipynb* - distribute goals into the associated percentile groups <br>

*05_Kendall.iypnb* - Kendall's tau on goals in 8 percentile groups <br>

*05_MWU.ipynb* - Chi-square test on goals above and below the $80^{th}$ percentile <br>

*06_Visualization.ipynb* - Visualization <br>

*06_Descriptives.ipynb* -  Descriptive statistics <br>



The prefix number indicates the order dependency of the code within it. Running a file prefixed with 02 before all 01 files will most likely cause an error. Files with the same prefix can be run independently  from each other. <br>

For some context on the project check out my first publication on the Success-Score. I learned a lot since then though :D <br>
DOI: https://doi.org/10.2478/ijcss-2022-0009 <br>

You can also check out the original paper: <br>
DOI: https://doi.org/10.1515/ijcss-2017-0005 <br>


The publication, the product of this code, will be linked here as soon as it is published: 

Feel free to reach out to me if there are any questions left. <br>

### References:
Brinkjans, D., Memmert, D., Imkamp, J., & Perl, J. (2022). Success-Score in Professional Soccer – Validation of a Dynamic Key Performance Indicator Combining Space Control and Ball Control within Goalscoring Opportunities. International Journal of Computer Science in Sport, 21(2), 32–42. https://doi.org/10.2478/ijcss-2022-0009 <br>
Perl, J., Grunz, A., Memmert, D., & Gutenberg-University, J. (2013). Tactics Analysis in Soccer – An Advanced Approach. International Journal of Computer Science in Sport, 12. <br>
Perl, J., & Memmert, D. (2017). A Pilot Study on Offensive Success in Soccer Based on Space and Ball Control – Key Performance Indicators and Key to Understand Game Dynamics. International Journal of Computer Science in Sport, 16(1), 65–75. https://doi.org/10.1515/ijcss-2017-0005 <br>




# Stack Overflow Analysis
This repo contains a Jupyter Notebook analysis examining programming language preferences in the United States over the last five years. The analysis is based on data from the stack overflow developer survey.


## Table of Contents
1. [Installation](#installation)
2. [Project Motivations](#motivation)
3. [File Descriptions](#filedesc)
4. [Summary of Results](#summary)
5. [Licensing and Acknowledgements](#license)



## Installation <a name="installation"></a>
The code was written in Python 3 and uses the following additional libraries.

- numpy
- pandas
- matplotlib
- seaborn
- mlxtend
- sparklines
- base64
- requests
- time
- itertools
- io
- datetime
- IPython


## Project Motivations <a name='motivation'></a>
The intent behind this project is to help answer the following questions using Stack Overflow's developer survey results.

- How has use and interest in various programming languages changed from 2016 to 2020?
- Which languages have the most hype (2020 results)?
- How does language interest vary by each language in use and what insights can we gain (2020 results)?
- Which languages are most likely to be used together (2020 results)?


## File Descriptions <a name='filedesc'></a>

 |-Developer Programming Language Use and Interest.ipynb    
 |-README.md    
 |-2016 Stack Overflow Survey Responses.csv     
 |-survey_results_public_2017.csv   
 |-survey_results_public_2018.csv   
 |-survey_results_public_2019.csv   
 |-survey_results_public_2020.csv   
 |-READ_ME_-_The_Public_2016_Stack_Overflow_Developer_Survey_Results.txt    
 |-survey_results_schema_2017.csv   
 |-survey_results_schema_2018.csv   
 |-survey_results_schema_2019.csv   
 |-survey_results_schema_2020.csv

<br>

Due to GitHub storage limitations only the analytics notebook pertaining to the above questions has been provided in this repo. The csv files containing the stackoverflow data and schemas (as well as the 2016 schema readme .txt) can be downloaded here - https://insights.stackoverflow.com/survey.

In order to properly run the notebook, download the full dataset for years 2016 thru 2020 and extract to the same parent directory where notebook has been saved.


## Summary of Results <a name='summary'></a>
Discussion of results is available [here](https://peter-vladimirovich.medium.com/python-rust-php-or-perhaps-objective-c-a44748c0997a).

## Licensing and Acknowledgements <a name='license'></a>
Acknowledgements for the helpful sparkline and apriori/association rule mining libraries/documentation go to the respective authors of these libraries that can be found at:
- https://github.com/iiSeymour/sparkline-nb
- http://rasbt.github.io/mlxtend/

Also, an acknowledgement to Stack Overflow for making the data freely accessible. Data is licensed under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/1-0/).



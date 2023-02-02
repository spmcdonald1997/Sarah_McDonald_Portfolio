# Sarah_McDonald_Portfolio
Samples of current and previous data science and data analysis projects

### Analysis of 2019 COVID data using R
This is a snapshot of code written in R to assess statistical significance of mean age difference for 2019 COVID-19 survivors and deaths with a two tailed t-test. The full project and linked dataset can be found [here](https://spmcdonald1997.github.io/R_Project/)

### COVID-19 Vaccine Survey from Pew Research
Here is sample code I used to create a crosstabulation of survery respondents' view of the impact of the COVID-19 vaccine on the economy, and their overall feelings of the impact of science on society: 

pd.crosstab(pewdata.SC1_W83, pewdata.VACCECON_W83, normalize = 'index').round(2).reindex(['Mostly positive', 'Equal positive and negative effects','Mostly negative', 'Refused'])[['Help the economy a lot', 'Help the economy a little', 'Not make much of a difference', 'Refused']]

The full notebook is on my profile [here](https://github.com/spmcdonald1997/COVID-19-Vaccine-Analysis---Pew-Research/blob/main/Americans'%20view%20on%20COVID-19%20Vaccine%20Impact%20on%20U.S.%20Economy.ipynb)

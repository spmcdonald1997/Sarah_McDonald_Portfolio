# Sarah_McDonald_Portfolio
Samples of current and previous data science and data analysis projects

### Analysis of 2019 COVID data using R
This is a snapshot of code written in R to assess statistical significance of mean age difference for 2019 COVID-19 survivors and deaths with a two tailed t-test. The full project and linked dataset can be found [here](https://spmcdonald1997.github.io/R_Project/)
<img width="947" alt="Screen Shot 2023-02-02 at 3 23 06 PM" src="https://user-images.githubusercontent.com/119249664/216473752-1fbfd71d-1ca9-45d2-9429-8b3695d97651.png">


### COVID-19 Vaccine Survey from Pew Research
Here is sample code I used to create a crosstabulation of survery respondents' view of the impact of the COVID-19 vaccine on the economy, and their overall feelings of the impact of science on society: 
pd.crosstab(pewdata.SC1_W83, pewdata.VACCECON_W83, normalize = 'index').round(2).reindex(['Mostly positive', 'Equal positive and negative effects','Mostly negative', 'Refused'])[['Help the economy a lot', 'Help the economy a little', 'Not make much of a difference', 'Refused']]

<img width="788" alt="Screen Shot 2023-02-02 at 4 06 26 PM" src="https://user-images.githubusercontent.com/119249664/216478951-a6035776-0d4f-43fe-8d66-be16eac36caf.png">



The full notebook is on my profile [here](https://github.com/spmcdonald1997/COVID-19-Vaccine-Analysis---Pew-Research/blob/main/Americans'%20view%20on%20COVID-19%20Vaccine%20Impact%20on%20U.S.%20Economy.ipynb)

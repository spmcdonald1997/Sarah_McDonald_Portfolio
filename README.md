# Sarah_McDonald_Portfolio
Samples of current and previous data science and data analysis projects

### [R: Analysis of 2019 COVID data](https://spmcdonald1997.github.io/R_Project/)
- Analyzed 2019 COVID-19 infection information for death rate by country
- Cleaned data to account for missing values and values stored incorrectly 
- Computed statistical significance of mean age for COVID-19 deaths by gender and age
- This is a snapshot of code written in R to assess statistical significance of mean age difference for 2019 COVID-19 survivors and deaths with a two tailed t-test. 
<img width="947" alt="Screen Shot 2023-02-02 at 3 23 06 PM" src="https://user-images.githubusercontent.com/119249664/216473752-1fbfd71d-1ca9-45d2-9429-8b3695d97651.png">


### [Python: COVID-19 Vaccine Survey from Pew Research](https://github.com/spmcdonald1997/COVID-19-Vaccine-Analysis---Pew-Research/blob/main/Americans'%20view%20on%20COVID-19%20Vaccine%20Impact%20on%20U.S.%20Economy.ipynb)
- [Questionaire and materials provided by Pew Research] (https://github.com/spmcdonald1997/COVID-19-Vaccine-Analysis---Pew-Research/tree/main/W83_Feb21)
- Created analysis of American survey respondents' view on economic impact of COVID-19 vaccine using NumPy and Pandas using Pew Research published report
- Generated visualization of the survey results using Matplotlib
- Created crosstabulation of respondents' view of the impact of the COVID-19 vaccine on the economy, and their overall feelings of the impact of science on society: 
- Here is the sample code for the crosstabulation, and the table output:

pd.crosstab(pewdata.SC1_W83, pewdata.VACCECON_W83, normalize = 'index').round(2).reindex(['Mostly positive', 'Equal positive and negative effects','Mostly negative', 'Refused'])[['Help the economy a lot', 'Help the economy a little', 'Not make much of a difference', 'Refused']]

<img width="788" alt="Screen Shot 2023-02-02 at 4 06 26 PM" src="https://user-images.githubusercontent.com/119249664/216478951-a6035776-0d4f-43fe-8d66-be16eac36caf.png">
 

### [Tableau: Visualization of GDP and CO2 emissions for four sample countries:](https://public.tableau.com/shared/FPZGYJNKF?:display_count=n&:origin=viz_share_link)
- Created simple visualization of GDP and CO2 emissions on shared axis with sample data provided by Tableau Public
<img width="686" alt="Screen Shot 2023-02-02 at 2 44 32 PM" src="https://user-images.githubusercontent.com/119249664/216479164-f4ca5126-9ed6-4f14-9db9-89da91f41aac.png">



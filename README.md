# Sarah_McDonald_Portfolio
Samples of current and previous data science and data analysis projects

### COVID-19 Vaccine Survey from Pew Research
Here is sample code I used to create a crosstabulation of survery respondents' view of the impact of the COVID-19 vaccine on the economy, and their overall feelings of the impact of science on society: 
pd.crosstab(pewdata.SC1_W83, pewdata.VACCECON_W83, normalize = 'index').round(2).reindex(['Mostly positive', 'Equal positive and negative effects','Mostly negative', 'Refused'])[['Help the economy a lot', 'Help the economy a little', 'Not make much of a difference', 'Refused']]

The full notebook is on my profile here: Americans' view on COVID-19 Vaccine Impact on U.S. Economy.ipynb

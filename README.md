# Viral data science from October 2021

Here are some Python Jupyter data science notebooks from **October 2021** analyzing world COVID-19 data available from [Our World
in Data](https://ourworldindata.org/).

They are some of (the better) solutions produced by students as the first mini-project (out of three) in [P176M010 Advanced Machine Learning](https://admissions.ktu.edu/programme/m-artificial-intelligence-in-computer-science/#P176M010) course at [Kaunas University of Technology](https://ktu.edu/) [Faculty of Informatics](https://fi.ktu.edu/) given by [Mantas Lukoševičius](https://mantas.info/). 

Students had to come up with their own unique questions and answer them using the data. A solution template notebook was provided. A snapshot of the https://covid.ourworldindata.org/data/owid-covid-data.csv data from that time [is included](owid-covid-data.csv). Some of the solutions use additional sources of data.

*The notebooks are provided for reference and instruction with no warranty of any kind. They are in the state that they were submitted originally. They are anonymized if the author so desired. Some additional data needed to run them might not be easily shareable. For that you may contact the authors directly.*

## The Mini-Projects:
---

### [Author: Skirmantas Navickas](AML_MP1_Navickas.ipynb)

### Questions:

1. Compare average daily deaths in Europe's top 5 countries by GDP per person to Lowest 5.
2. How does the stringency index correlate with weekly daily new cases and new hospitalizations in Lithuania, Latvia, Estonia.
3. Can we predict Lithuania's future stringency index based on, daily new cases, daily deaths, and new hospitalizations historical data.

---
### [Author: Anonymous course participant 1](AML_MP1_Anon1.ipynb)

### Questions:
1. How did the crime rates change in Lithuania during the lockdowns? 
2. What is the correlation between covid cases and crime rates?
3. Is it possible to predict the crime rates based on covid cases?

### Additional data sources:
* https://www.ird.lt/lt/paslaugos/tvarkomu-valdomu-registru-ir-informaciniu-sistemu-paslaugos/nusikalstamu-veiku-zinybinio-registro-nvzr-atviri-duomenys-paslaugos/nvzr-nusikalstamumas-pagal-savivaldybes?year=2021&month=11&municipality=0
* https://open-data-ls-osp-sdg.hub.arcgis.com/datasets/ba35de03e111430f88a86f7d1f351de6_0/explore

---
### [Author: Yusef Savid](AML_MP1_Savid.ipynb)

### Questions:
1. Taking into account the last record of every country before vaccines were introduced, what pairs of additional/added features (Zinc deficiency, Hours of sunshine per year, Arrivals per country, Human freedom index and Global hunger index) and dependent variables (total cases, total deaths and others) have an R value higher than 0.2?
2. Taking into account global data, how does new daily cases and 'Covid 19 testing' google trends search interest correlate?
3. After building a regression model using the added features mentioned in the first question, does the RMSE of the model decrease?

### Additional data sources:
* Datasets on zinc and global hunger index: https://ourworldindata.org/micronutrient-deficiency
* Dataset on arrivals into countries: https://www.kaggle.com/ayushggarg/international-tourism-demographics?select=API_ST.INT.ARVL_DS2_en_csv_v2_1927083.csv 
* Dataset on Human freedom index: https://www.kaggle.com/gsutters/the-human-freedom-index
* Dataset on Sunshine duration per country:
https://en.wikipedia.org/wiki/List_of_cities_by_sunshine_duration
* Dataset on search interest results: https://trends.google.com/trends

---
### [Author: Anonymous course participant 2](AML_MP1_Anon2.ipynb)

### Questions:
1.When did the OECD countries that spend most on healthcare per capita in 2019 had vaccinated (with one dose) at least 70% of the population?
2.Does lower corruption in country correlates to percent of people vaccinated? (Europe)
3.Can we predict when certain percent of population is vaccinated in France?

### Additional data sources:
* OECD https://stats.oecd.org/Index.aspx?ThemeTreeId=9#
* CPI https://www.transparency.org/en/cpi/2020/table/nzl
https://opensource.stackexchange.com/questions/8372/use-of-creative-commons-licenses-by-an-anonymous-user    

---
### [Author: Deividas Tamkus](AML_MP1_Tamkus.ipynb)

### Questions:
1. Which 10 countries have the highest percentage of smokers?
2. How does the percentage of smokers correlate with covid mortality rate (total_deaths/total_cases)?
3. Can we predict the total deaths based on total cases and percentage of smokers?

### Additional data sources:
* https://ourworldindata.org/gender-ratio

---
### [Author: Indrė Segalovičiūtė](AML_MP1_Segaloviciute.ipynb)

### Questions:
1. What is the average percent of people who are unvaccinated, half vaccinated and fully vaccinated in 2021?
2. What is the correlation between vaccinated/not vaccinated and amount of covid cases in 2021?
3. Is it possible to predict the future prognosis of CODIV-19 cases based on vaccinations rates? 

---
### [Author: Marius Oliandra](AML_MP1_Oliandra.ipynb)

### Questions:
1. Compare the new daily cases growth difference of covid-19 in Asia and Europe continents (2021 January to 2021 September).
2. How does fully vaccinated people percentage corelate with daily mortality rate?
3. Is it possible to predict new hospitalized patients number by new cases smoothed per million and people vaccinated per hundred in Baltic states?

---
### [Author: Anonymous course participant 3](AML_MP1_Anon3.ipynb)

### Questions:
1. Ignoring countries that ever dropped below 0.9 HDI during the dates being analysed, how has the average percentage of male smokers changed in Europe in the 2nd month of 2020, compared to the 2nd month of 2021?
2. How does diabetes prevalence correlate with GDP per capita? Compare Europe to North America.
3. Can we predict the tests per case in Europe for countries with population higher than 5 million based on total cases, total deaths and stringency index?

---
### [Author: Mantas Arlauskas](AML_MP1_Arlauskas.ipynb)

### Questions:
1. Which 10 countries has the highest total number of people who received at least one vaccine dose per 100 people in the total population?
2. How does the share of the population living in extreme poverty correlate with covid mortality rate in different continents?
3. Predict what will be the percentage of people vaccinated in Lithuania after next 30 days.

---
### [Author: Rūta Buckiūnaitė](AML_MP1_Buckiūnaitė.ipynb)

### Questions:
1. Does higher % of tertiary educated population correlate with total vaccinations per hundred in Europe?
2. Did mandatory green pass in Lithuania affect the number of new cases and vaccinations?
3. Can we predict housing price changes in Lithuania based on COVID cases?

### Additional data sources:
* https://appsso.eurostat.ec.europa.eu/nui/submitViewTableAction.do
* https://osp.stat.gov.lt/informaciniai-pranesimai?articleId=9174198

---
### [Author: Anonymous course participant 4](AML_MP1_Anon4.ipynb)

### Questions:
1. Which month most people were vaccinated in Lithuania?
2. Is there correlation between new covid-19 cases in USA and Bitcoin price?
3. Is it possible to predict S&P500 index using new covid-19 cases and new vaccinated people count in USA or world?

### Additional data sources:
* BTC: https://finance.yahoo.com/quote/BTC-USD/history
* S&P500: https://www.marketwatch.com/investing/index/spx

---
### [Author: Titas Petravičius](AML_MP1_Petravicius.ipynb)

### Questions:
1. Compare and visualise which countries has the max/mean/min case-to-death ratio
2. How does population density and median age correlate with the case-to-death ratio?
3. Is it possible to predict that a new Covid wave is coming? 

---

## Acknowledgments

The course was aided by TAs: Lukas Stankevičius and Eglė Butkevičiūtė.

## License

The authors agreed to their work being published under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International license</a>. <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons licencija" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png"/></a> 

So is this intro summary by [Mantas Lukoševičius](https://mantas.info/).


![alt text](https://github.com/gorodnichy/iTrack-COVID/raw/master/docs/covid-48.png)


# [iTrack COVID](https://itrack.shinyapps.io/covid) Web App


## App Links:

To proceed, please select one of the following links:


- Coronavirus Daily Report - Canada:  [https://itrack.shinyapps.io/covid/daily-report-canada](https://itrack.shinyapps.io/covid/daily-report-canada.Rmd)
- Canada App: [https://itrack.shinyapps.io/covid/ca.Rmd](https://itrack.shinyapps.io/covid/ca.Rmd) 
- USA App: [https://itrack.shinyapps.io/covid/us.Rmd](https://itrack.shinyapps.io/covid/us.Rmd) 
- International App: [https://itrack.shinyapps.io/covid](https://itrack.shinyapps.io/covid) 

"This App provides LIVE updates on the situation with COVID-19 in Canada and other countries at the municipal level. The unique feature of the App is a fully automated *data science driven* approach for searching and identifying high-risk regions in the country. In addition, to searching by Total and New Cases, you can also search by Acceleration, which is change in new cases a day, and Growth Rate, also known as Reproduction Rate or Rt."


## Main features:

- The iTrack COVID App provides LIVE updates on the situation with COVID-19 in Canada, USA, and other countries around the globe, by merging  data from variety of sources: [Government of Canada](https://www.canada.ca/en/public-health/services/diseases/coronavirus-disease-covid-19/epidemiological-economic-research-data.html), [University of Toronto Coronavirus database](https://art-bd.shinyapps.io/covid19canada/),
[Johns Hopkins University Coronavirus database](https://coronavirus.jhu.edu) (additional databases can be added upon request)

- It computes multiple characteristics about the pandemic dynamics, such as pandemic Speed, Acceleration, and Growth, also known as Reproduction Rate or Rt, in addition to reporting the raw number of cases, reported elsewhere. In doing that, it checks the data for abnormalities and cleans the data were possible.  This makes it possible to report and compare results at more detailed geographic and time scale, such as at municipal level and for each day), as opposed to reporting combined results at a provincial level or larger period of time, as done elsewhere. 

- It can compute the regression model of the dynamic spread at municipal levels for all of the computed metrics, making it easier to see the trends and predict the future.

- It allows one to summarize the pandemic dynamics for the country or region graphically and in interactive tabular form  for the current day or any historical day, making it possible to efficiently compare it across municipalities. 

- Finally and  in critical distinction from other dashboards, it allows one to conduct a fully automated search of high risk areas in the country using  criteria measured from multiple pandemic dynamics characteristics.


## Backhground

With many open data-sets about COVID-19 and data science tools available, is the possible to build an Expert System that would help us to make decisions related to the risks associated with the spread of the pandemic in your community and around the globe? It was this question that drove the design of an interactive Web App, called iTrack COVID, available from: https://itrack.shinyapps.io/covid.

The App reads data from Statistics Canada, Johns Hopkins University Global Coronavirus database and University of Toronto Coronavirus database, and finds automatically the areas of highest risk, according to the selected criteria, such as: daily speed (new cases a day), acceleration (change in speed a day), mortality rate, and growth (aka reproduction) rate. 

As opposed to majority of other Apps and websites that report COVID statistics averaged over large regions (e.g., over entire province or country), [iTrack COVID App](https://itrack.shinyapps.io/covid) provides results at much finer scale - at municipality level. This can make a large difference for decision makers and residents of those municipalities, as it is very common that, while *in average* the province is improving, there are muicipalities where the situation is actually deteriorating. It is therefore very important  to identify those municipalities, so that appropriate measures can be undertaken there. And this is what [iTrack COVID App](https://itrack.shinyapps.io/covid)  does.


The App includes both local (city level) information for Canada and US, as well as global information for all countries around the globe, is compatible with mobile devices, and provides region specific URL short-cuts...


Read Full Article:  [https://www.linkedin.com/pulse/interactive-web-app-visualize-predict-spread-covid19-gorodnichy](https://www.linkedin.com/pulse/interactive-web-app-visualize-predict-spread-covid19-gorodnichy)


![](https://github.com/gorodnichy/iTrack-COVID/raw/master/docs/covid.png)

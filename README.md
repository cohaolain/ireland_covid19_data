# ireland_covid19_data

Data pulled from [here](https://www.gov.ie/en/news/7e0924-latest-updates-on-covid-19-coronavirus/).
Tableau dashboard [here](https://public.tableau.com/profile/andrew.maguire#!/vizhome/IrealndCovid19Data/Daily).
Blog post [here](https://andrewm4894.com/2020/03/23/ireland-covid19-data/).
 
## Notes: 
- 'txt_...' fields are numbers scraped from regex on the text of the press release. 
- all other numbers are scraped from the html tables in the press releases. 
- there seems to be some delay of a couple of days between the tables in the press releases and the numbers in the text.
- looks like some manual process generating the press releases so things may change and break.
- Two main tables are `daily_stats.csv` and `daily_stats_long.csv`, these are the main headline figures and any other daily metric in both a wide (column per metric) and long (row per metric) format. 
- Any changes, additions, questions, please feel free to raise an issue.
- Feel free to fork, change or use however you want.

## Useful Links:
- https://twitter.com/IrishDataViz - some great analysis and insights.
- http://gov.ie/covid19 - official portal for news from Irish government.
- https://github.com/datasets/covid-19 - a more international repository of data.
- https://github.com/CSSEGISandData/COVID-19 - most popular source by Johns Hopkins     

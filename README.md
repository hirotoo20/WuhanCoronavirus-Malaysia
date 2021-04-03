# WuhanCoronavirus-Malaysia
Statistics of Wuhan coronavirus (COVID-19) in Malaysia  
Summary is  
https://drxyzw.github.io/WuhanCoronavirus-Malaysia/  
  
## Case number analysis result is under /data folder.   
* Total  
    Nationwide total in Malaysia. The data is taken from Star online website.
  * totalRaw.csv - Raw data from Star online. Below data files are generated from this raw file.
  * dailyTotal.csv - Statistics of cumulative cases, deaths, recovered cases, and active cases. Cumulative cases are on confirmed basis.
  * dailyTotalChange.csv - Daily change of dailyTotal.csv.
  * dailyDynamics.csv - New cases vs cumulative cases. Any exponential growth is on y=x line.
  * latestTotal.csv - of cumulative cases, cumulative deaths, recovered and active cases. This shows composition on a pie chart.
* By state  
    Number for each state in Malaysia. The data is taken from Wikipedia until 26 Oct 2020, and from a blog of Health Director of Malaysia since 27 Oct 2020.
  * byStateRaw.csv - Raw data from Wikipedia. Below data files are generated from this raw file.
  * totalInfectedByStates.csv - Cumulative cases of each state. Cumulative cases are on confirmed basis.
  * newDailyInfectedByStates.csv - Daily change of totalInfectedByStates.csv.
  * byStateDynamics.csv - New cases vs cumulative cases. Any exponential growth is on y=x line.
## Rt (effective reproduction number) analysis is under /Rt/data folder.  
* [State name].csv - Rt of each state. Nationwide result is Malaysia.csv.
* Document is https://github.com/drxyzw/WuhanCoronavirus-Malaysia/tree/master/doc/Rt-Malaysia.ipynb


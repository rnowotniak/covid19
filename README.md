# covid19
Coronavirus spread analysis in Python, Jupyter and pandas

Active =  Confirmed - (Recovered + Deaths)

* Another dashboard for data comparison: https://app.powerbi.com/view?r=eyJrIjoiOGY4OWEwYzAtZTFjOC00N2JkLWI5Y2UtNjQxYjFhYzJmNTMzIiwidCI6ImY5YmQ2ZGY2LWM0NDktNDgxZi1hYmI1LTM3YmQwMzZiZWI3NiIsImMiOjl9


Data sources:
* https://github.com/CSSEGISandData/COVID-19
* Global confirmed catime series: https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv

Tools to reproduce and to rerun this analysis:

* docker pull jupyter/scipy-notebook
* docker run -p 8888:8888 -v "$PWD:/home/jovyan/work"   --rm jupyter/scipy-notebook

# covid_government

This repo serves to pull data for covid government response modelling.
It pulls live data from the Coronavirus Government Response Tracker (https://www.bsg.ox.ac.uk/research/research-projects/coronavirus-government-response-tracker), and the Our World in Data sources (https://ourworldindata.org/coronavirus-data ), adds democracy and free press indices from Freedom House (https://freedomhouse.org/report/freedom-world) and the Reporters withourt Borders(https://rsf.org/en/detailed-methodology)

* gov_action_data_prepapartion.ipynb is an Ipython notebok which compiles the analysis dataset. You need to run this if you want the latest case numbers 
* the analysis dataset is called 20200515_complete.csv, and is located with other, raw datasets in the /data folder
* statistical modeling is done in R, code is in the gov_analisys.Rmd file


This is very much work in progress. Code is released for reproducability. Any changes, suggestions are welcome.

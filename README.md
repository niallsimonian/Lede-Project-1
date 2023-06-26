Lede Project 1 : 'Where and When to Film in NYC'

In this project, I aimed to demostrate my ability to used python, with pandas, to read in a csv file and then scrape data from it. 
Additionaly, I aimed to get comfortable with DataWrapper as a first tool for data visualization 

In terms of findings, I discovered that Manhattan was the most popular location for film permits in NYC. In addition, winter is the least popular season for film permits. 

I aqquired the csv file for this data through NYC OpenData (https://data.cityofnewyork.us/City-Government/Film-Permits/tg4x-b46p). 
There was both an API and CSV route available, but- after playing around with the API for a while- I made the decision to use the csv file. 
Unfortunately, I could only find data from July, 2021 to July, 2023 on this site. I was unable to contact the MOME office, who manages film permits, despite a few calls and voicemails!
 
The data analysis process consisted of sorting the data by the date of the permit, so that I could eventually create the chart by season. I also converted some of the columnns from string types to data.time types. Then I eliminated the dates, leaving just the months and years. 
Furtermore, I created new data frames that only looked at the Borough column by using the drop() function in pandas, and then I used value.counts(), before exporting to new csv files.  

I grew the most during this project with regards to the visualization process, as I had no previous expierence with DataWrapper or any other similar program. In addition, I was able to make a small site on GitHub to display the project, which I will use in the future for subsequent projects. This was my first time actually using HTML, so again it was very valuable to put the lessons we've had into practice. 

I did not have access to data from earlier than July, 2021. If I had, I could have done a more elaborate analysis- and used more of a time graph instead of a column chart. I would also, with more time, look into the average length of each film shoot. 

-Niall Simonian
 

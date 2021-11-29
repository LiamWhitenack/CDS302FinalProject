# Converting Raw .csv Data into a Database file with NBA Statistics

*Liam Whitenack*  
*CDS 302 - Scientific Data and Databases*  
  
Those who study data Science are well aware that statistics have become the new bread and butter for perfecting anything. We live in the information age, and data has never been more easily accessible than it is right now. Because so much data is now available, many processes have been made much more efficient by the use of data analysis. Basketball is one of the many fields that data analysis is revolutionizing. Many people make a living off of developing opinions on game statistics and by watching games. Their information is often supplied to them by a website called cleaningtheglass.com. This website makes advanced statistics available and easier to interpret than the mainstream available data, but it charges a monthly fee for using the website. If the average NBA fan (like myself) wants to learn anything from statistics, I am mostly reliant on free websites. However, these websites are not able to answer some of the questions that I have, such as, "Does a high number of free throw attempts correlate to a high field goal percentage?" If I wanted to answer a question like this, I would have to use a program that was able to move statistics around very freely, ina  way that is not possible in most free websites.  

SQL is a free online data browser that allows a user to make new observations on data by mixing and matching different values and dataframes. If I was able to open NBA data in a program like SQL, I would be able to make all kinds of observations that were not possible with the static data online. Therefore, this project is developed to making a program that can make NBA data available in SQL.

## Retrieving NBA Data

It is likely that a great amount of NBA data could be made available with a little bit of web scraping, but this data could be easily accessed online at a site called advancedsportsanalytics.com/nba-raw-data. This site allows a use to download, for free, a 52 columns of NBA data during a set amount of time. 

## Drawing a Diagram of the Data

An ER diagram can be made to show the qualities of some of these tables:  

![ER_NBA](https://user-images.githubusercontent.com/78373945/143905829-7b7adbfa-df0a-42b7-957f-2fe9b57e4403.png)

All of the attributes of these tables are omitted because of how many different attributes would have to be included. Each one of the above entities and relationships are created in python, where they are then uploaded to SQL.


## Converting to SQL

A jupyter notebook is attatched that processes the NBA data, converts to several different tables, and then sends these tables to SQL to be processed there.

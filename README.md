

# Bitcoin Analysis

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiYmIyZmU3MGMtNmQxZC00N2RhLWFlMzYtM2ZiMzA1ZjRlNmFlIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9

## Problem Statement
 I wanted to start my project with first finding geniune problem that I can solve or contribute to solve, However while doing my research I was only able to find problems that were already pretty much solved or had been covered by someone else , to find something unique I thought  why don’t I look upon the impacts of problem that the world is facing then I came upon the idea of calculating the impact of  one the biggest pandemic covid-19 on the fastest growing financial sector the  crypto currency 


This dashboard shows the impact that BTC(USD) faced during its bear run of NOV 2021 - DEC 2022 through series of events that resulted in this bear run 

Since Bitcoin fell almost fell down by 75% this was no ordinary move it made on daily basis. This bizzare move by btc led many big tech company to file bankruputcy while also leading whole countries treasure to be halved 



### Data collection  

- Step 1 :  Decideing the time frame of BTC analysis
- Step 2 :  Using API KEY from coinmarket cap we fetced data using PYTHON's requests library for an API 
![Screenshot 2024-03-06 143950](https://github.com/Harry1sol/Bitcoin_2021/assets/162426151/f4ef697b-1417-4604-81af-8d9dfd1a73e0)
- Step 3 : After acquring the data coverting it to csv.file for further analysis via python code ![Screenshot (3)](https://github.com/Harry1sol/Bitcoin_2021/assets/162426151/26c5bc4e-f0f2-4c80-9046-dec2bca544a6)

- Step 4 : It was observed that in none of the columns errors & empty values were present 
- Step 5 : For calculating the reasons of BTC fall we webscrape various news aggregators headlines during the time period of NOV 21YY - DEC 22YY that could have led btc's downfall 
![Screenshot 2024-03-06 150030](https://github.com/Harry1sol/Bitcoin_2021/assets/162426151/5efd05e3-495e-46f9-9882-cb9246d7b5df)
- Step 6 : In the report view, 12 events were observed 
- Step 7 : Since the data only contains obsereved impact and not the actual percentage to calculate that we used a simple formula of percentage that is 
![Screenshot 2024-03-06 150647](https://github.com/Harry1sol/Bitcoin_2021/assets/162426151/99c427ee-da56-4b18-b193-fa06dc65d6f3)
  
which gave us these results ![Screenshot (13)](https://github.com/Harry1sol/Bitcoin_2021/assets/162426151/f3512dae-7d53-42ae-9463-5eaa23a8facb)                            

### Synthesize the Information: 
The next task was to put together all the information gathered to perform further analysis.
     
INFORMATION GATHERED 


- BTC Historical data NOV 21YY - DEC22YY 
- MAJOR EVENTS affecting bitcoin price



### Data cleaning
There were no major cleaning steps required as the data itself was imported through API'S only small maintaince on data was required 
while changing the data type  of columns and in some cases merging the columnn. 
NO blank space or nulls were recored during the gathering process




### Data Analysis
- Step 1 : Performing statistical analysis on BTC historical data on POWER bi 
- Step 2 : Identifying trends on data 
- Step 3 :  Finding correlations or patterns that shows the market movement aligning with the impact chart

### Visual Representation

- Step 1: Classifying correct data into right charts in order to build user friendly chart 
- step 2 : We started with btc historical data and putting it into line chart
- step 3 : Adding fileters and sliders to make it easy for the viewer to zoom in and zoom out 
- Step 4 : Adding "EVENT_CATORGARY" into legends of line chart which accurately matches with  the major price movements as suspected during our analysis 
- Step 5 : Adding column charts that indicates which events affected more on bitcoins price movements making it more convenient to spot difference between the percentage of price affected

### Key Takeaway 

- Voyager Digital files for bankruptcy on 2021-11-12:

Change from the day before to the day of the event: -1.22%

Change from the day of the event to the day after: 0.49%

- Celsius Network declares bankruptcy on 2021-12-12:

Change from the day before to the day of the event: 1.49%

Change from the day of the event to the day after: -6.71%

- FTX files for Chapter 11 bankruptcy on 2022-01-12:

Change from the day before to the day of the event: 2.84%

Change from the day of the event to the day after: -3.09%

- BlockFi files for Chapter 11 bankruptcy on 2022-02-12:

Change from the day before to the day of the event: -0.39%

Change from the day of the event to the day after: -0.11%

These percentage changes indicate the immediate market response to each event. While not all events lead to significant price movements, understanding these fluctuations helps analyze the market's sensitivity to news and external factors.


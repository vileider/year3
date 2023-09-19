Technical
LO3.9.1.5
Insight from data
Design, develop and evaluate a non-trivial big data analysis system.

All software can be made to give off data - whether that be performance statistics or user statistics of some kind.  Develop a system to analyse that and produce either a dashboard or another output that can be used to generate actionable advice.  Non-trivial means that it should do more than one thing you can learn in a single tutorial and use more than one type of data.  This should be able to be combined with any of the other technical learning outcomes that require development.


after a meeting with neil i uderstood more what is this outcome about. First I will do research for intersting data sources, and I will pick one that will be entertaing for me.

I think i will compare 4 main curencies, gold price, bitcoin price, oil price, 4 main curency coutrys debt.
my plan for the 1 stage is to establish framework nad set up software environment. 
stage 2 search for api that will allow to get information i need and succesfuly recive http request with proper data.
stage 3 display data in a most primitive way on a screen divied by month/day/year. 
stage 3 research for the easiest to implement graphic framework and learn it
stage 4 display data on the screen and compare them by using graphs.
stage 5 add ui and refeactor the code.

I meet with the students to "hash out design problems and strategy problems on an ongoing basis".
What we discussed problems that we might find:
What problem I want to solve?
What conclusion I  want to reach?
Do I want to predict something from the conclusion?
What tools you want to use?
How are we going to find the data source?
How I am  going to process the data?
How I Develop a system to analyse data?
How will I summarize the conclusion?
What type of output will I choose?
Will I export summarized findings from the extensive data analysis for evaluation by a relevant party?

After a research i found historical rates of gold, and curencies from
https://metalpriceapi.com
Oli Prices API
https://public.opendatasoft.com/explore/dataset/commodity-prices/api/

during stad up Neil suggested Pandas library using pytrhon

I have found a website that provides API but unfortunetelly i cant get to right database. Fortunatelly  this website provide csv files so there is way get data I need. 
https://www.imf.org/en/Data
I will focus on creating the backend and retrieving data from APIs and sending it to the frontend. After reconsidering my approach, I decided to use CSV files for my project.

After some struggles with asynchronously retrieving data from CSV files, I finally managed to display gold prices with dates on the screen. My next step will be to trim the excess and attempt to display just 2 CSV data files. The upcoming challenge is to standardize the format of the dates since I discovered that the two files have different date formats. It's worth noting that time constraints are pushing me to use non-trivial data in the most minimalistic way possible. I'm determined to finish this project by Friday. I will need to efficiently resolve these formatting issues and display both sets of data side by side.
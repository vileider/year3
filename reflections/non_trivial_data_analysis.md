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

I made a significant change in the project by switching to a library that processes CSV files and converts them into JSON format. I learned how to use this library from https://c2fo.github.io/fast-csv/docs/parsing/methods. I also developed a reusable function for asynchronous data processing. Additionally, I created a more structured API route in Next.js for this purpose. This change allows me to retrieve multiple CSV files more efficiently. Using the fetch function, I obtain the JSON data from the local API. My next step is to standardize the date format and implement a framework for displaying data in a chart.

I successfully integrated a React library based on D3 for creating charts. I learned how to add new data records to these charts and display them on the screen. In my research, I found that 'react-vis' was one of the easiest libraries to implement. I can find more detailed information on how to use it at https://github.com/uber/react-vis. Now I just need to map over the oil or gold array and create aray of objects and by react-vis display it. 

I successfully displayed oil and gold data on a chart, although the data required some minor adjustments before mapping it to the chart library. Ideally, this data modification should be done on the server side to save on performance, but I'm pleased that I managed to get it working within the time constraints. It took me two weeks to reach this point, during which I learned how to use 'react-vis,' which could be a valuable feature in future projects. Additionally, I took another step in understanding asynchronous JavaScript. I also see the potential for further analysis, as I could evaluate the received data and potentially draw conclusions about the relationship between gold and oil prices, especially in significant changes. If I could incorporate more data as originally planned, I believe I could draw even more insightful conclusions.
https://github.com/vileider/nontrivial_data

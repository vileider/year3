### Technical
### LO3.9.1.5
# Design, develop and evaluate a non-trivial big data analysis system.


In this reflection, I will delve into the journey of designing, developing, and evaluating a non-trivial big data analysis system. This project has involved a series of stages, from initial research and data source selection to the implementation of data visualization tools. I've encountered challenges, made crucial decisions, and learned valuable lessons along the way. This reflection serves as a documentation of my experiences, insights, and the progress made in this ambitious endeavor.

For the first stage, I intend to establish the framework and set up the software environment. I plan to research interesting data sources and select one that personally engages me. I'm considering comparing four main currencies: gold price, Bitcoin price, oil price, and the debt of four major currency countries. In the second stage, I will search for APIs that allow me to retrieve the necessary information and handle HTTP requests effectively. The third stage involves displaying the data on the screen in a basic format, categorized by month/day/year. In the fourth stage, I will research the easiest-to-implement graphic framework and learn how to use it. The fifth stage will focus on displaying the data on the screen and comparing them using graphs, followed by adding a user interface and code refactoring in the final stage.

After a meeting with Neil, I gained a better understanding of the outcome's objectives. 
Neil and I discussed potential design and strategy problems that might arise during the project, such as defining the problem to solve, determining the desired conclusions, and identifying the tools and data sources to use. Neil also suggested using the Pandas library in Python for data analysis.
In my research, I discovered the Pandas library, a powerful Python tool that provides comprehensive data analysis and manipulation capabilities. Pandas is built on top of the NumPy library, which is widely used for scientific computing in Python. I remember encountering NumPy when I was searching for the most efficient way to process arrays of objects. As I delved deeper into Pandas, I learned that it can be seamlessly integrated with other Python libraries, such as Matplotlib or SciPy, to perform a wide range of data science tasks. ( nikhilaggarwal3, 2023) This newfound knowledge of Pandas opened up exciting possibilities for data analysis within my project. However, my initial plan to combine JavaScript with Python libraries had to be adjusted due to time constraints.

I met with the students to 'hash out design problems and strategy problems on an ongoing basis.' During these discussions, we explored various aspects:
* What problem do I want to solve?
* What conclusions do I want to reach?
* Do I want to predict something from the conclusion?
* What tools do I want to use?
* How are we going to find the data source?
* How will I process the data?
* How will I develop a system to analyze data?
* How will I summarize the conclusion?
* What type of output will I choose?
* Will I export summarized findings from the extensive data analysis for evaluation by a relevant party?
    These questions were invaluable in guiding my project. This design exercise showed me how to expand the phases of the system creation process. It has been beneficial to listen to others' ideas and implement them in my work when they prove more efficient than my original plans. (Todorow, 2023 a)

In further research, I found historical data sources for gold, currencies, and oil prices.
I found a Website that provides APIs for the data I need but faced difficulties accessing the right database. While my initial plan involved combining JavaScript with Python libraries and using Cython in the backend with Flask, time constraints have led me to explore alternative solutions. Fortunately, the website offers CSV files as an alternative data source. As a result, I decided to focus on creating the backend, retrieving data from APIs, and sending it to the front end using CSV files. (opendatasoft, 2023)

After some challenges with asynchronous data retrieval from CSV files, I managed to display gold prices with dates on the screen. My next step is to refine this process by displaying two CSV data files and standardizing date formats, despite the time constraints. I aim to complete the project by Friday, which requires efficient data formatting and display.

One day later I made a significant change by incorporating a library for processing CSV files into JSON format. I learned how to use this library from the tutorial website. (Martin, 2021) Additionally, I developed a reusable function for asynchronous data processing and structured an API route in Next.js for efficient data retrieval. This change allows me to retrieve multiple CSV files more efficiently and obtain JSON data from the local API using the fetch function. The next steps involve standardizing date formats and implementing a charting framework.

I successfully integrated a React library based on D3 for creating charts, making it easier to add new data records and display them on the screen. 'react-vis' proved to be one of the easiest libraries to implement. Detailed information on how to use it I found at its repository's readme file. ( Uber Open Source, 2023)

I successfully displayed oil and gold data on a chart, despite the need for minor data adjustments before mapping it to the chart library. While data modification for performance optimization should ideally occur on the server side, I'm pleased with the progress made within the time constraints. This two-week journey improved my understanding of 'react-vis' and asynchronous JavaScript. Further analysis is possible, as I could evaluate the received data and draw conclusions. Notably, it becomes evident that significant changes in gold and oil prices are the key factors influencing their relationship. Incorporating more data, as initially planned, could lead to even more insightful conclusions.
(Todorow, 2023 b)

nikhilaggarwal3 (2023) Introduction to pandas, GeeksforGeeks. Available at: https://www.geeksforgeeks.org/introduction-to-pandas-in-python/ (Accessed: 23 September 2023). 

Todorow, B. (2023) big data design thinking, bitbucket repository. Available at: https://github.com/vileider/year3/blob/main/images/bigData_designThinking.png (Accessed: 2023). 

opendatasoft (2023) Real-time precious metal rates and currency conversion API, MetalpriceAPI. Available at: https://metalpriceapi.com/ (Accessed: 23 September 2023). 

Martin, D. (2021) Methods, Fast-CSV. Available at: https://c2fo.github.io/fast-csv/docs/parsing/methods (Accessed: 23 September 2023). 

Uber Open Source (2023) Uber/react-VIS: Data Visualization Components, GitHub. Available at: https://github.com/uber/react-vis (Accessed: 23 September 2023). 

Todorow, B. (2023b) nontrivial data, GitHub. Available at: https://github.com/vileider/nontrivial_data (Accessed: 23 September 2023). 
###

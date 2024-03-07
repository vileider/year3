Technical
LO3.7.3.5
Releasing a minimum viable product
Confidently design and apply algorithms for manipulating data in programming solutions for a variety of problems.
Suggest doing leetcode and kaggle competitions or following some data science tutorials for this one.  Whatever you choose you need to identify what the DATA is, how you are REPRESENTING it and why you are manipulating in the way that you are.  This is a great learning outcome for referencing academic literature.

Note that you need to persuade the marker what you did to DESIGN the algorithm, you cannot just plug it into a single function and say that's the design.  You can however join multiple techniques together to produce an output and claim you designed that pipeline.  

Try and do something interesting such as image recognition, text analysis or something you would not normally do.  You can start from a tutorial and then try and adjust the technique to a new domain for instance.

DOCUMENT your failures as well as your successes.

### What I have done
Throughout one semester, I created a graph tool capable of displaying graphical visualizations of gold prices over nearly a century. This has shown me how to analyze large datasets. Today, I am attempting to create an algorithm to manipulate data for another project, and I would like to apply professional techniques to assist me.
### progresss
I was working on displaying the background for the game depending on the key pressed. The background was initially a CSV file containing letters representing water tiles and ground tiles in each row and column. I had to create a method that would read the CSV and turn it into a 2D array. Once I had a two-dimensional array, I had to display it on the screen. Our team decided to create an isometric view of the displayed tiles. I had to set the position for the first tile and then calculate the next position from the given 2D array. Once the first line had been displayed, the algorithm had to start again with the new line. The top tile had to be slightly to the right and at the bottom from the initial first tile. I had to design a way to display every line from the two-dimensional array on the screen.
# https://bitbucket.org/vileider/year3/src/main/images/dispalyed_csv_file_no1.png
Once I managed to apply this algorithm, I wanted to create a bigger map and display it. I created a CSV file with 100 records and 100 lines. Each record represented land or water. Once I displayed it on the screen, the game's frames per second dropped down significantly. I had to find a solution to improve the game's refresh rate. I could do it by cutting a piece from the 2D array that currently covers the visible screen frame. I created a function that checked the first tile's top-left isometric position. If the player moves, the top-left isometric coordinates position adjusts to the player's new position. All of the above required the following methods:
* Read the CSV file
* Modified the 2D array into a 2D array of dictionaries with the second parameter containing its coordinates on the 2D array
* Cut a displaying piece from the 2D array, for example, 17x17
* Turned the sliced array into a list and added coordinates on the screen starting from the first tile on the list

### how I designed this
# https://bitbucket.org/vileider/year3/src/main/images/mural_tile_desing1.png
To design that solution, the Python game team had multiple design sessions where we discussed possible solutions. The first idea was to create big chunks of the map, but it was abandoned due to poor performance.
# https://bitbucket.org/vileider/year3/src/main/images/planning_2.png
# https://bitbucket.org/vileider/year3/src/main/images/proof_of_concep_tiles.png
After I proposed a solution during a planning meeting that would include multiple small tiles that the player would work on, we agreed to give me a chance to prepare a proof of concept in a couple of days. I created an example algorithm that was reading a simplified CSV file. It met with positive feedback, so we moved forward with this idea. We redesigned the code and started adding data manipulation solutions aligned with the algorithms for moving the player on the tile grid.
### How I adjusted the algorithm to make smooth movement
After implementing player movement and updating the new player position in the sliced array function, I needed to devise an algorithm to ensure smooth movement. I calculated the relative position from the center of the tile on which the player stood. When the new sliced array was displayed, the player's position was adjusted accordingly, resulting in a smoother player movement experience. However, the code complexity reached a point where refactoring was necessary.
We brought in Neil for a code review, and he recommended incorporating design patterns. Thanks to his advice, we were able to reduce the complexity of the project's code architecture. After two weeks of refactoring, we successfully achieved our goal. Now, the project appears more straightforward to comprehend, and adding new features seems significantly easier.
### What I learned
In my programming journey, I acquired skills in efficiently reading and processing CSV files, showcasing a practical understanding of data handling in various formats. I understood 2D array manipulation, implementing algorithms that improved performance and allowed for cutting and displaying pieces based on specific criteria. A notable achievement was the design and application of a smooth player movement algorithm, demonstrating my ability to create effective solutions for dynamic in-game scenarios. Through a collaborative code review with Neil, I incorporated design patterns to optimize algorithm efficiency and conducted thoughtful refactoring to simplify the project's architecture. This experience showcased not only technical expertise but also adaptive project management skills, as I adjusted algorithms based on feedback and project needs. 
### how I will use my knowledge in the future
I will continue to use data manipulation algorithms shortly, and I will expand my knowledge by embedding Python databases. I already see our team is nearing a limit in utilizing CSV.
I am sure I will continue to look for a more efficient use of libraries like NumPy or Pandas. The game will need high-efficiency algorithms, so I will keep improving my knowledge about them by practice and research.
I believe applying algorithms for manipulating data is something I want to do, and with a better understanding of OOP and the Python language, I can achieve very good results.
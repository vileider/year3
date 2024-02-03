LO3.7.2.3
User experience design
Conduct effective research, using literature and other media, into IT and business-related topics.
You need to show you read the tech news and then you are interested in it!  Start with some articles that are related to a project you are doing, find related literature, books and videos.  What do you find interesting?  What are the challenges they are trying to solve? Are they doing a good job?  Are there ethical concerns?  Does it apply to all industries or just a specific one.  Look into how to do research effectively.  For this one we are looking for an output that represents a structured and considered view of a topic.

#
i was doing reaserch every time i stuck insomething or i wanted to expand my knowlede.I could gice many examples of the proces from tthe past but i will start from the one i currently woorking on.

right now i want to optimize the code and i need logic design flowchart diagram to understand where my code is bottlenecking. 
To lerne little bit about diagrams i looked at the viedeo
# https://www.youtube.com/watch?v=SWRDqTx8d4k
The video iteached me about flowcharts, which are diagrams that show the steps or logic of a process or program. The video let me understand what flowcharts are and how they can help in writing code, also what symbols and rules are used to create them. I have noticed some examples of flowcharts for simple programs and algorithms
i used lucid app do create grtaphic representation of alghoritms
# https://lucid.app/documents#/documents?folder_id=recent
# https://bitbucket.org/vileider/year3/src/main/images/flow_chart_part1.png
i can compare the from the app efficiency before i used diagram:
# https://bitbucket.org/vileider/year3/src/main/images/app_before_refactor.png
before refactoring with the help of flowchar diagram frames per second oscilated arround 200
and after i organized the code better :
# https://bitbucket.org/vileider/year3/src/main/images/app_after_refactor.png
fps rised up to 333
i can defientely say that creating flowcharts help with big picutre view on applicatn and
relations between classes. I could noticed that i have been updating one variable multiple time and that
one funciton has been called more often than it should be. Thanks to that I was able to imporve efficiently by 60%

I took another task at my project. I had to store save data. I started searching for best python data storing examples.
# https://www.askpython.com/python/examples/save-data-in-python
The articlew on askpython says that pickle is a module that can serialize and deserialize Python objects, such as lists, dictionaries, or custom classes.
It also says that sqlite is a lightweight database that can store and query data using SQL commands.
The article provides examples of how to use pickle and sqlite to save and load data in Python.

I get into idea of using sqlite for map reading and writing, it would let me store information about current tile
with mutiple atributes. I had to only check if it is efficient enough, becaue I would liek to avoid delas in data tranasfer.

# https://www.sqlite.org/speed.html
After reading the numbers I noticed that biggest speed bost has been achioeved when synchorinizaiton has been turned off
The article says:
"With synchronization off, SQLite is sometimes much faster, but there is a risk that an operating system crash or an unexpected power failure could damage the database."
it could be useful only if I would read a data not write it. unless I will find something more about it

I decided to look for something faster and once I woudl store just no relation data I can use nonSQL database.
# https://charlesleifer.com/blog/completely-un-scientific-benchmarks-of-some-embedded-databases-with-python/
I looked at the db benchmark and noticed that level db is efficient. I will have to test it on live data.
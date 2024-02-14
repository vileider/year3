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
I looked at the db benchmark and noticed that level db is efficient. I will have to test it on live data once I will get to the point at my project where that will be priority. Right now I gained this knowledge from pure curiosity

# bitbucket/year3/Neil on research
From Neils lecture i learned about the importance of documenting the research topic and findings in a markdown file. He suggests rephrasing and enriching search terms if needed and stresses checking the publication date of sources. during  the lecture I confirmed that aiming to validate findings with at least three reliable sources and breaks down complex problems into manageable parts is a good approach. His adviced to utilize a mix of digital and academic resources for comprehensive understanding, highlighting the skill of efficiently skimming information to identify relevant data.

###
I was researching every time I got stuck or wanted to expand my knowledge. I could give many examples from the past, but I'll start with what I'm currently working on.

Right now, I want to optimize the code, and I need a logic design flowchart diagram to understand where my code is bottlenecking. To learn a bit about diagrams, I looked at a video. The video taught me about flowcharts, which are diagrams that show the steps or logic of a process or program. It helped me understand what flowcharts are and how they can assist in coding, including the symbols and rules for creating them. I saw some examples of flowcharts for simple programs and algorithms. I used the Lucid app to create a graphic representation of algorithms. I can compare the app's efficiency before I used the diagram. Before refactoring with the help of a flowchart diagram, frames per second oscillated around 200, and after I organized the code better, FPS rose to 333. I can definitely say that creating flowcharts helps with a big picture view of the application and the relationships between classes. I noticed I had been updating one variable multiple times and that one function had been called more often than it should be. Thanks to that, I was able to improve efficiency by 60%.

I took another task in my project to store save data. I started searching for the best Python data storing examples. The article on askpython says that pickle is a module that can serialize and deserialize Python objects, such as lists, dictionaries, or custom classes. It also says that SQLite is a lightweight database that can store and query data using SQL commands. The article provides examples of how to use pickle and SQLite to save and load data in Python.

I got the idea of using SQLite for map reading and writing, which would let me store information about the current tile with multiple attributes. I only had to check if it was efficient enough because I wanted to avoid delays in data transfer. After reading the numbers, I noticed the biggest speed boost was achieved when synchronization was turned off. It could be useful only if I read data, not write it unless I find something more about it.

I decided to look for something faster, and since I would store just non-relational data, I can use a nonSQL database. I looked at the DB benchmark and noticed that LevelDB is efficient. I will have to test it on live data once I get to the point in my project where that will be a priority. Right now, I gained this knowledge from pure curiosity.

From Neil's lecture, I learned about the importance of documenting the research topic and findings in a markdown file. He suggests rephrasing and enriching search terms if needed and stresses checking the publication date of sources. During the lecture, I confirmed that aiming to validate findings with at least three reliable sources and breaking down complex problems into manageable parts is a good approach. He advised utilizing a mix of digital and academic resources for comprehensive understanding, highlighting the skill of efficiently skimming information to identify relevant data.

After reading the LO title couple more times I discovered that I should focus more on business  related topic not on searching in general. I can treat the journey abov as evidence of my searching skills and lerning process.

Inspired by the Neil during one of the lectures, I decided to research on how AI is changing modern software developing.
At google schoolars I have found an article to this topic.
"Impact of Generative AI on the Software Development Lifecycle" investigates the impact of Generative AI on the Software Development Life Cycle (SDLC), proposing a new model, the Generative AI-Assisted Software Development Life cycle (GAASD Lifecycle)
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4536700

It discusses the integration of Agile methodologies with generative AI technologies like ChatGPT to enhance efficiency. Through interviews with 30 tech professionals, the research explores generative AI's influence on each SDLC phase. Article highlight the potential for generative AI to speed up software deployment and improve reliability. Generative AI can analyze historical data from previous projects to identify patterns and generate accurate estimates for future tasks and sprints. It can also suggest define project scope, and help in creating user stories by using Natural Language Processing. The ability to select appropriate architecture patterns and generating system designs from scratch based on tech leaders definitions. It can evaluate existing designs for weaknesses, suggest alternative approaches. Iwhich could imporve my

The study also notes limitations such as hallucination, incoherence, possible inaccuracy and lack of originality, underscoring the need for human oversight. 


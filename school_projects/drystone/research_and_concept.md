
# DRYSTANE WALL PROJECT

I intend to create a simple application that calculates values and costs. My plan is to utilize C# for the application's user interface (UI) and Python for performing the necessary calculations. I will conduct some research to confirm the feasibility of this approach.

The text compares C# and Python for UI development:
* C# has more built-in support and user-friendly libraries for UI development than Python.
* Python can be used for scripting and automating tasks in a C# application or testing its UI.
* The choice between C# and Python depends on the use case and the developer’s preference.
https://www.quora.com/Is-C-good-at-UI-or-should-I-use-Python-instead

After conducting some research, I've decided to develop the user interface for the Windows application using C#. Now, my next step will be to figure out how to configure my Integrated Development Environment (IDE) for C#


I encountered difficulty in properly debugging my program. To address this, I sought advice from Stack Overflow and was able to implement code to print debug messages in the console. This approach helped reveal some underlying issues, such as unbound buttons and error codes resulting from flawed logic and syntax. 
https://stackoverflow.com/questions/33669957/where-can-i-read-the-console-output-in-visual-studio-2015

I expanded my knowledge by watching a tutorial on creating input fields and passing arguments into the output box.
https://www.youtube.com/watch?v=BFT2QMTXoms&t=460s

I gained an important insight. I realized that if a panel doesn't have a text field, I need to create one that contains the required text. Once I've done that, I can modify it in any way I need to.

In debug window i was getting message ```The thread 0x26e4 has exited with code 0 (0x0).``` I was curious what does it mean and by reading mirosoft guide page i learned that it means "The default value is 0 (zero), which indicates that the process completed successfully."

https://learn.microsoft.com/en-us/dotnet/api/system.environment.exitcode?view=netframework-4.8
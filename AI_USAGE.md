# AI Usage

Briefly describe how you used AI (tools, prompts, code snippets, fixes). Be concise and honest (using AI is fine; it's just a tool; we want to know your method). If you did not use AI, state that here.

OS: Linux ubuntu
IDE: Visual Studio Code
AI: Claude AI

Using claude ai, i started by getting instructions on how to install specific npm and openJDK versions. 
Secondly i let the AI analize the project and find the problem areas using.
AI defined that most business logic is made in LibraryService.java file.
I copied the default code and let AI explain each function and how they work. 
Then I gave ai a piece of the code, And asked to make changes which would align with the assignment. Manually tested the changes and made corrections if needed. Did so with every function. Once initial changes were done, i started manually testing the code by testing loan,reserve,cancel and return functions and made sure members cant interfere with other members loans or reservations. 

Due to lack of personal time, i wasnt able to enforce visible loan limits, but double loan prevention, reserve queue and reservation cycle should work as asked for. API tests passed

------
 My Digital Rain Project
------
As part of my fourth year C++ module we were tasked with creating a unique Digtial Rain Project

## *Introduction* 
When brainstorming project ideas, we were shown examples from past years for inspiration. This is where I discovered the concept for my first main component: colors. I knew I wanted a bright, random color display, which kickstarted my search for a way to bring this vision to life. I wanted something unique, something I hadn’t encountered during my research. Eventually, I settled on the idea of using downward slashes (|), which I felt would create a realistic, fast-paced downpour—something common in Ireland. 

To start my project i decided to create a basic version of my vision without colours and just to tackle the rain fall and size of the rain fall. 
## *Design & Research*
This is the first thing i found in my reaserch, it is a previous students blog which she uses colours and explains how she did hers: 
[Sarahs's blog](https://sarahmatu.github.io/DigiRainProject/)

I wanted to have random colour pattern over picked and hardcoded colours. I ended up having a block of different colours cascading down the screen, while this was not my original idea I ended up liking it more then the idea of random colours all together 

This is my first draft of my project, to figure out how the slashes look falling down the screen, the speed and size i need for the project aswell, once i was happy with my knowledge base i started a new project and started to add the features i wanted. 

<img src="https://raw.githubusercontent.com/ellenmcintyre123/emc-digital-rain-cpp.io/main/docs/assets/images/firstdraft.png" width="400" height="400">

I used AI to help me with my idea of the fading colours down the screen, I gave it my orginal code and asked for the colours to be added, this is what it came back with and althought it was not exactly that i had in my head i ended up prefering it and stuck with it, I wanted to understand what the added colour code did and take snippets of the code and explain it.

**Code Snipet for colour**

<img src="https://raw.githubusercontent.com/ellenmcintyre123/emc-digital-rain-cpp.io/main/docs/assets/images/first.png" width="400" height="200">


This is the code to pick the colours used on the project using [ANSI colour](https://ss64.com/nt/syntax-ansi.html) with red, green, yellow, blue, megenta and cyan being the 6 colour blocks shown 


<img src="https://raw.githubusercontent.com/ellenmcintyre123/emc-digital-rain-cpp.io/main/docs/assets/images/second.png" width="800" height="200">


This section of code changes the text colour in the terminal, the colour number is used to pick a specific colour and the '\33' and 'm' tells the terminal to change the colour. 

## *Terminal Demo*

<img src="https://raw.githubusercontent.com/ellenmcintyre123/emc-digital-rain-cpp.io/main/docs/assets/images/final.png" width="500" height="400"><img src="https://raw.githubusercontent.com/ellenmcintyre123/emc-digital-rain-cpp.io/main/docs/assets/images/full.png" width="500" height="400">

This is two screenshots of my finial outcome, the first (left side) is showing the all the colours that fell down the screen changing colours, the second(right side) is showing how the terminal looks after running the code as i have not added a clear screen for the screen so it completely fills the screen size that i have set 

------
 My Digtial Rain Project
------
As part of my fourth year C++ module we were tasked with creating a unique Digtial Rain Project. The project was developed with a focus on using Object-Oriented Programming (OOP) principles and modern C++ features, ensuring that the code is modular, reusable, and easily maintainable.

## *Introduction* 
When brainstorming project ideas, we were shown examples from past years for inspiration. This is where I discovered the concept for my first main component: colors. I knew I wanted a bright, random color display, which kickstarted my search for a way to bring this vision to life. I wanted something unique, something I hadn’t encountered during my research. Eventually, I settled on the idea of using downward slashes (|), which I felt would create a realistic, fast-paced downpour—something common in Ireland. 

To start my project, I decided to create a basic version of my vision without colors, just focusing on the rain effect and the size of the downpour.

## *Design & Research*
One of the first things I found in my research was a previous student’s blog, where she used colors and explained how she did hers: 
[Sarahs's blog](https://sarahmatu.github.io/DigiRainProject/)

I wanted to have random colour pattern over picked and hardcoded colours. I ended up having a block of different colours cascading down the screen. While this wasn’t my original idea, I ended up liking it more than the idea of random colors scattered all together.
Here’s the first draft of my project, where I focused on figuring out how the slashes looked falling down the screen, as well as their speed and size. Once I was happy with my understanding, I started a new project to make it unique to me and add in my ideas with the colours.


<img src="https://raw.githubusercontent.com/ellenmcintyre123/emc-digital-rain-cpp.io/main/docs/assets/images/firstdraft.png" width="400" height="400">

I used AI to help me with the idea of fading colors down the screen. I gave it my original code and asked for the colors to be added. Although the result wasn't exactly what I had in mind, I ended up preferring it and decided to stick with it. I wanted to understand what the added color code did and take snippets of the code to explain it.

**Code Snipet for colour**

<img src="https://raw.githubusercontent.com/ellenmcintyre123/emc-digital-rain-cpp.io/main/docs/assets/images/new.png" width="400" height="200">


This is the code to pick the colours used on the project using [ANSI colour](https://ss64.com/nt/syntax-ansi.html) with red, green, yellow, blue, megenta and cyan being the 6 colour blocks shown and prints the slash symbol 


<img src="https://raw.githubusercontent.com/ellenmcintyre123/emc-digital-rain-cpp.io/main/docs/assets/images/second.png" width="800" height="200">


This section of code changes the text colour in the terminal, the colour number is used to pick a specific colour and the '\33' and 'm' tells the terminal to change the colour. 
## *Algorithm*
I have made use of multiple algorithms in my project
- Initialize screen size
- Randomly generate raindrops
- sets the colours
- controls the speed

## *Modern C++/ Object-Oriented Programming*
- Random Number Generation with <random> sdt::mt19937 and std::uniform_int_distribution
- Timing with std::chrono and std::this_thread::sleep_for
- I used constructor initialization lists to initialize the random number generator std::mt19937 gen and std::uniform_int_distribution<> dis
- All the core functionality is encapsulated in the DigitalRain class which handles random color generation, cursor positioning, and the rain effect

  
## *Terminal Demo*

<img src="https://raw.githubusercontent.com/ellenmcintyre123/emc-digital-rain-cpp.io/main/docs/assets/images/final.png" width="500" height="400"><img src="https://raw.githubusercontent.com/ellenmcintyre123/emc-digital-rain-cpp.io/main/docs/assets/images/full.png" width="500" height="400">

This is two screenshots of my final outcome, the first (left side) is showing the all the colours that fell down the screen changing colours, the second(right side) is showing how the terminal looks after running the code as i have not added a clear screen for the screen so it completely fills the screen size that i have set 

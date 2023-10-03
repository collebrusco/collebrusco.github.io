# Frank Collebrusco
## collebrusco.frank@gmail.com
## Austin, TX 78756
## [Resume](https://drive.google.com/uc?export=download&id=1THA1L63mcjz_gFhSnWfv5WgmrYNrWkTA) &nbsp;|&nbsp; [Github](https://github.com/collebrusco)
# About Me
I am a junior at the University of Texas at Austin studying Computer Engineering with a focus on Software Engineering and Design. My areas of interest include low level software, computer graphics, embedded systems, game design, and audio and signal processing. Currently, I am seeking internships for the Summer of 2024.  
    
  
# Background
After high school, I worked at an auto shop for three years. I went from cleaning floors, to doing oil changes, to eventually doing things like engine and electrical repair. I found myself fascinated with the workings of all of the machinery and electronics I was working on, working on my own car and racing (on a track) every weekend. (improved the 1/4 mile time from 14.6 -> 12.9 if you're into that stuff) Following my interest, I enrolled in EE at Texas State University, where I held a 4.0, and transferred to UT Austin ECE. Here I've maintained the 4.0 and work as a Teacher's Assistant with the Electrical and Computer Engineering department. In the Summer of 2023 I worked as an Embedded Firmware Engineer Intern with Enphase.     

![Me in the Shop](/docs/assets/images/me_working_on_merc_small.PNG) ![Hemi Rebuild](/docs/assets/images/hemi_rebuild_small.png)   

Having field experience performing electrical and mechanical repair has really helped me in my engineering endeavors. The same kind of problem solving and technical skills come into play when debugging hardware and software, after all figuring out what's wrong with a car is sort of just "debugging" its systems.    
   
# Projects   

## FLGL (Franks low-fat Graphics Library)
### [Github Repo](https://github.com/collebrusco/flgl) &nbsp;|&nbsp; [Youtube Demo]()   
![UI](/docs/assets/images/flgl_code.png)
FLGL is a windowing and graphics library I built for myself that exposes OpenGL/GLFW functionality through a consice interface in C++. Projects like [adrift](https://github.com/collebrusco/adrift) and this [flappy bird demo](https://github.com/collebrusco/flappy-bird) use FLGL. FLGL can create windows, read mouse and key input, read, compile, link and upload to shaders, upload and use textures and meshes, render, & more. All of the GPU memory management is handled behind the scenes. This came about because I was writing a lot of the same verbose, complicated low-level windowing and graphics code for all of my game and shader projects, and needed a simpler interface that still let me control the GPU at a low level. This is my largest passion project and I am continuously updating it.

## Handheld Game Competition (2nd Place)
### [Github Repo](https://github.com/collebrusco/ECE-319K-game-competition) &nbsp;|&nbsp; [Youtube Demo](https://youtu.be/LUv89gF3i-0) &nbsp;|&nbsp; [Photos](https://www.flickr.com/photos/utece/albums/72177720304144100)   
![319K PCB](/docs/assets/images/PCB.PNG)   
This game won 2nd place in UT's ECE 319K game design competition. The system is driven by a TM4C microcontroller, and interfaces with a 128x160 TFT LCD display, a 6-bit DAC, a joystick & a slidepot, 4 buttons and 6 LEDs through a PCB that I designed. The gameplay is sort of "bullet hell" style, with 5 levels, a boss fight, and upgrades available for purchase throughout with in-game currency. This was a lot of fun.

## Library App
### [Github Repo](https://github.com/collebrusco/ECE-422C-final-project) &nbsp;|&nbsp; [Youtube Demo]()   
![UI](/docs/assets/images/library_ui.png)
For Software Design and Implementation II at UT, I created a library app that uses a client/server structure to maintain a database of library items and user accounts, and lets clients login and check items in and out with a UI. Multiple clients can connect at once, and all client/server communication is done over sockets. The database is hosted with MongoDB.

## Grocery List Maker
### [Github Repo](https://github.com/collebrusco/grocery-list-maker) &nbsp;|&nbsp; [Youtube Demo](https://youtu.be/nFomeJMN-k0)
![grocery list maker home screen](/docs/assets/images/grocery-list-maker.png)
Out of necessity, I created a tool that keeps a list of recipes and meals you like, and uses it to create you a grocery list by randomly selecting you a desired number of recipes or snacks based on your input. For example, you can tell it you need 7 meals for the week, only 3 of which you want to have to cook. It will look through your recipe list and select you some options at random, from which you can add/remove entries, confirm, and then the program will save you a grocery list in an external file.   
Your recipies and ingredients are kept in an external file and enumerated using a unique yet fairly natural syntax. The program can also simply act as a recipe book, letting you search and see information about all of your recipes.

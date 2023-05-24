# Frank Collebrusco
## collebrusco.frank@gmail.com
## (512)-963-5859
## Austin, TX 78756
## [Resume](https://drive.google.com/uc?export=download&id=1n8p5glkNKDxpOJUPyrUv0BStAs2tjlE1) &nbsp;|&nbsp; [Github](https://github.com/collebrusco)
# About Me
I am a junior at the University of Texas at Austin studying Computer Engineering with a focus on Software Engineering and Design. My areas of interest include low level software, computer graphics, embedded systems, game design, and audio and signal processing. Currently, I am seeking internships for the Summer of 2023.  
    
  
# Background
After high school, I got a job in an auto shop, where over three years I went from cleaning floors, to doing oil changes, to eventually performing complex jobs including top-end engine rebuilds, electrical diagnosis, and suspension repair. During these years I discovered a love of engineering that inspired me to pursue my education. I enrolled at Texas State University, where I held a 4.0 GPA before transferring to UT Austin. Here I've maintained a 4.0 and work as a teacher's assistant with the Electrical and Computer Engineering department.

Having field experience performing electrical and mechanical repair is a unique advantage. Being an auto technician is nothing if not problem solving, and that skill has certainly transferred to the software and computer engineering field. I find that software and hardware debugging often utilize the same sort of thought processes and logic that apply to narrowing down the reason for a fault in a vehicle, though in a different medium. 
   
![Me in the Shop](/docs/assets/images/me_working_on_merc_small.PNG) ![Hemi Rebuild](/docs/assets/images/hemi_rebuild_small.png)   
# Projects   
## Handheld Game Competition (2nd Place)
### [Github Repo](https://github.com/collebrusco/ECE-319K-game-competition) &nbsp;|&nbsp; [Youtube Demo](https://youtu.be/LUv89gF3i-0) &nbsp;|&nbsp; [Photos](https://www.flickr.com/photos/utece/albums/72177720304144100)   
![319K PCB](/docs/assets/images/PCB.PNG)   
At the end of Intro to Embedded Systems at UT, the class puts everything from the semester together into a handheld game design competition, in which this game won 2nd place. The system is driven by a TM4C microcontroller, and interfaces with a 128x160 TFT LCD display, a 6-bit DAC, a joystick & a slidepot, 4 buttons and 6 LEDs through a PCB that I designed. The gameplay is sort of "bullet hell" style, with 5 levels, a boss fight, and upgrades available for purchase throughout with in-game currency. The game was written in one week in November 2022 with a combination of C and C++. My lab partner assisted with the design, art, gameplay, and input drivers, while I focused on the game engine, which in this case, is entirely in-lined in the main file for fast prototyping.   

## FLGL (Franks low-fat Graphics Library)
### [Github Repo](https://github.com/collebrusco/flgl) &nbsp;|&nbsp; [Youtube Demo]()   
![UI](/docs/assets/images/flgl_code.png)
I'm facsinated by graphics programming, and for use in my many graphics experiments I've created a concise OpenGL library that exposes basic OpenGL/GLFW functionality through a convenient Object Oriented interface in C++. FLGL can create windows, read mouse and key input, read, compile, link and upload to shaders, upload and use textures, and of course render. All of the GPU memory management is handled behind the scenes. Essentially, flgl provides easy access to all of the core graphics and windowing functionality needed for a low level graphics project like building an engine.

## Library App
### [Github Repo](https://github.com/collebrusco/ECE-422C-final-project) &nbsp;|&nbsp; [Youtube Demo]()   
![UI](/docs/assets/images/library_ui.png)
For Software Design and Implementation II at UT, I created a library app that uses a client/server structure to maintain a database of library items and user accounts, and lets clients login and check items in and out with a UI. Multiple clients can connect at once, and all client/server communication is done over sockets. The database is hosted with MongoDB.

## OpenGL Game Engine
### [Github Repo](https://github.com/collebrusco/opengl-game-engine) &nbsp;|&nbsp; [Youtube Demo](https://youtu.be/hJseGaKIq68)   
![OpenGL Shader Code](/docs/assets/images/shader_code_eg.png)
In the Summer of 2022, I challenged myself to learn OpenGL and make as much of a game/engine as I could in 8 weeks. This was by far the largest software project I'd undertaken at the time. After learning the fundementals and building code capable of doing basics such as opening a window, reading/compiling/uploading shaders, creating VAOs on the GPU & rendering, I began designing an engine for an interactive game. At the end of these 8 weeks, I had an environment in which the user can control a pixart character in top down view, where they can walk, aim, sprint, zoom in & out, and collide with nearby objects.   
This project taught me an immense amount not only about computer graphics, but about the challenges of software design and organization. As this was my first project anywhere near this scale, there's a lot I want to improve and finish. I'm currently refactoring this project into a more organized codebase located [here](https://github.com/collebrusco/flgl) where I will continue to make improvements and work on building it into an engine.

## Grocery List Maker
### [Github Repo](https://github.com/collebrusco/grocery-list-maker) &nbsp;|&nbsp; [Youtube Demo](https://youtu.be/nFomeJMN-k0)
![grocery list maker home screen](/docs/assets/images/grocery-list-maker.png)
Out of necessity, I created a tool that keeps a list of recipes and meals you like, and uses it to create you a grocery list by randomly selecting you a desired number of recipes or snacks based on your input. For example, you can tell it you need 7 meals for the week, only 3 of which you want to have to cook. It will look through your recipe list and select you some options at random, from which you can add/remove entries, confirm, and then the program will save you a grocery list in an external file.   
Your recipies and ingredients are kept in an external file and enumerated using a unique yet fairly natural syntax. The program can also simply act as a recipe book, letting you search and see information about all of your recipes.

# Frank Collebrusco
## collebrusco.frank@gmail.com
## (512)-963-5859
## Austin, TX 78756
## [Resume](https://drive.google.com/uc?id=1a0R4pNb9xapC8YmqukClF14nWq5w4CvP&export=download) &nbsp;|&nbsp; [Github](https://github.com/collebrusco)
# About Me
I am a junior at the University of Texas at Austin studying Computer Engineering with a focus on Software Engineering and Design. My areas of interest include low level software, computer graphics, embedded systems, game design, and audio and signal processing. I plan on graduating in 2025 and entering the software industry. Currently, I am seeking internships for the Summer of 2023.  
    
  
# Background
After high school, I got a job in an auto shop, where in three years I worked my way up from cleaning floors, to doing oil changes, to eventually performing complex jobs including top-end engine rebuilds, electrical diagnosis, and suspension repair. During these years I discovered a love of engineering that inspired to pursue my education. I enrolled at Texas State University, where I held a 4.0 GPA before transferring to the University of Texas at Austin.  

Throughout my studies, my technical background from working in the auto shop has proven to be a significant advantage. My technical experience gives context to much of my applied studies, and affords me a unique perspective. My matured diagnostic skills help me to quickly debug software and track down electrical issues. Being an auto technician is nothing if not problem solving: and these skills and experiences have absolutely made me a better student and prospective engineer.  
   
![Me in the Shop](/docs/assets/images/me_working_on_merc_small.PNG) ![Hemi Rebuild](/docs/assets/images/hemi_rebuild_small.png)   
# Cirricular Projects   
## Handheld Game Competition (2nd Place)
### [Github Repo](https://github.com/collebrusco/ECE-319K-game-competition) &nbsp;|&nbsp; [Youtube Demo](https://youtu.be/LUv89gF3i-0) &nbsp;|&nbsp; [Photos](https://www.flickr.com/photos/utece/albums/72177720304144100)   
![319K PCB](/docs/assets/images/PCB.PNG)   
At the end of Intro to Embedded Systems at UT, the class puts everything from the semester together into a handheld game design competition, in which this game won 2nd place. The system is driven by a TM4C microcontroller, and interfaces with a 128x160 TFT LCD display, a 6-bit DAC, a joystick & a slidepot, 4 buttons and 6 LEDs through a PCB that I designed. The gameplay is sort of "bullet hell" style, with 5 levels, a boss fight, and upgrades available for purchase throughout with in-game currency. The game was written in one week in November 2022 with a combination of C and C++. My lab partner assisted with the design, art, gameplay, and input drivers, while I focused on the game engine, which in this case, is entirely in-lined in the main file for fast prototyping.

# Extra-Cirricular Projects
These are some projects I have worked on on my own time for research, learning, fun, to solve a problem, or all of the above.
## OpenGL Game Engine
### [Github Repo](https://github.com/collebrusco/opengl-game-engine) &nbsp;|&nbsp; [Youtube Demo](https://youtu.be/hJseGaKIq68)   
![OpenGL Shader Code](/docs/assets/images/shader_code_eg.png)
In the Summer of 2022, I challenged myself to learn OpenGL and graphics programming and make as much of a game as I could in 8 weeks. I began research into computer graphics, OpenGL and GPU programming and began working. After learning the fundementals and building code capable of doing basics such as opening a window, reading/compiling/uploading shaders, creating VAOs on the GPU & rendering, I began designing an engine for an interactive game. At the end of these 8 weeks, I had an environment in which the user can control a pixart character in top down view, where they can walk, aim, sprint, zoom in & out, and collide with nearby objects. This project taught me an immense amount not only about computer graphics, but about the challenges of software design and organization. As this was my first project anywhere near this scale, there's a lot I want to improve. I'm currently refactoring this project into a more organized codebase located [here](https://github.com/collebrusco/opengl-template) where I will continue to make improvements and work on building it into an engine.

## Grocery List Maker
### [Github Repo](https://github.com/collebrusco/grocery-list-maker) &nbsp;|&nbsp; [Youtube Demo](https://youtu.be/nFomeJMN-k0)
![grocery list maker home screen](/docs/assets/images/grocery-list-maker.png)
Out of necessity, I created a tool that keeps a list of recipes and meals you like, and uses it to create you a grocery list by randomly selecting you a desired number of recipes or snacks based on your input. For example, you can tell it you need 7 meals for the week, only 3 of which you want to have to cook. It will look through your recipe list and select you some options at random, from which you can add/remove entries, confirm, and then the program will save you a grocery list in an external file.   
Your recipies and ingredients are kept in an external file and enumerated using a unique yet fairly natural syntax. The program can also simply act as a recipe book, letting you search and see information about all of your recipes.

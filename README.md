# Frank Collebrusco
## collebrusco.frank@gmail.com
## Austin, TX 78756
## [Resume](https://drive.google.com/uc?export=download&id=1JvVf30a5W-G3EooZ9gLII2dkPyc_2CC2) &nbsp;|&nbsp; [Github](https://github.com/collebrusco)
# About Me
I am an undergraduate at the University of Texas at Austin studying Computer Engineering. My areas of interest include low level software, computer graphics & GPU programming, embedded systems, and game design.   
  
# Background
After high school, I worked at an auto shop for three years. I went from cleaning floors, to doing oil changes, to eventually doing things like engine and electrical repair. I found myself fascinated with the workings of all of the machinery and electronics I was working on, so I enrolled in EE at Texas State University, transferred to UT Austin ECE, and now work as a Teacher's Assistant for Embedded Systems while I earn my Computer Engineering degree. In the Summer of 2023 I worked as an Embedded Firmware Engineer Intern with Enphase, where I wrote safety critical watchdog modules, configured a unit testing suite for a firmware repo, wrote unit tests, and configured an emulator to emulate a native firmware binary.     

![Me in the Shop](/docs/assets/images/me_working_on_merc_small.PNG) ![Hemi Rebuild](/docs/assets/images/hemi_rebuild_small.png)   
   
# Projects   

## FLGL (Franks low-fat Graphics Library)
### [Github Repo](https://github.com/collebrusco/flgl) &nbsp;|&nbsp; [Youtube Demo]()   
![UI](/docs/assets/images/flgl_code.png)
FLGL is a windowing and graphics library I built for myself that exposes OpenGL/GLFW functionality through a consice interface in C++. Projects like [adrift](https://github.com/collebrusco/adrift), [gunpowder](https://github.com/collebrusco/gunpowder), and this [flappy bird demo](https://github.com/collebrusco/flappy-bird) use FLGL. FLGL can create windows, read mouse and key input, read, compile, link and upload to shaders, upload and use textures and meshes, render, & more. All of the GPU memory management is handled behind the scenes. FLGL has granular abstractions for control as well as broad abstractions for convenience, resulting in a huge reduction in development time for my graphics applications. This came about because I was writing a lot of the same verbose, complicated low-level windowing and graphics code for all of my game and shader projects, and needed a simpler interface that still let me control the GPU at a low level. This is my largest passion project and I am continuously updating it.

## Handheld Game Competition (2nd Place)
### [Github Repo](https://github.com/collebrusco/ECE-319K-game-competition) &nbsp;|&nbsp; [Youtube Demo](https://youtu.be/LUv89gF3i-0) &nbsp;|&nbsp; [Photos](https://www.flickr.com/photos/utece/albums/72177720304144100)   
![319K PCB](/docs/assets/images/PCB.PNG)   
This game won 2nd place in UT's ECE 319K game design competition. The system is driven by a TM4C microcontroller, and interfaces with a 128x160 TFT LCD display, a 6-bit DAC, a joystick & a slidepot, 4 buttons and 6 LEDs through a PCB that I designed. The gameplay is sort of "bullet hell" style, with 5 levels, a boss fight, and upgrades available for purchase throughout with in-game currency. This was a lot of fun.

## Library App
### [Github Repo](https://github.com/collebrusco/ECE-422C-final-project) &nbsp;|&nbsp; [Youtube Demo]()   
![UI](/docs/assets/images/library_ui.png)
For Software Design and Implementation II at UT, I created a library app that uses a client/server structure to maintain a database of library items and user accounts, and lets clients login and check items in and out with a UI. Multiple clients can connect at once, and all client/server communication is done over sockets. The database is hosted with MongoDB.

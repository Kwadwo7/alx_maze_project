Maze Project
The maze project is an adaptation of the Wolfenstein 1981 game. The project uses the concept of Raycasting to serve as the viewpoint of the player, giving it a first-person player view. Maps in the game are created using 2D-matrix arrays, which are seen when the player's raycast touch the blocks of the map.

Technologies Used
C Programming Language - The project was done using C programming language. The language is installed upon the installation of the gcc compiler on your Operating System (In this case, a Linux distro).
SDL2 - Known as Simple DirectMedia Layer is a cross-platform software development library designed to provide a hardware abstraction layer for computer multimedia hardware components. Software developers can use it to write high-performance computer games and other multimedia applications that can run on many operating systems such as Android, iOS, Linux, macOS, and Windows. (Wikipedia). In simple terms, it creates windows for any kind of media file, giving each window the ability to interact with the hardware components of a system(i.e Keyboard and mouse) and also the ability to quit, maximize or minimize each media file/application. This was used as the window that holds the entire functionality of the project.
Ubuntu 20.04LTS - The operating system used in this project. Ubuntu is a distro for the Linux Operating system.

Features and Functionalities
To make this maze, I used ray-casting to draw the walls and textures to design the game by using the C programming language and the SDL2 library to render and add the textures. The maps are defined in 2D arrays in text files, which are parsed when passed as an argument to the maze executable. 0 represents open space, all other integers are drawn as walls.

The SDL2 or the Simple DirectMedia Layer 2 is a cross-platform development library designed to provide low-level access to I/O devices (audio, keyboard, mouse, joystick), and graphics hardware via OpenGL and Direct3D or simply the SDL2 library allows us to interact with various devices like graphics hardware, audio, keyboard, mouse, etc. Thus, by using SDL2 library, I was able to map keyboard keys to different movements inside the game. To navigate through the maze, the player can use either the arrow keys or “WASD” keys.


Challenges
During the development of the program, I faced a number of technical and non-technical challenges. The most insidious ones were non-technical issues such as time constraints and schedule recovery. Whereas on the technical side, the most difficult challenge I faced was with regard to implementing a detection of wall collision which was a feature that will block camera rays to pass through the walls. Additionally, installing SDL2 was a major challenge because the majority of the materials were written in C++. After more research, I was able to install it. I chose to work on a real machine in order to run and test the game.

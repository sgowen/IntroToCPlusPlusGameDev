# Intro to C++ Game Dev
Learn how to build a simple Snake Game in C++!

## Controls

WASD moves the snake up, left, down, and right

## Building/Running in your Web Browser

1. Head on over to <a href="https://www.tutorialspoint.com/compile_cpp_online.php" target="_blank">Tutorials Point</a>
2. Clear the contents of the main.cpp window
3. Open up the main.cpp file inside terminal-snake/unix and paste its contents into the main.cpp window you just cleared
4. Hit the Compile button
5. Click inside the window at the bottom labeled "Default Term"
6. Run this command to run the game: ./main

## Building/Running on Unix (Linux, Ubuntu, Mac OS X, etc.)

1. You'll need to download a compiler like <a href="https://gcc.gnu.org/" target="_blank">GCC</a>
2. Open the Terminal and navigate (cd) to where you downloaded main.cpp (either inside terminal-snake/cross-platform or terminal-snake/unix)
3. Run this command to build the game: g++ -o main main.cpp
4. Run this command to run the game: ./main

## Building/Running on Windows

1. You'll need to download a compiler. I recommend <a href="https://www.visualstudio.com/vs/community/" target="_blank">Visual Studio</a>
2. Open the Command Prompt (cmd) and navigate (cd) to where you downloaded main.cpp (either inside terminal-snake/cross-platform or terminal-snake/windows)
3. Assuming you have Visual Studio 2017 installed on your machine, run this command to initialize your machine for compiling and linking: "C:\Program Files (x86)\Microsoft Visual Studio 17.0\VC\bin\vcvars32"
3. Run this command to build the game: "C:\Program Files (x86)\Microsoft Visual Studio 17.0\VC\bin\cl.exe" main.cpp
4. Run this command to run the game: main.exe

## Now it's your Turn!

Once you’re ready, here are a few ways you can enhance the Snake Game:

1. Make the snake pop out on the other side instead of crashing into the wall
2. Spawn multiple food pellets at a time
3. Spawn obstacles other than walls
4. Add a 2 player mode where one player uses "WASD" and the other uses "IJKL”
5. Make the snake move faster as time goes on to increase the challenge
6. Display the score during gameplay instead of just at the end

Happy Coding!

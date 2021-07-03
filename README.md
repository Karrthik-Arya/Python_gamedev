# Welcome to Week-3 of Learner's Space

This week we are going to learn to use Pygame, a collection of fun, powerful Python modules
that manage graphics, animation, and even sound, making it easier for you to build sophis-
ticated games. With Pygame handling tasks like drawing images to the screen, you can skip much of the
tedious, difficult coding and focus on the higher-level logic of game dynamics.

Making games is an ideal way to have fun while learning a language. It’s deeply satisfying to watch others play a game you wrote, and writing a simple game 
will help you understand how professional games are written.  

To learn about the pygame library we will be making an *Alien invasion game* on python somewhat like *asteroids*. Note the game will span a number of different files, so make a new folder called alien_invasion. Be sure to save all files for the game to this folder so *import* statements will work correctly.


## Setting up Pygame
Before we begin coding, we must install Pygame. Here’s how to do so on Linux, MacOS X, and Microsoft Windows:  
To install on Windows you can go through [this](https://www.youngwonks.com/blog/How-to-Install-PyGame-on-Windows) link.  
To install on Mac you can go through [this](https://www.youngwonks.com/blog/How-to-Install-PyGame-on-a-Mac) link.
### Installing Pygame on Linux
To install Pygame using the package manager.
Open a terminal window and run the following command, which will
download and install Pygame onto your system:  
```
 sudo apt-get install python-pygame
```
If you are using pyhton 3 just replace `python-pygame` with `python3-pygame`.  
To make sure its been installed correctly open the python interpreter by runnning `python` or `python3` on the terminal depending on your version of python.
Then try running `import pygame`. If it runs without any error then pygame is successfully installed.

## Starting the Game Project
Now to begin building our game we will first make the pygame window where we will add the various elements of the game like ship and aliens, setup the background etc. You will learn how to create *surfaces* with pygame which refer to a part of the screen where you display a game element. Each element in the game is a *surface*. You will also learn about *events* which is an action that the user performs while playing the game, such as pressing a key or moving the mouse.  
You can go through this notebook to learn about these things. 

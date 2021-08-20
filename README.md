# Welcome!

I’ve included this handy Guide that will help you navigate my GitHub. These are all my main projects you should check out first before exploring around my GitHub in general. Feel free to look around!f

# PenTesting App Ver2: https://github.com/RoyMBull/Pen-Testing-App-Ver2

   This is a second build of a penetration testing app I've developed that is meant to automate     a variety of the different tools I've written. The interface only includes      code that has been fully tested thoroughly. Any others,  feel free to browse and look at it. You won't see it in the interface but it's there in case you wish to see it.        The following to look at first are:

   * Bash_Interface.py (This is the main interface): https://github.com/RoyMBull/Pen-Testing-App-Ver2/blob/main/PenTesting%20App%20Ver2/Bash_Interface.py
      
   * LinuxInstall.py (Installs all needed components, including PYQ5 in case you don't have it installed. Also compatible with windows via pip installer)
     https://github.com/RoyMBull/Pen-Testing-App-Ver2/blob/main/PenTesting%20App%20Ver2/LinuxInstall.py
      
   * Installer Module.sh(Script that will install all needed compilers for Linux should you not have them installed)
     https://github.com/RoyMBull/Pen-Testing-App-Ver2/blob/main/PenTesting%20App%20Ver2/InstallerModule.sh

# Penetration Testing Drone Prototype: https://github.com/RoyMBull/Pen-Testing-Drone-Prototype
       
  The following files and or folders to check out are:
      
   * Custom Drone Software Sub folder under this repository: 
      https://github.com/RoyMBull/Pen-Testing-Drone-Prototype/tree/main/PenTesting%20Drone%20Prototype/Custom%20Drone%20Software

   I reverse engineered how the tello drone API communicates with the drone in order to fabricate my own user interface. The final build will integrate the arduino library in      order to directly communicate and control the server motors for the drone, as well as allowing me to properly integrate the pentesting app with it. 
       
   * Drone Schematics.cpp: https://github.com/RoyMBull/Pen-Testing-Drone-Prototype/blob/main/PenTesting%20Drone%20Prototype/Drone%20Schematics.cpp

   I know this file says CPP, but it's actually just all text and documents the full schematics of the project, and will help you better understand how I critically think,          analyze, and organize my projects. A must read
       
   * RB_Flight_Controller_Module.ino: https://github.com/RoyMBull/Pen-Testing-Drone-Prototype/blob/main/PenTesting%20Drone%20Prototype/RB_Flight_Controller.ino
              
   This is the main face of the program. I'm creating my own flight controller, that will control a series of servo motors, via ESC modules, that will allow me send various        data signals to the drone in order to manipulate the speed of the motors in order to manipulate the altitude and movement of the motors. 

# Python Penetration Testing Tools: https://github.com/RoyMBull/Python-Pen-Testing-Tools
      
   This is a collective of all the tools I've written for penetration testing. This will help you get a better understanding of all the vast libraries I utilize for the tools      that I write, as well as further see what I currently use python for. If you have any questions let me know of course. I have a special copy of a reverse shell for testing on    both separate systems on a network, however I left it out in order to make people more comfortable testing it. It’s 100&% safe and only works on the same system via two          terminals, one for client, and one for server.

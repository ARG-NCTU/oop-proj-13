# oop-proj-13-advanture

## Description
This is a adventure game, explore and kill enemy with your ability. Up down left right to control your position, q and e to change weapon and power, space to attack.

This project was integrated and developed by kayeedelau and teammates in OOP course in 2023.
It is used as teaching materials in the OOP and Advnaced OOP courses in NYCU.

Part of the materials are based on:
https://github.com/clear-code-projects/Zelda
under the Creative Commons Zero (CC0) license.
The art assets and the soundtrack have been done by Pixel-boy and AAA and can be found here: https://pixel-boy.itch.io/ninja-adventure-asset-pack They are also published under a CC0 license.


<img src="./oop13.gif"/>

## Getting Started

### Ubuntu
git clone the game:
```
$ cd ~
$ git clone git@github.com:ARG-NCTU/oop-proj-13-advanture.git
```
Run docker
```
$ cd oop-proj-13-advanture
$ source docker_run.sh
```
Start the game
```
$ python3 main.py
```

### Windows
Install Anaconda from following site.
https://docs.anaconda.com/free/anaconda/install/windows/
#### Download oop-proj-13-advanture
Download oop-proj-13-advanture as a zip, and unzip.
#### activate base env, and start the game
You can change "oop_env" to what ever the name you like.
```
$ conda create --name oop_env python=3.8.10
$ conda activate oop_env
$ conda install -c conda-forge pygame
$ conda install -c conda-forge numpy
```
cd to your oop-proj-proj-13 dir location, and run the game.
```
$ cd oop-proj-proj-13
$ python main.py
```

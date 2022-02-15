# What is a TriggerBot?

A TriggerBot is a Basic Code which Shoots automatically whenever there is a Enemy Detected.

# How does this Work?

So basically, this code is simply detecting a change in color around the crosshair and if there is any change in color it shoots immediately (27-30 ms).
This code uses the Win32 MouseEvent function and shoots or say it mimics the real mouseclick and shoots the enemy.

# What we need to do for the setup?

Steps to be followed:
1. Download and Install Python3 from official Website - https://www.python.org/downloads/
2. Open Cmd and Open the path where you kept this file
3. In the Cmd Type - "pip install -r Req.txt" and hit enter
4. Open Game and Open this file 
5. Whenever you want, press the Keybind to activate 
6. ENJOY!!

(NOTE - It deactivates automatically after shooting so Activate it again)


# What to do in Game ?

First Open the game and then this script (by double click)

The current KeyBind is as Follows - 
Pressing 'e' or 'q' to ACTIVATE or DEACTIVATE
and
Pressing 'p' to Close the Script

# Which Games does this work on?

It works on Every Games, except the ones which doesnt allow or are exposd to mouse event, for example Valorant, you might try it but I guess it wont work.

# What Resolutions does it work on?

The current Reolution is 1920x1080, if you have other resolution then dont worry follow this steps to change the working flow of the script.

Lets take an example of 1600x800 Resolution

Steps to be followed
1. Open Calculator
2. Divide 1600 and 800 By 2 and note them (If u have other Resolutions put their dimensions and divide by 2)
3. Then Subtract 5 from each and Note them.
4. Now U Will have 2 new Dimension - 795, 395
5. Now put this 2 inside the script on line - 23, which is -  img = pyautogui.screenshot(region=(955, 535, 10, 10))
6. Remove the 955, 535 and put the new ones being, 795,395,
7. So it will look like this Now -  img = pyautogui.screenshot(region=(795, 395, 10, 10))
8. DONE!!


# Feeling Lazy and just wanna plug n play? I got you
Heres, a release of the same with 1920x1080 resolution, 
keybinds are the same - 'e' to activate and deactivate - 'p' to close the tab
Guess what? You dont even need anything for this to run, its a standalone app so simply open and play, thats it....

# Want to Follow me for more?
Join my Telegram Channel I created recently - @ascarrehacks

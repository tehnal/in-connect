# in-connect

- ABSTRACT -
The Linkedin Connect Bot is a tool for people - particularly students - to rapidly grow their connections. It emphasizes people in their immediate network such as their school or prior connections. 

- MAIN - 
This project is intended to be a fun little test, using pyautogui in order to open linkedin, go to the "Grow your network"
section, and connect with everyone it "sees". 


- SET UP and USE -
In order to set this up, open a chrome tab, expand it to the full size (double left-click the top of the window), and exit it.
This is to ensure that the window that connectbot opens will be properly sized.
From here, run the script "connectbot.py", either from the terminal (python3 connectbot.py), or from VSCode.
You can then do nothing as the bot does its thing.



- FAILSAFE -  
If the code isn't working properly, then slam your cursor to one of the 4 corners of your screen. Pyautogui has a failsafe installed that will break the current run if your cursor is in the corner. 


- ISSUES AND WARNINGS -
There are a few things that are kind of an issue with this bot. Primarily, the linkedin terms and conditions.
There are certain rules against using bots (primarily clause (insert clause here)), which states that you cannot use bots/
scrapers on linkedin.
However, I believe if I were to code it so that the mouse were to move slow, click at irregular intervals, and not be so precise
/ fast - all of which I can do - then the bot would pass undetected. 


- SCRIPT STRUCTURE - 
The main script is in "connectbot.py". The "functions.py" script is used as storage for the functions used within the main script.

- DISCLAIMER -
It is worth noting that I wrote this to work well FOR ME. Not to be used by others. Which because of this, it is perfectly calibrated to my display and setup. If you were to reuse this, there would be a little bit of work to make it truly work.

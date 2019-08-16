# pytesting
python3
before you do anything open powershell and just type the word python --version. This will show you the current mode of python on your machine. you need v3+ .. preferrably v3.7 is what were using now. link below. If your python is out of date try typing python alone in the power shell line and see if it brings you too a screen to update. it did me.. 

if you type python and get stuck in the shell type ctrl + c then quit() -- 

The other way to open the file would be to right click and go to edit with IDLE , then go to run in the corner box and go to Run Module. 
I prefer just leaving powershell open so i can re run as needed to check temps and in  the case any other code runs need done. Also lots of fun tools in pwrshell.



**LINK :: Written in pyton v3.7+ -- be sure to download the latest code/binaries : https://www.python.org/downloads/

Once you have python make a text file on your desktop ( or folder if you want a codes folder, however it will take slight navigation.)

Once you have a blank text file save the code in ctof.py as whatever you want, i prefer something short and easy to type , just make sure to include the file extension .py so it knows how to be interpreted. 

Open windows powershell (or cmd line works too just powershell is easier to navigate IMO) - 

type ls - this will list the contents of the directory powershell is operating out of .. example:

PS C:\Users\vulca> ls


IF you created a folder for your new files you will need to change directory to this folder now

First we will need to change to Desktop

Type: cd Desktop (cap D)

new output: 
PS C:\Users\vulca> cd Desktop
PS C:\Users\vulca\Desktop>

PS C:\Users\vulca\Desktop> ls


i have re listed my files, here my folder is called git. i change to git. 

inside git is only ctof.py

i type 

python3 ctof.py 
the above will run the code ctof.py in python3 via powershell. its basically like a linux terminal, just not as interactive or powerfull.
 ( you can type python3 c tab and it will tab to complete) in powershell cmd line .. this should run as a python script and will prompt you with the question you see in the code if you open it up ( right click and "edit with IDLE") 
 
 Feel free to make any changes to the wording. I would like to find a way to put it on a repeating loop so i dont have to re run the line of code everytime even. 
HOWEVER - after you run this once if you keep powershell or cmd line open and press the up arrow on keyboard it will return your last command.. in our case python3 ctof.py 

Hint:

for playing with the code the \xb0 is a callsign , \ omits this from the code line and xb0 calls for the degree symbol in python. move it around, remove it , play with the code. its basic but you can see how a basic python code runs from this, it can get extremely complex quick and we could turn this into hundreds of line of code for a task. If you get curious check out my other python branches. 
  



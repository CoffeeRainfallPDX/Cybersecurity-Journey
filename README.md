# Cybersecurity-Journey
Progress reports on my cybersecurity learnings.



#NOVEMBER 3RD, 2025 - A NEW BEGINNING.
Tired of where life was taking me, I decided to put down the xbox controller and pick up a keyboard. 

*ACTIONS TAKEN THAT DAY* : Downloaded Oracle virtualbox, downloaded a copy of parrotOS security edition and mounted the image to virtual machine file,
installed the OS, then practiced linux commands. Ran into an issue where mkdir didn't work, utilized claudeAI to diagnosed the $PATH output message and 
concluded issue was a missing colon in the path. Fixed it temporarily with the EXPORT= command, but will need to implement a permanent fix. Started,
Google cybersecurity certificate program.


#NOVEMBER 4th, 2025
"_the journey of a thousand miles begins with a single step" ~_lao Tzu__. 

*ACTIONS TAKEN THAT DAY* : when I installed parrotOS on the virtualbox the other day something mustve went wrong as the mkdir command wasn't working.
After using claudeAI to troubleshoot, the problem was found within the $PATH. The installed $PATH was "/usr/local/bin:/usr/bin:/bin/usr/local/games:/usr/games",
having the path point to "/bin/usr/local/games" is like saying: "hey go check out the kitchen bedroom". We want the OS to find the BIN file- so the appropriate colon
was inserted accordingly. I did this by opening a nano instance of the .bashrc script, then running an export PATH= command.  




#NOVEMBER 5th, 2025

ACTIONS TAKEN: I ran out of time yesterday so I went to work on the bash script issue. I keep getting a syntax error and when I went through .bashrc 
it looked pretty garbled towards the end. I felt a little out of my depth troubleshooting this error as I have no clue what an appropriate .bashrc looks like
and quite frankly im a little pissed it even got messed up in the first place during install. Whatever- went through google cybersecurity module 2 and completed it so 
I still felt a sense of progress while keeping to my routine. I think im just going to look on reddit for homelab ideas instead of asking AI.....

# sneakyBat

When the targetted user runs the .bat file, the target's ip configuration is sent to your email and then sends a friendly message and (optionally... see note below) restarts their machine.
I would recommend to not download the zip file, as the formatting is very messy and difficult to read when you open it in notepad.
Instead, I would recommend copying the code from the repo file, and then paste it in a notepad file, saving it as a .bat file and giving it a realistic name that a target would run.
Be sure to first view the code before sending to target in order to set your email address, or if you wanted to make any changes or additions.
If you would like to change the email it sends from, change the variables "GmailAccount" and "GmailPassword", which contain the credentials of the email that sends the ip info file.
There are comments documenting what each line does to help understand if there are parts you would like to remove or that are adjustable.
There is a comment in there ":: shutdown /r" that gives you the option to also shut down the machine; remove the comment ("::") to enable the command.
Tip: if playing as a prank, be sure that target would be fine if pc shuts down, as shutdown /r restarts their computer and may cause them to lose any unsaved work.
Use carefully and have fun! :D


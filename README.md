# sneakyBat

## Functionality:
When the targetted user runs the .bat file, a powershell script is created to send the target's ip configuration to your email, and then delays the console for 5 seconds to display a friendly message B). Afterwards, it deletes the .bat and powershell file so the target can't view the code and then (optionally... see note below) restarts their machine. None of the commands are printed to the console, so the target doesn't know what's happening. hee hee
- Uses environmental variables as shortcuts for referencing directories

## Suggestions:
- I would recommend to not download the zip file, as the formatting is very messy and difficult to read when you open it in notepad.
Instead, copy the code from the repo file, and then paste it in a notepad file, saving it as a .bat file and giving it a realistic name that a target would run.
- I also would suggest to run the code without the comments, as it will allow for faster execution time (cmd doesn't have to read and process each commented line).
- Be sure to first view the code before sending to target in order to set your email address, or if you wanted to make any changes or additions.
- If you would like to change the email it sends from, change the variables "GmailAccount" and "GmailPassword", which contain the credentials of the email that sends the ip info file (also commented where in the code).

## Extra Notes:
~~To make it more advanced, you could send the file or place it on the target's machine with a different icon than the gear used to denote .bat files. (replacing the image would trick a more experienced user). I would suggest converting the bat file to an .exe, where you can then define what image you would like to use for the executable.~~

**Reminder:** If you test the code on your machine, it will delete the .bat file. It's simple to create again, but it's something to keep in mind for lazy ones who don't want to have to recreate the file *cough* me *cough*
- To send the email, the default sending smtp email config is set for Gmail. For other email platforms, reference your smtp server address and assign the variable $SMTPServer to it. 
###### **IMPORTANT:** *If changing the sending email, you **MUST** change settings to ENABLE "Less Secure App Access." The default email already has this setting configured for use.*
- There are comments documenting what each line does to help understand if there are parts you would like to remove or that are adjustable.
- There is a comment in there ":: shutdown /r" that gives you the option to also shut down the machine; remove the comment ("::") to enable the command.
###### Tip:
***If playing as a prank, be sure that target would be fine if pc shuts down, as shutdown /r restarts their computer and WILL cause them to lose any unsaved work.
Use carefully and have fun! :D***


# 1993 TRAP.BAT
 Security


Creation Date: Unknown
Last update: 1993-03-22 14:22
OS: Novell Netware
Category: Security


TRAP.BAT was used to log snoopers in my file directory on the Novelle Network at St. Bedes Grammar school. 

It hopefully activated if I left myself logged in, or my login details were captured and the snooper was exploring the directory structure, or if an elevated user was running programs in directories. 

It has the following behaviours:

1. Logs the environment variables (which included user name) to a file. 
2. Write protects the file.
2. Prints a few intimidating messages.
3. Changes the user's CLI prompt to " °±²Û²±° i'm the nosy git who was in GITESH's area ". This persists after logout.
4. Sounds the 'bell' on the PC to draw the attention and alert users in the vacinity.
5. Logs out the user.

The characters: ° ± ² Û ² ± °  are shaded DOS boxes, not easily shown here.
 


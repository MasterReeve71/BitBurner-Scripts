First, use 'nano <name>.js' to create each of the scripts, using the name of each text file as <name> in the command.
Just copy/paste the text from each of the text files named for a script into the script of the matching name.

Then... simply type 'run start.js' on your in-game command line.

The scripts take care of:

1) hacking all the servers
2) buying additional servers to hack other servers
3) upgrading your purchased servers
4) buying/selling stocks (if you've already bought all the stock market stuff)
5) solving contracts (it doesn't do ALL of them, sadly... i haven't found code to solve them all)
6) buying and upgrading hacknet nodes

You still need to manually:

1) join factions
2) build rep with factions
3) buy augmentations from factions
4) install augmentations
5) buy all the stock market API stuff so auto-trade.js will work
6) advance through the game to get some parts of the scripts to function

Interestingly, this script seems to take more RAM to run on some 'home' servers than on others.
(If you're far enough into the game to understand that, you will. Otherwise, just take it as
a given and assume that you might not have enough RAM.)

If this is the case, you're basically back to 'hacking 101'. Use the 'auto-hack.js' script by
copying it to target servers and, once you've gotten root access on them, running the script
(use as many threads as possible) to have the script target the server it's on (use the target
server's name as all four of the scirpt's arguments).

Don't forget to run 'auto-hack.js' on your 'home' server, too, using as many threads as possible.
For this instance of the script, I recommend 'n00dles foodnstuff sigma-cosmetics joesguns' be 
the four arguments used, so as to maximize speed of hacking and cash-gain from hacking.

As you acquire port-opening programs, such as BruteSSH.exe, copy 'auto-hack.js' to the faction
servers, such as CSEC, and run the script there to target the weak target servers (use as many
threads as possible, as always) after you've rooted that server.

Save up money and upgrade your 'home' RAM until you can run the start script.

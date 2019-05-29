Welcome to the Tintin++ Soundpack for Mac

Written by A. R. Meyer

Getting Started:
In order for the Soundpack to work best, the following programs should be installed:
-Tintin++
-Sox
--TDSR

In my experience, Homebrew tends to have a more recent version of Tintin++ than Macports.

--Installing TDSR:
TDSR can be obtained from the git repository at https://github.com/tspivey/tdsr.git.
At a Terminal prompt, type: 
git clone https://github.com/tspivey/tdsr.git

Follow the instructions in the cloned directory to get TDSR up and running.

Install Homebrew from their website at: https://brew.sh

At a terminal prompt, type the following two commands:
brew install sox
brew install tintin

Change back to the directory where this soundpack was cloned to and type: ./start

If all goes well, the soundpack files will load and Tintin++ will be running.

If you wish to add your own personal aliases, actions, gags, Macros, or substitutions, please first open the user class by typing.:
#class User open
Enter the add the alias, action, gag, etc and then type: .save-class User
Note: Tintin classes are case-sensitive so please be sure to capitalize User. This will ensure the class is saved to the correct file in the correct location.


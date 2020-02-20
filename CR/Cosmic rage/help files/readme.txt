			**Introduction**

Thank you for taking the time to download the VIP Cosmic Rage Experience! This document provides instructions for installing and running the soundpack, as well as references to useful commands built into the pack. It is highly recommended you read the other files in this folder as well to answer any questions you have. Snapp thanks you for doing your part to keep what's left of his sanity intact.

			**System Requirements**

A computer capable of running the latest version of VIPMud 2.0 is a requirement. In addition, the soundpack requires at least 1 GB of RAM and a bit of extra processing power to accommodate the playing of wave files.  You should also have a sound card capable of playing multiple simultaneous audio streams. In this day and age, it's highly unlikely anyone would have issues, but best to be certain.
Included in the main soundpack directory is a file called sounds.ini. This file has been optimized to allow VIP to play up to 100 sound files at a time. Just copy sounds.ini into your main documents VIP directory and answer yes to the replace file prompt if you would like to take advantage of this feature.

			**Installation**

1. To install this soundpack, first go and obtain it. Several methods have been implemented for downloading the soundpack as well as all future updates.
	A. VIP2.0 downloads
		1. There is the standard .zip file. The link to obtain this is, https://www.dropbox.com/s/6s71ritxyidvkw3/Snapps%20VIP%20dropbox%20soundpack.zip?dl=1
		2. A shared Dropbox folder has been created as well. If you'd like to be invited to the folder, just let Angelica Hamilton or Lara Stardust know in game, and you will be invited as soon as possible.
	B. VIPMud 1.0 Downloads
		1. A VIPMud 1.0 pack has been created to support those users staying on the older version of VIPMud. This pack is very limited in sounds and features do to limits put in place within the program.
		2. The link to download this soundpack is 
https://www.dropbox.com/s/snndzzljnq558k8/Snapp%27s%20VIP1%20Soundpack%20for%20Cosmic%20Rage.zip?dl=1
2. You will need to go and make sure all the information is correct in the connection setup wizard within VIPMud. several questions have been asked about this, so answers will be provided.
	A. Under the Connect menu within VIPMud's menu structure, find the Character Setup/Connect option. Hit enter on that and you'll be dropped into the connection wizard. A few edit boxes and options will present themselves. The NVDA screen reader does not read these edit boxes, so the window text has been captured and is shown below. Fields that are required are marked with asterisks.
		1. *Character Name*. This is normally the name you give your character within the MUD. Not filling this out will cause the pack to throw errors. Note: This cannot be "Unnamed" and cannot contain spaces.
		2. *Character Reference*. A unique name that VIPMud uses to identify your character. It is usually the same as your character name, or if you use this character in other MUDs, a name closely related. Not filling this out will cause the pack to throw errors. Note: This cannot be "Unnamed" and cannot contain spaces.
		3. MUD List. This list is compiled from other characters you have created.  If you have already entered a character for a MUD, the MUD name will appear here. Select the MUD and press Enter.  The MUD related information will automatically be filled in.  If there is no reference to the MUD, Tab past this list and enter the MUD information in the following three edit boxes.
		4. *MUD Name*. The name the MUD calls itself. For the pack to work correctly, the MUD name must be Cosmic rage and be sure to include the space between Cosmic and Rage or else the pack cannot load correctly.
		5. *Host Name*. The address to the MUD. The available addresses to connect to Cosmic Rage are: cosmicrage.earth, cosmicrage.nathantech.net, or an IP address such as 87.106.252.196.
		6. *Port Number*. The port number is usually in the form of two to four digits and is usually supplied with the host name. The port for Cosmic Rage is 7777.
		7. Notes and Descriptions. A text box that is used to enter any information you need to remember regarding your character.
		8. Password. The password of the character. This information is securely encrypted in VIPMud and cannot be retrieved. If enabled, this information is used to automatically log your character into the MUD.
		9. Auto Login Checkbox. Check this if you would like your character logged in automatically. It uses the alias "login" from within start.set to perform this function.  If this alias doesn't work for a specific MUD, you can make the appropriate changes.
		10. Keep Variable Values checkbox. When checked, VIPMud will save your original and current variables files when you exit the character.  They are automatically loaded the next time you load the character.
		11. Simple Script Control checkbox. When checked, VIPMud will use the simple scripting file control method. See the "Using Script Files" section of the VIPMud manual for more details on this function.
3. After you have obtained the soundpack and completed the necessary steps from within VIPMud, select all from within the downloaded folder, then locate your VIPMud directory. Assuming you haven't moved the directory, it will be in your documents directory. The directory name should look something like this: C:\users\insertUsername\Documents\VIPMud Paste the downloaded folders content, then either restart VIPMud, or use the #reload command from within the game.
4. Upon first run of the pack, you must complete the following steps.
	A. Copy settings.set that is located in the root directory of the soundpack, then paste this file in Cosmic Rage/misc. Failing to copy this file will load the pack with very odd settings values, including audio volume being all the way at 100 percent. Users who already have settings how they'd like, feel free to ignore this file unless you lose all your settings data.
	B. Launch VIPMud. You will then need to set up your settings like buffers, volumes, toggles, ETC. Please see the help files for aliases and keys.
	C. Create a blank txt file and name it CosmicRageBufferlist.txt. Not having this bufferlist file in the vipmud root directory, will cause the soundpack to get angry and throw errors at you.
	D. Finally, save your packs settings with control-s. Failing to follow the directions by not typing Control-S will throw endless errors if you try to load the pack once more. If this happens, just type SaveBuffers, and you'll be fine. It is not our fault if you fail to do this. It's also a good idea to back up your buffer settings and general pack settings after you get them how you'd like.
If everything went according to plan, you should have a fully working pack! If something goes wrong, please go through and read the installation instructions outlined above and apply any changes necessary before contacting Angelica or Lara.

			**Updating Your Soundpack**

To update the soundpack using the Dropbox shared folder, please do the following:
1. Please hit alt-V or type SpVersion and take note of the latest change listed.
2. After this, open the folder that the soundpack is downloading to. Check the changelog and make sure you are seeing the last change that the moo showed.
3. Copy any files listed in the changelog, or you can just do a full copy of the folder. Please make sure to back up your characters .set file if you don't want to lose any added alias's or triggers.
If you have downloaded the zip version of the pack, first extract the folder, then copy the content of the soundpack directory into your VIPMud directory.
The Dropbox shared folder is updated as soon as changes to code or sounds are made, while the pack that has the downloadable link is updated each Sunday unless a major change is made.
adding custom music for ship combat
1, find some music
2, go to the sounds/music/combat folder
3, rename the files like in the folder like
theme 1.wav theme2.wav bla bla bla up to theme132.wav
nnote, there is no limit for this, as long as the music is at the wav format, and if you renamed your files like i did, you wont struggle
enter vipmud, note the pack should be loaded to this to work properly, that means you must hear the sounds fine as normal
5, type themechange and a number, this will be the max number that the music will end
like if you have 100 music in the combat folder, you should type themechange 100
note, if you dont want to pack to break, just type numbers here
6, enjoy
		 customising private networks
if your connected to more then 1 prvate network at a time, the channels may confuse
there for, we have a system that lets you spesify the networks your in and play diffrent sounds
1, go to the vipmud char manager, and click the cosmic rage character, like john cosmic rage
2, find edit
3, checked the save the variables apon logging off checkbox.
4, click ok.
5, login to game
6, type pn1, to for and a channelname
like
pn1  animal kingdom
the name should be exact with the game, 
or
pn4 ghostbusters
hope that helps

			**Miscellaneous Notes**

In some cases, ambience fails to work for some players. This is due to the fact that they have brief mode enabled. To fix this, type brief, then disable hiding of descriptions.
To access the configuration manager, please hit "F-2."
If by chance you find that a sound has gotten stuck, or is not acting as expected, you may use the alias StopSound, or the key Control-F11 to stop all currently playing sounds.
If you hear that gagging is in effect, please hit control-slash. This will force VIP to ungag your speech.
To view any of the help files related to this soundpack, you may either use the alias SpHelp, or use the key alt-shift-H.
To see the last change that was posted, without opening the changelog, you can either type SpVersion, or use the key Alt-V.
If you have a suggestion you'd like to see added to the pack, this can be done by using the alias "SpSuggest." A note about suggestions. If one of the soundpack administrators asks for text from you to make a trigger work, whether it be for gagging the text, adding a sound, etcetera, and no text has been given to create the suggested trigger after a month's time, the suggestion will be removed as it will be assumed it is no longer desired
If you have a bug that you need to report, this can be done by using the alias "SpBug."  Please be as detailed as possible in your bug report. Try to include the error, the command you sent that gave you the error, and any other misc information.  Bugs that contain just an error, or two words, are likely to be deleted as the soundpack administrators needs more details to implement a solution.

			**Error Notice**

If you're seeing errors and you have not updated your pack prior to October 10, 2018, you must totally replace the entire Cosmic Rage directory, get rid of Cosmic Rage/misc/settings.set, then resave. This is due to how options are now configured. Failing to do this causes the pack to try to read settings entries that are not in use any longer.
If you have updated and are not seeing errors when toggling options or changing volumes, you've nothing to worry about. This issue only seems to affect a small number of users.
If you have any questions or concerns, please first take a look at the Help Files directory. More than likely your question will be answered in one of those documents. If not, feel free to get ahold of one of the soundpack administrators via an OTR link or over the soundpacks channel in the game. To enable the soundpacks channel, please type spon from within the MUD. To disable the channel, use the command spoff. To establish an OTR link, please type olink then hit enter. You will then be presented with an edit field. Just type the name of one of the soundpack administrators and hit enter. One of the administrators will accept your link request as soon as possible. If more help is needed with OTR links, please read the help file "Communicating out of character" in Cosmic Rage's help system.
If a soundpack administrator is not around to answer your questions, likely someone is on the soundpacks channel who can. If not, you are more than welcome to send one of them mail on the MUD and that person will get back with you as soon as possible.

			**Compatibility**

This soundpack supports the Nathan Tech VIPMud soundpack installer.
Download from:  https://nathantech.net/files/VIPMud%20Soundpack%20Installer%20v1.0%20setup.exe

			**Legal Stuff and Things**

The soundpack administrators are not lawyers, don't know any lawyers, and are entirely unwilling to pay for the services of any legal advice regarding this project. That being said, you should note that the soundpack administrators do not guarantee any level of functionality of this soundpack with your particular situation.  The soundpack administrators may not necessarily always be available to answer questions, help you install it, ETC.  If your computer suddenly decides that it can't handle it, catches fire, melts down or produces extreme amounts of smoke or radiation that result in your untimely demise, we had nothing to do with it.  This soundpack has been tested under windows 7 and 10, as well as released for private beta use amongst friends. We would not be releasing it as such if he believed that it would not be functional to a level of acceptableness. But do keep in mind that the pack is constantly being developed, so check back frequently for updates! In smart and legal terms, we or any other developer of this pack cannot be held liable for any damages caused by using this pack or anything relating to this pack.

		*A note from Nate, the head admin of Cosmic Rage*

Hello!

While it is not said often, please take a moment to think about this soundpack.
Over 500, nearly 600 changes at the time of writing this file, stemming back over a year of soundpack development.
The road is long, and definitely not smooth.
Snapp working his way through like this though has been absolutely astounding.
There may be things you dislike about the pack.
There may be things you love about the pack.
But when you use it, make sure and tip your hat to snapp in a "thank you", because he's worked dang hard for it.
Thanks

Nate.

			Happy MUDding!
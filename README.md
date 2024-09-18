Fairy Tail Portable Guild - English Translaton patch
====================================================

To Start with let my make it clear I have no idea what I'm doing.
Also I would like to point out that this project will require the translation of over 150 diffrent files so don't expect this to be quick.
I would like some help if you are willing reach out to me at Alehmann04@post.com 

Discoveries
-----------

For anyone looking at this here is the info I have found. 
_________________________________________________________

1: The text is stored in PSP_Game/USRDIR/FTPack.cpk/Tables/

2: The text seems to be mostly stored in shift-js, but using ascii hexcodes works and latin characters are present in the font.

3: The hex is not perfictly spaced for 2 byte shift-js so the best working hex editor I've found is madedit.

4: The start of each text file seems to hold the names, order, and pictures of speakers.

5: The scrpits are not in order, what I mean is that somtimes the file calls previous lines or skips chunks.

6: The text porions of each of the files contain certin popups, location names, and title cards used during the events

What do you do?
---------------
In regards to how to use the stuff I'm giving you.
_________________________________________________

1: get an iso

2: double click the iso to mount it

3: open the "disc drive" and copy the whole thing to a folder

4: extract FTPack.cpk using critools from modohack in the thread here "https://gbatemp.net/threads/adding-fonts-files-with-special-characters-for-translated-games.567919/"

5: replace the tables in the table folder inside the FTPack.cpk with the ones im providing with 

6: use the tool again to rebuild FTPack.cpk using these settings ![image](https://github.com/user-attachments/assets/b001e839-0c00-4047-8a22-80bbf3d03273)

7: use UMDGen to recreate the iso 

8: run the iso

Done
----
* translate the item based on other repository
* Untranslated text added to the translation tables for: 
  * skills
  * materials
  * items

In Progress
-----------
* translate the materials
* Adding Untranslated text to the translation tables for eventtext000-010
  * Untranslated text added to the translation tables for:
    * eventtext000
	* eventtext001
	* eventtext002
	* eventtext003
	
Todo
----
* finish the eventtext000.bin translation
* complete translation tables
  * Add the untranslated text to each of the translation tables
    * Add untranslated text to the translation table for eventtext
    * Add untranslated text to the translation tables for eventtext011-020
    * Add untranslated text to the translation tables for eventtext021-030
    * Add untranslated text to the translation tables for eventtext031-040
    * Add untranslated text to the translation tables for eventtext041-050
    * Add untranslated text to the translation tables for eventtext051-060
    * Add untranslated text to the translation tables for eventtext061-070
    * Add untranslated text to the translation tables for eventtext071-080
    * Add untranslated text to the translation tables for eventtext081-090
    * Add untranslated text to the translation tables for eventtext091-100
    * Add untranslated text to the translation tables for eventtext101-110
    * Add untranslated text to the translation tables for eventtext111-120
    * Add untranslated text to the translation tables for eventtext121-130
    * Add untranslated text to the translation tables for eventtext131-140
    * Add untranslated text to the translation tables for eventtext141-150
    * Add untranslated text to the translation table for GuildEvent
    * Add untranslated text to the translation table for GuildEventText
    * Add untranslated text to the translation table for GuildEventFirst
    * Add untranslated text to the translation table for GuildEventFirstText
    * Add untranslated text to the translation table for Powerupitem
    * Add untranslated text to the translation table for Quest
    * Add untranslated text to the translation table for QuestAssist
  
  * Add the speakers to the translation tables for:
    * Add the speakers to the translation table for eventtext
	* Add the speakers to the translation tables for eventtext000-010
    * Add the speakers to the translation tables for eventtext011-020
    * Add the speakers to the translation tables for eventtext021-030
    * Add the speakers to the translation tables for eventtext031-040
    * Add the speakers to the translation tables for eventtext041-050
    * Add the speakers to the translation tables for eventtext051-060
    * Add the speakers to the translation tables for eventtext061-070
    * Add the speakers to the translation tables for eventtext071-080
    * Add the speakers to the translation tables for eventtext081-090
    * Add the speakers to the translation tables for eventtext091-100
    * Add the speakers to the translation tables for eventtext101-110
    * Add the speakers to the translation tables for eventtext111-120
    * Add the speakers to the translation tables for eventtext121-130
    * Add the speakers to the translation tables for eventtext131-140
    * Add the speakers to the translation tables for eventtext141-150
    * Add the speakers to the translation table for GuildEvent
    * Add the speakers to the translation table for GuildEventText
    * Add the speakers to the translation table for GuildEventFirst
    * Add the speakers to the translation table for GuildEventFirstText
    * Add the speakers to the translation table for Quest
    * Add the speakers to the translation table for QuestAssist
  
  * Directly translate the text in the translation tables
    * Directly translated text added to translation tables for eventtext011-020
    * Directly translated text added to translation tables for eventtext021-030
    * Directly translated text added to translation tables for eventtext031-040
    * Directly translated text added to translation tables for eventtext041-050
    * Directly translated text added to translation tables for eventtext051-060
    * Directly translated text added to translation tables for eventtext061-070
    * Directly translated text added to translation tables for eventtext071-080
    * Directly translated text added to translation tables for eventtext081-090
    * Directly translated text added to translation tables for eventtext091-100
    * Directly translated text added to translation tables for eventtext101-110
    * Directly translated text added to translation tables for eventtext111-120
    * Directly translated text added to translation tables for eventtext121-130
    * Directly translated text added to translation tables for eventtext131-140
    * Directly translated text added to translation tables for eventtext141-150
    * Directly translate the skills

** Complete the translation of the Hex files
  * Add translated names to the bin files for:
    * Add translated names to the bin file for eventtext
	* Add translated names to the bin files for eventtext000-010
    * Add translated names to the bin files for eventtext011-020
    * Add translated names to the bin files for eventtext021-030
    * Add translated names to the bin files for eventtext031-040
    * Add translated names to the bin files for eventtext041-050
    * Add translated names to the bin files for eventtext051-060
    * Add translated names to the bin files for eventtext061-070
    * Add translated names to the bin files for eventtext071-080
    * Add translated names to the bin files for eventtext081-090
    * Add translated names to the bin files for eventtext091-100
    * Add translated names to the bin files for eventtext101-110
    * Add translated names to the bin files for eventtext111-120
    * Add translated names to the bin files for eventtext121-130
    * Add translated names to the bin files for eventtext131-140
    * Add translated names to the bin files for eventtext141-150
    * Add translated names to the bin file for GuildEvent
    * Add translated names to the bin file for GuildEventText
    * Add translated names to the bin file for GuildEventFirst
    * Add translated names to the bin file for GuildEventFirstText
    * Add translated names to the bin file for Quest
    * Add translated names to the bin file for QuestAssist

Add implementable translations to the translation tables

Credit
------
I would like to credit this repository with having some of the game's text translated. "https://github.com/Aerow/Fairy-Tail-Translation"

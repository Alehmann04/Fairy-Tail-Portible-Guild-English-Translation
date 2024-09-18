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
* ★ Completly translated
  * ★ items
	
Todo (□ = not done, ▼ = Partal, ★ = done)
----
* □ complete translation tables
______________________________
  * □ Add the untranslated text to each of the translation tables for:
    * □ eventtext
    * ▼ eventtext000-010 (000, 001, 002, 003)
    * □ eventtext011-020
    * □ eventtext021-030
    * □ eventtext031-040
    * □ eventtext041-050
    * □ eventtext051-060
    * □ eventtext061-070
    * □ eventtext071-080
    * □ eventtext081-090
    * □ eventtext091-100
    * □ eventtext101-110
    * □ eventtext111-120
    * □ eventtext121-130
    * □ eventtext131-140
    * □ eventtext141-150
    * □ GuildEvent
    * □ GuildEventText
    * □ GuildEventFirst
    * □ GuildEventFirstText
    * □ Powerupitem
    * □ Quest
    * □ QuestAssist
    * ★ skills
    * ★ items
    * ★ materials
  * □ Add the speakers to the translation tables for:
    * □ eventtext
    * ▼ eventtext000-010 (*000)
    * □ eventtext011-020
    * □ eventtext021-030
    * □ eventtext031-040
    * □ eventtext041-050
    * □ eventtext051-060
    * □ eventtext061-070
    * □ eventtext071-080
    * □ eventtext081-090
    * □ eventtext091-100
    * □ eventtext101-110
    * □ eventtext111-120
    * □ eventtext121-130
    * □ eventtext131-140
    * □ eventtext141-150
    * □ GuildEvent
    * □ GuildEventText
    * □ GuildEventFirst
    * □ GuildEventFirstText
    * □ Powerupitem
    * □ Quest
    * □ QuestAssist
  
  * □ Directly translate the text in the translation tables for:
    * □ eventtext
    * □ eventtext000-010
    * □ eventtext011-020
    * □ eventtext021-030
    * □ eventtext031-040
    * □ eventtext041-050
    * □ eventtext051-060
    * □ eventtext061-070
    * □ eventtext071-080
    * □ eventtext081-090
    * □ eventtext091-100
    * □ eventtext101-110
    * □ eventtext111-120
    * □ eventtext121-130
    * □ eventtext131-140
    * □ eventtext141-150
    * □ GuildEvent
    * □ GuildEventText
    * □ GuildEventFirst
    * □ GuildEventFirstText
    * □ Powerupitem
    * □ Quest
    * □ QuestAssist
    * ▼ skill
    * ★ items
    * ▼ material
	
  * □ Add implementable translations to the translation tables for:
    * □ eventtext
    * ▼ eventtext000-010 (*000)
    * □ eventtext011-020
    * □ eventtext021-030
    * □ eventtext031-040
    * □ eventtext041-050
    * □ eventtext051-060
    * □ eventtext061-070
    * □ eventtext071-080
    * □ eventtext081-090
    * □ eventtext091-100
    * □ eventtext101-110
    * □ eventtext111-120
    * □ eventtext121-130
    * □ eventtext131-140
    * □ eventtext141-150
    * □ GuildEvent
    * □ GuildEventText
    * □ GuildEventFirst
    * □ GuildEventFirstText
    * □ Powerupitem
    * □ Quest
    * □ QuestAssist
    * ▼ skill
    * ★ items
    * ▼ material

* □ Complete the translation of the Hex files
_____________________________________________
  * □ Add translated names to the bin files for:
    * □ eventtext
    * □ eventtext000-010
    * □ eventtext011-020
    * □ eventtext021-030
    * □ eventtext031-040
    * □ eventtext041-050
    * □ eventtext051-060
    * □ eventtext061-070
    * □ eventtext071-080
    * □ eventtext081-090
    * □ eventtext091-100
    * □ eventtext101-110
    * □ eventtext111-120
    * □ eventtext121-130
    * □ eventtext131-140
    * □ eventtext141-150
    * □ GuildEvent
    * □ GuildEventText
    * □ GuildEventFirst
    * □ GuildEventFirstText
    * □ Powerupitem
    * □ Quest
    * □ QuestAssist
	
  * □ Add the translated text to the bin files for:
    * □ eventtext
    * □ eventtext000-010
    * □ eventtext011-020
    * □ eventtext021-030
    * □ eventtext031-040
    * □ eventtext041-050
    * □ eventtext051-060
    * □ eventtext061-070
    * □ eventtext071-080
    * □ eventtext081-090
    * □ eventtext091-100
    * □ eventtext101-110
    * □ eventtext111-120
    * □ eventtext121-130
    * □ eventtext131-140
    * □ eventtext141-150
    * □ GuildEvent
    * □ GuildEventText
    * □ GuildEventFirst
    * □ GuildEventFirstText
    * □ Powerupitem
    * □ Quest
    * □ QuestAssist
    * □ skill
    * ★ items
    * □ material	

Credit
------
I would like to credit this repository with having some of the game's text translated. "https://github.com/Aerow/Fairy-Tail-Translation"

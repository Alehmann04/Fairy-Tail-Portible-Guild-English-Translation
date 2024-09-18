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
* Untranslated text added to translation tables for skills, materials, and items

In Progress
-----------
* translate the materials
* Untranslated text added to translation tables for eventtext000-010

Todo
----
* finish the eventtext000.bin translation
* Add the untranslated text to each of the translation tables
  * untranslated text added to translation tables for eventtext011-020
  * untranslated text added to translation tables for eventtext021-030
  * untranslated text added to translation tables for eventtext031-040
  * untranslated text added to translation tables for eventtext041-050
  * untranslated text added to translation tables for eventtext051-060
  * untranslated text added to translation tables for eventtext061-070
  * untranslated text added to translation tables for eventtext071-080
  * untranslated text added to translation tables for eventtext081-090
  * untranslated text added to translation tables for eventtext091-100
  * untranslated text added to translation tables for eventtext101-110
  * untranslated text added to translation tables for eventtext111-120
  * untranslated text added to translation tables for eventtext121-130
  * untranslated text added to translation tables for eventtext131-140
  * untranslated text added to translation tables for eventtext141-150
* For relevant files add the speaker to the translation table
  * add the speaker to translation tables for eventtext011-020
  * add the speaker to translation tables for eventtext021-030
  * add the speaker to translation tables for eventtext031-040
  * add the speaker to translation tables for eventtext041-050
  * add the speaker to translation tables for eventtext051-060
  * add the speaker to translation tables for eventtext061-070
  * add the speaker to translation tables for eventtext071-080
  * add the speaker to translation tables for eventtext081-090
  * add the speaker to translation tables for eventtext091-100
  * add the speaker to translation tables for eventtext101-110
  * add the speaker to translation tables for eventtext111-120
  * add the speaker to translation tables for eventtext121-130
  * add the speaker to translation tables for eventtext131-140
  * add the speaker to translation tables for eventtext141-150
* for relevent files translate names
  * translated names added to translation tables for eventtext011-020
  * translated names added to translation tables for eventtext021-030
  * translated names added to translation tables for eventtext031-040
  * translated names added to translation tables for eventtext041-050
  * translated names added to translation tables for eventtext051-060
  * translated names added to translation tables for eventtext061-070
  * translated names added to translation tables for eventtext071-080
  * translated names added to translation tables for eventtext081-090
  * translated names added to translation tables for eventtext091-100
  * translated names added to translation tables for eventtext101-110
  * translated names added to translation tables for eventtext111-120
  * translated names added to translation tables for eventtext121-130
  * translated names added to translation tables for eventtext131-140
  * translated names added to translation tables for eventtext141-150
* Directly translate the text in the translation tables
  * Directly translated text added to translation tables for eventtext011-020
  * translated names added to translation tables for eventtext021-030
  * translated names added to translation tables for eventtext031-040
  * translated names added to translation tables for eventtext041-050
  * translated names added to translation tables for eventtext051-060
  * translated names added to translation tables for eventtext061-070
  * translated names added to translation tables for eventtext071-080
  * translated names added to translation tables for eventtext081-090
  * translated names added to translation tables for eventtext091-100
  * translated names added to translation tables for eventtext101-110
  * translated names added to translation tables for eventtext111-120
  * translated names added to translation tables for eventtext121-130
  * translated names added to translation tables for eventtext131-140
  * translated names added to translation tables for eventtext141-150
* translate the skills
* translate the rest of the text

Credit
------
I would like to credit this repository with having some of the game's text translated. "https://github.com/Aerow/Fairy-Tail-Translation"

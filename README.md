To Start with let my make it clear i have no idea what im doing.
For anyone looking at this here is the info i have found 
1: the text is stored in PSP_Game/USRDIR/FTPack.cpk/Tables/
2: the text seems to be mostly stored in shift-js but using ascii hexcodes works and latin characters are present in the font
3: the hex is not perfictly spaced for 3 byte shift-js so the best working hex editor ive found is madedit

in regards to how to use the stuff im giving you.
1: get an iso
2: double click the iso to mount it
3: open the "disc drive" and copy the whole thing to a folder
4: extract FTPack.cpk using critools from modohack in the thread here "https://gbatemp.net/threads/adding-fonts-files-with-special-characters-for-translated-games.567919/"
5: replace the tables in the table folder inside the FTPack.cpk with the ones im providing with 
6: use the tool again to rebuild FTPack.cpk
7: use UMDGen to recreate the iso 
8: run the iso

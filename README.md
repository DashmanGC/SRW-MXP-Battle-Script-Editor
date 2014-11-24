SRW MX Portable Battle Script Editor by Dashman
---------------------------------------

This program allows you to edit the contents of BATTLE files extracted from BATTLE2.BIN using the BATTLE2 Splitter application.


How to use this:

I think it's pretty straightforward, but here's some basics:

1) Go to File -> Open and browse for one of the BATTLE files.

2) Once you open the file, the Navigation panel (top-left) will be activated and will display which battle quote out of the total you're viewing (you start at the first). Use the controls in this panel and the options in the Navigate menu to move through the different battle quotes inside the file.

3) You have two text areas displaying the battle quotes. The one on the left shows the text read originally, the one on the right is where you write your translation (initially has the same original text).

4) When writing your translation, keep an eye on the top-right, where you can see how much screen width will be used by the quote. If it turns red, you wrote too much. The game probably won't care, but the player will have a harder time reading that.

* NOTE: It's not been tested yet, but it's possible that the game will shrink lines that are too long. I'd try to stick to the max width listed, just in case.

5) You can ignore the Tools menu and the "Convert keystrokes to SJIS" option, those are there just in case somebody decides to use VWF in the future.

6) Once you're done editing, go to "File -> Save as..." to save your modifications as another BATTLE file. The file saved through this CAN'T BE USED BY THE GAME. Well, it can, but the game will probably crash. The reason I tell you to save in this format is because if you open your saved file again, you'll be able to read the quotes the way you wrote them. The other save option saves the text after converting every letter pair into kanji, which you most probably won't understand. ALWAYS make a save of your edits with this method.

7) To save your edits as a file that the game can read, you have to use "File -> Convert and Save as...". You should only do this when you want to create files to insert into the game.


IMPORTANT NOTES:

* The keys assigned to the options in the Navigate menu won't work if you're inside a text area. Try clicking into the "Jump to" field if you want to use these keys.

* A battle quote can only have 2 lines. If you use more than that, well, anything can happen. Don't use more than 2 lines.

* The files don't contain the name of the characters who speak. However, you can extract the TX48 files from BFACEPACK_ADD.BIN to partially orientate yourself.

* Battle quotes inside a BATTLE file are typically repeated. That is, you can have several instances of the same battle quote for different actions. However, you shouldn't see any repetition, since the program takes note of the all the repetitions and only displays each different quote once. That also means that, if you translate two similar quotes with the exact same text, save your changes and open the file again, you'll see one quote less than before in the total. It's still there, don't panic.
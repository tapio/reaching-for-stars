Reaching for Stars! README
--------------------------
(for version beta 3)

CONTENTS
 
 1. About & License
 2. Installation & Requirements
 3. Gameplay
       Galaxy view controls
       Other keys
       Hints
       How to Play-by-E-Mail or through LAN
       How to add your own race pictures
 4. Credits
 5. Known Issues
 6. Version History



1. ABOUT & LICENSE
------------------
Reaching for Stars! is a space empire game (a bit like Master of Orion). You take control of a race and try to survive in a star cluster with other races.

This game is free. It is licenced under Creative Commons 3.0 Attribution license, which allows you to distribute and modify the game freely as long as my name (Tapio Vierros) is mentioned in the credits. More info in LICENSE-file.


2. INSTALLATION & REQUIREMENTS
------------------------------
Just unzip the zip-archive into your desired location.
The game requires DirectX 7.0 or higher and Windows 98 or higher and around 3 MB of free storage space.
Read & Write rights are required in order the game to function.


3. GAMEPLAY
-----------

Galaxy view controls:
 *Left click selects stars and fleets
 *Hold right mouse button while moving mouse to rotate stars
 *Hold left mouse button while moving mouse to move stars
 *Use mouse wheel to zoom
 *[Backspace] or press mousewheel to deselect current selection
 *[Tab] resets the positions of stars and tabs (in galaxy-view)
 *[Space] toggles selected star/fleet centering (default: on)
 *Hold [Shift] while rotating the stars to rotate around galaxy center

Other keys:
 ESC - Menu/Resume/Close Screen
 F9  - Save (in galaxy-view)
 F10 - Load (in galaxy-view)
 F11 - Screenshot (will be saved as shot#####.bmp, where ##### is a random number)
 §   - Console
 CTRL + Q = Instant Quit

Hints:
 * Allways have a research project in progress, otherwise the research resources are wasted (they don't stack).
 * Be careful when adjusting the solar systems' sliders; in most cases you don't want to let the ecology drop too low as it will decrease your population and thus decrease production resources.
 * When sending an attack fleet, remember that travelling is slow (without proper propulsion technics); if your forces were superior when they set sail, the enemy has plenty of time to build cannons and ships, while you are travelling.
 * If you have a relatively small galaxy, it might be easier to handle it if you disable the "auto-center selection" feature by hitting spacebar.

How to Play-by-E-Mail or through LAN?
Start a new game with a right number of non-AI players and play your turn. When you have ended your turn and the game asks for password for the next human player, press ESC and save the game from the menu. After that, swap to Windows and send the save game file, located in the saves-directory, to the next player by E-mail or through local area network (you have to do this manually, as you can see). The receipist moves the save game file to the saves-folder and loads it from the game menu, enters a password, plays his turn, saves and sends the file to the next player.
NOTE: If your computers share a folder (or a hard-drive) you can change the saving directory to point to that folder, so you won't need to move the save game files manually: This is done by hitting the §-key in the galaxy view and typing "savedir C:\SharedFolder" without quotation marks; C:\SharedFolder being the path to the shared folder. Savedir will reset when the program is exited.

How to add your own race pictures?
Make a 60*60 pixels png (Portable Network Graphics) image with a white (RGB 255,255,255) background color and place it in the game's data/races -folder.



4. CREDITS
----------
This is game is coded and designed by Tapio Vierros.
Some of the UI elements have been modified from codes of others:
button - nixe
listbox - jare
textfield - alodnal
radiobutton - alodnal



5. KNOWN ISSUES
---------------
 * AI is not very smart
 * Inputfields don't support arrowkeys nor numpad
 * Fleets cannot engage other fleets that are in space
 * No sounds



6. VERSION HISTORY
------------------

beta 3 (public)
 * AI has taken first steps in communication
 * most screens are now windows

beta 2 fix 1
 * bug fixes and balancing
 * slightly smarter AI

beta 2 (public)
 * first public version!
 * sabotage & spying (for AI as well)
 * fleets can change destination during flight
 * filing and hordes of bug fixes & tiny new features

beta 1
 * some kind of AI
 * improved multiplayer with password protection
 * turn style of the game was changed from simultaneous to sequential
 * new game generation screen
 * galaxy centers around selection, making the management of bigger galaxies possible
 * "fog-of-war" (only the positions and color of further away stars are visible)

alpha 3
 * diplomacy
 * primitive multiplayer possibility
 * new InputBox (previous used Windows API)
 * most of the code was transfered inside functions (doesn't see outside, but was quite important in other ways)

alpha 2
 * travelling, landing and invasions
 * technology system
 * saving and loading

alpha 1
 * 3d galaxy
 * economy
 * simplified travelling

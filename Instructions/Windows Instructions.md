# Windows Instructions
Please note that this modpack is optimized for 1920 x 1080 displays in full screen mode and for Large GUI scale, if your display has a different resolution you will have to edit a couple of settings after you install the Modpack.

 

 

1. Install Java (if you haven't already). (You can download it from https://www.java.com).

​

2. Launch the Modpack (Double click the "CheatBreaker Modpack.exe" file, Click the launch button, and log in with your Minecraft email and password. The modpack will crash on the first launch.

​

3. At first you won't see your skin at the top near your username, it's a glitch with the CustomMainMenu mod on 1.7.10. To get your skin to show there you will need to open your CheatBreaker Modpack folder (Its in your Documents folder), then go to instances/CheatBreaker Modpack/minecraft/config, then open the CustomMainMenu folder and open the "mainmenu.json" file with NotePad++. In line 16 (in the "mainmenu.json" file) edit the #username# text to your username (example: "image" : "web:https://minotar.net/helm/ShonP40/64.png",).

​

4. If the main menu will look fine (all the buttons will be in their place and the background picture will be centered) then precede to "Settings that need to be changed", but if your main menu is messed up, continue to the troubleshooting steps at the bottom of this file and then come back to the "Settings that need to be changed".


Settings that need to be changed:

​

1. If you want to use the Clear Glass mod you need to turn off Connected Textures by going to Options, Video Settings..., Quality....

​

2. On the first time that you start the modpack and join a server or a single player world, their will be a pop-up from The VoxalMap mod, to dismiss it simply press M (or the button that you've mapped for entering the VoxalMap menu).

​

In-Game commands:

/cbhud - Access the CheatBreaker Hud to edit the location of the mods on your screen.
/perspectivemod - Allows you to choose to hold or to click the Left Alt key for the perspective mod.
/wingsmod - Allows you to turn on or off and edit your wings.
/sidebarmod - Allows you to edit the sidebar.
/motionblur - Allows you to enable or disable motion blur.
/glintcolorizer - Allows you to turn on or off Shiny Pots/Enchanted items or change the color of the pots/enchanted items.
/fasttime - Changes the game time speed (Only on your screen).
/day - Sets the game time to day (Only on your screen).
/night - Sets the game time to night (Only on your screen).
/sunset - Sets the game time to sunset (Only on your screen).
/resettime - Resets the game time back to vanilla time (Server controlled or world controlled).

/cooldowns - Allowes you to edit the Cooldowns location or add new cooldowns.
/directionhud - Allowes you to edit the Directions HUD.

Press P to access the Profiles Mod.



Troubleshooting:

If your main screen buttons (Single player, Multiplayer, etc...) are messed up or the image is not centered then you will need to follow the steps:

1. Go to your CheatBreaker Modpack folder (Its in your Documents folder).

​

2. Go to instances/CheatBreaker Modpack/minecraft/config.

​

3. Go to the CustomMainMenu folder.

​

4. Open the "mainmenu.json" file with NotePad++ (you can download it from here: https://notepad-plus-plus.org/download/)

​

5. Find the "refresh" section, edit the "text" line (just type there something that you will see [for example: "text" : "Refresh",] (you can delete it later)  and change the posX and posY to 0 ("posX" : 0,) ("posY" : 0,).

​

6. Now launch the modpack, put your minecraft into the mode that you are playing with (for example full screen) and if you've edited it right, you will see the text that you've writed in the middle of the screen.

​

7. Now play with the posX and posY of the refresh button until the button will be an the bottom left of the screen (just change the number in the posX and posY lines and press the refresh button every time you edit them).

​

8. At this point you can delete the text of the refresh button (leave just the brackets).

​

9. Now play with the posX and posY numbers of the "title" (main image) and of the buttons: Singleplayer, Multiplayer, Options, Cosmetics (aka mods list), Exit button, skin photo and the username until you get every thing in place like in the image on the home page (at the bottom of the page) (Its the second image).

​

10. Enjoy

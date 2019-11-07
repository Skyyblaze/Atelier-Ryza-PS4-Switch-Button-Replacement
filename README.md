# Atelier-Ryza-PS4-Switch-Button-Replacement

General Info:

In this guide I'll explain how to alter the game to either show Playstation 4 Dualshock 4 or Nintendo Switch Pro Controller icons instead of the default XBOX One icons so let's get going! :)

You'll need the SpecialK injector for that and we'll be using a specific older version since the newer ones somewhat cause trouble with certain other things in Atelier Ryza.

The texture-mod is based upon the work of Steam User Monterossa from here: https://steamcommunity.com/app/1121560/discussions/0/1696095261011549013/

I simply built onto their work and expanded it for all languages and Nintendo Switch icons.

Unlike theirs, my mod does not include a X and O swap and also doesn't swap the touch-pad icon for the SHARE button icon for the PS4 version. However my guide will also explain how to get the correct touch-pad and SHARE behavior on PC with a Dualshock 4.



Necessary Downloads:

Special K 0.9.8: mega.nz/#!UN5BhSCQ!AYetU7JyoDbFyE8eFiKOfqbChMO84NVEKCi_xsAH9aw


Known Issues:

The configurator appears when launching the game:

Due to the game reacting a bit weird to the injector it can happen that the game's configurator appears when launching the game, sometimes multiple times. You can simply click it away with "Cancel" each time and the game will launch.

Game crashes right after launching:

This can also happen on some configurations, in this case go to your dxgi.ini and set

Fullscreen=false

to

Fullscreen=true

it might help on your system.


Installation:

I'll try to make the instructions as simple as possible and step by step.

1: Unpack the Special K injector and my mod to a safe location

2: Open your Ryza game folder, you can do so by right-clicking on the game in Steam --> Manage --> Browse Local Files

3: Copy

- CEGUI
- SK_Res
- dxgi.dll
- dxgi.ini

from the Special K download to your Atelier Ryza folder

4: Copy the SK_Res folder you wish to use from my mod to the Atelier Ryza folder. You can chose between Playstation 4 Dualshock icons or Nintendo Switch Pro Controller icons.

5: Launch the game and enjoy! :D


How to make the Dualshock 4 Touchpad work like on a PS4:

If you are playing with a PS4 controller you might now notice that the game shows the PS4 touchpad icon in a few cases but only half of the touchpad actually works as intended and the SHARE button has the same function as half of the touchpad.

To fix this and get the same experience as on an actual PS4 you can load my customized controller configuration. It will make the whole touchpad work as intended and as a bonus let you take screenshots with the SHARE button.

To use my configuration, first connect your PS4 controller to your PC either wireless or wired and then enter the following link in your web-browser:

steam://controllerconfig/1121560/1903246374

A new Steam Input window should pop-up letting you preview the configuration. Press Square to apply and save it. When you launch the game now the new config should be loaded.

Warning:

This won't work if you use DS4Windows or any other Dualshock 4 tool. It's intended for users that use a Dualshock 4 via Steam's native Steam Input implementation.


Special Thanks:

I want to thank the following Steam Users for helping me with this mod in one way or another:

Monterossa
Uranus Queen
30705

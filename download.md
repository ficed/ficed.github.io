# Download

Download [Braver v0.1.5 here](https://github.com/ficed/Braver/releases)

Unzip the files to any location, then run BraverSetup. It will ask
you to enter a few locations - mainly where FF7 is installed.

You can then run Braver.exe and hopefully, you will see the starting menu!

![Starting menu](splash.png)

If you have an XInput-compatible gamepad connected, the first gamepad should
automatically control the game. Alternatively, the default keyboard controls
are as follows:

| Key | Game control |
| --- | ------------ |
|  W  | Up |
|  A  | Left |
|  S  | Down |
|  D  | Right |
|  Enter  | OK |
|  Space  | Cancel |
|  [  | Left shoulder / rotate left |
|  ]  | Right shoulder / rotate right |
|  F1  | Start |
|  F2  | Select |
|  F3  | Menu |

## In case of problems

Braver should create a log file called `log.txt` in the folder you ran it from.
Any errors should hopefully be recorded here.

## Plugins

Braver supports various plugins to alter the functionality of the engine. Plugins can be enabled or configured from the second tab of the launcher. The plugins included with the base engine are:

### Tolk

Allows outputting the menu UI and various descriptions of the game locations and actions via text-to-speech engines using the Tolk library. Also supports footstep sounds that trigger only when the character is moving, to help work out when you're stuck on a wall or not, and "focus" sound effects to select an object in field locations and play a regular ping that increases in frequency as you approach the object.

### FFNx Compatibility

Supports various FFNx additional features such as ambient field audio and replacement sound effects. Usually only makes sense to enable this in combination with 7th Heaven mods.

### 7th Heaven compatibility

Basic - not yet complete! - support for loading 7th Heaven mods within Braver. To enable a mod, copy the .IRO file into the same folder as the plugin, usually plugins\7HCompatibility. Then run the Braver launcher and any options for the 7th Heaven mod will show up against this plugin.

So far, replacement sound effects, music, and field ambient sounds have basic support. Other mods that replace files, such as difficulty or dialog changes, may or may not work - full 7th Heaven compatibility isn't complete yet.

## v0.1.5

Release July 23rd 2023. Added a lot more plugin options, including basic 7th Heaven and FFNx support.

## v0.1.1

Released March 21st 2023. Should allow playing field locations up to the point 
where you leave the bar to begin the second reactor mission.

![Sector 7](v0_1_1.png)

## v0.1.0

Released March 13th 2023. Initial public release. Allows playing
field locations up to the train scenes while escaping from the first 
reactor mission.
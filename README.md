# TBar-Engine
The Enhanced Engine that makes lua coding easier and adds more functions as well to make programming more expansive (includes ghostUtil functions)
# Features
The T-Bar Engine contains a lot of extra functions that separates itself from Psych Engine, including:
1. 3D Model support:
  this is the big one, 3D model support! A couple things to note is that you'll need to use things like awayBuilder to make   models for the game (or blender if you can follow its limitations). Now as of right now there isn't any lua functions       added that can add 3D models, so you'll need to use ```runHaxeCode()``` and ```addHaxeLibrary``` to add them. All of the 
  libraries are added to PlayState and FunkinLua so you can just use these for ```addHaxeLibrary```.

2. More Lua Lines:
   Way more lua lines have been added for better and more possibilities for lua coders. for example:
   ```setWindowMode('DARK')```
   ```getDataFromURL('https://www.youtube.com)```
   ```doTweenNumber('coolTween', 1, 45, 3, 'sineInOut')```
  In addition to this, GhostUtil functions have also been added (huge thanks to GhostGlowDev)
   ```setWindowProperty", function('borderless', true)```
   ```windowAlert('Hi, I'm a message', 'Title Lol')```
   ```windowTweenY('windowGoBurY', 100, 7, 'linear')```

4. New Options:
   New options are added to the options menu now! This includes a whole new section: Application, a window theme changer,      an option to enhance the FPS. The FPS Enhancer makes the FPS limit higher than ever, so you can go up to 500 FPS!
   
# How To Compile
To compile the TBar Engine source, you'll need to follow the Psych Engine installations, as this engine uses the same projects.
You'll need some extra projects too. first you'll need to install away3D so 3D model functionality can work. to do this, simply go into cmd and type:
```haxelib install away3d```
if you need to install a specific version, add it to the command:
```haxelib install away3d 5.0.9```
Now you got everything set up for compiling!

# Credits
~T-Bar: Main Programmer / Creator / Owner
~Ghost: Cool Guy / Owner of GhostUtil
~Original Psych Engine Crew: Created Psych Engine
~Funkin' Crew: Created the base game

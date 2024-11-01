# T-Bar Engine Changelog

---

## v1.0.0
> ### Options Menu 
> 
> - **Graphics** <br> 
>     - **`Show Memory`**: Show the memory part of the FPS text. Changes instantly if your over 63 fps.
> - **Visuals & UI** <br> 
>     - **`FPS Enhancer`**: "Enhances" the game's FPS limit. The FPS new limit is 500 FPS (might not run well on bad cpu's)
> - **Application** <br> 
>     - **`Auto Pause`**: If you unfocus the application, the game will auto pause, else it will just keep running like normal.
>     - **`Fullscreen`**: Game goes into fullscreen mode.
>     - **`Window Mode`**: Your perfered window mode, can be Dark Mode or the default Light Mode.
> 
> ### Lua Variables
> 
> - **Edited**:
>   - **`version`** <sup>(string)</sup>: now shows "tbarEngine " in front of the tbar engine version. Perfect for checking if a modpack is running on the T-Bar Engine.
>
> - **New Features**:
>   - **`versionTBarEngine`** <sup>(string)</sup>: Same as 'version', only without the "tbarEngine " and just shows the version.
>   - **`FPSEnhance`** <sup>(boolean)</sup>: Checks to see if the option "FPS Enhancer (Visuals & UI)" is enabled.
>   - **`autoPause`**: <sup>(boolean)</sup>: Checks to see if the option "Auto Pause (Application)" is enabled.
>   - **`fullScreen`** <sup>(boolean)</sup>: Checks to see if the option "Fullscreen (Visuals & UI)" is enabled.
>   - **`windowMode`** <sup>(string)</sup>: Checks to see what option in "Window Mode (Application)" section is selected (can either return "DARK" or "LIGHT").
>   - **`showMemory`** <sup>(boolean)</sup>: Checks to see if the option "Show Memory (Graphics)" is enabled.
>   <br>
>   <br>
>   - **Online Variables**:
>     - **`introText`** <sup>(string)</sup>: All of the intro text used on the title screen. Returns the entire string.
>     - **`discordClient`** <sup>(string)</sup>: Returns the current Disord RPC client ID as a string.
>     - **`latestVersion`** <sup>(string)</sup>: Grabs the latest version of the T-Bar Engine. It's kinda useless as this can change and could break some scripts but it there if you need it.
>     - **`mainEngineWebsite`** <sup>(string)</sup>: Returns the link to the main website where you can download the T-Bar Engine.
>   <br>
>   <br>
>   - **Application / Monitor**:
>     - **`defaultWidth`** <sup>(number)</sup>: The default width of the game. Equals to 1280.
>     - **`defaultHeight`** <sup>(number)</sup>: The default height of the game. Equals to 720.
>     - **`moniterWidth`** <sup>(number)</sup>: The width of your moniter screen.
>     - **`moniterHeight`** <sup>(number)</sup>: The Height of your moniter screen.
> 
> ### General
> - Added a package that lets the game support 3D model files. For now, its only accessable using custom paths and `runHaxeCode`/HScript.
> - Discord RPC has been updated with Buttons.
> - Online data has been added.
> - Added the "Applications" Category to the Options menu.
> - Added "Show Memory (Graphics)" and "FPS Enhancer (Visuals & UI)" as options.
> - Added a countdown animation (can be disabled using `setProperty('countdownAnimation', false)`)
> - Time Bar color now changes depending on the character Icon color (can be disabled using `setProperty('timeBarColors', false)`)
> - Added `RPCDetails` and `RPCState` to keep track of the discord rpc details all in one place.
> - Score text and Time text now turn pixelated if the current stage is a pixel stage.
> - Rating Popups now have Angular Acceleration if not a pixel stage.
> - The health icon's antialiasing is false when the current stage is a pixel stage, for better looking pixel icons.
> - Botplay text bops.
> - Added a new map: `modchartBackdrops`. Used with `makeLuaBackdrop` and `addLuaBackdrop` to have `FlxBackdrop` in the game.
> - Chroma Shader has been added. can be accessed using `setSpriteChroma` or using filters. Class path is `shaders.ChromaShader`.
> - 3D model support has been __**PARTIALLY**__ added to Lua. Doesn't work as of yet, so add it using `runHaxeCode`.
> - Some of the base game stages has been cleaned up, week 6 has an NTSC Shader (`shaders.NtscShader`), and an "options" option has been added to the pause menu.
> - Soundtray has been fixed. You can also change the font on the soundtray by replacing `soundtray.ttf` in a modpack or in assets.
> - Official Release of 0.0.5 Beta! x64 and x32 builds are being released. No source yet.

---

# Draft
## v0.0.0
> ### Section
> - **Minor Section**:
>   - Point 1
>   - Point 2
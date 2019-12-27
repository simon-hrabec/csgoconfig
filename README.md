## Instructions and info

How to copy/install
- `730` to `C:\Program Files (x86)\Steam\userdata\YOUR_STEAM_ID`
- `myTest.cfg` to `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg`
- Set launch options inside steam UI

## Launch options

You can set them in steam (Game Library -> CSGO -> Properties -> General -> SET LAUNCH OPTIONS...) or you can create a desktop shortcut and put your options there. You can have multiple shortcut with different launch options. In the target or the shortcut you need to write `<path>\steam.exe -applaunch 730 -windowed -novid ...etc`.

Copy paste: `-novid`

Explanations:
- **`-tickrate 128`** When you start offline server it runs at 128 tick. This is important for nade practice as nades with jumpbind fly differently on 64 and 128 tick servers.
- **`-novid`** Won't play the initial CSGO video. Faster startup.
- **`-nojoy`** Omits joystick support. Saves some RAM
- **`-fullscreen`** Starts the game in fullscreen mode
- **`-windowed`** Starts the game in windowed mode
- **`-noborder`** The CSGO window wont have the typical minimise, maximise buttons and border
- **`-w 800 -h 600`** Sets the resolution to width * height
- **`-refresh 240`** Starts the game with 240hz refresh rate (for 240hz screen)

## Test config

Go to console write `map de_mirage` (or other map) and then write `exec myTest.cfg`.

Useful binds:
- **F** - enables noclip mode (flying)
- **C** - rethrows last grenade
- **H** - jumpbind (for throwing grenades)
- **V** - speeds up the game 8x (to let smokes disapear)

## Game config

### Settings

### Binds

- jump bind
- swich weapon hand
- zoom in/out radar
- jump crouch bind
- decays removal bind

# Wreckfest Discord Rich Presence

Shows what you are doing in Wreckfest on your Discord profile, for example:

<img width="241" height="110" alt="image" src="https://github.com/user-attachments/assets/7064331a-a4ff-4d10-9048-520341020d52" />


> **Wreckfest**
> Banger Race · Firwood Motocenter
> Rally Circuit · 24 cars · 3 laps

In menus it shows "In menus".

## Other Functionality

Fixed the Nexus Tournament spoiler crash caused by loading the Nexus RX with the Tournament Front Spoiler + any non-stock bumper with a mod active that changes shared vehicle files (FFB)
Fixed Wreckfest ignoring mod vehicle files that overwrite stock vehicle files (chassis/steering/differential/sounds)


## Install

Copy `dinput8.dll` into the Wreckfest folder, next to `Wreckfest_x64.exe`. With Steam that is usually `C:\Program Files (x86)\Steam\steamapps\common\Wreckfest`. Discord's activity sharing must be on (User Settings → Activity Privacy).

To uninstall, delete `dinput8.dll`.

## Notes

- It works with the current Steam build of Wreckfest. On any other build it shows plain "Playing Wreckfest".
- It only reads game memory and never changes game files or memory. DirectInput is passed through to Windows unchanged.
- Mod tracks show their internal name, tidied up.
- It conflicts with other mods that also ship a `dinput8.dll`.




This project is not affiliated with THQ Nordic, Bugbear or Discord.

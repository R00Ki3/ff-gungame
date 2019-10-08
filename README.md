# ff-gungame
Fortress Forever Gun Game/ Arms Race

### How to Install and Use

1. Download and install [Fortress Forever](https://store.steampowered.com/app/253530/Fortress_Forever/) for free on Steam.
1. Drop the **gun_game.lua** file into your **\Fortress Forever\FortressForever\maps\globalscripts** folder.
1. With your server running use the console command '**sv_globalluascript gun_game**' to enable the script.
1. Restart the game with console command **ff_restartround**.

### Changing Weapon List

Modify the weapon_list with the weapons of your choice. They will be given in the order they appear on the list.
```lua
local weapon_list = {
    'ff_weapon_rpg',
    'ff_weapon_crowbar',
    'ff_weapon_shotgun',
}
```
##### Fortress Forever Weapon Choices:
ff_weapon_assaultcannon  
ff_weapon_autorifle  
ff_weapon_crowbar  
ff_weapon_deploydispenser  
ff_weapon_deploysentrygun  
ff_weapon_deploymancannon  
ff_weapon_flamethrower  
ff_weapon_grenadelauncher  
ff_weapon_ic  
ff_weapon_jumpgun  
ff_weapon_knife  
ff_weapon_medkit  
ff_weapon_nailgun  
ff_weapon_pipelauncher  
ff_weapon_railgun  
ff_weapon_rpg  
ff_weapon_shotgun  
ff_weapon_sniperrifle  
ff_weapon_supernailgun  
ff_weapon_supershotgun  
ff_weapon_tommygun  
ff_weapon_tranq  
ff_weapon_umbrella  

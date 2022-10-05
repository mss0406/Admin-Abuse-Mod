# SETUP
## Adding Admins
Firstly, you'll need to add yourself or others as admins.

1: Go to `~/Titanfall2/R2Northstar/mods/Karma.Abuse/mod.json`

![image](https://user-images.githubusercontent.com/22678145/158139463-d34d12c4-512d-4016-96dc-9b63085b09db.png)

2: Change the Default Values of "grant_admin" to your name or UID
- You can see your own UID by going into the Northstar lobby and typing `sv_cheats 1; script print(GetPlayerArray()[0].GetUID())`
- To add multiple admins, write their UID **in lowercases** and add a comma in between without spaces.
- Ex : `DefaultValue: "12321321321321,12032103911321,213321435436"`

3: Optionally, change the autoannounce messages and color which plays during the start of every match.

# Admin-Abuse-Mod
Admin Abuse Mod for Northstar Client in Titanfall 2

Want to bully anyone who joins your server? Look no further with this mod! Now you can
- `slay someone/imc/militia/all`
- `switchteam/st someone/imc/militia/all`
- `respawn/rpwn someone/imc/militia/all someone/spawn/BLANK pilot/titan/BLANK`
- `gift <weaponId> <someone/imc/militia/all> <mods1> <mods2> <mods3>` //gives selected person a weapon also using the "save" keyword after the 3rd argument saves it to the player
- `rearm someone/imc/militia/all` // refill tacticals/abilities/cores
- `fly someone/imc/militia/all` //to noclip
- `titanfall/tf <someone/imc/militia/all>`
- `teleport <someone/imc/militia/all> <someone/crosshair>` //teleport everybody to your crosshair, teleport someone to another person, teleport everyone to you, 
    teleport one team to your crosshair
- `removeweapon/rw someone/team/all main weapons`
- `freeze someone/team/all`
- `unfreeze someone/team/all`
- `hp/health someone/team/all <value>` to change max hp, 100 for base pilot, 2500 per bar for titans
- `announce someone/team/all <word1> <word2> <word3>`
- `getteam someone`
- `shuffleteam/shuffleteams`  theres a better one in northstar-mods called AutoBalance
- `v/vanish someone/imc/militia/all`
- `uv/unvanish someone/imc/militia/all`
- `sonar someone/imc/militia/all <duration>`
- `prop someone/imc/militia/all <duration> <modelpath>`
- `unprop someone/imc/militia/all`
- `getmod/gm/getmods <weaponId>`
- `fgetmod/fgm/fgetmods <weaponId>`
- `bubbleshield/bs someone/imc/militia/all <duration>`
- `unbubbleshield/unbs someone/imc/militia/all`
- `airaccel/aa someone/imc/militia/all <value> [save]`
- `spawnturrettick` spawns a funny tick with a turret at your crosshair.

so, yeah. enjoy your players malding probably

# v1.2.8 Gift Update
Now you can save what weapons to gift to players so they will have the same weapons/abilities upon respawning!

By inserting the word "save" anywhere after the 3rd argument, the weapon and mods you've given to any player will now save.

For example, to respawn with an **Amped Smart Pistol** from now on, you can type:
`gift smart karma burn save`
which will always give an Amped Smart Pistol to the player(s) that contains the name "karma" after they respawn.

Any loadouts will reset after map change.

To clear a player's loadout, you can type:
`gift clear karma`
which will clear all pre-existing loadouts for that player, if any.

## TL;DR
- `gift <weaponId> <playername/imc/militia/all> [mods1] [mods2] [mods...] [mods99] [save]`
- `gift <clear> <playername/imc/militia/all>`

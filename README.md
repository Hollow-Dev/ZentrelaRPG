# ZentrelaRPG
RPG plugin for the Zentrela Minecraft server.

See [releases](https://github.com/edasaki/ZentrelaRPG/releases) for the last working build. You will likely need to figure out how to build it from source yourself if you plan to ever add new features. You will certainly need to build from source if you want any sort of saving (SQL details are in ZentrelaCore and hardcoded).

Zentrela Core required: [https://github.com/edasaki/ZentrelaCore](https://github.com/edasaki/ZentrelaCore)

Project built in Eclipse with Maven plugin.

No support provided for any code - the plugin is being released because I have no plans to work on any other Minecraft related things.

Note: Votifier does not have a maven repo - you will have to add it to a local repo to get it to work with maven. See pom.xml for an example of how I did it.

Completed features include:
- NPC Shops
- Configuration-based quest system
- Full custom combat (PvP and PvE)
- 7 classes and 50+ custom spells
- "Soaring"; custom flying feature with incomplete support for particles
- Horse/stables system
- Dungeon system
- Buycraft integration
- Votifier integration
- Custom hologram API
- Custom chat manager
- Custom ranks
- Dupe-free trading system
- Polygon (with automated rectangle detection) Region & Danger Level system
- Custom PvP & Mob
- Donor ranks and perks
- Warp system
- Custom command manager
- Parties with EXP sharing
- Automatically generated items/equipment
- Formula-based item and mob balancing
- Fancy /help menu
- Trinket system
- Reward point system
- Integrated toplist
- Badges
- Ban/IPBan/Mute system
- Option manager
- Motd manager
- Menubuilder API
- and a couple other things, probably

Incomplete/Unimplemented features (stuff that's partially coded but never got added to the game):
- World bosses (nearly complete)
- Skills (Woodcutting, etc.)
- Music system
- Instanced dungeons
- Rebirths
- Custom Pets (nearly complete)
- Cheat detection

You will need to get the other repo, ZentrelaCore, as well (two plugins required).

You will need to build ZentrelaCore from source; the SQL stuff is hard-coded.

Not for hire.

It's a bit disorganized as it was a one-man project, but it should be more than clean enough to work with.

Feel free to send pull requests, I'll accept if it's something useful.

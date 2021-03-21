# Minecraft Java: Gamerules Explained
In this guide, you will learn what gamerule is, and how to utilise them on your server!

### What is a Gamerule?
Gamerules are an advanced feature of Minecraft that allow you to change the behavior of the game.
You can change a gamerule by running `/gamerule <Name of Gamerule> <New Value>`
See the table below for a list of all existing gamerules, and their functions.

### List of Gamerules (and their functions)
The table below explains all available gamerules as of Minecraft: Java Edition 1.16.5.
See the notes section below for notes to take when changing certain gamerules.


| Gamerule | Function | Accepted Values | Default
| --- | --- | --- | --- |
| `announceAdvancements` | Controls whether announcements of advancements being earnt will be sent to all online players | `true` or `false` | `true` |
| `commandBlockOutput` | Controls whether command blocks should notify admins when they perform commands | `true` or `false` | `true` |
| `disableElytraMovementCheck` | Controls whether a player will be checked for invalid movement packets when wearing an elytra | `true` or `false` | `false` |
| `disableRaids` | Controls whether Pillager Village Raids should be disabled. | `true` or `false` | `false` |
| `doDaylightCycle` | Controls whether the server will cycle through the regular day / night cycle. Disabling this freezes the server at it's current time. | `true` or `false` | `true` |
| `doEntityDrops` | Controls whether entites that are not mobs should drop their regular items upon death | `true` or `false` | `true` |
| `doFireTick` | Controls whether fire should spread and exinguish itself naturally. | `true` or `false` | `true` |
| `doImmediateRespawn` | Controls whether players should bypass the respawn screen and be teleported back to spawn or their bed upon death | `true` or `false` | `false` |
| `doInsomnia` | Controls whether the **Phantom** mob is able to spawn during the night. | `true` or `false` | `false` |
| `doLimitedCrafting` | Controls what items players can craft. (When Enabled: Players can only craft items they have personally unlocked the recipe for) | `true` or `false` | `false` |
| `doMobLoot` | Controls whether mobs should drop items upon death. | `true` or `false` | `true` |
| `doMobSpawning` | Controls whether mobs can naturally spawn in the world | `true` or `false` | `true` |
| `doPatrolSpawning` | Controls whether Patrols of Pillagers can naturally spawn | `true` or `false` | `true` |
| `doTileDrops` | Controls whether blocks drop items when broken | `true` or `false` | `true` |
| `doTraderSpawning` | Controls whether the **Wandering Trader** Mob naturally spawns.| `true` or `false` | `true` |
| `doWeatherCycle` | Controls whether the server will cycle through the regular sun / rain / thunder cycle. Disabling this freezes the server at it's current weather. | `true` or `false` | `true` |
| `drowningDamage` | Controls whether players take damage from drowning underwater | `true` or `false` | `true` |
| `fallDamage` | Controls whether players take damage from falling | `true` or `false` | `true` |
| `fireDamage` | Controls whether players take damage from walking into / over fire-related blocks | `true` or `false` | `true` |
| `forgiveDeadPlayers` | Controls whether normally-neutral mobs should stop being angry when the player being attacked dies. | `true` or `false` | `true` |
| `keepInventory` | Controls whether players keep their inventory and EXP on death (No items are dropped from the dead player's body) | `true` or `false` | `true` |
| `logAdminCommands` | Controls whether admin-related commands run by OPs and Admins are logged to the server's log file. | `true` or `false` | `true` |
| `maxCommandChainLength` | Controls the number at which the chain command block acts as a "chain". | `true` or `false` | `true` |
| `maxEntityCramming` | The number of entities a player can be in a small space with before taking 1.5 hearts of suffocation damage per second. | Any valid integer | `24` |



### Notes
- Changing `disableElytraMovementCheck` is not recommended as it does not check a player's movement packets when a player wears the concerned armour piece. This means they may be able to bypass speed and fly hack checks in some cases.
- `disableRaids` does not disable spawning of Pillagers / Ravagers / Illagers. It just prevents them from getting agitated and raiding a nearby village.
- `maxEntityCramming` watches for all of the following mobs: `All Non Spectator-Mode Players, All mobs (except bats), Boats and Minecarts`


### How do I change a gamerule?

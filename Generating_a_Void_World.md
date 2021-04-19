# Generating a Void World on your server
Ever wanted to paste an empty world on your server, suitable for something like pasting schematics? Well this guide is for you!
In this guide, you'll learn how to install VoidGenerator, and how to generate a void world!

### Pre-requistes
A Minecraft Service
Access to connect to your server's files
Access to download / upload plugins and files to/from your server's files

### Getting Started
If you would like to generate your server's default world (`world`) as a void, follow these steps.
If you would like to generate a new or custom world as a Void, follow the section below about Multiverse.

- Step 1: Stop your server
- Step 2: Download the newest version of VoidGenerator from [SpigotMC](https://www.spigotmc.org/resources/voidgenerator.25391/) *(Click to download)*
- Step 3: Upload the plugin to your servers Plugins Folder (`/plugins/`)
- Step 4: Open the file `bukkit.yml` from your servers __root folder__ (`/`)
- Step 5: Scroll to the bottom of `bukkit.yml` and add the following:

```
worlds:
  world:
    generator: VoidGenerator:VANILLA
```

- Step 6: Save and upload the updated version of `bukkit.yml` to your server
- Step 7: Delete the following folders from your server's root folder: `world`, `world_nether`, `world_the_end`

> Warning: If you want to save your inventory, builds, playerdata and other files associated with the world, make sure to backup your folders before deleting!

- Step 8: Restart your server
- Step 9: Tada! Your default world is now a void 🎉

### Generating a custom or new world with Multiverse
Generating a void world with multiverse is super easy! It only takes one command!
Follow the steps below to create a Void World using Multiverse

1. **Step 1:** Login to your server using the IP provided on your server's panel
2. **Step 2:** Ensure that you are a __server operator__, or you have permission to run Multiverse Commands

> Tip: Multiverse permissions can be found [here](https://github.com/Multiverse/Multiverse-Core/wiki/Big-List-O'-Permissions)

3. **Step 3:** Type the following command: `/mv create <YourWorldName> NORMAL -g VoidGenerator:VANILLA -t FLAT`
4. **Step 4:** If you typed the command correctly, the world will be created
5. **Step 5:** Travel to the world using `/mv tp <YourWorldName>`
6. **Step 6:** All done! 🎉

### Notes
- When modifying the default world, change `level-type` in `server.properties` to `FLAT`. This way, the void darkness will start a Y Level 0, instead of Y Level 64.
- When creating a world, you can change the `VANILLA` option to any valid biome. A list of biome IDs can be found [here](https://hub.spigotmc.org/javadocs/spigot/org/bukkit/block/Biome.html)

### Need assistance?
If you need help with anything in this article, be sure to reach out to us on our discord, or via a Ticket!

- Our Discord: https://discord.versatilenode.com/
- Submit a Ticket: https://billing.versatilenode.com/submitticket.php/

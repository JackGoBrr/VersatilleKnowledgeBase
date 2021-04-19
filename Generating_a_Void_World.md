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
Stuff_here.exe

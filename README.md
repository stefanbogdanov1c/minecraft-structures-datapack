# Minecraft structures datapack
A repo for storing custom Minecraft buildings/villages as a datapack which can be included into Your world.

## Adding structures
Use a Minecraft structure block to generate a `.nbt` file, and add it to the `data/village/structure` directory, if You want to make a single building, or if You wanna create a larger project, add it to `data/village/structure/project_name`.
The `village` is a workspace name, so if You wanna create a fork or something, feel free to rename it as You wish.

## Using the datapack
Once You have cloned this repo, just copy it (name it whatever You want, just make sure that the `data` directory and `pack.mcmeta` files are located in the directory You'll copy), and paste it to the `worldName/datapacks`. If You are already loaded in a world, use the command `/reload`. If not, it will already be loaded.
To find the structure, use the `/locate` command. For example: 
``` /locate structure village:village_grass
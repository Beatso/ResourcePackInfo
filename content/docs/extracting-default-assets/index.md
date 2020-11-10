---
title: "Extracting Default Assets"
weight: 3
---

When creating resource packs, it's incredibly useful, if not essential to have Minecraft's default assets to hand. You will be able to see vanilla textures you might want to modify, look at the structure of a resource pack and more. You can find them [here](https://mcasset.cloud/) (alhtough I'm not entirely sure how copyright allowed that site is), or you can extract them yourself, which i advise doing. Luckily, it's not that hard.

> These instructions are designed to work on both Windows and Mac, as long as you have Minecraft Java Edition installed. No other software is required. This does not explain how to create a resource pack. This explains how to see the default resource pack of the vanilla game.

## Instructions

### Step 1: finding your .minecraft folder
Firstly, you need to open your `.minecraft` folder. If you don't know how to do that, follow [these instructions](https://minecraft.gamepedia.com/.minecraft#Locating_.minecraft).

### Step 2: finding the version folder
From your `.minecraft` folder, go to the versions folder, then open up the folder of the version of the game you want to extract the assets of. For example, if you want the assets of 1.16, you should have gone to `.minecraft/versions/1.16/`.

### Step 3: finding the version.jar file
In the folder you have just gone to, there should be a file called `1.16.jar` (or whatever version you are extracting). Duplicate (copy then paste) this file.
> If you're on windows and can't see the file endings (like `.jar` and `.json`), in file explorer, go to the "View" tab, then make sure "File name extensions" is on. You'll need this for future steps.  
> If you do not see the `.jar` file, and only a `.json` file, you need to start up your game from the launcher in this version first. Then the `.jar` file should appear.

### Step 4: getting the assets
Rename the file you copied (*not* the original file) to `minecraft_assets.zip`. If you get asked if you're sure you want to change it, select Yes. Copy the file.

### Step 5: pasting the assets
Next, find the folder on your computer in which you want to keep your default assets (preferably not in your `.minecraft` folder). Paste the `minecraft_assets.zip` file from the previous step here. Extract the zipped folder (on Windows, right click then press Extract All).  

## Finished
You now have Minecraft's default assets saved on your computer, easy to access. This is also in the structure of a resource pack you would make yourself (or a datapack); you can look to find which files go where.
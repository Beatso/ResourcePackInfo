---
title: "Finding Other Default Resources"
weight: 6
---

When you extract the default assets, it is missing some files such as sounds. It also only comes with the `en_us` lang file. But how do you find other ones? You can either extract them manually, as followed by this tutorial, or get them at [mcasset.cloud](https://mcasset.cloud/).


## Getting language locale code

If you are looking for a lang file, find the locale code for the language you want to get: go to [this](https://minecraft.gamepedia.com/Language#Available_languages) wiki page and expand the table.
![Find the locale code on the Minecraft Wiki](locale-codes.png)  


## Finding the hash

Go to `.minecraft/assets/indexes` and open the file for the latest version (e.g. `1.16.json`).

Nearly all text editing programs have an option for finding (Ctrl+F or Cmd+F on Mac). Search for the file name you are looking for. If you are looking for a lang file, search for the locale code you found earlier.

Copy the corresponding hash for the language.

![In my example, I searched for `fr_fr`, the locale code for French (France). My hash was `244c2676688dc566a50d65f36194f751d2e89414`.](finding-hash.png)  
In my example, I searched for `fr_fr`, the locale code for French (France). My hash was `244c2676688dc566a50d65f36194f751d2e89414`.


## Locating the object file

Go to `.minecraft/assets/objects` and then open the folder named as the first two characters of the hash you found.

In that folder, there should be a file with the exact name of the hash you found earlier.

This is the file you were looking for.


## Saving the file

Copy the file, then paste it somewhere else on your computer. Rename the file as `file_name.json`, or `.png`, depending on the file type you are looking for.

You can replace `file_name` with whatever you want; it's the `.json` that's important.

You can now open this JSON file with your [preferred text editor](/docs/recommended-software).
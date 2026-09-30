# Toi's Armory

![Minecraft Version](https://img.shields.io/badge/Minecraft-26.2-brightgreen.svg)
![Data-Driven](https://img.shields.io/badge/System-Data_Driven-blue.svg)

[👉 **日本語の説明はこちら (Read in Japanese)**](README_ja.md)

Toi's Armory is a versatile and lightweight Gun Datapack for Minecraft.
It provides realistic gunplay mechanics such as recoil patterns, ADS, bullet physics with damage falloff, and a highly customizable attachment system using only Datapacks and Resourcepacks, all while maintaining excellent performance.

**Note: This datapack currently only works on Minecraft 26.3.**

## ✨ Features

- **Rich Gunplay Mechanics**
  - **Projectile Physics**: Bullets have velocity and gravity, and damage transitions dynamically based on distance.
  - **Recoil & Sway**: Each gun has a unique recoil pattern. Crosshair sway and accuracy reduction upon firing are dynamically calculated.
  - **Dynamic Reloading**: Reload times and animations change depending on whether there is a bullet left in the chamber or the gun is completely empty.
  - **Accurate Hitboxes**: Uses the `Hitbox` module from the `Bookshelf` library to perform precise DDA (Digital Differential Analyzer) raycasting for highly accurate hit detection.
- **Attachment System**
  - Customize your weapons with various sights, barrels, and grips. Attachments actively affect weapon stats such as ADS speed, recoil control, and weapon sway.
- **Data-Driven Gunpack System**
  - You can easily create and add your own custom guns!
  - By appending NBT data to the `toisarm:import` storage during load, you can configure everything from animation frames, sound timings, recoil patterns, damage transitions, to attachment modifiers. (See the `default_gunpack` folder for examples).

## 🔫 Included Weapons
*(More weapons will be added in future updates!)*

- **Assault Rifles**: M4A1, AKM, AK-74, AS VAL, SCAR-H
- **SMGs**: MP5, Scorpion EVO3, UZI
- **Sniper / Marksman**: M700, SVD
- **Shotguns**: Mossberg 590
- **Handguns**: USP45

## 🎮 Controls

The default controls are as follows. You can swap the actions assigned to "Swap Offhand" and "Drop Item" via the Dialog Menu.

- **Right Click**: Fire
- **Left Click**: Aim Down Sights (ADS)
- **Swap Offhand**: Reload (Default) or Change Fire Mode
- **Drop Item**: Change Fire Mode (Default) or Reload
- **Dialog Menu (Default: G)**: Opens the settings dialog menu.
  - You can swap key assignments.
  - Customize your gun's attachments.
  - (OP Only) Access the admin menu to get weapons and attachments.

## 📦 Installation
1. Download both the **Datapack** and the **Resourcepack**.
2. Place the Datapack in your world's `datapacks` folder.
3. Place the Resourcepack in your `resourcepacks` folder and enable it in-game.
4. Because the datapack includes custom enchantments, you must rejoin the world or restart the server after installation (the `/reload` command is not sufficient).

## 🎨 Using with Shader Packs

This datapack uses vanilla core shaders to display arm textures in first-person view. If you use shader packs that require mods, the rendering pipeline is replaced, and the arms will not display correctly.
For this reason, we provide a Web Patcher Tool to make the resource pack work correctly in shader environments. From the URL below, you can automatically inject compatibility code for Toi's Armory into your shader's ZIP file.

🔗 **[Open Toi's Armory Shader Patcher](https://toitoi110.github.io/Tois-Armory-Public/tools/shader-patcher.html)**

Confirmed to work with: [ComplementaryUnbound](https://modrinth.com/shader/complementary-unbound)

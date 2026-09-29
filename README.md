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

The default controls are as follows (Keybinds can be changed via the Dialog Menu):

- **Right Click**: Fire
- **Left Click**: Aim Down Sights (ADS)
- **Swap Offhand (Default: F)**: Reload
- **Drop Item (Default: Q)**: Change Fire Mode (Auto/Semi, etc.)
- **Dialog Menu (Default: G)**: Opens the settings dialog menu.
  - You can rebind your keys.
  - Customize your gun's attachments.
  - (OP Only) Access the admin menu to get weapons and attachments.

## 📦 Installation
1. Download both the **Datapack** and the **Resourcepack**.
2. Place the Datapack in your world's `datapacks` folder.
3. Place the Resourcepack in your `.minecraft/resourcepacks` folder and enable it in-game.
4. Join the world, or if you are already in the world, execute the `/reload` command.

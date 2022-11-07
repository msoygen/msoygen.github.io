---
title: Onto a New Game Jam
author: M Serdar Oygen
date: 2022-11-07 18:52:00 +0800
categories: [Events & Jams, Game Jams, Devlogs]
tags: [devlog]
---

Hi everyone! [Game Off 2022](https://itch.io/jam/game-off-2022) submissions started 7 days ago. I decided to join with an FPS shooter game. This time I'm not only gonna write a postmortem but also a devlog. I really want to make YouTube videos about it too but first let me tell you what I'm planning. The theme is cliche. This brings lots of ideas to my mind which inevitably many will be discarded. I started with the unlimited ammo cliche then iterated to a shooter game called Protagonist vs Antagonist([GitHub Repo](https://github.com/msoygen/Protagonist-vs-Antagonist)). Enemies will come in waves, both the player(protagonist) and the enemies will have unlimited ammo, unrealistic damage rates, unrealistic health regeneration(like going over an apple - am I too good for this? :D -) and at the end of each wave the antagonist will come into the scene with guns that uses projectile ammo (unlike others using raycasts)  with the ability to perish protagonist with one shot. The objetive is to not get shot by the antagonist and complete waves. 

Here is my plan:

| Goal      | Description |
| ----------- | ----------- |
| Player Controller MVP      | Bare minimum: looking around, walking, jumping       |
| Player Shooting MVP   | Bare minimum: single gun, shotting, muzzle flash, impact        |
| Enemy Controller MVP   | Bare minimum: single gun, looking around, walking, jumping         |
| Enemy AI MVP   | Bare minimum: following the player up to a range, shooting plyer        |
| Antagonist Controller MVP   | Bare minimum: looking around, walking, jumping        |
| Antagonist Shooting MVP   | Bare minimum: single gun, one shot kill, projectile ammo        |
| Antagonist AI MVP   | Bare minimum: following the player up to a range, shooting palyer        |
| Game Logic - Waves MVP | Bare minimum: difficulty decisions, enemy population density |
| Levels - Gray Box | Different graybox scenes for waves |
| Play Test | get rekt |
| Bug Fixing and Improvements | I'll probably have ton of issues to solve at this point |
| Character Models - MVP | Replacing capsule models with actual models |
| Character Animations - MVP | Running, walking animations |
| Player Polish | Fixing issues, improving game feeling |
| Enemy Polish | Fixing issues, improving game feeling |
| Antagonist Polish | Fixing issues, improving game feeling |
| Audio MVP | Shotting, walking, impact sounds |
| Particle System Polish | Improving muzzle flash, impact and projectile particle effects |
| Play Test | get rekt |
| Bug Fixing and Improvements | I'll probably have even more issues to solve at this point |
| Audio Polish | Shotting, walking, impact sounds |
| Game Logic - Perpetual Waves | Implementing continious waves |
| Game Logic - Scene transitions | Switching scenes between waves |
| Levels - Textures | Dress up the scenes |
| Levels - Terrain | Who walks on a 100x100x100 gray rectangular? |
| Play Test | get rekt |
| Bug Fixing and Improvements | Ugh help me! |
| Makeshift UI | I think I can barely finish this game |
| Audio - Ambiance | Add music to scenes |

I started with character controller and shooting couple days ago but I accidentally deleted many files while I was reainstalling Windows to my computer. I'm gonna start over, write weekly devlog and hopefully make YouTube videos.

Until next devlog... See you everyone!
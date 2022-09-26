---
title: Happy Game Jam Post-Mortem
author: M Serdar Oygen
date: 2021-01-27 21:03:00 +0800
categories: [Events & Jams, Game Jams]
tags: [happy game jam, game dev, game jam, post-mortem]
image: /assets/img/happy-game-jam-post-mortem/hgj-title.png
---

## Introduction 

In this post I'll be reviewing my first mobile game jam adventure. First, let's talk about little bit of organizers and rules.
Happy Game Jam is a game jam focused on hypercasual genre organized by [Happy Game Company](https://www.happygamecompany.com/) and supported by [Voodoo](https://www.voodoo.io/) from Sep 18 - Sep 27, 2020.

### Quick Peek: Theme, Rules and Evaluation of the Games

Theme announced as physics based hypercasual runner game with satisfying or frustrating gameplay. They made an awesome presentation about rules and theme. It was informative for an inexperienced person like me. Before moving into the presentation and theme let me briefly explain how winners picked then I'll explain them seperately. There were two category; USA's Apple Store or ad platforms. It was up to teams. These two aspects measured by CPI(for App Store) and CTR(for ad platforms) tests. Tests were pretty realistic for a competition. I was suprised how fast was the process. Tests took 4 days ona fixed budget as I remember and when the results came developers could rapidly make adjustments for next launch. There were experienced teams already discussing about data and possibilities for the next launch while I could just punch my keyboard to catch up with other teams :D . Contrary to popular belief developing a hypercasual game is a well structured and really fast paced process which makes it challenging otherwise games would fail.

### Theme

![theme-rules](/assets/img/happy-game-jam-post-mortem/theme-rules.png)
_Theme rules from kick off presentation_

*Hypercasual runner game based around physics and satisfying or frustrating gameplay.*

There are two key points in the theme. Happy Game Jam organizers explained them as follows,

First, physics:
  - It's intuitive,
  - Players can play again and again in different ways because physics makes inputs unique,
  - It has a visual outcome which can be frustrating or satisfying.


Second, satisfying or frustrating: 
  - Proven in marketing,
  - [Youtubable](https://www.urbandictionary.com/define.php?term=Youtubable)
  - Reactive gameplay


We prototyped ton of ideas on paper and tried to cover theme rules. We failed every single time until the last one. Whenever one of my teammates comes up with an idea it sounds awesome at first but later when we try to turn it into a game, problems occured such as "what is the goal?", "what makes a win or lose?", "what are the elements that gives density to gameplay?", "why is it not fun to play?", etc.. Eventually we answered the questions and moved on to the prototyping part.

### Prototyping

We were team of four. 1 level designer, 1 UI/UX designer and 2 developers(I'm one of the developers). We discussed the structure and methods we are going to use then split the work. Meanwhile it was the 3rd day. Idea part took two and a half day. I'm not gonna talk about the developing process. We didn't do anything special on that part but I'm definetely going to tell you why we failed so badly. Let's take a look at in game screenshots and continue with another bullet list :D

|                 |                  |                         |
| ![roll a color 3d in game screenshot 1](/assets/img/happy-game-jam-post-mortem/roll-a-color-1.jpg) | ![roll a color 3d in game screenshot 2](/assets/img/happy-game-jam-post-mortem/roll-a-color-2.jpg) | ![roll a color 3d in game screenshot 3](/assets/img/happy-game-jam-post-mortem/roll-a-color-3.jpg) |


- There is no ending.

Game ends where player flys from a ramp and lands back to the ground. So????

- Poor diversity on levels.

Every single level is the same as the others. There is only one obstacle type which is ramp and only pick ups are color plates.

- Poor and insufficient animations.

In a fast paced gameplay, the absence of animations are cruel to the players. In our prototype there were 3 animations: player running, cylinder slowly expanding or shrinking and flying from the final ramp. It looks incomplete. Some other teams did a really good job(I can't review it technically. Only from a player's point of view.) on animations and fulfilled satisfaction feel. It helps a lot for building feelings on players.

- Limited use of physics.

As the theme suggests we should have used physics more interactively. At first while we were prototyping on a paper it wasn't so obvious to us. Maybe from the excitement of jam or the fear of not to be able to land an idea to a game. 

- Fixed camera movements.

Camera was straight forward, just following the player from a distance. No excitement, no surprises.

- Missing satisfying and frustrating gameplay.

Since we failed on many visual and technical things, we couldn't reflect feelings to the players. 


All these down sides mixed and created a boring game. You can play the game on your iPhone. [App Store URL](https://apps.apple.com/us/app/roll-a-color-3d/id1533456939#?platform=iphone)

### Evaluation of the Games

We choosed the CPI test for our game. As the days past we got updated about the test data daily. Here are the results:

| Day 1 | Day 2 | Day 3 | Day 4 |
| $1.84 | $1.59 | $1.39 | $1.42 |

It's not a good result.

### Final Words

I'm happy to be able to see my mistakes. There is a different Serdar at every game jam. See you everyone. Thanks for reading my post. Have a good day! 
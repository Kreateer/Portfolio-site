---
title: "Projects"
description: "A comprehensive showcase of projects I've worked on"
draft: false
---

This page is a comprehensive showcase of projects I have worked on throughout my studies and journey as a game developer. 
Each project showcased here has been handpicked and represents a unique challenge and an opportunity to unleash my creativity, problem-solving skills, and passion for innovation.

{{< toc >}}

# Gun Samurai (Prototype) - Class-based Shooter

{{< imageres-500px src="/images/gs_aimtest.gif" alt="Gun Samurai Prototype Aim Test" >}}

A class-based competitive first-person shooter created with Unreal Engine 5. Set in feudal Japan, it has 12 players fight for control over objectives using authentic era weaponry. It is inspired by popular class-based shooters like [Team Fortress 2](https://store.steampowered.com/app/440/Team_Fortress_2/) and [Overwatch](https://store.steampowered.com/app/2357570/Overwatch_2/).

**DISCLAIMER**: This is a W.I.P. project, so many things are subject to change and will be updated here accordingly.

## Overview

The game has the players battle in objective-based matches, where the winning team is the one that either has the highest score after the match timer runs out or that successfully completes their objective. Players are able to switch between 6 classes during the match: Engineer, Kaboomer, Monk, Ninja, Ronin and Samurai. Each class is represented by a unique character with their own personality and design.

Each character is able to enter a temporary state of focus to deflect most incoming projectiles. That is, they are able to briefly block incoming attacks by literally cutting down arrows or bullets. This represents the main mechanic of the game, as well executed blocks can save players from otherwise certain death. As such, the game dynamic relies on careful balancing between blocking and attacking during battles.

## Prototype

The prototype version of Gun Samurai is built with Blueprints in Unreal Engine 5.4. It focuses solely on the Samurai class and features a single King Of The Hill map. The current state of the game allows players to deal and receive damage, as well as block. It also utilizes the new [Motion Matching](https://dev.epicgames.com/documentation/en-us/unreal-engine/motion-matching-in-unreal-engine) system to create realistic character movements.

# Phantasmagoria - VR Puzzle Horror

{{< imageres-500px src="/images/phantasmaintro.gif" alt="Phantasma Intro Movie Screenshot" >}}

As part of my master thesis research, this project drew inspiration from 18th century phantasmagoria performances and modern VR game design. Developed in Unreal Engine 5, it serves as the basis for research aiming to provide a comprehensive understanding of the impact of a combination of phantasmagoria performance elements and VR on player immersion. With this study, it was my hope to create opportunities for VR technology to redefine the boundaries of horror gaming, potentially creating new avenues for storytelling, gameplay mechanics, and player engagement.

## Overview

With this project, I focused on creating a highly immersive virtual environment that replicates elements of phantasmagoria performances. Drawing inspiration from historical and cinematic references, the game uses creative design, lighting, particle effects, and soundscapes to evoke eerie, supernatural atmospheres. Some key elements include:

- **Virtual Camera & Magic Lantern**: The player’s headset is linked to a virtual camera simulating the magic lantern, projecting animated supernatural figures that serve as antagonists.
- **Natural Interaction**: Leveraging hand-tracking via Meta Quest 3, players interact with the environment using natural motions (e.g., grabbing, pushing), and experience haptic feedback through a vest to simulate physical sensations.
- **Visual & Atmospheric Design**: The game employs post-processing effects like volumetric fog, bloom, and Niagara particle systems (e.g., fire, smoke) to create a dark, eerie atmosphere. Additionally, 3D assets from the Victorian era and procedural generation techniques (e.g., for swarms of spiders) contribute to the overall aesthetic.
- **Themed Challenges**: The game features levels inspired by common fears (e.g., ghosts, spiders, heights), each with distinct gameplay mechanics:
    {{< imageres-500px src="/images/phantasmaghost.gif" alt="Phantasmagoria Main Level" >}}
    - **Ghost’s Lament**: An event-driven system that triggers sound effects and haptic feedback based on the ghost's movement, with mechanics for gradual power buildup.
    {{< imageres-500px src="/images/phantasmaspider.gif" alt="Phantasmagoria Second Level" >}}
    - **Spider’s Nest**: A room-scale VR experience with collision-based interactions for clearing spiders off the player's virtual body, linked to visual and audio cues.
    {{< imageres-500px src="/images/phantasmalava.gif" alt="Phantasmagoria Final Level" >}}
    - **Inferno Rise**: Physics-based platforming gameplay that integrates dynamic object placement and real-time destruction of platforms.
  
The project files are available on [GitHub](https://github.com/Kreateer/Phantasmagoric)

The full paper contains more details on the purpose and results of the research and is available on the [Diva Portal](https://www.diva-portal.org/smash/record.jsf?dswid=-8254&pid=diva2%3A1881449&c=1&searchType=SIMPLE&language=sv&query=Matija+Milakovic&af=%5B%5D&aq=%5B%5B%5D%5D&aq2=%5B%5B%5D%5D&aqe=%5B%5D&noOfRows=50&sortOrder=author_sort_asc&sortOrder2=title_sort_asc&onlyFullText=false&sf=all)

# No More Fish - Multiplayer Puzzle Game

{{< imageres-500px src="/images/nmf_title.jpg" alt="Ghost" >}}

This 4-player competitive game developed in Unity was created as part of the Nordic Alliance for Sustainability in Gaming (NASG) 'Un-jam' 2023 and criticizes the impact of corporate greed on Iceland’s marine ecosystem, society and culture.

## Overview

{{< imageres-500px src="/images/nmf_ready.png" alt="Ready Screen" >}}

Each player controls a fishing trawler with the main goal to collect the most fish to win. The players have a choice to overfish and progressively destroy the ecosystem or to work together to find a balance between maintaining the ecosystem and fishing enough to win. Destroying the ecosystem causes all players to lose the game, while maintaining the environment allows a player to win. A player leaderboard is presented at the end of a match, highlighting the winner and individual scores.

## Contributions

I worked primarily as a UI programmer, where I was responsible for designing and implementing the user interface. This involved creating interactive menus, buttons, and a dynamic leaderboard. I integrated the UI components with the gameplay logic and the input system using event-driven programming and state management systems, ensuring seamless communication between the UI elements and the underlying game mechanics. Additionally, I optimized the UI for gamepads, making it responsive and ensuring smooth controls across various gameplay states.

The game is available for download on [itch.io](https://kreateer.itch.io/no-more-fish).

# Unforgotten Thoughts - Single-player Side-scroller Adventure Game

{{< imageres-500px src="/images/uft_500px_35s.gif" alt="Unforgotten Thoughts" >}}

This was a commissioned serious game project developed in Unity as part of a university course. The project's main focus was to educate players about four Metacognition methods for lowering internal stress levels and to raise awareness about the downsides of stress as a way to combat the increasing buildup of stress per capita in Sweden and other European countries.

## Overview

The game has the player engage in a short adventure within a child's dream. The player goes through several encounters that present a stressful experience for the child and its up to the player to guide them by managing the child's thoughts on each issue. Successfully clearing the final level revealed an epilogue to the narrative and further pointed out one of the Metacognition methods to the player.

## Contributions

I was project leader and programmer for this project. As such, my main responsibilities were divided between organizing the team and actively working on the game. 
From a managerial perspective, my job was to make sure every team member was aware of their role and the work they were assigned to, while keeping team morale high and solving any issues that may arise in communication. This involved organizing physical or virtual bi-weekly team meetings, organizing work via Trello and making crucial decisions that impacted the overall design of the game.
From a game designer and programmer perspective, my job was to find an optimal design for achieving our project’s serious goal and to create appropriate working code to breathe life into the concept.
---
title: "Projects"
description: "A comprehensive showcase of projects I've worked on"
draft: false
---

This page is a comprehensive showcase of projects I have worked on throughout my studies and journey as a game developer. 
Each project showcased here has been handpicked and represents a unique challenge and an opportunity to unleash my creativity, problem-solving skills, and passion for innovation.

{{< toc >}}

# Gun Samurai (Prototype) - Class-based Shooter
A class-based competitive first-person shooter created with Unreal Engine 5. Set in feudal Japan, it has 12 players fight for control over objectives using authentic era weaponry. It is inspired by popular class-based shooters like [Team Fortress 2](https://store.steampowered.com/app/440/Team_Fortress_2/) and [Overwatch](https://store.steampowered.com/app/2357570/Overwatch_2/).

**DISCLAIMER**: This is a W.I.P. project, so many things are subject to change and will be updated here accordingly.

## Overview
In the game's setting, various japanese clans are fighting for control of the nation, using whatever means necessary. The game focuses on the interactions between several fictional clans. 

The game has the players battle in objective-based matches, where the winning team is the one that either has the highest score after the match timer runs out or that successfully completes their objective. Players are able to switch between 6 classes during the match: Engineer, Kaboomer, Monk, Ninja, Ronin and Samurai. Each class is represented by a unique character with their own personality and design.

Given their extensive martial prowess, each character is able to enter a temporary state of focus to deflect most incoming projectiles. That is, they are able to briefly block incoming attacks by literally cutting down arrows or bullets. This represents the main mechanic of the game, as well executed blocks can save players from otherwise certain death. As such, the game dynamic relies on careful balancing between blocking and attacking during battles.

## Prototype
The prototype version of Gun Samurai is built with Blueprints in Unreal Engine 5.4. It focuses solely on the Samurai class and features a single King Of The Hill map. The current state of the game allows players to deal and receive damage, as well as block. It also utilizes the new [Motion Matching](https://dev.epicgames.com/documentation/en-us/unreal-engine/motion-matching-in-unreal-engine) system to create realistic character movements.

# Phantasmagoria - VR Puzzle Horror

As part of my master thesis research, this project drew inspiration from 18th century phantasmagoria performances and modern VR game design. Developed in Unreal Engine 5, it serves as the basis for research aiming to provide a comprehensive understanding of the impact of a combination of phantasmagoria performance elements and VR on player immersion. With this study, it was my hope to create opportunities for VR technology to redefine the boundaries of horror gaming, potentially creating new avenues for storytelling, gameplay mechanics, and player engagement.

## Game Design

The game’s virtual environment is designed to mimic several elements of phantasmagoria performances as accurately as possible, based on examples provided by top researchers in the field of cinematography and history of the art mentioned in the paper. An attempt has been made to create a dark environment with eerie undertones through creative use of virtual props, lighting, post-processing and particle effects. The player’s headset, connected to a virtual camera, is used as a virtual equivalent of the magic lantern that renders animated shapes or characters within the virtual environment. 

IMAGE HERE

These characters serve as antagonists or monsters within a narrative that draws on themes of the occult and supernatural, which is presented by a virtual master of ceremonies. Sounds and music are used extensively in an attempt to enhance immersion and create a more engaging experience for the player. Effects simulating the use of galvanism in physical performances have been achieved through projection of eerie and distorted images on a virtual fog and through transformation of objects.

### Detailed Overview
More specifically, the implementation of previously mentioned elements within the virtual environment includes the usage and combination of post-processing effects such as volumetric fog and bloom, particle effects such as fire and smoke created with UE5’s Niagara particle system and low-intensity lighting to simulate an unnerving virtual environment. To complement this virtual aesthetic, various props are used in tune with the look and feel of the scene. 3D models of early 19th century (Victorian era) furniture, swarms of procedurally generated spider models, various decals featuring eerie drawings and human remains are some of the miscellaneous items used to decorate the scene.

IMAGE HERE

To facilitate additional immersion, the player is able to interact with the game world using their own hands, thanks to the advanced hand tracking capabilities of the Meta Quest 3 headset. Using this technology, the player is able to see a 3D model rendition of their hands, both within and outside the confines of the game. The immersive factor of this design choice comes from the ability to use natural hand motions to touch, grab, punch, push and pull entities or objects within the game. Additionally, the player owns a simple virtual upper body that they are able to feel with the help of the haptic feedback vest. Actions such as being touched, tickled, punched or pushed are able to be felt by the player in this way.

IMAGE HERE

The game also follows a narrative, with the player being stranded within a fictional alternate dimension. The player’s goal is to escape this dimension by completing a series of challenges. To do so, the player can physically navigate through them and use their hands to interact with the environment. Each challenge features a distinct setting eliciting a different fear response from a pool of common fears, such as phasmophobia (fear of ghosts or the supernatural), arachnophobia (fear of spiders and arachnids) and acrophobia (fear of heights). The purpose of using common fears in particular is that it generates a high chance of evoking a fear response from the player. Accordingly, the challenges are based on these fears and organized as separate game levels with distinct gameplay mechanics:

- Ghost’s Lament: The player must fight off a ghost that attacks them from different angles, triggering a combination of sounds and haptic feedback in the process. The player’s goal is to keep the ghost away long enough to banish it with a gradual buildup of “holy power”.
- Spider’s Nest: The player is in a room-scale spider’s nest, with some of them crawling up their virtual body. They must shake off the spiders by going over them with their hands, else they risk getting covered in them and not being able to see past them. This is important, as the player’s goal is to reach a button on the other side of the room that dissipates the spiders from the area and allows the player to proceed.
- Inferno Rise: The player is on a breakable platform, high from a gradually rising large lava pool. The player is tasked to avoid heavy falling objects, else they risk their platform getting destroyed and rapidly falling down into lava. The player must try to survive as long as possible before the lava inevitably rises to the platform and ends the game.

Finally, the experience also contains a brief introductory level where the player is given a short introduction to the narrative, which provides the player with previously mentioned context for the rest of their playthrough.

The full paper contains more details on the purpose and results of the research and is available on the [Diva Portal](https://www.diva-portal.org/smash/record.jsf?dswid=-8254&pid=diva2%3A1881449&c=1&searchType=SIMPLE&language=sv&query=Matija+Milakovic&af=%5B%5D&aq=%5B%5B%5D%5D&aq2=%5B%5B%5D%5D&aqe=%5B%5D&noOfRows=50&sortOrder=author_sort_asc&sortOrder2=title_sort_asc&onlyFullText=false&sf=all)

# No More Fish - Multiplayer Puzzle Game

This game was developed as part of the Nordic Alliance for Sustainability in Gaming (NASG) 'Un-jam' 2023 and criticizes the impact of corporate greed on Iceland’s marine ecosystem, society and culture.

## Overview

It was developed as a 4-player competitive game, where each player controls a fishing trawler with the main goal to collect the most fish to win. The players have a choice to overfish and progressively destroy the ecosystem or to work together to find a balance between maintaining the ecosystem and fishing enough to win. Destroying the ecosystem causes all players to lose the game, while maintaining the environment allows a player to win. A player leaderboard is presented at the end of a match.

## The Reason Behind It

The specific problem this game criticizes is about large companies hogging the Iceland's fishing quota and continuously overfishing, which has a major impact on the local marine ecosystem - causing some species to become near extinct - as well as smaller fishing boats and fishermen, who can now scarcely survive from their profession alone. Additionally, these companies are exporting the majority of all the fish caught and whatever is left for the local market is ridiculously overpriced - further ruining the tradition and culture of Iceland as an island nation living off the ocean.
Furthermore, the game criticizes the impact fishing can have on the environment and the management of local endangered species.

The game is available for download on [itch.io](https://kreateer.itch.io/no-more-fish).

# Unforgotten Thoughts - Single-player Side-scroller Adventure Game

This was a commissioned serious game project developed in Unity as part of a university course. The project's main focus is to educate players about four Metacognition methods for lowering internal stress levels and to raise awareness about the downsides of stress as a way to combat the increasing buildup of stress per capita in Sweden and other European countries.

## Overview

The game has the player engage in a short adventure within a child's dream. The player goes through several encounters that present a stressful experience for the child and its up to the player to guide them by managing the child's thoughts on each issue.
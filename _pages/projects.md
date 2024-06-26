---
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

## [METAL BEANS](https://store.steampowered.com/app/2792960/METAL_BEANS/ "METAL BEANS on Steam") (Link to Steam Page)

<div style="margin-bottom: 0.2rem">
  <style scoped>
    #img-list {
      display: flex;
      gap: 0.5rem;
      width: 100%;
    }

    @media (max-width: 924px) {
      #img-list {
        flex-wrap: wrap;
      }
    }
  </style>
  <div id="img-list">
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery05" href="/images/project-screenshot-05-1.png">
        <img src="/images/project-screenshot-05-1.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery05" href="/images/project-screenshot-05-2.png">
        <img src="/images/project-screenshot-05-2.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery05" href="/images/project-screenshot-05-3.png">
        <img src="/images/project-screenshot-05-3.png" />
      </a>
    </div>
  </div>
</div>
<p style="color: rgb(100, 100, 100); margin-bottom: 0.4rem;">(Click image to expand)</p>
<div style="max-width: 560px; margin-bottom: 0.6rem;"><iframe src="https://www.youtube.com/embed/hCqIjcY1UaQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
A 3D low-poly roguelite action-arcade game where the player controls and upgrades their two desktop buddies to fight through virus creatures and protect the PC in the computer space.
<br><br>
As a programmer, I implemented the character controller, combat system (including player actions with combos and input buffers), enemy AI, the entire tutorial system (including dialogues), part of the sub-game mode logic, and UI. Then, I handled code maintenance with version control, expandable infrastructure, bug fixes, and optimizations such as object pooling and reference/memory management.
<br>
As a technical designer, I designed and prototyped both combat features (elements, abilities, combos) and enemy types and behaviors. Then I drafted the roguelite player/world progression system and partly worked on sub game modes. After that, I handled tutorial and narrative design. 
<br><br>
I enjoyed working on this project and learned a lot during the creative process. With all of our hard works and support from friends and communities, the game went beyond my expectations and we are proudly announcing the release of METAL BEANS on Steam!

## [GPT Dungeon Curator](https://drive.google.com/file/d/1Tnx30Yo7MMvfy3T64xcUyCPtr4-YzoBH/view?usp=sharing) (Link to demo video)

<div style="margin-bottom: 0.2rem">
  <style scoped>
    #img-list {
      display: flex;
      gap: 0.5rem;
      width: 100%;
    }

    @media (max-width: 924px) {
      #img-list {
        flex-wrap: wrap;
      }
    }
  </style>
  <div id="img-list">
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery03" href="/images/project-screenshot-03-1.png">
        <img src="/images/project-screenshot-03-1.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery03" href="/images/project-screenshot-03-2.png">
        <img src="/images/project-screenshot-03-2.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery03" href="/images/project-screenshot-03-3.png">
        <img src="/images/project-screenshot-03-3.png" />
      </a>
    </div>
  </div>
</div>
<p style="color: rgb(100, 100, 100); margin-bottom: 0.4rem;">(Click image to expand)</p>
This R&D project aimed to explore the potential of large language models as a Game AI assistant in guiding and curating player progression within a dungeon RPG setting. This initiative seeks to replace traditional game UI, which relies heavily on numerical statistics. The LLM receives a prompt with historical information like player stats and game state, then returns output parsed into game instructions, player guidance dialogues, battle information, and other explanatory texts.
<br><br>
I designed and prototyped a basic RPG player stats framework and set up AI prompt standards. Then, I studied OpenAI API and implemented formatted instructions and parser in Unity C# to fit GPT-4 so the AI feedback loop can adapt to battle and exploration situations. 
<br><br>
Initially, my focus was on integrating the AI assistant system-wide. However, the team later pivoted towards emphasizing narrative elements after evaluating the capabilities of traditional game AI and weighing the costs associated with AI-generated content. Throughout the trial and error process of testing AI prompts, GPT-4 demonstrated remarkable capabilities in context analysis. I believe this integration pattern can enhance the narrative with AI curation and potentially help increase replayability.

## [THE FORSAKEN SCIENCE](https://steamcommunity.com/sharedfiles/filedetails/?id=2949491278) (Portal 2 Map)

<div style="margin-bottom: 0.2rem">
  <style scoped>
    #img-list {
      display: flex;
      gap: 0.5rem;
      width: 100%;
    }

    @media (max-width: 924px) {
      #img-list {
        flex-wrap: wrap;
      }
    }
  </style>
  <div id="img-list">
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery04" href="/images/project-screenshot-04-1.png">
        <img src="/images/project-screenshot-04-1.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery04" href="/images/project-screenshot-04-2.png">
        <img src="/images/project-screenshot-04-2.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery04" href="/images/project-screenshot-04-3.png">
        <img src="/images/project-screenshot-04-3.png" />
      </a>
    </div>
  </div>
</div>
<p style="color: rgb(100, 100, 100); margin-bottom: 0.4rem;">(Click image to expand)</p>
<div style="max-width: 560px; margin-bottom: 0.6rem;"><iframe src="https://www.youtube.com/embed/RyaJMgJvOZ4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
A _Portal 2_ custom map made with the original Puzzle Creator and _BEE2.4_. The map's theme is the decaying and rusty Aperture Science Enrichment Center after countless years of testing. GlaDOS is still in charge, but the test seems not the same as before...
<br><br>
I'm a super _Portal_ fan and have been fascinated by fan-made maps and mods over the decade. _Portal_'s level design and puzzle-making are tricky because there are many ways to achieve the goal if players are not limited to specific mechanic choices. However, this possibility and creativity is actually what makes it fun, so a clever level design where all mechanics make sense is the key. By reconfiguring the same level or replacing the available map mechanics, the same room could feel completely different. It is challenging, but that's why I love it so much :) In this map, I tried guiding players by limiting the options at the beginning (using contrast and obvious tutorials) and leaving some freedom for players to choose their way to play mid-game. I also reconfigured the level along with player progression to reuse previous elements and make backtracking meaningful.

## [Dream of the Icy Mountain](https://drive.google.com/file/d/1F62vmos6PeJvLz9cMHYCP7KNTbcFvybY/view)<br>(Link to Mod .zip file, require PC Celeste base game & Everest API)

<div style="margin-bottom: 0.2rem">
  <style scoped>
    #img-list {
      display: flex;
      gap: 0.5rem;
      width: 100%;
    }

    @media (max-width: 924px) {
      #img-list {
        flex-wrap: wrap;
      }
    }
  </style>
  <div id="img-list">
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery02" href="/images/project-screenshot-02-1.png">
        <img src="/images/project-screenshot-02-1.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery02" href="/images/project-screenshot-02-2.png">
        <img src="/images/project-screenshot-02-2.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery02" href="/images/project-screenshot-02-3.png">
        <img src="/images/project-screenshot-02-3.png" />
      </a>
    </div>
  </div>
</div>
<p style="color: rgb(100, 100, 100); margin-bottom: 0.4rem;">(Click image to expand)</p>
<div style="max-width: 560px; margin-bottom: 0.6rem;"><iframe src="https://www.youtube.com/embed/pF_zpxnms3M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
A _Celeste_ mod for experienced players (finished Chapter 4 A-side and collected some strawberries along the way) with a small custom map illustrating a dream of Madeline's.
<br><br>
This mod was a good level design practice. I liked playing _Celeste_ and decided to make a level for it, so I began learning to use the Loenn map editor. I designed all level elements from sketching while imagining and drawing the player's progression. According to the player's metrics, I made a prototype level with documented ideas. Then I decorated the map tiles with a snowy theme and added player guidance. After a series of playtests, I added a checkpoint (spawnpoint) and rebalanced several challenge difficulties. I enjoyed making this map and looking at others play.


## [King of Kings](https://www.ageofempires.com/mods/details/123352)<br>(Link to Age of Empires 4 mods page, requires Microsoft/Steam login)

<div style="margin-bottom: 0.2rem">
  <style scoped>
    #img-list {
      display: flex;
      gap: 0.5rem;
      width: 100%;
    }

    @media (max-width: 924px) {
      #img-list {
        flex-wrap: wrap;
      }
    }
  </style>
  <div id="img-list">
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery0" href="/images/project-screenshot-0-1.png">
        <img src="/images/project-screenshot-0-1.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery0" href="/images/project-screenshot-0-2.png">
        <img src="/images/project-screenshot-0-2.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery0" href="/images/project-screenshot-0-3.png">
        <img src="/images/project-screenshot-0-3.png" />
      </a>
    </div>
  </div>
</div>
<p style="color: rgb(100, 100, 100); margin-bottom: 0.4rem;">(Click image to expand)</p>
<div style="max-width: 560px; margin-bottom: 0.4rem;"><a data-fslightbox="gallery001" href="/images/project-screenshot-0-4.png"><img src="/images/project-screenshot-0-4.png" alt="King of Kings description"></a></div>
<p style="color: rgb(100, 100, 100); margin-bottom: 0.6rem;">Mod description</p>
An _Age of Empires 4_ mod that illustrates a capture-the-flag 2-player scenario in a crafted map. 
<br><br>
This mod was an independent study project where we connected to Age 4 dev team members (from _World's Edge_, a studio of _Xbox Game Studios, Microsoft_), including Senior Producer _Seb Grinke_ and _Yasemin Kuyumcu_. After generating a good idea around the Capture-the-Flag game mode, our team worked closely with the dev team and the modding community throughout the development process. As the lead gameplay programmer, I learned to write Lua script with Age 4's content editor and implemented the game mode prototype from 0 experience. After integrating the crafted map, I ported the game mode into a map scenario. I tweaked the details around core mechanics, including winning condition, objective UI, and flag respawn/tracking in fog-of-war. We conducted two playtests in an observation room and several with peer volunteers from all skill levels. Then we published the mod to the Age 4 mod's page with live updates and is ready for players to enjoy.

## [AI Generated Sound Effects for Games](https://www.gamesoundcon.com/schedule)<br>(Link to GameSoundCon 2022 event schedule, the talk is on Wednesday, October 26, at 11:50 am - 12:20 pm by Brian Hansen)

<div style="margin-bottom: 0.2rem">
  <style scoped>
    #img-list {
      display: flex;
      gap: 0.5rem;
      width: 100%;
    }

    @media (max-width: 924px) {
      #img-list {
        flex-wrap: wrap;
      }
    }
  </style>
  <div id="img-list">
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery01" href="/images/project-screenshot-01-1.png">
        <img src="/images/project-screenshot-01-1.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery01" href="/images/project-screenshot-01-2.png">
        <img src="/images/project-screenshot-01-2.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery01" href="/images/project-screenshot-01-3.png">
        <img src="/images/project-screenshot-01-3.png" />
      </a>
    </div>
  </div>
</div>
<p style="color: rgb(100, 100, 100); margin-bottom: 0.4rem;">(Click image to expand)</p>
<div style="max-width: 720px; margin-bottom: 0.4rem;"><a data-fslightbox="gallery011" href="/images/project-screenshot-01-4.png"><img src="/images/project-screenshot-01-4.png" alt="Unity project image"></a></div>
<p style="color: rgb(100, 100, 100); margin-bottom: 0.6rem;">Unity project</p>
A research project about AI utilization to generate sound effects for implementation in games: explores the use of neural networks to model and synthesize "procedural audio" as an alternative to the main contemporary approach of playing back pre-recorded audio files.
<br><br>
I built a Unity scene with online assets to create a zombie/monster scene. With all animations tracked via specific parameters from body movement, I used Open Sound Control (OSC) plugin to send messages to the trained audio encoder/decoder model to guide the sound generation.
<br><br>
_Project showcased as an example of the researched AI model on October 26, 2022, at Game Music and Sound Design Conference (GameSoundCon)._


## [Range Shooter Plus](https://ccd729.itch.io/range-shooter-plus) (Link to Itch.io page and download)

<div style="margin-bottom: 0.2rem">
  <style scoped>
    #img-list {
      display: flex;
      gap: 0.5rem;
      width: 100%;
    }

    @media (max-width: 924px) {
      #img-list {
        flex-wrap: wrap;
      }
    }
  </style>
  <div id="img-list">
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery1" href="/images/project-screenshot-1-1.png">
        <img src="/images/project-screenshot-1-1.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery1" href="/images/project-screenshot-1-2.png">
        <img src="/images/project-screenshot-1-2.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery1" href="/images/project-screenshot-1-3.png">
        <img src="/images/project-screenshot-1-3.png" />
      </a>
    </div>
  </div>
</div>
<p style="color: rgb(100, 100, 100); margin-bottom: 0.4rem;">(Click image to expand)</p>
<div style="max-width: 560px; margin-bottom: 0.6rem;"><iframe src="https://www.youtube.com/embed/byxF5zNNaDE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
A singleplayer first-person shooter where players choose their weapons and either play without rules with sandbox targets or complete the built-in replayable scored trials and challenges for better scores. 
<br><br>
This game was created as an experimental playground for newly learned skills as I wanted to implement several features inspired by many games I've played recently. I implemented the weapon system and gameplay mechanics such as character controller, shooting, recoil and weapon handling. I also created 3D assets like guns and map objects, then made animation, HUD, menu UI, particles, and sound/visual effects. Design wise, I constructed challenge levels and targets' behaviors, and tweaked the project as the development progressed. In this project, I prototyped multiple system design approaches for large-scale systems. The game grew to have more content than I imagined and functioned well, so I decided to publish and share it on Itch.io.

## [KANGARUMBLE](https://kangarumble.itch.io/kangarumble) (Link to official site and download)

<div style="margin-bottom: 0.2rem">
  <style scoped>
    #img-list {
      display: flex;
      gap: 0.5rem;
      width: 100%;
    }

    @media (max-width: 924px) {
      #img-list {
        flex-wrap: wrap;
      }
    }
  </style>
  <div id="img-list">
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery2" href="/images/project-screenshot-2-1.png">
        <img src="/images/project-screenshot-2-1.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery2" href="/images/project-screenshot-2-2.png">
        <img src="/images/project-screenshot-2-2.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery2" href="/images/project-screenshot-2-3.png">
        <img src="/images/project-screenshot-2-3.png" />
      </a>
    </div>
  </div>
</div>
<p style="color: rgb(100, 100, 100); margin-bottom: 0.4rem;">(Click image to expand)</p>
<div style="max-width: 560px; margin-bottom: 0.6rem;"><iframe src="https://www.youtube.com/embed/bO-pFA_Xl3I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
A local multiplayer turn-based party platformer where up to 4 players compete as their unique choices of kangaroos. Players can only move during their turn, and for every stomp they score, their turn gets shorter. Action heats up as tension builds all the way to the final stomp, where only one kangaroo will be victorious!
<br><br>
This game was my capstone project, took a year to build with a team of 12 students. As the lead programmer, I was in charge of full-purpose coding and team code management. Starting from the pitch, I prototyped and contributed to physics, gameplay, menu/UI, character selection, cross-platform support, version control, code integration, optimization, etc. I also modified Unity's new input system package code to adapt our gamepad and split-keyboard control scheme with cross-platform support. The _KANGGANG_ worked as a whole and put our efforts and love together sprint from sprint to create this game that we are all proud of.
<br><br>
_Game awarded Capstone Production Award and Peer Choice Award (Overall Excellence) at UCSC Games Showcase 2020._


## [Skyward Odyssey](https://hpaing.itch.io/skyward-odyssey) (Link to play in browser)

<div style="margin-bottom: 0.2rem">
  <style scoped>
    #img-list {
      display: flex;
      gap: 0.5rem;
      width: 100%;
    }

    @media (max-width: 924px) {
      #img-list {
        flex-wrap: wrap;
      }
    }
  </style>
  <div id="img-list">
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery3" href="/images/project-screenshot-3-1.png">
        <img src="/images/project-screenshot-3-1.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery3" href="/images/project-screenshot-3-2.png">
        <img src="/images/project-screenshot-3-2.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery3" href="/images/project-screenshot-3-3.png">
        <img src="/images/project-screenshot-3-3.png" />
      </a>
    </div>
  </div>
</div>
<p style="color: rgb(100, 100, 100); margin-bottom: 0.4rem;">(Click image to expand)</p>
<div style="max-width: 560px; margin-bottom: 0.6rem;"><iframe src="https://www.youtube.com/embed/q5_rguiviks" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
An endless sidescroller where the player accompanies a ninja on his unending journey to the end of the world. The player navigates through the skies, leaping across clouds and evading inky threats while exploring temples to piece together the story of the ninja's odyssey.
<br><br>
This game was 3-person teamwork over three months. We started with a simple endless runner (game state 1) and pitched new content to enrich the gameplay and story. I prototyped and implemented core mechanics into new states, integrated teamwork weekly with version control, and collaborated code optimization with team members.
<br><br>
_Game nominated and showcased at UCSC Games Showcase 2019._


## Smart-Tuney Karting

<div style="margin-bottom: 0.2rem">
  <style scoped>
    #img-list {
      display: flex;
      gap: 0.5rem;
      width: 100%;
    }

    @media (max-width: 924px) {
      #img-list {
        flex-wrap: wrap;
      }
    }
  </style>
  <div id="img-list">
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery4" href="/images/project-screenshot-4-1.png">
        <img src="/images/project-screenshot-4-1.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery4" href="/images/project-screenshot-4-2.png">
        <img src="/images/project-screenshot-4-2.png" />
      </a>
    </div>
    <div style="flex-grow: 1">
      <a data-fslightbox="gallery4" href="/images/project-screenshot-4-3.png">
        <img src="/images/project-screenshot-4-3.png" />
      </a>
    </div>
  </div>
</div>
<p style="color: rgb(100, 100, 100); margin-bottom: 0.4rem;">(Click image to expand)</p>
<div style="max-width: 560px; margin-bottom: 0.6rem;"><iframe src="https://www.youtube.com/embed/LeObdbd_d5o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
An algorithmic soundtrack generator with goal-oriented action planner that responds to user input and chooses a BGM combination for a Unity Learn Microgame.
<br><br>
The research goal was to test a general model that responds to human input of desired quantified attributes and dynamically plan the best suitable progressive combination from predefined assets with weighted attribute values. In this project, these were musical instrument patterns and values for loudness, emotion, and tempo. Inspired by the behavior of AI in _F.E.A.R._, I decided to write an A* planner with only the goal value appointed and let it dynamically adjust the following steps based on the current state and average mathematical deviation from the goal (as heuristic). Theoretically, this model could be expanded and applied to any project with a demand of input-responsive customized experience with quantifiable factors and is possible to combine with other technologies and adapt to more complicated human inputs.
<br><br>
I served as the audio designer and AI Programmer, created layers of tracks in sound base (with PureData), and implemented AI planner (A* based search). Then I generated Unity plugin with hvcc compiler and modified the original project to integrate the sound generator.


<script src="https://cdn.jsdelivr.net/npm/fslightbox@3.3.1/index.js"></script>

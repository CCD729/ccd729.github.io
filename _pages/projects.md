---
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from: 
  - /portfolio
  - /cv
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

## GPT Dungeon Curator

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


## Dream of the Icy Mountain

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


<script src="https://cdn.jsdelivr.net/npm/fslightbox@3.3.1/index.js"></script>

<script>
console.log(`
@@@@@@@@@@@@@@@@@@@&&&&&&&&##BGGGPPPGPPGPPPPPPPPPPPPYY5YYPPPPPPPPPPPPPPGG#P5GBBGGBBB#&@@@@@@@@@@@@@@\n@@@@@@@@@@@@@@@@@@@@@@&&&##BGPPPPPPPPPPPPPPPPP55555P5YYY5PPPPP5PPPPP5PPPGPPPGGB#BBBG5YB@@@@@@@@@@@@@\n@@@@@@@@@@@@@@@@@@@@@@&#BGPPPPPPPPPPPPPPPPP555555555555P5555555555555PPPP55PP5J?YPPYJYG&&@@@@@@@@@@@\n@@@@@@@@@@@@@@@@@@@@@#BPPPGGPPPPPPPPP5555555555555555P555555555555555PPY5P5PP5YJY5J?JJ#GG@@@@@@@@@@@\n@@@@@@@@@@@@@@@@@@&&BGGGGGGGGGPPP5555555555555555P5?YGPY555555555555555JPPJ555555PJ?JJ5J5&@@@@@@@@@@\n@@@@@@@@@@@@@@@@@&#GGGGGGGGGGYPPJY555555555555555PY?YGY7J555555555555555G57Y55555J!7YY?J5#@@@@@@@@@@\n@@@@@@@@@@@@@@@&GGGGGGGGGGGGP5Y5Y55555555555555555YJ5P5?Y555555555Y5555555Y5555555?7J?!5YG&@@@@@@@@@\n@@@@@@@@@@@@@@@#GGGGGGGGGGGGPPPPP55555555555555YYYY555555YYYYY55555Y555555555555555?7!?5?Y&@@@@@@@@@\n@@@@@@@@@@@@@@#GGGGGBGGGGGGGPPP5555555YY5YYYY5YYYYYYYYYYYYYYYYYYYYYYY5JJJY555555555Y??JY7J&@@@@@@@@@\n@@@@@@@@@@@@@#GGGGPGGGGGGGGPGGP55555555YYYYYYYYYYYYYYYYYYYYYYYYY5YYYY5?!???Y555555555J?JY55&@@@@@@@@\n@@@@@@@@@@@@&GGGPGGGGGGGGGY?BB7~G5Y55YYYYYYYYYYYYYJ???Y5YYYYYYYYYYYYYY5YJ?!Y55YY555555JJJ??B@@@@@@@@\n@@@@@@@@@@@@#GGGGGGGGGGGGBJJ#G~7G5Y5YYYYYYYYYYYYYY^~PY^JYYYYYYYYYYYYYYYYYY55Y5555555555555P#@@@@@@@@\n@@@@@@@@@@@@BGGGPGGGGGGGPGY5BGY55555YYYYYYYYYYYYYY?^??:JYYYYYYYYYYYYYYYY555555555555555PGBB&@@@@@@@@\n@@@@@@@@@@@&GGGP5GBGGGGGPPGGPPP5555555YYYYYYYYYJYYYJ??JYYYYYYYYYYYYYY55Y555555555555YY5PGGB&@@@@@@@@\n@@@@@@@@@@@&BGP5PBBGGGGGGGPPPP5555YY5YYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYYP5!?GYYY55555555Y555YG&@@@@@@@@\n@@@@@@@@@@@&BG55PBGGGGGGGGPPPP55555555YYYYYYYYYYYJYYYYYYYYYYYYYYYYYYY5Y~?G7J555555555PPPYJG@@@@@@@@@\n@@@@@@@@@@@&BGPPGGGGGGGGGGGGP5PP5555Y55YYYYYYYYYYYYYYYYYYYYYYYYYYYYYYY55PP75555555555PPPPP#@@@@@@@@@\n@@@@@@@@@@@&BGBBBGGGPGGGGGP?!755PPPPPPPPPPPPP555?!YBYJY555YYYYYYYYYYYYYY55P55555555PPPPPPB&@@@@@@@@@\n@@@@@@@@@@@&BBBBBBGGGBBGGGPY5YYYYYJJJJJJYYYYYPPP!~Y#?^!Y5555YYYYYYYYYYYYY55555555555PPPPG&@@@@@@@@@@\n@@@@@@@@@@@&BB#BB#BGGPYJ7!~~^^^^::::...::::::::^^~~~!7?JJJYY55555YYYYY55555PPP55555PJ5PG#@@@@@@@@@@@\n@@@@@@@@@@@&BB#BG5YYYYJJJ?7!~^:::::::.:::::::::..\u00A0\u00A0\u00A0\u00A0\u00A0\u00A0...:^~!7JYY555Y~!?YPPP555555P55PG&@@@@@@@@@@@\n@@@@@@@@@@@@BBBYJYPB&&&@@@&&#GP5J7~^^::^^^^^^^^^~7JY5PGGBBBBBBGP5Y?7JYYJ!~5P5555555PPPPG#@@@@@@@@@@@\n@@@@@@@@@@@@BBYJYG###BGGGGB#&&@@&#PY!~^^^^^^^~!?5GB####BBPY777?JYPPPY??JYY5PP555555PPPGPB&@@@@@@@@@@\n@@@@@@@@@@@@#PJY5PP555PGBGGGGPPGBBGP5J7!~^^^^~!7?JJY5PPPP5Y??77!!7?YJJ777?J5P55555YYPPPGB&@@@@@@@@@@\n@@@@@@@@@@@@@PY55PP5P#&&GYP#&GGGYPGB#GY7~::::^~7JY5PPP5G&&B##BGP5YJ??77777?JY5PP5Y5YPPPB#@@@@@@@@@@@\n@@@@@@@@@@@@@BJY55PGB&#G?^7PBGP7^?Y5##PJ~^..:^~JYY55J!.~5BBBPJPBBP5YJJ??????JJYPGG5Y5PPB&@@@@@@@@@@@\n@@@@@@@@@@@@@&YYY555PPGP5YJJJ?!~~!?YG#G?~^.:^^~?J?YYYJ?7??77!!7?JJ?????????JJYY5B&#GGPPG&@@@@@@@@@@@\n@@@@@@@@@@@@@@G555YY55PPP55YYJJJJ?J5PB5?!^:^^^~!7?JY5555YJ??????77!7777????JYY5PGP5#&BGG&@@@@@@@@@@@\n@@@@@@@@@@@@@@G55YYJJJYYYYYYYJJJ?JJYPGY7~^^^^^^~~~!77??J????77!!!~!!!777???JY55PG?^YGGGB@@@@@@@@@@@@\n@@@@@@@@@@@@@@GP5YJ??77777777777?JY5PP?!^^^^~~^^~~^^^^~~~~!~~~~~~~~~!!!7??JY5555G?~J7!J#@@@@@@@@@@@@\n@@@@@@@@@@@@@@GP5YJ?77!!!!!!!!!7?YY5557~^^^^~^^~~~^^^^:^^^~~~~~~^^^^~~!!7?JY55Y5G?77~^~G@@@@@@@@@@@@\n@@@@@@@@@@@@@@GP55YJ?77!!!!!!!77?Y555Y7~^^^^~~~~~~^^^^^^^^^^^^^^^^:^~~!7??JYYYYPP?!!~~!G@@@@@@@@@@@@\n@@@@@@@@@@@@@@GP555YJ?7777!!!77?Y55PY7~^^^^^^~!!!!!~^^^^^^^^^^:^:^^^^~!7?JJYYYYPP?!~7?G@@@@@@@@@@@@@\n@@@@@@@@@@@@@@BPPP55YJ??77777??YYJJY?!^::::^^^~~~~~!!~^~~~~~~^^^^^^^~!7?JJYYYY5GP55Y5G&@@@@@@@@@@@@@\n@@@@@@@@@@@@@@&PPPP55YJJ?7????J5YJJJ7^:....:^^~7?7!77^^^~~!7777!!~~!!!7?JJJYYY5GPYYY5P&@@@@@@@@@@@@@\n@@@@@@@@@@@@@@@GGPPP55YJ?????JY5GBBGY!^::::~!7JY55J?~^^^^^~~!!7?JJ??7????JJY5YPBPJJJYP#@@@@@@@@@@@@@\n@@@@@@@@@@@@@@@&GGPP555YJJJ?????YPB##GYJ????7!!!!!!!~~~~~~!!!!!77JYJ??????JY55GB5JJJYP#@@@@@@@@@@@@@\n@@@@@@@@@@@@@@@@BGPPP555YYJJ??7??JY5PPGP5J77!!!!!!!!!!!!!!!77?????JJ??????JY5PGG5JJY5PB@@@@@@@@@@@@@\n@@@@@@@@@@@@@@@@&GPPPPPP55YJJJ????????J?7!!7!!!!~~~~~~~~~7?JYYJY?????????JJ5PGGGYYYY5GG#@@@@@@@@@@@@\n@@@@@@@@@@@@@@@@@#GPPPGPP55YJJ?7!!!!!!!!~~~!~~!!!!77??J5PP5YJJJ??JJJ???JJY5PGGGPYYY5PPPG#@@@@@@@@@@@\n@@@@@@@@@@@@@@@@@@BGGPGGGPP5YYYJJJJJJJYYYYJY55555555555YJ7!7????JJJJJJJY55PGGGG5YY55PPPGB#&@@@@@@@@@\n@@@@@@@@@@@@@@@@@@@#BGGGBGGPPGB###BGGPPP555YYJ???77????77!7?JJJJYYY5YY55PPPGGG5YYY5PPPGGGGGB#&&@@@@@\n@@@@@@@@@@@@@@@@@@@@&#BBBBBGPP5PPP5YJ?7!!~~~~~~~!?JJJJ?777?JYYY5555555PPPPPGPYJY55PPPPGGGGGGGGGB#&@@\n@@@@@@@@@@@@@@@@@@@@@@#####BGP55555555YJ?7777???JJJJJ?777?JJYYYY55555PPPPPPJ??JY5PPPPPPPPPPPPPPPPGB#\n@@@@@@@@@@@@@@@@@@@@@@@&####BGGPP555PPPPPPPPPP55YJ??777?JJYYYYY5555PPPGPPY?7??J5P55PPPPPP555555555PP\n@@@@@@@@@@@@@@@@@@@@@@@@@&###BBGGP55555PB&##BPYJ?7777?JJJYYYYY55PPPPPPP5J?77?JY55555PPP555Y5Y55Y5555\n@@@@@@@@@@@@@@@@@@@@@@@@@@@&#BBBGPP55555PBGG5J?77777??JYYYYY555PPPPPP5YYJ???JY55YY555555555YYYYYYY55\n@@@@@@@@@@@@@@@@@@@@@@@@@@@@&#BBGPP55555555J?77?7????JYYYYY55PPPGGP555YJJ??JY5YYJYY555YYYYYYYYYYYYY5\n@@@@@@@@@@@@@@@@@@@@@@@@@@@@@##BGPGGPPPPPP5YJJJJJJJJJJYYY55PPGGGPP555YYJJJY5YJJJJJYY5YYYYYYYYYYYYYY5\n@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@&#BGGGGGGBBBGPP55YYYYYYY555PGGGGPPP555YYYY55YYYJ???JYY55555555YYYYYYYY\n@@@@@@@@@@@@@@@@@@@@@@@@@@@@@&&&##B#BBB####BGPP55555PPPPPGGGPPPP555555555YYYJ????JY555555555YYYYYYYY\n@@@@@@@@@@@@@@@@@@@@@@@@@@@@&&###&&&&&&&&&&&BBGGGGGGGGGGGGGPPPP555555??Y5YYYJ??7?JY555555555YYYYYYJJ\n@@@@@@@@@@@@@@@@@@@@@@@@@@&&&######&&&&&&&&&&##BBBBBBGGGGGPPPPP5PP5?~7Y5YYYJ???7?JY55P5P5555YYYYJJJJ\n@BGG5GPPYG@@@@@@@@@@@@@@&&####BB###&##&&&&&&&&####BBBGGGPPPPPPPPPJ77YP55YYYY??77?JY5PPPPPP55YYYYJJJJ\n@GGGPPGPPG@@@@@@@@@@@@@&&&########&&&&&&&&&&&&#####BBBGGGGGGGGG5?7YPPP55555YJ???JYPGGGGGPP55YYYYYJJY
`);
</script>
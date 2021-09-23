---
title: "Isolated Island"
excerpt: "2D strategy Game: survive a storm on an isolated island"
number: 3
header:
  overlay_image: /assets/images/game_isolated.png
  overlay_filter: 0.5
  teaser: /assets/images/game_isolated.png
  # actions:
  #   - label: "More Info"
  #     url: "https://uscgamesexpo.com/game"

gallery:
  - image_path: /assets/images/isolatedIsland/clip1.png
  - image_path: /assets/images/isolatedIsland/clip2.png

gallery2:
  - image_path: /assets/images/isolatedIsland/clip3.png
  - image_path: /assets/images/isolatedIsland/clip4.png

---
## Intro
I worked on this game project from January - April 2021 with my friends. It is a **2D survival game** where you
needs wisdom to survive on a isolated island.

The game tells a story that after a big storm, a girl named Jin is separated from her family, she needs to survive by herself on a drifting island and try to find her family.  With the help of the robot Bee01 which is built by Jin's father, Jin can collect resources in the sea, build new constructions and continue her journey. 

The game is constructed under the *Rx.Net* framework. We use **observers/subscribers** model to fulfill various
responses needed in the game. 

## Contribution
* Implemented the **build system** to build island under constraints.
* Set up the **numerical management system** to manage player status(health/thirsty/hunger state).
* Developed the conversation **follow** mechanism.
* Imported an **audio manager** to play background/effect music.

{% include gallery%}

{% include gallery id="gallery2" %}
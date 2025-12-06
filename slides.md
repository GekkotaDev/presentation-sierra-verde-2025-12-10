---
theme: neversink
mdc: true
fonts:
  sans: Fira Sans
  mono: Fira Code

transition: view-transition
layout: cover
color: navy
---

# Sierra Verde {.inline-block.view-transition-title}

~~Lightning talk~~ by **Jeremy** and **Joseph** under the team ~~**Dreadbytes Softworks**~~ **Bitflip Softworks**

:: note ::

\* Presented with [Slidev](https://sli.dev), also available in `PPTX` format \



---
layout: side-title
side: l
color: red
titlewidth: is-4
align: rm-lm
title: Side Title Layout (Another)
---

:: title ::

# Slides Found @ {.inline-block.view-transition-title}

# <mdi-arrow-right />

:: content ::

- **Repository/Source** \
  github.com/gekkotadev/presentation-sierra-verde-2025-12-10
- **Deployed Live @** \
  gekkotadev.github.io/slides/presentation-sierra-verde-2025-12-10



---
layout: section
---

# `Ch. 1`: INTRODUCTION {.inline-block.view-transition-title}

  “What kinda game do we wanna make?”



---
layout: section
color: navy
---

# Background of the Study {.block.view-transition-title.text-center}



---
layout: section
color: navy
---

# Area of Investigation {.block.view-transition-title.text-center}

*Fresh takes on proven if not stale mechanics* {.block.text-center}



---
layout: section
color: navy
---

# Game Overview {.block.view-transition-title.text-center}

*For a plot driven RPG with sentient cars* {.block.text-center}



---
layout: section
color: navy
---

# Genre {.block.view-transition-title.text-center}

*Action RPG, Driving + Racing* {.block.text-center}



---
layout: section
color: navy
---

# Target Audience {.block.view-transition-title.text-center}

🪟🐧🍎🤖 {.block.text-center}



---
layout: section
---

# `Ch. 2` REVIEW OF RELATED LITERATURE {.inline-block.view-transition-title}

  “What can we learn from what others have done?”



---
layout: two-cols-title
color: navy
---

:: title ::

# Foreign Literatures {.inline-block.view-transition-title}

Primarily composed of documentation and other presentations.

:: left ::

- Godot game engine and assoc. documentation
- Engine Simulator by Ange Yaghi
- ~~Blender~~ Blockbench Wiki
- Material Maker documentation
- Multiple context aware dialog systems

:: right ::

The foreign literatures that were selected for inclusion into the project were primarily
concerning with the development of the game itself — in other words, what are the right
tools for the job?



---
layout: two-cols-title
color: navy
---

:: title ::

# Local Literatures {.inline-block.view-transition-title}

Less game development and more game design.

:: left ::

- The United Nations Sustainable Development Goal #9
- “The Development of a 3D Game Engine” (Espiritu, Limcaoco, Santiago, 2003
- Build! Build! Build! and Build Better More programs
- TESDA Training Regulations Manual for 3D Game Development NC III

:: right ::

The selected local literatures here are geared towards game design and influencing the
direction of the plot.



---
layout: two-cols-title
color: navy
---

:: title ::

# Foreign Games {.inline-block.view-transition-title}

:: left ::

- The Choro-Q games by far the biggest inspiration; a series of quirky car RPGs that have you going on adventures (e.g: become the president of the entire world)
- Despite Electronic Arts™, Need For Speed admittedly has high quality level design
- Forza Horizon rewarding the mere act of having fun driving.

:: right ::

Videos presenting gameplay

<Youtube id="lSOobaKUlEs?start=32" autoplay />

<Youtube id="_oeEL41X3yE?start=267" autoplay />



---
layout: two-cols-title
color: navy
---

:: title ::

# Local Games {.inline-block.view-transition-title}

Games made within the Philippines

:: left ::

- Until Then developed by Polychroma Games and published by Maximum Entertainment
- Fallen Tear: The Ascension developed by Winter Crew Studios and published by CMD Studios
- Academia: School Simulator developed by Squeaky Wheel Studio Inc and published by Paradox Interactive
- Jeepney Simulator developed and published by Spacezero Interactive

:: right ::

:img{src="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/1574820/header.jpg?t=1746722193"}
:img{src="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/1446900/header.jpg?t=1755871869"}



---
layout: section
---

# `Ch. 3`: METHODOLOGY {.inline-block.view-transition-title}

  “How is it done?”



---
layout: top-title
color: navy
---

:: title ::

# Design Version {.inline-block.view-transition-title}

:: content ::

The current minimum hardware it had been tested on

- Windows 11 25H2; Godot supports up to Windows 10
- AMD Ryzen 3700U (4-cores, January 2019)
- Integrated Radeon RX Vega 10 graphics; **current bottleneck**
- Runs on Hard Disk Drives; assumed to be less than 5 GB large when fully production ready.
- 24 GB RAM though guesstimated can run on devices with less than 8 GB RAM



---
layout: top-title
color: navy
---

:: title ::

# Design Guidelines {.inline-block.view-transition-title}

:: content ::

Targets we strive to hit

- United Nations Sustainable Development Goals
- Low poly PSX style graphics
- Zero to Hero ~~(or bootlicker)~~ plot with a narrative around working odd-jobs and having fun
- Consistent 24+ FPS on Ryzen 7 3700U + Radeon RX Vega 10 integrated graphics



---
layout: top-title
color: navy
---

:: title ::

# Game Design Definition {.inline-block.view-transition-title}



---
layout: top-title
color: navy
---

:: title ::

# Game Architecture {.inline-block.view-transition-title}

:: content ::

- COTS ("Commercial" Off The Shelf) software — more free/libre and open source than commercial
- Vertical Slice Architecture
- Menus for user navigation and accessibility


---
layout: top-title
color: navy
---

:: title ::

# Conceptual Framework {.inline-block.view-transition-title}

:: content ::

- 



---
layout: top-title-two-cols
color: navy
---

:: title ::

# Algorithms In The Game {.inline-block.view-transition-title}

:: left ::

## Used

- Middleware system `O(n)`: Add functionality to cars without directly hard
  coding it into the car.
- Dynamic camera effects
- Data-driven contextual dialog system **?**: Implementation remains incomplete and
  likely would only be finished past this term.

:: right ::

## Missing

- Behavior Tree based AI
- NoSQL binary serialization based save system: Implemented using Godot Resources
  with additional work done to prevent arbitrary code execution (potentially injecting
  malware)



---
layout: quote
author:  ̶G̶L̶a̶D̶O̶S̶ Jeremy
---

# Room for Improvements {.text-center.view-transition-title}

This was a ~~triumph~~ failure, I'm making a note here ~~"Huge success"~~ "Revolting"



---
layout: top-title
color: navy
---

:: title ::

# Managerial Mishaps {.text-center.view-transition-title}

:: content ::

::blockquote{.block.text-center.translate-y-[16vh]}

  *My biggest mistake was not growing a spine a la Gordon Ramsay when it was most needed*

  — **Jeremy**
::



---
layout: top-title-two-cols
color: navy
---

:: title ::

# Overpromising, Underdelivering {.text-center.view-transition-title}

:: left ::

The scope of the game meant it was bound to be unfortunately incomplete this term.

To make up for this failure **Bitflip Softworks** hopes that it sets the groundwork /
foundation for their actual thesis game and/or future endeavors

<br />

It is what is considered in **development hell** not helped by the battle over the rights
to the game that had demoralized the team's motivation.

:: right ::

# Develpoment Limbo Example {.block.text-center}

:img{src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi0.wp.com%2Fgeardiary.com%2Fwp-content%2Fuploads%2F2011%2F06%2F2011-06-27_00001.jpg&f=1&nofb=1&ipt=f94dec5cfb6e2d2426897266b1f86c6ddb6c4ef86e7f6d1f72fc23bec3994065"}



---
layout: top-title
color: navy
---

:: title ::

# Overthinking {.text-center.view-transition-title}

:: content ::

  # What Is Analysis Paralysis?
  
  > Analysis paralysis is an inability to make a decision due to over-thinking a problem. An individual or a group can have too much data. The result is endless wrangling over the upsides and downsides of each option, and an inability to pick one.



---
layout: credits
color: black
---

# Fin. {.inline-block.view-transition-title}

<!--
SPDX-FileCopyrightText: 2023 Dominik Wombacher <dominik@wombacher.cc>

SPDX-License-Identifier: MIT
-->

# Customization

To replace any image in `assets/`, add your custom version into this folder (`custom/`).

When the game starts, it will first check the `custom/` folder and fallback to `assets/`. 
This means, custom images have precedence over assets shipped with the code.

List of customizable assets:

- Mascot / Bird
  - bird-sprite.png
- Game title
  - title.txt
- Welcome screen
  - message-initial.png
- Restart button
  - restart-button.png
- GameOver logo
  - gameover.png
- Scoreboard numbers
  - number0.png
  - number1.png
  - number2.png
  - number3.png
  - number4.png
  - number5.png
  - number6.png
  - number7.png
  - number8.png
  - number9.png
- Pipes
  - pipe-green-top.png
  - pipe-green-bottom.png
  - pipe-red-top.png
  - pipe-red-bottom.png
- Backgrounds
  - background-day.png
  - background-night.png
- Ground
  - ground-sprite.png

Pipes and Background change every 10 points, example: 
- 0-9 points = green pipe and day background
- 10-19 points = red pipe and night background.
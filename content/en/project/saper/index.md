---
title: Minesweeper
summary: Minesweeper game in Python
tags:
  - Python games
date: '2022-05-28T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo from https://minesweeper.online/ru/
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Watch code
    url: https://gist.github.com/milhani/daa3c8a3442b3a554029d847ed5f4a5a
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---
Minesweeper is a computer puzzle game.

Game principle

A flat or voluminous playing field is divided into adjacent cells (squares, hexagons, cubes, etc.), some of which are "mined"; the number of "mined" cells is known. The goal of the game is to open all cells that do not contain mines.

The player opens the cells, trying not to open a cell with a mine. Having opened a cell with a mine, he loses. Mines are placed after the first move, so in new versions it is impossible to lose on the first move. In the first version (Windows 95-Windows XP), it was quite common for a mine to appear under the first open cell. If there is no mine under the open cell, then a number appears in it, showing how many cells adjacent to the newly opened cell are “mined” (in each version of the game, the neighborhood is determined in its own way); using these numbers, the player tries to calculate the location of the mines, however, sometimes even in the middle and at the end of the game, some cells still have to be opened at random. If there are no mines under the neighboring cells, then some “non-mined” area opens up to the cells in which there are numbers. The player can mark "mined" cells so as not to accidentally open them. By opening all "non-mined" cells, the player wins.

---
title: Tic-tac-toe
summary: Tic-tac-toe game in Python
tags:
  - Python games
date: '2022-05-28T00:00:00Z'

image:
  caption: Photo by George Shuklin
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Watch code
    url: https://gist.github.com/milhani/7a76f0166bffb76edaa7d47e6073426a

---

Tic-tac-toe is a logic game between two opponents on a square field of 3 by 3 cells or larger (up to the "endless field"). One of the players plays with "crosses", the second - with "noes". The traditional Chinese game (Gomoku) uses black and white stones.

Rules of the game

Players take turns putting 3×3 signs on the free cells of the field (one is always crosses, the other is always zeros). The first one to line up 3 of their pieces vertically, horizontally or diagonally wins. The first move is made by the player placing crosses.

Usually, at the end of the game, the winning side crosses out with a line its three characters (zero or cross), which make up a continuous row.

Analysis

Algorithms are well-known for each of the parties that guarantee a draw in any game of the opponent, and if he makes a mistake, they allow you to win. Thus, the game is in a state of "no man's death".

Below are some of these strategies. It is believed that the player always respects two rules that take precedence over all others:

Rule 1. If a player can win immediately, he does so.
Rule 2. If a player cannot immediately win, but his opponent could immediately win by making a move to a square, the player himself makes a move to that square, preventing an immediate loss.

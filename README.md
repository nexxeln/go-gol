<h1 align="center">Go-Gol</h1>

![demo](https://github.com/nexxeln/go-gol/blob/main/images/demo.gif?raw=true)

## Overview

Yet another implementation of the [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), this time in Go. This was just to practice my newly acquired Go skills.

If you're not familiar with the rules of the game, here's a quick overview from Wikipedia:

> The universe of the Game of Life is an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, alive or dead, or "populated" or "unpopulated". Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

> 1.  Any live cell with fewer than two live neighbours dies, as if caused by underpopulation.

> 2.  Any live cell with two or three live neighbours lives on to the next generation.

> 3.  Any live cell with more than three live neighbours dies, as if by overpopulation.

> 4.  Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

> The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed—births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick (in other words, each generation is a pure function of the preceding one). The rules continue to be applied repeatedly to create further generations.

## Built with

- [Go](https://golang.org/)
- [Ebiten](https://github.com/hajimehoshi/ebiten)

## Usage

- Clone the repository:

  ```bash
  git clone https://github.com/nexxeln/go-gol.git
  ```

- Run the program:

  ```bash
  cd go-gol
  go run ./main.go
  ```

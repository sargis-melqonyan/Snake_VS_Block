# Snake VS Block

## Overview
**Snake VS Block** is a simple, terminal-based game written in C++ that uses the `ncurses` library for handling graphical output. The game is inspired by the popular mobile game where the player controls a snake that must navigate through blocks, collecting items to grow longer and avoiding collisions that could end the game.

## Features
- Terminal-based interface using `ncurses`
- Dynamic gameplay with increasing difficulty
- Simple and intuitive controls

## Prerequisites
- C++ compiler (e.g., `g++`)
- CMake (version 3.10 or higher)
- `ncurses` library

## Installation

### Step 1: Install dependencies

#### Debian/Ubuntu
```sh
sudo apt-get update
sudo apt-get install -y g++ cmake libncurses5-dev libncursesw5-dev
```
### Step 2: Clone the repository
```sh
git clone https://github.com/sargis-melqonyan/Snake_VS_Block.git
cd Snake_VS_Block
```
### Step 3: Build the project
```sh
mkdir build
cd build
cmake ..
make
```
### Step 4: Run the game
```sh
./Snake_VS_Block
```

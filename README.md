[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/KjUzOSFc)

# Project 1 | Alien Love Letters – Group Info & Execution Guide

## Group Members

- Member 1: GONDA, Stephen James
- Member 2: MAGPANTAY, Antonio
- Member 3: MERCADO, Ervin Jerod
- Member 4: BUGAOAN, Carl Joseph

## Contributions

- Member 1: Part A
- Member 2: Part A
- Member 3: Part B
- Member 4: Part B

## Description

This repository contains the relevant files for Project 1 of CS 21.

> > Note that the instructions loaded in Part B of the project are 16 bits long to be consistent with the format used in Part A. In example, Instructions 8 bits long can be loaded as is.

> > Instructions 16 bits long (2 separate bytes) should be concatenated first before loading.

## Part A

`A1.py` contains the assembler for Part A

`A2.py` contains the registers, the memory and the main logic for executing commands

`A2_emulator.py` contains the pyxel instance acting as the monitor for executing Arch 242 commands.

`input.asm` contains the assembly code for running the snake program

`snek.asm` contains the assembly code for Part A3

### How to use

#### Part A1

Running from the root,

Simply run,

`python ./parta1/A1.py ./path/toyour.asm <hex | bin>`

(Replace python with whatever python version you have)

And replace hex or bin with your preferred output format.

This should output,

`output.txt` at the root of your directory.

#### Part A2

Running from the root,

Simply run,

`python ./parta1/A2_emulator.py ./path/toyour.asm`

(Replace python with whatever python version you have)

#### Part A3

Running from the root,

Simply run,

`python ./parta1/A2_emulator.py ./parta3/input.asm`

(Replace python with whatever python version you have)

## Part B

`B_logisim.circ` contains the Logisim-based implementation for Arch-242
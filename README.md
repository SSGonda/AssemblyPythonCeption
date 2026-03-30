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

> Note that the instructions loaded in Part B of the project are 16 bits long to be consistent with the format used in Part A. In example, Instructions 8 bits long can be loaded as is.

> Instructions 16 bits long (2 separate bytes) should be concatenated first before loading.

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

`python ./parta2/A2_emulator.py ./path/toyour.asm`

(Replace python with whatever python version you have)

#### Part A3

Running from the root,

Simply run,

`python ./parta2/A2_emulator.py ./parta3/input.asm`

(Replace python with whatever python version you have)

### Development Convenience

- We had opted to add support for both comments and branch labelling for easier developer experience! At the moment we support only inline comments denoted by `#` similar to RISC V.

- We had also opted to use the labelling system used by RISC V to ease the usage of branch instructions for our snake game.
  - Kindly note that this implementation only supports when the instruction is on the same line as the label.
E.g:
```
this_works: nop
```
```
this_wont_work:
                nop
```



## Part B

`B_logisim.circ` contains the Logisim-based implementation for Arch-242
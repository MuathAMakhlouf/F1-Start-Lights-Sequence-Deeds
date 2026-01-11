# F1-Start-Lights-Sequence-Deeds
A simulation of the F1 start light sequence using Digital Logic components in Deeds.

# F1 Start Light Sequence Simulator 🏎️

## Overview
This project is a digital logic simulation of the Formula 1 Race Start procedure. It replicates the sequential 5-red-light buildup and the specific "Lights Out" trigger used to start Grand Prix races.

Built using **Deeds (Digital Electronics Education and Design Suite)**.

## How It Works
The circuit uses a **5-bit Johnson Counter** logic design to control the sequence:
1.  **State 0-5:** Lights turn on sequentially (1... 2... 3... 4... 5) representing the engine rev buildup.
2.  **Hold State:** All 5 lights remain on, building tension.
3.  **Lights Out:** An Asynchronous Clear signal is triggered manually to instantly reset all Flip-Flops to 0, signaling the start of the race.

## Circuit Features
* **Components:** 5x D-Flip Flops, Clock Source, Logic Switches, LEDs.
* **Logic:** Sequential Shift Register behavior with manual Asynchronous Reset.

## Screenshots
*(Upload your screenshot here or delete this line)*

## How to Run
1.  Download the `.pbs` file.
2.  Open it in **Deeds Circuit Simulator**.
3.  Enable simulation and toggle the "Start" switch.

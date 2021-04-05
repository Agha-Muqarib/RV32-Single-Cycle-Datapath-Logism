# RV32-Single-Cycle-Datapath-Logism

This repository contains Risc V 32 bit single cycle data path simulated on Logism upon loading instructions.

![Image to Circuit](https://github.com/Agha-Muqarib/RV32-Single-Cycle-Datapath-Logism/blob/main/Images/Risc%20V%2032%20Bit%20SIngle%20Cycle%20Datapath.jpg)

## Instructions

To simulate, follow these steps:

* Open [Venus](https://www.kvakil.me/venus/).
* Write your customised instructions and click on dump to get the hex code.
* Create a .txt file (say "x.txt")
* Copy the hex code from venus into "x.txt" and save it.
* Clone this repository and open  [Combined.circ]( https://github.com/Agha-Muqarib/RV32-Single-Cycle-Datapath-Logism/blob/main/Combined.circ).
* Load x.txt into Instructions Memory and simulate.

## Supported Instructions:

Given below is the supported instruction set for RV32I except privilege instructions.

![Ibstruction Set](https://github.com/Agha-Muqarib/RV32-Single-Cycle-Datapath-Logism/blob/main/Images/instructionRV32I.png)

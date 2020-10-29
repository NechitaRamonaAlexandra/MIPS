# MIPS
## MIPS(Microprocessor without Interlocked Pipeline Stages)
This is my implementation of a single-cycle, reduced instruction set MIPS(Microprocessor without Interlocked Pipeline Stages). It is implemented to run on a Basys3 development board, and the code is written in VHDL. It has a structural architecture and 5 execution stages: instruction fetch, instruction decode, execution unit, memory unit and write back.

The microprocessor can perform arithmetic and logic instructions, immediat arithmetic and logic instructions, branch instructions and jump instructions. It has a short program written that performs adding, substraction, logic or and some jumps, purely for testing out the functionalities of the MIPS.

The 7-segment display of the development board is also used, by default for displaying the memory address, but using the switches on the Basys3 it can display also:
- the result obtained by the ALU (execution unit)
- PC
- jump address (if available)
- some of the flags

It is a particularly interesting project, since it was extremely interesting to explore the depths of how computers work, how pieces of hardware put together read and understand the instructions given. It was a thrill to design a microprocessor from scratch and to learn about computer's architecture.

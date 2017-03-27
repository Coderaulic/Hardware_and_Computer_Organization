# Hardware_and_Computer_Organization

#### Objectives:

- An introduction to the architecture, operation, and organization of a modern computing machine.
- Topics: basic logic operations, state-machines, register models, memory organization, peripherals, and system issues. 
- Assembly language taught in order to understand the instruction set architecture and memory model of the computer. 

===============================================================================<br>
Title:&emsp;&emsp;&emsp;&emsp;
Assembly Final Project<br>
Date:&emsp;&emsp;&emsp;&nbsp;&nbsp;&nbsp;
03/13/2016<br>
Authors:&emsp;&emsp;&nbsp;&nbsp;
Ryu Muthui, Joon Jung, Kevin Tan<br>
Description:&emsp;
Reassemble machine code in memory back into human readable assembly code.<br>
===============================================================================<br>
### The <a href="https://github.com/Coderaulic/Hardware_and_Computer_Organization/blob/master/JKR_DISASSEMBLER_MAIN_W16.L68">Disassembler</a>:

This program is written in Motorola 68000 Assembly Language (M68k), and its purpose is to reassemble machine code back into human readable opcodes and effective addresses.

The program flow begins by asking the user the starting and ending memory address of where the program is located in memory. From the starting memory address, the disassembler project code (this program) will read-in the machine code (as Hexadecimal values) and decode it back to readable code. For non-decodable data, "$DATA" is printed. The program code that was loaded into memory is basically re-displayed back. It will decode line-by-line until the specified ending memory address. When reaching the ending address, the program can be restart or terminated.

This project was extreamly challenging yet fantastically rewarding. Learning to program at the lowest level for the CPU was quite the experience and deepened my appreciation for high-level languages.

Sample output of the program: Green shows memory addresses and Blue shows reassembled machine code from memory.<br>
![demo](https://cloud.githubusercontent.com/assets/10789046/24360657/cee7eeac-12bc-11e7-9558-74af19971f37.jpg)<br>

Motorola 68000 Assembly Language (M68k) at a glance:<br>
![opcode](https://cloud.githubusercontent.com/assets/10789046/24360662/d18f3a52-12bc-11e7-81bb-5069f9296bbb.jpg)

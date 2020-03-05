# CHUMP-processor
CHUMP (for: Cheap Homebrew Understandable Minimal Processor) is a tiny processor intented to be implemeted with less than 10 TTL chips. from my experience i never saw more simplistic Do it Yourself processor. it was described by Dave Feinberg in his paper A Simple and Affordable TTL Processor for the Classroom. It premary tergets teaching porposes.

This repository contains two implementations of CHUMP using the digital simulator [Logisim](http://www.cburch.com/logisim/), one is totally identical to the paper circuit using the same TTL chips, the second use more generalists components each created from scratch with logic gates.

This project was first prescribed like a mini project for college students, it was required for students to implement two basic programs, Factorial program and Fibonacci program.

## Files description:
1. CHAMPS.circ : the main circuit with components created from scratch.
2. CHAMPS-TTL.circ : the main TTL circuit.
3. 74xx Libary.circ : 74xx TTL chips library, used in CHAMPS-TTL circuit.
4. Control Signals.ROM : the Control Signals ROM to use in the CU-ROM (Control Unit) in CHAMPS circuit.
5. Control Signals-TTL.ROM : the Control Signals ROM to use in the CU-ROM (Control Unit) in CHAMPS-TTL circuit.
6. Instructions Control Signals.txt : a text file describing the binary content of Control Signals ROM.
7. Instructions Control Signals [TTL].txt : a text file describing the binary content of Control Signals-TTL ROM.
8. A Simple and Affordable TTL Processor for the Classroom.pdf : the initial paper describing CHUMP.
9. mini-projet.pdf : the project statement with a description and a guideline for constructing CHUMP (in french language).
10. mini-projet [en].pdf : the project statement with a description and a guideline for constructing CHUMP.
11. factorial.ROM : the binary Factorial program. To load on PGM-ROM (program ROM).
12. factorial.txt : a text file describing the Factorial program with assembly and pseudo-code.
13. factorial.RAM : the binary RAM file to use with Factorial program, its porpose is to initialise the program variables. To load on RAM.
14. fibonacci.ROM : the binary Fibonnaci program. To load on PGM-ROM (program ROM).
15. fibonacci.txt : a text file describing the Fibonnaci program with assembly and pseudo-code.
16. test-pgm.ROM : contain the binary code of the program used in Dave Feinberg paper. To load on PGM-ROM (program ROM).

## Notes:
- Multiple seven segment displays were added to the datapath in the simulation for debugging purposes, allowing the user to see the evolution of the information through the processor.
- Credit to Ben Oztalay for the amazing 74xx Library. Some missing chips were added.

## Website:
[www.el-kalam.com](https://www.el-kalam.com/): my personal website, contains this project and others.

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WPMOLLWm)

**Names of group members**

- Santiago Gomez Ospina
- Miguel Angel Ortiz Puerta

**Operating Systems**

This code was run and works with the operating systems:
- Windows Pro 11 23H2 (64 bits)
- Ubuntu 24.04 LTS (64 bits)

**Programming Language**

- Python 3.12.3

**Tools Used**

- Visual Studio Code
- ChatGPT (used in the third step with the implementation of the maximum and minimum to solve the problem of range outputs for the array)

**Running Instructions**

To run the algorithm, it must be the following input:
1. Number of cases
2. Number of states
3. Alphabet characters in order
4. Final states
5. Transition rows (each row must start with the state and continue with the states to which it moves according to the order and characters used and written in step 3)

For ease of use, copy the following automata entries and paste them when running the code:

**Automaton 1:**
- 1
- 6
- a b
- 1 2 5
- 0 1 2
- 1 3 4
- 2 4 3
- 3 5 5
- 4 5 5
- 5 5 5

*Solution to be given by the algorithm*:  

(1, 2) (3, 4)

**Automaton 2:**
- 1
- 6
- a b
- 3 4 5
- 0 1 2
- 1 3 4
- 2 4 3
- 3 5 5
- 4 5 5
- 5 5 5

*Solution to be given by the algorithm*:
  
(1, 2) (3, 4) (3, 5) (4, 5)

**Automaton 3:**
- 1
- 6
- a
- 1 4
- 0 1
- 1 2
- 2 3
- 3 4
- 4 5
- 5 0

*Solution to be given by the algorithm*:  

(0, 3) (1, 4) (2, 5)

**Automaton 4:**
- 1
- 4
- a b
- 0 1
- 0 1 2
- 1 1 2
- 2 3 1
- 3 3 3

*Solution to be given by the algorithm*:  

(0, 1)

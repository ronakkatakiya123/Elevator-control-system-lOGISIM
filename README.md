# Elevator Control System (Digital Electronics Project)

## Project Overview
This project is a digital circuit simulation of an **Elevator Control System** designed using **Logisim**. [cite_start]It simulates the logical operations of an elevator moving between three floors (Ground, First, and Second) using combinational and sequential logic[cite: 8, 13].

## Key Features
* [cite_start]**Three-Floor Operation:** Logic for Ground, First, and Second floors[cite: 13].
* [cite_start]**Call System:** Includes "Up" and "Down" call buttons for each floor[cite: 13, 16].
* [cite_start]**Direction Logic:** Uses logic gates to determine if the elevator should move up or down[cite: 22, 27].
* [cite_start]**Visual Indicators:** - **Current Floor:** A 7-segment display shows the present floor[cite: 34].
    - [cite_start]**Direction Arrow:** An LED matrix indicates the direction of movement[cite: 29, 32].

## Technical Implementation
The circuit is built using several fundamental digital electronics components:
* [cite_start]**Sequential Logic:** D Flip-Flops are used to store and transition between floor states[cite: 8, 40].
* [cite_start]**Combinational Logic:** AND, OR, and NOT gates process the input signals from floor buttons[cite: 22, 40].
* [cite_start]**State Equations:** The system follows specific Boolean equations for state transitions (F(A) and F(B))[cite: 24, 25].
* [cite_start]**Prioritization:** The logic is designed to mimic real-world elevators by prioritizing calls in the current direction before reversing[cite: 37, 38].

## Components Used
| Component | Function |
|-----------|----------|
| **Logic Gates** | [cite_start]Decision-making for direction and movement[cite: 40]. |
| **D Flip-Flops** | [cite_start]Storing current floor status[cite: 40]. |
| **LED Matrix** | [cite_start]Visualizing elevator direction[cite: 40]. |
| **7-Segment Display** | [cite_start]Visualizing current floor position[cite: 34]. |
| **Clock Pulse** | [cite_start]Synchronizing sequential operations[cite: 40]. |

## How to Run
1. Download and install [Logisim](http://www.cburch.com/logisim/).
2. Download the `.circ` file from this repository.
3. Open Logisim and go to `File > Open` to load the circuit.
4. Use the **Poke Tool** (hand icon) to interact with the floor switches.

## Contributors
* [cite_start]**Katakiya Ronak** [cite: 5]

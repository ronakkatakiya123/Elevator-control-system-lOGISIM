# Elevator Control System (Digital Electronics Project)

## Project Overview
This project is a digital circuit simulation of an **Elevator Control System** designed using **Logisim**. [cite_start]It simulates the logical operations of an elevator moving between three floors (Ground, First, and Second) using combinational and sequential logic.

## Key Features
* **Three-Floor Operation:** Logic for Ground, First, and Second floors.
* **Call System:** Includes "Up" and "Down" call buttons for each floor.
* **Direction Logic:** Uses logic gates to determine if the elevator should move up or down.
* **Visual Indicators:** - **Current Floor:** A 7-segment display shows the present floor.
    - **Direction Arrow:** An LED matrix indicates the direction of movement.

## Technical Implementation
The circuit is built using several fundamental digital electronics components:
* **Sequential Logic:** D Flip-Flops are used to store and transition between floor states].
* **Combinational Logic:** AND, OR, and NOT gates process the input signals from floor buttons.
* **State Equations:** The system follows specific Boolean equations for state transitions (F(A) and F(B)).
* **Prioritization:** The logic is designed to mimic real-world elevators by prioritizing calls in the current direction before reversing.

## Components Used
| Component | Function |
|-----------|----------|
| **Logic Gates** | [cite_start]Decision-making for direction and movement |
| **D Flip-Flops** | [cite_start]Storing current floor status |
| **LED Matrix** | [cite_start]Visualizing elevator direction. |
| **7-Segment Display** | [cite_start]Visualizing current floor position. |
| **Clock Pulse** | [cite_start]Synchronizing sequential operations. |

## How to Run
1. Download and install [Logisim](http://www.cburch.com/logisim/).
2. Download the `.circ` file from this repository.
3. Open Logisim and go to `File > Open` to load the circuit.
4. Use the **Poke Tool** (hand icon) to interact with the floor switches.

## Contributors
* **Katakiya Ronak**

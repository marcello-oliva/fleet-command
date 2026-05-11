<h1 align="center">
  Fleet Command
</h1>

## Overview

Fleet Command is a **C++ implementation** of the classic Battleship game, designed with a focus on modular architecture, clarity, and extensibility.
It simulates a naval battle between two opposing fleets on a 2D grid. Players strategically deploy their ships and attempt to locate and destroy the enemy fleet.

The objective is simple: **sink all enemy ships before yours are destroyed.**

---

## Design Goals

- Clean modular C++ architecture
- Separation of game logic and presentation layer
- Extensibility for AI, networking, and GUI
- Application of modern C++ best practices

---

## Requirements

- C++17 or higher
- Compatible compiler (GCC, Clang, or MSVC)

---

## Build & Run

To build and run Fleet Command, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/marcello-oliva/fleet-command.git
   ```

2. Navigate to the project directory:

   ```bash
   cd fleet-command
   ```

3. Build the project:

   ```bash
   g++ -o main src/*.cpp
   ```

4. Run the executable:
   ```bash
   ./main
   ```

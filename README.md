# Coffee Ordering System

A console-based coffee ordering system built in C++ using core data structures — queue, linked list, and selection sort. Developed for the Data Structures & Algorithm subject (BERR 1233) at UTeM.

## Overview

This system simulates a coffee shop ordering experience where customers can customize their order and the system manages orders, calculates prices, and tracks order history — all without using standard built-in library functions.

## Features

- Choose from 6 coffee types: Americano, Espresso, Mocha, Latte, Cappuccino, Macchiato
- Customize temperature (hot/cold), topping, and size
- Maximum 3 orders per customer enforced via queue
- Real-time price calculation
- Order history stored and displayed using linked list
- Order types sorted alphabetically using selection sort

## Data Structures Used

| Structure | Purpose |
|---|---|
| Queue | Manages order prices, enforces 3-order limit |
| Linked List | Stores and displays order history |
| Selection Sort | Sorts coffee type names in order history |
| Struct (Array) | Stores menu items, prices, options |

## Tech Stack

- **Language:** C++
- **Tool:** Visual Studio Code
- **Concepts:** Queue, Linked List, Selection Sort, Modular Programming

## How to Run

1. Clone the repo
2. Open in Visual Studio Code or any C++ compiler
3. Compile: `g++ main.cpp -o coffee`
4. Run: `./coffee`

## Sample Output

The program greets the user, displays coffee types, prompts for temperature, topping and size, calculates total price, and tracks all orders. When 3 orders are placed, it displays the total bill and order history.

## Project Report

See [GB15_S2_S5_BERR_Report.pdf](./GB15_S2_S5_BERR_Report.pdf) for full documentation including flowchart, source code, and sample outputs.

## Video Demo

[Watch on YouTube](https://youtu.be/PPYvkgPHnC8?si=N9YuCSyx_AlLL4Ac)

## Team

Developed by Group 15, Section S2 & S5 — BERR 1233, Sem 2 2023/2024  
Universiti Teknikal Malaysia Melaka (UTeM)

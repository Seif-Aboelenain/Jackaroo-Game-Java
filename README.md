# 🎮 Jackaroo: Java Board Game

A Java-based implementation of the **Jackaroo board game**, playable against **three CPU opponents**, built using object-oriented programming and JavaFX.

---

## 📌 Overview

* 1 human player vs 3 CPU players
* Move marbles from **Home → Track → Safe Zone**
* First player to place all marbles in the Safe Zone wins

The project was built across 3 milestones:

* **Milestone 1 →** OOP design (classes, enums, interfaces)
* **Milestone 2 →** Game engine (rules, logic, validation)
* **Milestone 3 →** JavaFX GUI

---

## 🚀 Features

### 🎲 Gameplay

* 100-cell circular board
* Safe zones and base cells
* Trap cells that reset marbles
* Fire pit system (discard pile & deck refill)

### 🃏 Cards

* Standard + wild cards
* Movement, swapping, splitting, destroying, and skipping turns
* Card actions loaded from `Cards.csv`

### 🤖 CPU Players

* Automated gameplay
* Selects valid moves based on available cards and marbles

### 🖥️ GUI

* Built using JavaFX
* Interactive board and card selection
* Visual feedback for moves and turns

---

## 🧱 Project Structure

```
GAME/
├── src/
│   ├── application/      → JavaFX GUI (controllers, FXML, CSS)
│   ├── engine/           → Core game logic (Game, Board, Managers)
│   ├── model/            → Game entities (Cards, Players, Marbles)
│   └── exception/        → Custom exception handling
├── Cards.csv             → Card configuration
└── test/                 → Unit tests (Milestone testing)
```

---

## 🛠️ Tech Stack

* Java 17
* JavaFX (FXML + CSS)
* Object-Oriented Programming (OOP)
* Inheritance, Polymorphism, Encapsulation
* Interfaces (GameManager, BoardManager)
* Exception Handling (custom exceptions)
* File Handling (CSV)
* Collections (ArrayList)
* JUnit

---

## ▶️ How to Run

1. Open project in IntelliJ / Eclipse
2. Configure JavaFX
3. Run:

```
Main.java
```

---

## 📸 Screenshots


<img src="https://github.com/user-attachments/assets/d6a79efc-9e0c-480d-9f9a-241dc47846f6" />

<img src="https://github.com/user-attachments/assets/44427e29-e060-46e7-a7a6-fa0807ec9c1d" />

<img src="https://github.com/user-attachments/assets/5e7c626b-d3c6-420e-b42a-92406042b8a1" />



---

## 👨‍💻 My Work

* Implemented core classes: **Player, Board, Card, Marble**
* Built game logic for **movement validation, swapping, and traps**
* Developed **custom exception handling system**
* Implemented CPU player logic
* Designed project using **OOP principles**
* Built JavaFX GUI for gameplay

---

## 👤 Author

Seif Aboelenain
3rd Year Computer Engineering Student – GUC

# Unity Slot Machine Game

## Project Overview

A complete Slot Machine Game developed in Unity using C#.

The project simulates a classic casino-style slot machine featuring multiple reels, betting mechanics, random symbol generation, payout calculations, win detection, player balance management, result popups, and winning symbol visual effects.

The project was designed with a modular architecture following Object-Oriented Programming principles to ensure maintainability and scalability.

---

## Features

### Slot Machine System

* 3 Reel Slot Machine
* Random Symbol Generation
* Spin / Bet System
* Sequential Reel Stopping
* Player Balance System
* Payout System
* Result Popup System

### Gameplay Features

* Triple Match Win Detection
* Pair Match Win Detection
* Symbol-Based Payout Rewards
* Winning Symbol Highlight Effects
* Insufficient Balance Protection
* Payout Information Display

### User Interface

* Responsive Slot Machine Layout
* Balance Display
* Spin Button
* Lever Animation
* Result Notifications
* Payout Information Button

---

## Win Conditions

### Triple Match

The player wins when all three visible middle symbols match.

Examples:

* Cherry Cherry Cherry
* Bell Bell Bell
* BAR BAR BAR
* Seven Seven Seven

### Pair Match

The player receives a bonus reward when any two visible middle symbols match.

---

## Payout Table

| Combination          | Reward |
| -------------------- | ------ |
| Cherry Cherry Cherry | 200    |
| Bell Bell Bell       | 300    |
| BAR BAR BAR          | 500    |
| Seven Seven Seven    | 1000   |
| Any Pair             | 100    |

---

## Game Flow

1. Player presses the Spin Button.
2. Bet amount is deducted from the balance.
3. Reels begin spinning.
4. Reels stop sequentially.
5. Winning combinations are evaluated.
6. Rewards are added to the player balance.
7. Result popup displays the outcome.

---

## Project Architecture

### ReelController

Responsible for:

* Reel Spinning
* Symbol Generation
* Sequential Reel Stopping
* Win Evaluation
* Winning Highlight Effects

### SlotMachineManager

Responsible for:

* Spin Button Interaction
* Lever Animation Control
* Gameplay Flow Management

### Score

Responsible for:

* Player Balance
* Betting Logic
* Reward Calculation
* Payout Management

### PopUp

Responsible for:

* Result Notifications
* Payout Display
* User Feedback Messages

### WinningSymbolHighlight

Responsible for:

* Winning Symbol Visual Feedback

### PayoutButton

Responsible for:

* Displaying the payout table

---

## Technologies Used

* Unity Engine
* C#
* Unity UI System
* Coroutines
* Object-Oriented Programming

---

## Folder Structure

Assets/

├── Animations/

├── Materials/

├── Prefabs/

├── Resources/

├── Scenes/

├── ScriptableObjects/

├── Scripts/

│   ├── Manager/

│   ├── Reels/

│   └── UI/

├── Sounds/

├── Sprites/

├── UI/

---

## How To Run

1. Clone the repository.
2. Open the project using Unity.
3. Open the Main Scene.
4. Press Play.
5. Click the Spin Button to play.

---

## WebGL Build

A playable WebGL build is included in:

```text
Build/
└── WebGL/
```

---

## Development Approach

The project was developed using a modular architecture where gameplay systems are separated into dedicated components.

Key goals:

* Clean Code
* Reusable Components
* Separation of Responsibilities
* Scalable Architecture
* Clear Gameplay Feedback

---

## Future Improvements

Potential future enhancements:

* Wild Symbols
* Bonus Symbols
* Free Spins
* Jackpot System
* Multipliers
* Particle Effects
* Additional Sound Effects
* Leaderboards

---

## Author

Sunny Rajput

Unity Slot Machine Assignment

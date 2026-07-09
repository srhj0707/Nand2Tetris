# 🚦 Traffic Fever

**Traffic Fever** is a lane-crossing arcade game developed in the **Jack programming language** as part of the **Nand2Tetris (From NAND to Tetris)** course. The project runs entirely on the Hack computer platform and demonstrates how high-level game logic can be built on top of a computer system designed from first principles.

## 🎮 Gameplay

The objective is simple:

* Control the player vehicle.
* Avoid the continuously moving traffic.
* Stay within the road boundaries.
* Survive as long as possible without colliding with another vehicle.

The game ends immediately when a collision is detected.

---

## ✨ Features

* Object-oriented implementation in Jack
* Player movement using keyboard controls
* Multiple independently moving vehicles
* Collision detection using Hack memory mapping
* Lane-based road rendering
* Continuous game loop with real-time updates
* Game Over screen

---

## 🏗️ Project Structure

```text
Main
│
├── Lane
│   ├── prepares the road
│   ├── controls the game loop
│   ├── handles collisions
│   └── processes keyboard input
│
├── PlayerCar
│   ├── player movement
│   ├── drawing
│   └── screen boundary handling
│
└── Car
    ├── autonomous vehicle movement
    ├── drawing
    └── screen wrap-around
```

---

## 🛠 Technologies Used

* Jack Programming Language
* Hack Computer Platform
* Nand2Tetris OS
* Screen Library
* Keyboard Library
* Memory Library
* Output Library

---

## 📚 What I Learned

Developing this project helped me gain practical experience with:

* Object-oriented programming in Jack
* Event-driven game loops
* Graphics programming on the Hack platform
* Memory-mapped screen operations
* Collision detection
* Keyboard input handling
* Software design under hardware constraints

Most importantly, it strengthened my understanding of how software interacts with the underlying hardware in a computer built from the ground up.

---

## 🚀 Future Improvements

* More accurate pixel-level collision detection
* Multiple difficulty levels
* Score counter
* Increasing vehicle speed over time
* Sound effects
* Start menu and restart option
* Better vehicle graphics
* Multiple player lives

---

## 🙏 Acknowledgements

This project was developed as part of the **Nand2Tetris** course, an outstanding educational program that teaches how to build a complete computer system—from logic gates to modern software.

---

## 📄 License

This project is intended for educational purposes. Feel free to explore the code and learn from it.

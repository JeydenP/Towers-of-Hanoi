# 🏰 Towers of Hanoi (Python)

A command-line implementation of the classic **Towers of Hanoi** puzzle, built in Python using **stack data structures**.  

The goal of the game is to move all the disks from the first tower to another tower, following these rules:
1. Only one disk can be moved at a time.  
2. Each move consists of taking the top disk from one tower and placing it on another.  
3. No disk may be placed on top of a smaller disk.  
4. Traditionally, all disks must be moved from the **Left tower** to the **Right tower**, but in this version you can solve it on **any tower** as long as all disks end up stacked correctly (largest on bottom → smallest on top). 

## 📂 Project Structure
```text
Towers-of-Hanoi/
│── TowersofHanoi.py  # Main game logic
│── stack.py          # Stack class used to represent towers
│── node.py           # (If used) Node helper for stacks/disks
│── README.md         # Project documentation
│── .gitignore        # Ignored files (like __pycache__)
```
## ▶️ How to Play
1. Clone this repository:
   ```bash
   git clone https://github.com/JeydenP/Towers-of-Hanoi.git
   cd Towers-of-Hanoi
   ```
2. Run the game:
   ```bash
   python3 TowersofHanoi.py
   ```
3. Follow the prompts to move disks between stacks until you solve the puzzle.

## 🛠 Features
- Uses **Stack objects** to represent towers
- Enforces game rules (no larger disk on smaller one)
- Tracks and displays the minimum number of moves
- Interactive, text-based game loop

## 📸 Example Gameplay
```text
Let's play Towers of Hanoi!!

How many disks do you want to play with?
3

The fastest you can solve this game is in 7 moves


...Current Stacks...
Left Stack: [3, 2, 1]
Middle Stack: []
Right Stack: []

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
```

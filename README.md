# 🎮 Click-o-Mania: Color Matching Game with Python

A beginner-friendly **GUI puzzle game** built using Python's `tkinter`. Match all the color tiles within 25 moves. Designed to demonstrate GUI logic, randomization, score tracking, and game logic in a fun and interactive way!

![Preview](preview.png)

---

## 🧠 How It Works

- 🎯 **Objective**: Match all pairs of colored tiles in 25 moves or fewer.
- 🟪 Tiles start hidden in **grey**.
- 🎨 Clicking a tile reveals its color.
- ✅ Match two same-colored tiles → they stay revealed.
- ❌ Mismatch? Both go grey again. Your score (moves left) drops.
- 🔁 Use the **Reset** button to restart the game.

---

## 🧰 Tech Used

- `Python 3.x`
- `tkinter` (GUI library)
- `random` (for color shuffling)
- `functools.partial` (to pass arguments to buttons)

---

## 📷 Preview

![Game Demo](output(ss added in file) .png)

---

## 🚀 How to Run It

### 1. Clone the repo
```bash
git clone https://github.com/RICHARDKHRISTI/click-o-mania
cd click-o-mania

# 🎯 Card Sequence Deduction Game

A two-deck logic and deduction challenge where the **player** must guess a hidden 5-card sequence set by the **moderator** in **20 turns or less**.

---

## 🃏 Game Setup

### Decks
- **Deck 1 (Moderator's Deck)**  
  Contains 20 unique cards — Numbers **1 to 5**, each in **4 colors**:  
  **Red**, **Blue**, **Yellow**, **Green**.  

  Example:
    1Red, 1Blue, 1Yellow, 1Green
    2Red, 2Blue, 2Yellow, 2Green
    3Red, 3Blue, 3Yellow, 3Green
    4Red, 4Blue, 4Yellow, 4Green
    5Red, 5Blue, 5Yellow, 5Green

- **Deck 2 (Player's Deck)**  
Identical to Deck 1 but used only by the player for guessing.

---

## 🎮 How to Play

1. **Moderator Sets the Sequence**  
 - Using **Deck 1**, the moderator secretly selects **any 5 cards** in any order.
 - This sequence remains hidden throughout the game.

2. **Player Makes Guesses**  
 - Using **Deck 2**, the player selects and arranges 5 cards.
 - Cards can be placed in any order.

3. **Moderator Records Accuracy**  
 After each guess, the moderator provides feedback:
 - **Number Matches** → Correct number (color may differ)
 - **Color Matches** → Correct color (number may differ)
 - **Exact Matches** → Correct number **and** color **in the correct position**

 ⚠ An exact match counts towards **all three** categories.

4. **Game Continues**  
 - The player may make **up to 20 guesses**.
 - Feedback for each guess is stored in the **Guess History** table.

---

## 🏆 Winning & Losing

- **Win** → All 5 cards match exactly (number, color, position) within 20 guesses.  
- **Lose** → Fail to match the sequence exactly after 20 guesses.

---

## 💻 Game Features

- **Drag & Drop or Click** to arrange cards
- **Guess History Table** for past attempts
- **Timer** tracking total game time
- **Sound effects** for actions, wins, and losses
- **Win/Loss animations**
- **Restart & Clear Guess** buttons

---

## 🖱 Controls

- **Click a card** in the deck → Add to your guess.
- **Click a card in your guess** → Return it to the deck.
- **Drag a card** → Swap or place it in an empty slot.
- **Submit Guess** → Record your attempt.
- **Clear Guess** → Reset the current guess without using a turn.

---

## 📂 Files

- `index.html` → Main game file (HTML, CSS, JavaScript in one file).
- **Audio Assets**:
- [Winning Chimes](https://assets.mixkit.co/sfx/preview/mixkit-winning-chimes-2015.mp3)
- [Losing Drums](https://assets.mixkit.co/sfx/preview/mixkit-losing-drums-2026.mp3)
- [Select Click](https://assets.mixkit.co/sfx/preview/mixkit-select-click-1109.mp3)

---

## 🚀 How to Run

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Play the game!

---

## 🧑‍💻 Author

Created by **Manjot Singh Bajwa**, based on the classic sequence deduction concept.

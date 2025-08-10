# Blackjack Basic Strategy Trainer

An interactive, web-based quiz designed to help users learn and master the mathematically optimal **basic strategy** for Blackjack. The trainer provides instant feedback, performance tracking, and a clean, modern interface to make learning fast and effective.

---

# Table of Contents

1. [Features](#features)  
2. [How-to-Use](#how-to-use)  
3. [Technical-Details](#technical-details)  
4. [Future-Improvements](#future-improvements)  
5. [Contributing](#contributing)  
6. [License](#license)

---

# Features

This trainer is packed with features to create a comprehensive and user-friendly learning experience:

- 🃏 **Interactive Quiz Format**  
  Users are presented with random player hands and dealer upcards to simulate real game scenarios.

- 🧠 **Comprehensive Strategy Logic**  
  Logic is based on standard basic strategy and correctly handles:
  - Hard totals
  - Soft totals
  - Pairs (splits)
  - Late surrender options

- 💡 **Instant Feedback & Retry**  
  Immediate feedback on your action. If you make a mistake, you’re prompted to try again — reinforcing the correct play.

- ➡️ **Auto-Advance**  
  After a correct guess, the next hand is dealt automatically, keeping the training flow smooth.

- 📊 **Performance Reporting**  
  After a session of 20+ hands (configurable), receive a detailed report including:
  - Overall accuracy
  - Time-based rating of decision speed
  - A list of hands you struggled with

- ✨ **Sleek UI & Animations**  
  - Toggleable dark theme for comfortable viewing
  - Quick, realistic dealing animations

- ⚙️ **Customizable Sessions**  
  Choose how many hands you want to practice before starting.

- 📦 **Self-Contained & Portable**  
  The entire application runs from a single `index.html` file. No install or backend required.

---

# How to Use

## Online Play
- Click the following link to play online. https://xx-hekz-xx.github.io/BLACKJACK_TEACHER/
## Local Setup
1. Clone the repository or download the `index.html` file.  
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, etc.).

## Starting the Quiz
- Enter the number of hands you want to practice.
- Click **Start**.

## Playing the Game
- For each hand, observe your cards and the dealer’s upcard.
- Choose an action: **Hit**, **Stand**, **Double**, **Split**, or **Surrender**.
- The app gives instant feedback and allows a retry on an incorrect choice.

## Reviewing Performance
- After your session completes, a final report appears showing accuracy, average decision time, and hands to review.
- Click **Play Again** to start a new session.

---

# Technical Details

- **Frontend:** Vanilla HTML, CSS, and JavaScript (single file `index.html`).  
- **Styling:** Tailwind CSS via CDN for responsive UI.  
- **Architecture:** Pure client-side — no backend, no data is sent to any server.  
- **State Management:** Managed with JavaScript variables. Dark mode preference and (optionally) stats saved to `localStorage`.  
- **Basic Strategy Logic:** Implemented in JS — evaluates hand type (hard/soft/pair), dealer upcard, and recommended action based on standard basic strategy tables. Late surrender handled when enabled.  
- **Animations:** Lightweight, CSS + JS-based card dealing and feedback transitions.  
- **Portability:** Runs offline once the `index.html` file is downloaded (except when Tailwind CDN is used — for fully offline use, embed compiled CSS).

---

# Future Improvements

Potential features to prioritize next:

- **Rule Variations:** Options for rule sets (e.g., number of decks, dealer hits/stands on soft 17, doubling after split).
- **Card Counting Drill:** Separate mode to practice common counting systems (Hi-Lo, KO, etc.).
- **Sound Effects:** Subtle audio for dealing, correct/incorrect feedback.
- **Persistent Stats:** Save session history and progress across multiple sessions via `localStorage`.
- **Mobile Optimizations:** Further layout tweaks and touch gestures for mobile use.
- **Shareable Reports:** Export or share session results (CSV or image).

---

# Contributing

Contributions are welcome!

- Open an issue to discuss features or bugs.
- Send a pull request with changes or improvements.
- Keep the app single-file friendly where possible — if adding large assets, explain how to keep a portable distribution.

---

# License

This project is licensed under the **MIT License**.


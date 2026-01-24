# HEXGUESS

**HEXGUESS** is a sleek, fast, and open-source color guessing game where you challenge your knowledge of hexadecimal codes. Inspired by games like *Hexcodle*, HEXGUESS provides granular feedback to help you truly master the RGB spectrum.

---

## 🎮 How to Play

The objective is simple: **guess the 6-digit hex code** of the target color shown on the screen.

### Feedback Logic

For every character you guess, the game provides specific clues based on your selected difficulty:

* ✅ **Green Check** — The character is exactly correct.
* ⬆️ / ⬇️ **Single Arrow** — The value is close (off by 1–2 steps in the `0–F` sequence).
* ⏫ / ⏬ **Double Arrow** — The value is far (off by 3 or more steps).
* ❌ **Red X** *(Expert Mode)* — The character is incorrect, with no directional hints.

**Hex Order Reference**

```
0 < 1 < 2 < 3 < 4 < 5 < 6 < 7 < 8 < 9 < A < B < C < D < E < F
```

---

## 🚀 Features

* **Granular Clues**
  Real-time feedback for every single character of the hex code.

* **Difficulty Levels**

  * **Easy** — 10 guesses · Full proximity feedback (single + double arrows)
  * **Hard** — 5 guesses · Directional feedback only (single arrows)
  * **Expert** — 3 guesses · Binary feedback (Correct / Incorrect)

* **Persistent Progress**
  Your current game, settings, and full game history are saved to `localStorage`.

* **Game History**
  Revisit any previous game to see all guesses and their accuracy.

* **Midnight Theme**
  High-contrast, eye-friendly dark UI built with **Tailwind CSS**.

---

## 🛠️ Technology Stack

* **HTML5 / CSS3**
  Tailwind CSS for styling
* **JavaScript**
  Vanilla ES6+
* **Lucide Icons**
  Crisp, modern UI symbols

---

## 📦 Installation

HEXGUESS is a **web application** — no build process required.

### Run locally

Open `index.html` in any modern web browser.

---

## 📄 License

This project is licensed under the **MIT License**.
See the `LICENSE` file for details.

**Free and Open Source Software (FOSS).**

---

Created with passion for **color lovers** 🎨

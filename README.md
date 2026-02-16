# Flaggen-Quiz (Deutsch)

A German flag quiz game that loads all countries and flags online and quizzes the player with a timer.

## Features
- Shows a flag and asks: **"Welche Flagge ist das?"**
- **4 answers** always displayed in a clean **2x2 grid**
- Answers are **numbered (1–4)** and can be selected by mouse or keyboard
- **Timer per question** + speed bonus points
- Saves:
  - **High score** (best score)
  - **Score history** (last runs with date + settings)
- Export score history to a downloadable `flag-quiz-scores.json`

## How to Run
1. Create a folder, put `index.html` inside it
2. Open `index.html` in your browser
3. Internet is required (country + flag data is loaded online)

## Controls
- Click answers
- Keyboard:
  - **1–4** = choose answer
  - **Enter** = next question (after answering)

## Scoring
- Correct answer gives:
  - Base points
  - + (seconds left × bonus per second)
- Wrong answer or time out gives 0 points

## Data Source
- Countries + German translations + flag images are loaded from **REST Countries API**.

## Important Notes
- Needs internet access (flags are loaded online).
- If a flag fails to load, check your connection or the API availability.
- Score history and high score are stored in `localStorage` in the browser.

## Files
- `index.html` – the full game
- `README.md` – this file
- (Optional) `flag-quiz-scores.json` – exported score history file

## Next Ideas
- Difficulty levels (timer gets faster)
- Lives (❤️❤️❤️)
- Categories by continent
- Sound effects

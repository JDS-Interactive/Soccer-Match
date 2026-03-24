# ⚽ Soccer Match Deck

A lightweight, mobile-friendly soccer companion game you can run directly in your browser while watching a live match.

Built for casual, in-room play using a physical deck of cards and a phone — no backend, no install, no accounts required.

---

## 🃏 Concept

**Soccer Match Deck** turns a live soccer game into an interactive experience.

Players use a real deck of cards to make predictions about what will happen next in the match (goals, fouls, corners, etc.), then log those plays in the app and score points based on outcomes.

---

## 🎮 How It Works

1. Start a live soccer match on TV
2. Open the app on your phone
3. Add players
4. Each player draws cards from a physical deck
5. Players choose a card and log a prediction
6. Watch the match unfold
7. Mark each bet as **Win** or **Lose**
8. Track scores in real time

---

## 🧠 Card System

### Suits → Event Type

- ♥ **Hearts** → Goal events  
- ♠ **Spades** → Defensive events  
- ♦ **Diamonds** → Momentum events  
- ♣ **Clubs** → Chaos events (fouls, cards, etc.)

---

### Card Value → Time Window

| Card | Time Window |
|------|------------|
| A    | 1 minute   |
| 2–5  | 3 minutes  |
| 6–10 | 5 minutes  |
| J/Q/K| 10 minutes |

---

### Scoring

| Card Type | Reward | Penalty |
|----------|--------|---------|
| A        | +10    | -5      |
| 2–5      | +7     | -4      |
| 6–10     | +5     | -3      |
| J/Q/K    | +3     | -2      |

---

## 📱 Features

- Add and remove players
- Set teams and match label
- Log bets with suit + card value
- Automatic countdown timers
- Manual win/loss resolution
- Local storage (your game persists on your device)
- Fully mobile-friendly UI
- No internet required after load

---

## 🚀 Getting Started

### Option 1: Run via GitHub Pages

1. Create a repository
2. Upload `index.html`
3. Go to **Settings → Pages**
4. Set source to `main` branch `/root`
5. Open your live site:

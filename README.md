# ⚽ Soccer Match Deck

A mobile-friendly live soccer party card game that runs entirely in the browser.

Use a real 52-card deck, watch a live soccer match on TV, let every player lock one card into each round, then resolve the round based on what actually happens in the match.

No backend. No login. No install required.

---

## 🃏 Core Idea

**Soccer Match Deck** turns a live soccer match into a social card game.

Each player is dealt a hand from a physical deck.  
During each round, every player may commit one card from their hand and make a prediction tied to that card’s suit.

When a real event happens in the match, the round is resolved for everyone at once:

- winners gain app points
- losers lose app points
- losing cards are captured by the winners
- captured cards help determine the final winner

The game ends when the real match on TV ends — or earlier if someone earns an instant win.

---

## 🎮 How the Game Works

1. Enter the two teams
2. Add players
3. Deal the full deck evenly
4. Start a round
5. Each player locks one card and prediction
6. Watch the live match
7. Resolve the round based on the actual event
8. Continue until full time

---

## ♠️ Suit Categories

Each suit controls what kind of event the card can predict.

### ♥ Hearts — Goal / Finishing
Hearts are aggressive scoring cards.

Examples:
- Goal scored
- No goal in the window

---

### ♠ Spades — Defense / Prevention
Spades focus on stopping attacks.

Examples:
- Save happens
- Defensive stop / tackle
- No shot on target in the window

---

### ♦ Diamonds — Momentum / Buildup
Diamonds represent pressure and attacking buildup.

Examples:
- Corner kick
- Dangerous attack
- Possession swing

---

### ♣ Clubs — Chaos / Disruption
Clubs represent fouls, cards, and unpredictable interruptions.

Examples:
- Foul called
- Yellow card
- Substitution
- VAR check

---

## 🕒 Card Values and Time Windows

Card values affect both the time window and point strength.

| Card Value | Time Window | Risk / Reward |
|-----------|-------------|---------------|
| A         | 1 minute    | Highest       |
| 2–5       | 3 minutes   | High          |
| 6–10      | 5 minutes   | Medium        |
| J / Q / K | 10 minutes  | Lower         |

Each bet uses:

- **Base value:** 2 points
- **Card modifier:** based on card value

### Card Modifier

| Card Type | Modifier |
|----------|----------|
| A        | 6        |
| 2–5      | 4        |
| 6–10     | 3        |
| J / Q / K| 2        |

So:
- a winning Ace bet = **+8**
- a losing Ace bet = **-8**
- a winning 10 = **+5**
- a losing 10 = **-5**

---

## 🏆 Round Resolution

Every player can lock **one card per round**.

When the real event happens:
- all bets are checked together
- all correct bets win
- all incorrect bets lose

### Card Capture
If at least one player wins and at least one player loses:
- losing cards go to the round winners
- winners split those cards by winner strength order

Winning cards are discarded.

If everyone wins or everyone loses:
- all round cards go to discard

---

## 👑 Instant Win Rule

A player wins immediately if their **capture pile** contains:

- **10**
- **J**
- **Q**
- **K**
- **A**

of the **same suit**

This is called a **Royal Suit capture**.

---

## 📊 Final Winner

If no instant win happens, the game ends when the real soccer match ends.

The final winner is determined by:

**Total Score =**
- app points
- + capture pile bonus
- + remaining hand value

### Tiebreakers
1. Higher app points
2. Higher remaining hand value

---

## 📱 Features

- Mobile-friendly layout
- Multi-player support
- Full 52-card deck dealing
- Per-player hand tracking
- Round-based betting
- Shared round resolution
- Capture pile tracking
- Local device storage
- Instant-win detection
- Final leaderboard

---

## License

This project is licensed under the **Soccer Match Deck Community Attribution and Add-On License v1.0**.

You are free to use, share, and build add-ons for this project.  
If you rebrand or redistribute it, you must provide attribution to the original project and original author.

You may not redistribute modified versions of the original core code files.  
Public modifications must be added as separate add-on files or extensions.

This is a **source-available license**, not an OSI open-source license.

## 🚀 Running the App

### GitHub Pages

1. Create a repository
2. Upload `index.html`
3. Upload this `README.md`
4. Go to **Settings → Pages**
5. Deploy from the `main` branch `/root`

Your site will be live at:

```text
https://YOUR-USERNAME.github.io/REPOSITORY-NAME/
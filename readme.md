# 🧠 Generals – A Tactical Dice-Driven Board Game

Welcome to **Generals**, a fast-paced, turn-based strategy board game that combines chess-like positioning with the unpredictability of dice rolls. Whether you're defending your fortress or charging into the enemy keep, **Generals** demands wit, timing, and bold moves.

## 🎯 Objective

Generals is a two-player or 2v2 team-based board game where:

- **One side attacks** the opposing **General**.
- **The other side defends** using strategically placed units.
- The attacker **wins** by "hitting" the enemy General **3 times**.
- The defender **wins** by outlasting attacks or eliminating enough opposing units.

---

## 🧩 Game Components

- **Board Size**: 
  - Small Arena: `10x10` with `6 units` per garrison.
  - Large Arena: `12x12` with `10 units` per garrison.
  
- **Pieces**:
  - **Generals** (large pieces, 1 per team)
  - **Units** (small pieces, offensive/defensive soldiers)
  - **Garrisons** (starting zones)
  - **Moat** (area surrounding the Keep)
  - **Keep** (central zone housing the General)

---

## 🌀 Setup

1. **Toss**: Winner chooses:
   - Their team color
   - Whether to **Attack** or **Defend**
2. **Place General**:
   - Attacker places opponent’s General in the **Keep**
   - Defender places their General in the **Keep**
3. All Units start in their color's **Garrison**.

---

## 🎲 Movement Rules

- Units move in **straight lines only**: vertical, horizontal, or diagonal.
- A **die roll (1–6)** determines move distance.
- Units **cannot jump over** other units.

---

## ⚔️ Attack Mechanics

1. A unit can move onto an opponent’s square (and replace it) **if the die roll matches the exact distance**.
2. If there's **no defender in the Moat**, and the die roll allows reaching the General, it's a **successful "Hit"**.
3. The attacker **dies** after a successful Hit.
4. General **dies after 3 Hits**, attacker **wins**.

---

## 🛡️ Defense Mechanics

1. Defenders try to **occupy the Moat** (zones around the Keep).
2. If **any defender is in the Moat**, they **block** the General from being hit.
3. In such a block, **both the attacker and chosen defender die**.
4. If attacker rolls exact distance to a defender in Moat, they can remove it without damaging the General.

---

## 👑 General’s Win Conditions

- If fewer attacker units remain than remaining Hits required, **defense wins**.
- If **no defenders** remain, the General must survive **6 attacker dice rolls** for a **draw**.
- Only 1 offensive move is allowed (see Special Moves).

---

## ✨ Special Moves

### 1. GARRISONING
- **Use once per game**
- On a die roll of **6**, move **1 unit** between garrisons to an **empty** spot.

### 2. OFFENSIVE STRIKE
- **Use once per game**
- If < 3 defenders on board, and you roll a **1**, the General may **kill 1 attacker in the Moat**.

### 3. STALEMATE BREAK
- If dice consistently roll **5 or 6** and no move is possible, re-roll to break the block.

---

## 📏 Game End Conditions

| Scenario                  | Outcome            |
|--------------------------|--------------------|
| General gets 3 Hits      | Attacker wins      |
| Attackers < remaining hits | Defender wins    |
| General survives 6 rolls | Draw (if no defenders remain) |

---

## 📸 Sample Layout

(Include a screenshot or drawing of board setup here)

---

## 📦 Future Plans

- Digital simulator in Python or Pygame
- Web-based interactive version
- AI opponent using minimax or MCTS
- Online multiplayer via WebRTC

---

## 🤝 Contributions

Pull requests welcome! If you’ve playtested, made your own variant, or want to help digitize it—drop in a PR or open an issue.

---

## ⚖️ License

MIT License — free to fork, clone, or rage-quit after losing your last defender.

---

## 🧠 Designed By

**Piyush Goel**  
A strategist, hacker, and board game enthusiast from MIET Meerut.

---

📖 [Read the Full Rulebook](./generals.pdf)

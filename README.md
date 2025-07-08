# Summer2025-RogueLike

# 🃏 Creature Clash: A Roguelike Deckbuilder

> **Tagline:** _"Forge your team. Shape your deck. Survive the planes."_

### 👥 Team
- Ethan Fang – Game Designer & Developer
- [Other team members...]

📅 **Last Updated:** July 8, 2025

---

## 📘 Revision History _(Optional)_

| Version | Date       | Description                  |
|---------|------------|------------------------------|
| 0.1     | 2025-07-08 | Initial draft of the GDD     |
| 0.2     | TBD        | Added battle system details  |

---

## 🎯 Game Overview

- **Purpose:**  
  Combine successful mechanics from *Slay the Spire*, *Across the Obelisk*, and *Balatro* into a fast-paced roguelite deckbuilder with creature combat.

- **Intended Use:**  
  Standalone indie game release; first major title.

- **Justification:**  
  Builds on proven deckbuilding systems to attract fans of strategic roguelikes.

- **Target Audience:**  
  Players who enjoy roguelikes, card battlers, or games like *Pokémon TCG*, *Magic: The Gathering*, or *Slay the Spire*.

- **Genres:**  
  Roguelike, Deckbuilder

---

## 🕹️ Gameplay

### 🎯 Objectives
Defeat the final boss on the 4th plane using a custom-built deck, summoned creatures, and synergistic relics.

### 📈 Game Progression & Flow

Each **plane** features:
- A branching, tiered map of nodes
- Encounters like:
  - ⚔️ Battles
  - 🛒 Shops
  - 🎲 Random events
  - 🛌 Rest sites
- Players start at the bottom and progress upward toward the boss
- Decisions affect deck growth, economy, and creature synergy

**After each boss fight:**
- Players keep cards, gold, relics, and creatures
- Next plane increases in difficulty and complexity

---

## ⚙️ Mechanics

### 📏 Rules
- **Explicit:**
  - Energy cost for cards
  - Max hand size
  - Turn limits
  - 5-creature field limit
- **Implicit:**
  - Synergy rewards
  - Deck size tradeoffs
  - Creature slot management

### 🌍 Game World
- **Physics:** Not applicable
- **Economy:**
  - Gold is earned from battles
  - Used in shops to buy/remove cards or recruit creatures

### 🎮 Character Actions
- **Movement:**  
  Node-to-node map traversal

- **Combat:**
  - Turn-based
  - Max 5 creatures per side
  - When a creature dies, it deals **Death Damage** to its owner

- **Inventory:**
  - Card deck
  - Relics
  - Gold
  - Creature roster

### 🖥️ Screen Flow
`Map → Encounter → Battle → Reward → Map`

### 🔧 Game Options
- Difficulty
- Sound
- UI scaling

### 🔁 Replayability / Saving
- Procedural runs
- Meta-progression between runs
- Saves between maps or encounters

### 🥚 Cheats / Easter Eggs _(Optional)_
- TBD

---

## 📜 Story and Narrative _(Optional)_

### 🌌 Backstory
Summoners navigate four elemental planes, each ruled by ancient guardians. Creatures are manifestations of forgotten magic, bound to battle for their masters.

### 🧭 Plot Structure
- **Act 1: Initiation** – Enter the first plane, discover summoning magic
- **Act 2: Conflict** – Face stronger enemies, choose between power and principle
- **Act 3: Climax** – Confront the final boss, resolve the fate of the planes

### 🗨️ Narrative Delivery
- Event node text
- Dialogue snippets
- Card flavor descriptions

---

## 🚧 MVP Features In Progress
- [x] Core battle system (Player vs AI)
- [ ] Card play and creature spawning
- [ ] Basic relic and energy system
- [ ] Simple UI for hand, board, and turn order
- [ ] Win condition and turn management

---

### 📂 File Structure (WIP)

```plaintext
Assets/
├── Scripts/
│   ├── Core/
│   ├── Cards/
│   ├── Combat/
│   ├── UI/
├── Prefabs/
├── ScriptableObjects/
├── Scenes/
├── Art/
├── Audio/


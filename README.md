# 🎮 Final Fantasy Java Game

## 🧾 Overview

This repository contains a **2D RPG game** inspired by classic *Final Fantasy* titles, developed in **Java** using **AWT/Swing** for graphics. The project features a **tile-based world**, **interactive NPCs**, **inventory and trading systems**, and a **turn-based combat system**.

---

## ✨ Features

- 🗺️ **Tile-based map navigation**
- 🧍 **Player and NPC entities** with dialogue and interaction
- 🎒 **Inventory system** with stackable items, equipment, and consumables
- 🛒 **Trading system** with NPC shops
- ⚔️ **Turn-based combat mechanics**
- 💬 **Dialogue system** with typewriter effect
- 🔁 **Game states**: Title, Play, Pause, Dialogue, Character, Trade, Map, Game Over, End Game
- 🎵 **Sound and music support**
- 🧪 **Debug and God mode for development**

---

## 🛠️ Getting Started

### ✅ Prerequisites

- Java **17** or higher
- **IntelliJ IDEA** (recommended) or any Java IDE

### 📥 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/nt-thuyr/Final-Fantasy.git
   ```

2. **Open the project** in IntelliJ IDEA.

3. **Build the project** — no external dependencies are required.

---

### ▶️ Running the Game

- Run the `main.GamePanel` class.
- The game window will open — use your **keyboard** to control the player.

---

## 🎮 Controls

| Key         | Action                           |
|-------------|----------------------------------|
| **W/A/S/D** | Move player / Navigate menus     |
| **ENTER**   | Interact / Confirm               |
| **C**       | Open/close character screen      |
| **P**       | Pause/resume game                |
| **M**       | Open/close map                   |
| **SPACE**   | Use equipped item                |
| **ESC**     | Back / Cancel                    |

---

## 🗂️ Project Structure

```
src/
├── main/           # Game logic, UI, input handling
├── entity/         # Player, NPC, and character classes
├── item/           # Items and inventory logic
├── object/         # World objects (doors, chests, etc.)
├── tile/           # Tile and map management
└── sound/          # Sound and music management
```

---

## 📌 Key Classes

| Class         | Description                                     |
|---------------|-------------------------------------------------|
| `GamePanel`   | Main game loop and state management             |
| `KeyHandler`  | Keyboard input processing                       |
| `UI`          | Rendering of UI elements and dialogue           |
| `Player`      | Player entity logic and inventory               |
| `Item`        | Base class for items and item logic             |
| `NPC`         | Non-player character logic                      |

---

## 🧰 Troubleshooting

| Issue                             | Solution                                                                 |
|----------------------------------|--------------------------------------------------------------------------|
| `NullPointerException` in inventory | Ensure item objects are not null before accessing their properties       |
| `IndexOutOfBoundsException`      | Always check list size before accessing by index                         |
| Dialogue not updating            | Reset dialogue state when triggering new dialogue sequences              |

---

## 🤝 Contributing

Pull requests are welcome!  
Please follow standard Java coding conventions and include meaningful documentation/comments.

---

## 📄 License

This project is intended for **educational purposes**.  
See the `LICENSE` file for details.

---

## 👤 Credits

Developed by **nt-thuyr**.  
Inspired by classic JRPG titles like **Final Fantasy**.

---

📬 **For questions or issues**, please open an issue in this repository.

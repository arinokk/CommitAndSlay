# Jupyter Notebook — 1-Page Team Cheat Sheet

## 1. Core Concepts
* **Cell:** A block for either executable **Code** or formatted **Markdown** text.
* **Kernel:** The computational engine that runs your code and keeps variables in memory.

---

## 2. Two Modes (Important!)
* **Edit Mode (`Enter`):** Green/blue border — you are typing *inside* a cell.
* **Command Mode (`Esc`):** Grey border — you are managing cells *as blocks*.

---

## 3. Essential Keyboard Shortcuts

### Running Cells (Works in both modes)
| Shortcut | Action |
| :--- | :--- |
| `Shift + Enter` | Run current cell and jump to the next one |
| `Ctrl + Enter` | Run current cell and stay on it |
| `Alt + Enter` | Run current cell and insert a new one below |

### Command Mode Shortcuts (Press `Esc` first)
| Shortcut | Action |
| :--- | :--- |
| `A` | Insert new cell **Above** |
| `B` | Insert new cell **Below** |
| `M` | Convert cell to **Markdown** (text/headings) |
| `Y` | Convert cell to **Code** |
| `D`, `D` | **Delete** selected cell (press `D` twice) |
| `Z` | Undo cell deletion |

---

## 4. Helpful Tricks & Magic Commands
* **`Tab`** — Autocomplete variable or function names.
* **`?object`** (e.g., `?print`) — Open built-in documentation panel.
* **`%time`** — Measure execution time of a single line.
* **`%%time`** — Measure execution time of the entire cell.
* **`!command`** (e.g., `!pip list`) — Run terminal commands directly inside a cell.

---

## 5. Golden Rule for Our Team
1. Use **Jupyter (`.ipynb`)** for testing ideas, exploring data, and sharing visual reports.
2. Always run **Kernel -> Restart & Run All** before sharing a notebook to ensure cells work in the right order.
3. Move final production logic into clean **`.py`** files.
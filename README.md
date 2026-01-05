# 🎮 Csworld.Ge - Open.mp Server

![Language](https://img.shields.io/badge/Language-Pawn-orange)
![Platform](https://img.shields.io/badge/Platform-Open.mp-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Welcome to the official repository for the **Csworld.Ge** game server. This project is built using [Open.mp](https://www.open.mp/) (Open Multiplayer), a modern multiplayer modification for Grand Theft Auto: San Andreas.

---

## 📂 Repository Structure

Here is a quick overview of the main folders and files:

* **`gamemodes/`** - Contains the main server gamemode (`.pwn` and `.amx` files).
* **`filterscripts/`** - Additional scripts running alongside the gamemode.
* **`qawno/`** - The compiler used to build the scripts.
* **`components/`** - Server components/plugins essential for functionality.
* **`npcmodes/`** - Recordings and data for NPCs.
* **`omp-server`** - The Linux executable binary to run the server.
* **`config.json`** - Main configuration file for server settings.

## 🚀 Getting Started

### Prerequisites
To run this server, you need:
* A Linux environment (Ubuntu/Debian recommended) or Windows.
* Required dependencies for Open.mp (libssl, etc.).

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Blizzard1337/openmp.git](https://github.com/Blizzard1337/openmp.git)
    cd openmp
    ```

2.  **Permissions (Linux):**
    Make sure the server binary is executable:
    ```bash
    chmod +x omp-server
    ```

3.  **Configuration:**
    Check `config.json` to ensure settings (ports, hostname) are correct.

4.  **Run the Server:**
    ```bash
    ./omp-server
    ```

## 🛠️ Development

We use **Pawn** as the primary scripting language.
To compile the gamemode, use the compiler located in the `qawno/` directory.

## 🔗 Links

* **Website:** [Csworld.ge](https://csworld.ge)
* **Open.mp:** [open.mp](https://www.open.mp)

---
*Created by Blizzard1337 for Csworld.Ge*

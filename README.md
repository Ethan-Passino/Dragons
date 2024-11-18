# 🐉 Dragons Main Project

Welcome to the **Dragons Main** project! This project is designed to manage various elements involving dragons, including bosses, achievements, and other related configurations.

## 🕹️ Quick Start

To start the game, simply execute the `Run.bat` file:
```bash
Run.bat
```
## Commands and Live Demo
![](https://i.imgur.com/d7QvWFy.gif)

## 🚀 Features

- 🏆 **Achievements System**: Handle dragon-related achievements with `Achievement.py`.
- 🐲 **Dragon Management**: Core logic for dragon entities is found in `Dragon.py`.
- 👑 **Boss Mechanics**: Comprehensive boss interaction and behavior are implemented in `Boss.py` and `BossMove.py`.
- 🛠️ **Configuration Tools**:
  - `Check Config Syntax.bat` – A script to verify configuration syntax.
  - `Fix Old Config.bat` – A utility for updating older configuration files.
  - `ConfigReader.py` – Parses and reads configuration data.
  - `Config Editor.bat` – Launch an editor for modifying project configurations.
- 💬 **Dialogue Handling**: The `Dialogue.py` script manages in-game conversations and story elements.
- 📂 **File Management**: `FileActions.py` handles file operations to ensure efficient data processing.

## 📂 Project Structure

Here's an overview of the main files:

```plaintext
Dragons-main/
├── Achievement.py          # Achievements management script
├── Boss.py                 # Main script for boss behaviors
├── BossMove.py             # Boss movement and attack logic
├── Check Config Syntax.bat # Batch file for syntax checking
├── Config Editor.bat       # Configuration editor
├── ConfigReader.py         # Configuration reader and parser
├── Dialogue.py             # Dialogue management system
├── Dragon.py               # Core dragon class and logic
├── FileActions.py          # File handling utilities
├── Fix Old Config.bat      # Utility to update old configurations

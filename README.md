# Ayu Dark Skin for Midnight Commander

![Screenshot From 2025-06-04 13-25-57](https://github.com/user-attachments/assets/cb6c0a03-4105-4b15-a9e7-00f1196aa30b)

This is a color theme for [Midnight Commander (mc)](https://midnight-commander.org/), based on the popular **Ayu Dark** theme used in modern code editors.

## Installation

1. Clone or download this repository:
   ```bash
   git clone https://github.com/egorkonovalov/ayu-dark-mc.git
   ```

2. Create the skins directory if it doesn't exist:
   ```bash
   mkdir -p ~/.local/share/mc/skins
   ```

3. Copy the skin file:
    ```bash
    cp ayu-dark-mc/ayu-dark.ini ~/.local/share/mc/skins/
    ```
4. Launch Midnight Commander and activate the skin:

        Press F9 → Options → Appearance

        Choose ayu-dark from the skin list

        Save your settings

5. Or set it directly in your config file:
   ```bash
   echo "skin=ayu-dark" >> ~/.config/mc/ini
   ```

# Kitty Terminal Setup

## Fonts
**Font:** FiraCode Nerd Font Mono

## Theme
**Theme:** Mocha

## Installing the Catppuccin Theme

1. **Clone the Catppuccin Kitty theme:**
   ```bash
   git clone https://github.com/catppuccin/kitty.git ~/.config/kitty/catppuccin
   ```

2. **Navigate to the Catppuccin Kitty directory:**
   ```bash
   cd ~/.config/kitty/catppuccin
   ```

3. **Copy your chosen theme:**
   ```bash
   cp mocha.conf ~/.config/kitty/
   ```

4. **Update the Kitty configuration file:**
   Open the configuration file with your editor:
   ```bash
   vim ~/.config/kitty/kitty.conf
   ```
   Add the following line:
   ```
   include ./catppuccin-mocha.conf
   ```

5. **Restart the Kitty terminal** to apply the changes.

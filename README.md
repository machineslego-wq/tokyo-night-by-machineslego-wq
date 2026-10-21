# Tokyo Night Flat Theme for Obsidian

**English** | [Русский](./README.ru.md)

A strict, flat, and vibrant theme for Obsidian inspired by the **Tokyo Night** color palette. 

This theme is a logical continuation of my desktop environment setup. If you want your notes to look exactly like your terminal, window manager, and panel, this theme is for you.

![Screenshot 1](screenshots/screenshot1.png)
![Screenshot 2](screenshots/screenshot2.png)

## ✨ Features

- **Flat Design:** No distracting shadows or rounded corners. Strict, clean, and minimal.
- **Vibrant Accents:** Highly readable text highlights (`==`), distinct typography for bold, italic, and bold-italic.
- **Smart Callouts:** Fully styled and adapted for both desktop and mobile devices. Custom tags are supported.
- **Edit = Read:** The Live Preview mode is carefully tuned to look almost identical to the Reading mode.
- **Dual Mode:** Fully supports both Dark and Light (Day) Obsidian themes.

## 📦 Installation

### Option 1: Manual Installation (Linux & Windows)

This is the most reliable method if you want to install the theme directly from the source.

**Linux:**
1. Download the `theme.css` and `manifest.json` files from this repository.
2. Open your terminal and navigate to your Obsidian vault's themes folder:
   ```bash
   cd /path/to/your/vault/.obsidian/themes/
   ```
   *If the `themes` folder does not exist, create it: `mkdir -p .obsidian/themes/`*
3. Create a folder for the theme (e.g., `Tokyo Night Flat`) and copy the files into it:
   ```bash
   mkdir "Tokyo Night Flat"
   cp ~/Downloads/theme.css ~/Downloads/manifest.json "Tokyo Night Flat/"
   ```
4. Restart Obsidian, go to **Settings → Appearance → Themes**, and select **Tokyo Night Flat**.

**Windows:**
1. Download the `theme.css` and `manifest.json` files.
2. Open File Explorer and navigate to your vault folder.
3. Go into the `.obsidian` folder, then into the `themes` folder. (If `themes` doesn't exist, create it).
4. Create a new folder named `Tokyo Night Flat` and place both files inside.
5. Restart Obsidian, go to **Settings → Appearance → Themes**, and select **Tokyo Night Flat**.

### Option 2: Using BRAT (Auto-updates from GitHub)

[BRAT](https://github.com/TfTHacker/obsidian42-brat) (Beta Reviewers Auto-update Tester) is a plugin that lets you install and automatically update themes directly from a GitHub repository.

1. Install and enable the **BRAT** plugin from **Settings → Community plugins**.
2. Open **Settings → BRAT → Beta Themes List**.
3. Click **Add Beta Theme** and enter the repository URL:
   ```
   https://github.com/machineslego-wq/tokyo-night-by-machineslego-wq
   ```
4. The theme will be installed. Go to **Settings → Appearance → Themes** and select **Tokyo Night Flat**.

### Option 3: From GitHub Releases (ZIP)

If you prefer to download a packaged release:

1. Go to the [Releases](https://github.com/machineslego-wq/tokyo-night-by-machineslego-wq/releases) page.
2. Download the latest `.zip` file (e.g., `tokyo-night-flat-v1.0.0.zip`).
3. Extract the archive into your vault's `.obsidian/themes/` directory.
   *Ensure the final path looks like: `<vault>/.obsidian/themes/Tokyo Night Flat/`*
4. Restart Obsidian, go to **Settings → Appearance → Themes**, and select **Tokyo Night Flat**.

## 🔄 Updating

- **Manual Installation:** Download the latest `theme.css` and `manifest.json` from the repository and replace the existing files in your `.obsidian/themes/Tokyo Night Flat/` folder. Restart Obsidian or use the command palette (`Ctrl+P`) → **Reload app without saving**.
- **BRAT:** BRAT checks for updates automatically. You can also manually trigger a check in **Settings → BRAT**.
- **GitHub Releases:** Download the new `.zip` from the Releases page and extract it over the existing folder, replacing the old files.

## 🔗 Related

This theme is designed to perfectly match my minimalist BSPWM desktop setup. 
Check out the dotfiles here: **[BSPWM-machineslego](https://github.com/machineslego-wq/BSPWM-machineslego)**

## 📄 License

MIT
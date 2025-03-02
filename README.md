<div align="center">
  <img src="https://github.com/sxyazi/yazi/blob/main/assets/logo.png?raw=true" alt="Yazi logo" width="20%">
</div>

<h3 align="center">
	Aurora Theme Flavor for <a href="https://github.com/sxyazi/yazi">Yazi</a>
</h3>

## 👀 Preview


| Aurora Dawn (Light) | Aurora Storm (Dark) |
|---------------------|---------------------|
| <img src="https://raw.githubusercontent.com/kshawkat/yazi-themes/refs/heads/main/aurora-dawn.yazi/preview.png" width="350" /> | <img src="https://raw.githubusercontent.com/kshawkat/yazi-themes/refs/heads/main/aurora-storm.yazi/preview.png" width="350" /> |
| <img src="https://raw.githubusercontent.com/kshawkat/yazi-themes/refs/heads/main/aurora-dawn-arrows.yazi/preview.png" width="350" /> | <img src="https://raw.githubusercontent.com/kshawkat/yazi-themes/refs/heads/main/aurora-storm-arrows.yazi/preview.png" width="350" /> |


## ✨ Features

### Light

- **Soft & Eye-Friendly:** Uses warm, creamy off-whites (`#faf5ef`, `#f0e8e0`) to reduce harsh glare often found in pure-white light themes.
- **Nature-Inspired Palette:** Carefully chosen accent colors including ocean blues, forest greens, and sunrise roses/ambers.
- **High Readability:** Deep charcoal foregrounds (`#3a3530`) ensure text is always crisp and easy to read.
- **Distinctive UI Elements:** Clear visual hierarchy for active tabs, selected files, and the status bar.
- **Custom Filetype & Icon Colors:** Beautifully color-coded icons and MIME types to help you visually parse your directories at a glance.

### Dark

- **Deep Twilight Backgrounds:** Uses a rich, cool-toned dark base (`#161920`, `#1a1b2c`) that is easy on the eyes for late-night coding sessions.
- **Aurora-Inspired Accents:** Vibrant but soothing highlight colors including glowing teals, soft roses, and luminous ambers.
- **Crisp Readability:** Soft ice-blue foreground text (`#c8d0ea`) ensures excellent contrast without the harshness of pure white.
- **Powerline Ready:** Beautifully styled status bar and tabs with built-in powerline separator support.
- **Custom Filetype & Icon Colors:** Intuitive color-coding for different file types and directories to help you navigate at a glance.

## 🎨 Installation

### Manual install

```bash
# Linux/macOS
git clone https://github.com/kshakwat/yazi-themes.git 
cd yazi-themes
cp -r ./{aurora-dawn.yazi,aurora-storm.yazi,aurora-dawn-arrows.yazi,aurora-storm-arrows.yazi} ~/.config/yazi/flavors/
```
# Windows (use one of the following methods)

*(Execute the command in the CMD window)*

```CMD
git clone https://github.com/kshakwat/yazi-themes.git 
cd yazi-themes
for %i in (aurora-dawn.yazi aurora-storm.yazi aurora-dawn-arrows.yazi aurora-storm-arrows.yazi) do xcopy "%i" "%AppData%\yazi\config\flavors\%i\" /E /I /H /C
```

*(Execute the command in the PoweShell terminal)*

```powershell
git clone https://github.com/kshakwat/yazi-themes.git 
cd yazi-themes
Copy-Item -Path "aurora-dawn.yazi", "aurora-storm.yazi", "aurora-dawn-arrows.yazi", "aurora-storm-arrows.yazi" -Destination "$env:AppData\yazi\config\flavors\" -Recurse -Force
```

## ⚙️ Usage

Add the these lines to your `theme.toml` configuration file to use it:

```toml
[flavor]
use = "aurora-storm"
#use = "aurora-storm-arrows"
# For Yazi 0.4 and above
# switch between light and dark automatically based on terminal settings
dark = "aurora-storm"
light = "aurora-dawn"
#dark = "aurora-storm-arrows"
#light = "aurora-dawn-arrows"
```

## 🤝 Contributing

Pull requests and suggestions are welcome! If you find a UI element that lacks styling or have ideas to improve the color balance, feel free to open an issue.

## 📜 License

The flavor is MIT-licensed, and the included tmTheme is also MIT-licensed.

Check the [LICENSE](LICENSE) and [LICENSE-tmtheme](LICENSE-tmtheme) file for more details.

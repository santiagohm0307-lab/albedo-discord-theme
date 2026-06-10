# 🎨 Albedo God Theme

A sophisticated BetterDiscord theme inspired by the Albedo/Nazarick aesthetic with deep purples, glass-morphism effects, and elegant transparency.

## ✨ Features

- **Glassmorphism Design**: Premium frosted glass panels with subtle blur effects
- **Neon Accents**: Deep purple and pink neon highlights
- **Transparent Layers**: Wallpaper visible through UI with adjustable opacity
- **ClearVision Compatible**: Based on ClearVision-v7 transparency engine
- **Fully Customizable**: Easy-to-modify CSS variables in `:root`
- **Dark Theme**: Elegant moody aesthetic optimized for dark mode

## 📦 Installation

### For BetterDiscord Users:

1. **Copy the theme files:**
   - Copy `Albedo.theme.css` to your BetterDiscord themes folder
   - Copy the entire `assets/` folder alongside the CSS file

2. **Activate the theme:**
   - Open Discord
   - Go to **User Settings** → **BetterDiscord** → **Themes**
   - Find and enable **Albedo God Theme**

3. **Reload if needed:**
   - Press `Ctrl+R` to reload Discord if the background doesn't appear

### Theme File Location:
- **Windows**: `%APPDATA%\BetterDiscord\themes`
- **macOS**: `~/Library/Application Support/BetterDiscord/themes`
- **Linux**: `~/.config/BetterDiscord/themes`

## 🎨 Customization

Edit `Albedo.theme.css` and modify the CSS variables in the `:root` section:

```css
:root {
  /* Main Colors */
  --main-color: #8d25ff;           /* Primary purple */
  --hover-color: #b12dff;          /* Hover state */
  --focus-color: #cda5ff;          /* Focus highlight */
  
  /* Custom Variables */
  --albedo-black: #03020a;
  --albedo-blur: 10px;
  /* ... modify as needed */
}
```

### Popular Customizations:

- **Change main color**: Modify `--main-color` and related color variables
- **Adjust blur effect**: Change `--albedo-blur` value (in pixels)
- **Modify transparency**: Adjust `rgba()` opacity values
- **Change background**: Replace `assets/albedo-bg.png` with your image

## 📋 File Structure

```
.
├── Albedo.theme.css          # Main theme file (use this)
├── README.md                 # This file
├── assets/
│   ├── albedo-bg.png         # Background image
│   └── reference-mockup.png   # Style reference
└── .gitignore               # Git configuration
```

## 🔧 Requirements

- **BetterDiscord** plugin for Discord
- Discord (any version supported by BetterDiscord)
- Modern browser/Electron version (for CSS features)

## 📝 Notes

- The theme uses relative paths for assets, so keep `Albedo.theme.css` and the `assets/` folder together
- For best results, use with Discord's dark theme
- Some Discord updates may require CSS class adjustments
- The ClearVision library is imported via CDN for transparency effects

## 🐛 Troubleshooting

**Theme not appearing?**
- Ensure file ends with `.theme.css`
- Check that `assets/` folder is in the same directory as the CSS file
- Restart Discord completely (not just reload)
- Verify BetterDiscord is properly installed

**Background not showing?**
- Press `Ctrl+R` in Discord to reload
- Check that `assets/albedo-bg.png` exists
- Verify relative paths are correct in CSS

**Colors not updating?**
- Clear BetterDiscord cache
- Restart Discord
- Check for conflicting CSS selectors in other installed plugins

## 📜 License

This project is provided as-is for personal use with BetterDiscord.

## 🙏 Credits

- Inspired by ClearVision theme architecture
- Based on Albedo/Nazarick aesthetic design
- Built for the BetterDiscord community

## 💬 Support

For issues or questions:
1. Check the troubleshooting section above
2. Review the CSS variables in `:root`
3. Ensure all files are in the correct locations
4. Consider clearing Discord cache and restarting

---

**Version:** 3.5.0  
**Last Updated:** 2026

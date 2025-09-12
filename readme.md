# Zed Red - Dark Demonic Theme

A sinister dark theme for Zed editor designed for night-time coding sessions. Features deep blacks and blood reds for an edgy, demonic aesthetic that's easy on the eyes during long coding sessions.

## 🔥 Theme Preview

This theme embraces darkness with:
- **Pure black** backgrounds for minimal eye strain
- **Crimson red** text and accents for that demonic edge
- **Deep red** highlights and UI elements
- **Blood red** syntax highlighting for keywords and important elements
- **Dark red gradients** throughout the interface

Perfect for late-night coding sessions when you want something darker and more atmospheric than typical themes.

## 📦 Installation

### Method 1: Direct Download
1. **Download the theme file:**
   ```bash
   curl -O https://raw.githubusercontent.com/brad/zed-red/main/themes/zed-red.json
   ```

2. **Create Zed themes directory (if it doesn't exist):**
   ```bash
   mkdir -p ~/.config/zed/themes
   ```

3. **Move the theme file:**
   ```bash
   mv zed-red.json ~/.config/zed/themes/
   ```

4. **Apply the theme:**
   - Open Zed
   - Press `Cmd+,` (macOS) or `Ctrl+,` (Linux/Windows) 
   - Search for "theme"
   - Select "Zed Red - Demonic"

### Method 2: Clone Repository
1. **Clone this repository:**
   ```bash
   git clone https://github.com/brad/zed-red.git
   cd zed-red
   ```

2. **Copy themes to Zed:**
   ```bash
   cp -r themes ~/.config/zed/
   ```

3. **Apply the theme in Zed settings**

### Method 3: Manual Installation
1. **Download or copy** the contents of `themes/zed-red.json`
2. **Navigate to your Zed config directory:**
   - **macOS:** `~/.config/zed/`
   - **Linux:** `~/.config/zed/`
   - **Windows:** `%APPDATA%\Zed\`
3. **Create a `themes` folder** if it doesn't exist
4. **Save the file as** `themes/zed-red.json`
5. **Restart Zed and select the theme**

### Method 4: As Zed Extension (Coming Soon)
This theme will be available in the Zed extension marketplace.

## 🔧 Troubleshooting Installation

### Theme Not Appearing?
1. **Verify file location:** Make sure `zed-red.json` is in `~/.config/zed/themes/`
2. **Check file permissions:** 
   ```bash
   chmod 644 ~/.config/zed/themes/zed-red.json
   ```
3. **Restart Zed completely** (not just reload)
4. **Clear Zed cache:**
   ```bash
   rm -rf ~/.config/zed/logs
   rm -rf ~/.config/zed/db
   ```

### Different Operating Systems
- **macOS:** `~/.config/zed/themes/`
- **Linux:** `~/.config/zed/themes/`
- **Windows:** `%APPDATA%\Zed\themes\`
- **Windows (PowerShell):** `$env:APPDATA\Zed\themes\`

### Quick One-Liner Installation
```bash
# For Unix-like systems (macOS/Linux)
mkdir -p ~/.config/zed/themes && curl -o ~/.config/zed/themes/zed-red.json https://raw.githubusercontent.com/brad/zed-red/main/themes/zed-red.json
```

### Verify Installation
```bash
# Check if theme file exists
ls ~/.config/zed/themes/zed-red.json

# View theme contents (optional)
cat ~/.config/zed/themes/zed-red.json | head -20
```

## 🎨 Color Palette

The theme uses these carefully chosen colors for the demonic aesthetic:

- **Background**: `#000000` (Pure black for minimal eye strain)
- **Primary Text**: `#dc143c` (Crimson red)
- **Accent**: `#ff4444` (Bright red highlights)
- **Keywords**: `#ff0000` (Blood red for important syntax)
- **Functions**: `#ff4444` (Bright red for function definitions)
- **Strings**: `#b22222` (Fire brick red)
- **Comments**: `#5a0000` (Dark red, subtle but visible)
- **Numbers**: `#ff4444` (Bright red for constants)

## 🛠️ Customization

To customize the theme:
1. Edit `themes/zed-red.json`
2. Modify colors in the `style` and `syntax` sections
3. Save and the theme will reload automatically

## 🌙 Perfect For

- Late-night coding sessions
- Developers who prefer darker, more atmospheric themes
- Anyone wanting to reduce eye strain with pure black backgrounds
- Coders who like an edgy, distinctive look

## 🐛 Issues & Feedback

If you encounter any issues or have suggestions:
- Create an issue in this repository
- The theme follows Zed's official theme schema

## 📝 License

MIT License - Feel free to fork and customize for your own demonic coding needs!

---

*Code in darkness, debug with fire* 🔥
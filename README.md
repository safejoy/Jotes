# Joys Notes

![notes with joy](https://github.com/safejoy/Joys-Notes/blob/main/Images/joysnotes.png)

Taking notes in the browser has never been eaiser.

> A beautiful, privacy-focused note-taking app that lives entirely in your browser

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/demo-live-brightgreen.svg)](https://safejoy.github.io/Jotes)
[![Responsive](https://img.shields.io/badge/responsive-mobile%20%26%20desktop-blue.svg)](#features)


## Features

### **Privacy First**
- **100% Local Storage** - Your notes never leave your device
- **No Account Required** - Start writing immediately
- **Offline Ready** - Works without an internet connection

### **Beautiful Design**
- **Dark & Light Modes** - Easy on your eyes, any time of day
- **Pastel Color Themes** - Organize with beautiful note colors
- **Responsive Design** - Perfect on mobile, tablet, and desktop
- **Modern Interface** - Clean, distraction-free writing experience

### **Rich Text Editing**
- **TinyMCE Integration** - Professional WYSIWYG editor
- **Auto-Save** - Never lose your work
- **Format Text** - Bold, italic, lists, and more
- **Live Search** - Instantly find notes by title or content

### **Cross-Device Ready**
- **Export/Import** - Backup and sync your notes via JSON files
- **Mobile Optimized** - Touch-friendly interface
- **Keyboard Shortcuts** - Power user friendly

## Quick Start

### Option 1: Use Online (Recommended)
Visit **[JoyNotes Live Demo](https://safejoy.github.io/Jotes)** - no installation needed!

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/safejoy/Jotes.git
cd Joys-Notes

# Open with any web server
python -m http.server 8000
# OR
npx serve .

# Visit http://localhost:8000
```

### Option 3: Download & Use
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start taking notes!

## How to Use

### Creating Your First Note
1. **Click the `+` button** or press `Ctrl+N`
2. **Add a title** in the top field
3. **Write your content** using the rich text editor
4. **Pick a color theme** from the dropdown
5. Your note auto-saves as you type! 

### Organizing Notes
- **Color Code**: Use pastel themes (Rose, Mint, Lilac, Vanilla, Sky)
- **Search**: Type in the search box to filter notes instantly
- **Sort**: Notes are automatically sorted by last modified

### Backup & Sync
- **Export**: Click "Export" to download a JSON backup
- **Import**: Click "Import" to restore from a backup file
- **Cross-Device**: Use export/import to sync between devices

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+N` | Create new note |
| `Ctrl+S` | Save current note |
| `Escape` | Clear search |

## Technical Details

### Built With
- **Pure HTML/CSS/JavaScript** - No frameworks, fast loading
- **TinyMCE** - Professional rich text editing
- **localStorage** - Browser-based data persistence
- **CSS Grid & Flexbox** - Modern responsive layout

### Browser Support
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

### Storage
- Notes are stored in your browser's `localStorage`
- Typical storage limit: 5-10MB (thousands of notes)
- Data persists until you clear browser data

## Customization

Joy-Notes is designed to be easily customizable:

### Color Themes
Edit the CSS custom properties in the `:root` section:
```css
:root {
  --brand: #8a7cf0;     /* Primary brand color */
  --accent: #77d6c3;    /* Secondary accent */
  /* ... more colors */
}
```

### Note Colors
Add new note color options by extending the color system:
```css
--note-newcolor-light: #your-light-color;
--note-newcolor-dark: #your-dark-color;
```

## Contributing

We love contributions! Here's how you can help:

### Bug Reports
Found a bug? [Open an issue](https://github.com/safejoy/Jotes/issues/new) with:
- Browser and version
- Steps to reproduce
- Expected vs actual behavior

### Feature Requests
Have an idea? [Start a discussion](https://github.com/safejoy/Jotes/discussions) or open an issue!

### Pull Requests
1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

### Development Setup
```bash
# Fork and clone your fork
git clone https://github.com/YOUR-USERNAME/Jotes.git
cd Joys-Notes

# Create a branch for your feature
git checkout -b feature/your-feature

# Make changes and test locally
python -m http.server 8000

# Commit and push
git add .
git commit -m "Your descriptive commit message"
git push origin feature/your-feature
```

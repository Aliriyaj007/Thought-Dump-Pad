# Thought Dump Pad ✨

<div align="center">

![Thought Dump Pad Banner](https://img.shields.io/badge/Thought%20Dump%20Pad-Offline%20First%20Writing-blueviolet?style=for-the-badge)
![Version](https://img.shields.io/badge/version-2.0.0-success?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![Build](https://img.shields.io/badge/build-passing-success?style=for-the-badge)
![Size](https://img.shields.io/badge/size-67KB-lightgrey?style=for-the-badge)

**A zero-friction, offline-first writing space to quickly unload mental clutter**

[Live Demo](https://Aliriyaj007.github.io/Thought-Dump-Pad) • [Report Bug](https://github.com/Aliriyaj007/Thought-Dump-Pad/issues) • [Request Feature](https://github.com/Aliriyaj007/Thought-Dump-Pad/issues)

![Thought Dump Pad Screenshot](https://via.placeholder.com/800x450/4A90A4/FFFFFF?text=Thought+Dump+Pad+Preview)

</div>

## 🚀 Quick Start

**Option 1:** Clone and run locally
```bash
git clone https://github.com/Aliriyaj007/Thought-Dump-Pad.git
cd Thought-Dump-Pad
# Open index.html in your browser
```

**Option 2:** Use the live demo
- Visit: [https://Aliriyaj007.github.io/Thought-Dump-Pad](https://Aliriyaj007.github.io/Thought-Dump-Pad)
- Start typing immediately - no installation required!

**Option 3:** Download single file
- Download [index.html](https://raw.githubusercontent.com/Aliriyaj007/Thought-Dump-Pad/main/index.html)
- Open in any modern browser

## ✨ Features

### 🎯 Core Features

| Feature | Description | Status |
|---------|-------------|--------|
| **Offline-First** | Works completely offline, no internet required | ✅ |
| **Auto-Save** | Automatically saves as you type with visual feedback | ✅ |
| **Multiple Notes** | Create, rename, and manage multiple writing sessions | ✅ |
| **Rich Statistics** | Word count, character count, reading time, and more | ✅ |
| **Focus Mode** | Distraction-free writing environment | ✅ |
| **Themes** | 8 beautiful themes including dark mode | ✅ |
| **Import/Export** | Import from files/clipboard, export as TXT/MD/HTML | ✅ |
| **Find & Replace** | Advanced text search and replace functionality | ✅ |

### 🎨 Design Features

| Category | Features |
|----------|----------|
| **Themes** | Light, Dark, Sepia, Ocean, Forest, Lavender, Midnight, High Contrast |
| **Customization** | Adjustable font size, line height, font family |
| **Responsive** | Fully responsive design for all devices |
| **Accessibility** | Keyboard navigation, ARIA labels, screen reader friendly |
| **Animations** | Smooth transitions and visual feedback |

### ⚡ Performance Features

| Metric | Value | Description |
|--------|-------|-------------|
| **Load Time** | < 1s | Optimized for instant loading |
| **Storage** | LocalStorage | Unlimited notes within browser limits |
| **Size** | 67KB | Single HTML file, no dependencies |
| **Compatibility** | All modern browsers | Chrome, Firefox, Safari, Edge |

## 📋 Table of Contents

- [Features](#-features)
- [Installation](#-installation)
- [Usage Guide](#-usage-guide)
- [Keyboard Shortcuts](#-keyboard-shortcuts)
- [Themes](#-themes)
- [API Reference](#-api-reference)
- [Development](#-development)
- [Contributing](#-contributing)
- [FAQ](#-faq)
- [Author](#-author)
- [License](#-license)

## 🛠️ Installation

### Local Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Aliriyaj007/Thought-Dump-Pad.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd Thought-Dump-Pad
   ```

3. **Open in browser**
   - Double-click `index.html` or
   - Use a local server: `python3 -m http.server 8000`

### Browser Requirements

- Modern browser with JavaScript enabled
- LocalStorage support
- File API support (for import/export)
- Clipboard API support (optional)

## 📖 Usage Guide

### Getting Started

1. **Open the application** in your browser
2. **Start typing** in the main text area - everything auto-saves
3. **Create new notes** using the + button or Ctrl+N
4. **Switch between notes** using tabs at the top

### Advanced Features

#### 🎯 Focus Mode
- Click the Focus button or press F11
- All UI elements disappear except your text
- Press Escape to exit focus mode

#### 📊 Writing Goals
- Set daily word goals in Settings
- Track progress with the progress bar
- Visual indication when goal is reached

#### 🔍 Find & Replace
- Press Ctrl+F or click Find button
- Search through your text
- Replace single or all occurrences

#### 📁 Import/Export
- **Import**: From file or clipboard
- **Export**: As TXT, MD, or HTML
- **Backup**: Download complete backup

#### 🎨 Theme Customization
- Click theme buttons in header
- Themes persist across sessions
- Includes accessibility themes

## ⌨️ Keyboard Shortcuts

### Editing Shortcuts

| Shortcut | Action | Description |
|----------|--------|-------------|
| `Ctrl+S` | Save | Manually save current note |
| `Ctrl+Z` | Undo | Undo last action |
| `Ctrl+Y` | Redo | Redo last action |
| `Ctrl+F` | Find | Open find & replace |
| `Ctrl+N` | New Note | Create new note |
| `Ctrl+E` | Export | Open export menu |

### Navigation Shortcuts

| Shortcut | Action | Description |
|----------|--------|-------------|
| `F11` | Focus Mode | Toggle distraction-free mode |
| `Esc` | Exit Focus | Exit focus mode |
| `Ctrl+,` | Settings | Open settings modal |
| `Ctrl+/` | Shortcuts | Open shortcuts reference |

### Tab Management

| Shortcut | Action | Description |
|----------|--------|-------------|
| `Tab` | Next Tab | Navigate to next note tab |
| `Shift+Tab` | Previous Tab | Navigate to previous note tab |
| `Ctrl+W` | Close Tab | Close current note |
| `Ctrl+Shift+T` | Reopen | Reopen last closed note |

## 🎨 Themes

Thought Dump Pad comes with 8 carefully crafted themes:

| Theme | Description | Best For |
|-------|-------------|----------|
| **Light** | Clean, minimal white theme | Daytime writing |
| **Dark** | Easy-on-eyes dark theme | Nighttime writing |
| **Sepia** | Warm, book-like theme | Long writing sessions |
| **Ocean** | Cool blue theme | Creative writing |
| **Forest** | Green natural theme | Nature-inspired writing |
| **Lavender** | Purple soothing theme | Relaxed writing |
| **Midnight** | Deep dark blue theme | Late night sessions |
| **High Contrast** | Black & white theme | Accessibility |

## 📊 Statistics Tracking

The application tracks various writing metrics in real-time:

| Metric | How It's Calculated | Purpose |
|--------|---------------------|---------|
| **Word Count** | Spaces between words | Track progress |
| **Character Count** | All characters including spaces | Technical writing |
| **Sentence Count** | Periods, exclamation, question marks | Readability |
| **Paragraph Count** | Double line breaks | Structure analysis |
| **Reading Time** | 200 words per minute | Estimated reading time |
| **Session Timer** | Time since page load | Productivity tracking |

## 🔧 API Reference

### Storage API

The application uses LocalStorage with the following keys:

```javascript
// Available storage keys
thoughtDumpPad_notes      // All notes data
thoughtDumpPad_activeNote // Currently active note ID
thoughtDumpPad_theme      // Selected theme
thoughtDumpPad_settings   // User settings
```

### Note Structure

```javascript
{
  id: "timestamp_random", // Unique identifier
  title: "Note Title",    // User-defined title
  content: "Note content", // The actual text
  createdAt: 1640995200000, // Timestamp
  updatedAt: 1640995200000  // Last edit timestamp
}
```

### Settings Structure

```javascript
{
  fontSize: 18,      // Font size in pixels
  lineHeight: 1.8,   // Line height multiplier
  fontFamily: "serif", // Font family
  wordGoal: 500      // Daily word goal
}
```

## 💻 Development

### Code Architecture

The application follows a modular architecture:

- **Managers**: Independent modules for each feature
- **State Management**: Centralized state object
- **Event-driven**: DOM events with delegation
- **No Dependencies**: Pure HTML/CSS/JavaScript

### Building from Source

Since this is a single HTML file, no build process is required. However, for development:

1. **Code Organization**: All code is in the single `index.html` file
2. **CSS Structure**: Organized by component with CSS custom properties
3. **JavaScript**: IIFE pattern with strict mode
4. **Comments**: Extensive documentation throughout

### Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 60+ | ✅ Full Support |
| Firefox | 55+ | ✅ Full Support |
| Safari | 12+ | ✅ Full Support |
| Edge | 79+ | ✅ Full Support |
| Opera | 47+ | ✅ Full Support |

## 🚀 Usage

**Access the site** at `https://Aliriyaj007.github.io/Thought-Dump-Pad/`

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Ways to Contribute

1. **Report Bugs** - Open an issue with detailed bug report
2. **Suggest Features** - Propose new features or improvements
3. **Submit Pull Requests** - Implement fixes or features
4. **Improve Documentation** - Help improve this README or add guides
5. **Share Feedback** - Let us know how you use the app

### Development Workflow

1. **Fork** the repository
2. **Create a branch** for your feature
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Code Style Guidelines

- **HTML**: Semantic elements with ARIA labels
- **CSS**: BEM-like naming with CSS custom properties
- **JavaScript**: ES6+ with descriptive variable names
- **Comments**: JSDoc style for functions
- **Formatting**: Consistent indentation (2 spaces)

## ❓ FAQ

### General Questions

**Q: Is my data safe?**  
A: Yes! All data is stored locally in your browser. No data is sent to any server.

**Q: Can I use it offline?**  
A: Absolutely! The entire application works offline once loaded.

**Q: Is it free?**  
A: Yes, completely free and open source under MIT license.

**Q: Can I contribute?**  
A: Yes! Check the [Contributing](#contributing) section.

### Technical Questions

**Q: Where is my data stored?**  
A: In your browser's LocalStorage. You can export backups anytime.

**Q: What browsers are supported?**  
A: All modern browsers (Chrome, Firefox, Safari, Edge).

**Q: Can I sync between devices?**  
A: Not currently, but you can export/import backups manually.

**Q: Is there a mobile app?**  
A: No native app, but it works perfectly in mobile browsers.

### Feature Questions

**Q: Can I change the font?**  
A: Yes! In Settings, you can choose between Serif, Sans-Serif, and Monospace.

**Q: How do I set writing goals?**  
A: Go to Settings → Writing Goals and set your daily word goal.

**Q: Can I print my notes?**  
A: Yes! Use the Print button or Ctrl+P for a clean print layout.

**Q: Is there a word limit?**  
A: No hard limit, but performance depends on your browser's storage capacity.

## 👤 Author

**Riyajul Ali**

- GitHub: [@Aliriyaj007](https://github.com/Aliriyaj007)
- Portfolio: [Coming Soon](#)
- Email: Aliriyaj007@protonmail.com
- Linkedin: [@Aliriyaj007](https://linkedin.com/in/Aliriyaj007)
  
### Acknowledgments

- Icons from [Material Design Icons](https://materialdesignicons.com/)
- Color palettes inspired by [Tailwind CSS](https://tailwindcss.com/)
- Typography inspired by [Inter](https://rsms.me/inter/) and [Fira Code](https://github.com/tonsky/FiraCode)
- Design principles from [Refactoring UI](https://refactoringui.com/)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Ali Riyaj

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 🌟 Show Your Support

If you find this project useful, please consider:

1. ⭐ **Star the repository**
2. 🐛 **Report bugs or issues**
3. 💡 **Suggest new features**
4. 🔄 **Share with others**
5. ☕ **Buy me a coffee** (coming soon)

## 📞 Contact

For questions, suggestions, or just to say hi:

- **GitHub Issues**: [Create an issue](https://github.com/yourusername/thought-dump-pad/issues)
- **Email**: Aliriyaj007@protonmail.com
- **Linkedin**: [@Aliriyaj007](https://linkedin.com/in/Aliriyaj007)

---

<div align="center">

### Made with ❤️ by Aliriyaj007

_"Write without friction, think without limits"_

[⬆ Back to Top](#thought-dump-pad-)

</div>

# Visual Projects

**Project Planning and Task Dependencies - Visualize Your Projects**

A powerful yet simple web-based tool for project planning with Gantt charts and dependency graphs. Features CPM calculation, parallel tasks, decision points, and milestones.

![License: Non-Commercial](https://img.shields.io/badge/License-Non--Commercial-blue.svg)

## ✨ Features

- 📊 **Dual View**: Switch between interactive Graph and Gantt chart views
- 🔗 **Dependency Management**: Visual task dependencies with automatic scheduling
- ⚡ **Parallel Tasks**: Support for tasks that can start during dependency execution
- 📌 **Decision Points & Milestones**: Mark important project events
- 🎨 **Customizable Colors**: Color-code tasks for better organization
- 💾 **Auto-save**: Automatic browser-based project saving every 5 minutes
- 📤 **Export Options**: Export projects as JSON or save charts as PNG images
- 🌍 **Multi-language**: English and Swedish interface
- ⌨️ **Keyboard Shortcuts**: Efficient workflow with keyboard controls
- 📱 **Responsive**: Works on desktop and tablet devices

## 🚀 Getting Started

### Quick Start

1. **Download** the `visual-projects.html` file
2. **Open** it in your web browser (Chrome, Firefox, Edge, Safari)
3. **Start planning** - no installation or server required!

### Using the Tool

1. **Add Tasks**: Enter task name, duration, and dependencies in the left panel
2. **Set Dependencies**: Use the dropdown to select which tasks must complete first
3. **View Schedule**: Switch between Graph and Gantt views to visualize your timeline
4. **Export**: Save your project as JSON or export charts as PNG images

## 📖 Key Concepts

### Dependencies
- **Normal Dependencies**: Task B starts when Task A finishes
- **Parallel Tasks**: Task can start during another task's execution
- **Start Lock**: Manually override calculated start dates

### Special Markers
- **Decision Points**: Mark project decision milestones
- **Milestones**: Highlight important project events

### Auto-scheduling
The tool uses Critical Path Method (CPM) to automatically calculate:
- Early Start (ES) and Early Finish (EF)
- Late Start (LS) and Late Finish (LF)
- Task slack and critical path

## ⌨️ Keyboard Shortcuts

- `Ctrl+S` - Export project as JSON
- `+/-` - Zoom in/out
- `0` - Reset zoom
- `Esc` - Deselect tasks
- `Ctrl+Scroll` - Zoom (when hovering over canvas)
- `Shift+Drag` - Pan view

## 💾 Data Storage

- **Auto-save**: Projects are automatically saved to browser local storage every 5 minutes
- **Export**: Recommended to export regularly to JSON files as backup
- **Import**: Load previously exported JSON files

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No dependencies, frameworks, or build tools
- **Embedded Libraries**:
  - dagre (MIT) - Graph layout
  - lodash (MIT) - Utility functions
- **Browser Storage** - Uses localStorage for auto-save
- **Canvas API** - For graph and Gantt rendering

## 📋 Browser Compatibility

- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Opera 76+

## 🤝 Contributing

Contributions are welcome! This project is open for non-commercial use.

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development

The entire application is contained in a single HTML file for maximum portability. To modify:

1. Open `visual-projects.html` in your editor
2. Make your changes
3. Test by opening the file in a browser
4. Submit a pull request

## 📄 License

This project is licensed under a **Non-Commercial Use License**.

- ✅ Free for personal, educational, and non-profit use
- ✅ Modify and build upon the software
- ✅ Share your modifications under the same license
- ❌ Commercial use prohibited without permission

For commercial licensing inquiries, please contact via GitHub Issues.

See [LICENSE](LICENSE) file for full details.

## 🙏 Acknowledgments

- **dagre** - Graph layout algorithm
- **lodash** - JavaScript utilities
- Inspired by project management tools and the need for a simple, offline-capable planning tool

## 📞 Contact

- GitHub: [@Pelsius](https://github.com/Pelsius)
- Project Link: [https://github.com/Pelsius/visual-projects](https://github.com/Pelsius/visual-projects)

## 🗺️ Roadmap

Potential future features:
- [ ] Export to PDF
- [ ] Resource allocation
- [ ] Multi-project management
- [ ] Collaboration features
- [ ] Mobile app version

---

**Made with ❤️ for project managers, students, and anyone who needs to visualize task dependencies**

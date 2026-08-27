# UiPath Timeline 2026

An interactive timeline visualization for configuring and planning UiPath automation initiatives in 2026.

## 🚀 Quick Start

### Access Online
**[🌐 View the Timeline](https://sergekr.github.io/uipath-timeline/)** - Live version hosted on GitHub Pages

### Access Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/sergekr/uipath-timeline.git
   cd uipath-timeline
   ```

2. Open in your browser:
   - **Option A**: Double-click `index.html` to open directly
   - **Option B**: Use a local web server
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Python 2
     python -m SimpleHTTPServer 8000
     
     # Node.js (if installed)
     http-server
     ```
   Then visit `http://localhost:8000` in your browser

## 📋 Features

- **Interactive Timeline**: View UiPath implementation phases across 5 time periods (July → Dec 2026+)
- **Drag & Drop**: Reorganize timeline cards to reorder initiatives
- **Details Panel**: Click any card to see extended information
- **Architecture Flow**: Visualize connections between system components with animated flows:
  - Test Manager
  - Orchestrator
  - Jira
  - Confluence
  - Studio
  - SAP

## 📅 Timeline Phases

| Phase | Period | Focus |
|-------|--------|-------|
| 1 | July 2026 | Core Setup - Platform setup & SaaS configuration |
| 2 | August 2026 | Jira Integration - Tracking & defect management |
| 3 | September 2026 | Automation - Robot deployment & Studio rollout |
| 4 | Oct–Nov 2026 | SAP SuccessFactors - Cloud integration & automation |
| 5 | Dec 2026+ | SAP S/4HANA - Enterprise-scale automation |

## 🎨 How to Use

1. **View Timeline**: Scroll through the timeline cards to see all phases
2. **Get Details**: Click on any card to display full details in the panel below
3. **Reorder Cards**: Drag and drop cards to reorganize the timeline
4. **Architecture Flow**: Click on architecture nodes to visualize connections between systems

## 🔧 Technologies

- **HTML5** - Semantic markup
- **CSS3** - Styling & animations
- **Vanilla JavaScript** - Interactive functionality (no frameworks required)
- **Canvas API** - Animated flow visualization

## 📝 File Structure

```
uipath-timeline/
├── index.html    # Complete interactive timeline application
└── README.md     # This file
```

## 💡 Customization

To modify the timeline data, edit the `data` array in `index.html`:

```javascript
let data = [
  {id:1, title:"Your Phase", details:"Phase description"},
  // Add more phases...
];
```

To change the time periods, modify the `base` array:

```javascript
const base = ["July","August","September","Oct–Nov","Dec"];
```

## 🌐 Deployment

The application is automatically deployed to GitHub Pages. Any changes to the `main` branch will be reflected at:
```
https://sergekr.github.io/uipath-timeline/
```

## 📄 License

Open for personal and business use.

## 🤝 Contributing

Feel free to fork, modify, and enhance this timeline for your UiPath initiatives.

---

**Built with ❤️ for UiPath automation planning**

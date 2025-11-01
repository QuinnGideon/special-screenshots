# Special Screenshots

## MVP Scope Documentation

A modern, feature-rich screenshot and screen recording application designed for quick capture, annotation, and sharing.

---

## Core Features

### 1. Screenshot Capturing Functionality
- **Full Screen Capture**: Capture entire screen with a single hotkey
- **Window Capture**: Select and capture specific application windows
- **Region Select**: Click and drag to capture custom screen regions
- **Timed Capture**: Set delay timers for capturing menus and tooltips
- **Multi-Monitor Support**: Capture from any connected display

### 2. Annotation Tools
- **Drawing Tools**:
  - Freehand pen with adjustable thickness and colors
  - Shapes (rectangles, circles, lines)
  - Arrows with multiple styles
- **Text Tools**:
  - Add text boxes with customizable fonts, sizes, and colors
  - Text highlighting
- **Highlighter**: Semi-transparent overlay for emphasis
- **Blur/Pixelate**: Obscure sensitive information
- **Undo/Redo**: Full edit history support

### 3. Screen Recording Capabilities
- **Video Recording**: Record full screen or selected regions
- **Audio Capture**: System audio and/or microphone input
- **Frame Rate Control**: Adjustable FPS (15-60fps)
- **Format Options**: MP4, WebM export formats
- **Pause/Resume**: Control recording on the fly
- **Cursor Highlighting**: Optional cursor emphasis during recording

### 4. Quick Access Overlay/Hotkey System
- **Global Hotkeys**:
  - Screenshot: `Ctrl + Shift + S`
  - Region Capture: `Ctrl + Shift + R`
  - Start Recording: `Ctrl + Shift + V`
- **System Tray Integration**: Quick access from taskbar
- **Floating Toolbar**: Minimal overlay with capture controls
- **Hotkey Customization**: User-configurable shortcuts

### 5. Cloud Sharing Features
- **Instant Upload**: One-click upload to cloud storage
- **Shareable Links**: Generate public links with expiration options
- **Cloud Providers**:
  - Native cloud storage
  - Integration with popular services (optional)
- **History & Gallery**: Access previously captured screenshots
- **Copy to Clipboard**: Quick link copying for sharing

---

## Technical Architecture

### Project Structure
```
special-screenshots/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── CaptureControls/
│   │   │   ├── Editor/
│   │   │   ├── Overlay/
│   │   │   └── Gallery/
│   │   ├── utils/
│   │   │   ├── capture.js
│   │   │   ├── recording.js
│   │   │   └── hotkeys.js
│   │   ├── services/
│   │   │   ├── api.js
│   │   │   ├── storage.js
│   │   │   └── cloud.js
│   │   └── App.jsx
│   ├── public/
│   └── package.json
├── backend/
│   ├── src/
│   │   ├── routes/
│   │   ├── controllers/
│   │   ├── services/
│   │   └── models/
│   ├── uploads/
│   └── package.json
├── docs/
└── README.md
```

### Technology Stack
- **Frontend**: React.js, Electron (for desktop app)
- **Backend**: Node.js, Express
- **Storage**: Cloud storage API integration
- **Recording**: Web APIs (MediaRecorder, Screen Capture API)

---

## Getting Started

### Prerequisites
- Node.js v18+
- npm or yarn

### Installation
```bash
# Clone repository
git clone https://github.com/QuinnGideon/special-screenshots.git
cd special-screenshots

# Install dependencies
npm install

# Run development server
npm run dev
```

---

## Roadmap
- ✅ MVP Planning and Documentation
- 🚧 Core screenshot capture implementation
- 🚧 Annotation editor development
- 📋 Screen recording engine
- 📋 Cloud integration
- 📋 Desktop application packaging

---

## License
MIT License - See LICENSE file for details

---

## Repository Location
**GitHub**: https://github.com/QuinnGideon/special-screenshots

Ready for Cursor AI agent integration and further development.

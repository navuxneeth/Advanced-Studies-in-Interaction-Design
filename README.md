# Advanced Studies in Interaction Design (ASIID)

A comparative study of two habit tracking approaches through interactive web applications.

## 🎯 Overview

This project presents two distinct philosophies for personal growth and habit tracking:

1. **Emotion-Driven Tracker** - A gentle, nurturing approach focused on emotional awareness and self-compassion
2. **Function-Driven Tracker** - A strict, compliance-based system emphasizing accountability and streaks

## 🚀 Quick Start

### View Both Trackers Side-by-Side

Simply open `index.html` in your browser to experience both tracking philosophies simultaneously:

```bash
# Using Python 3
python3 -m http.server 8080

# Using Node.js
npx http-server -p 8080

# Then navigate to http://localhost:8080
```

### Desktop Experience (≥768px)
- **Split-Screen View**: Both trackers displayed side-by-side in a perfect 50/50 split
- **Compare & Contrast**: Interact with both approaches simultaneously
- **No Scrolling**: Everything visible at once for direct comparison

### Mobile Experience (<768px)
- **Button Selection Menu**: Choose your preferred tracker with simple buttons
- **EmotionDriven or FunctionDriven**: Tap a button to open that tracker
- **Clean Navigation**: Dedicated full-screen experience for each tracker

## 📁 Project Structure

```
.
├── index.html                      # Main entry point with split-screen view
├── Emotion-Driven-Tracker/
│   └── index.html                  # Nurturing, emotion-focused tracker
├── Function-Driven-Tracker/
│   └── index.html                  # Strict, compliance-focused tracker
└── README.md                       # This file
```

## 🎨 Individual Trackers

### Emotion-Driven Tracker (`/Emotion-Driven-Tracker/`)

**Philosophy**: "A Place to Grow" - Gentle self-care and emotional awareness

**Features**:
- Set intentions with personal "why" statements
- Track emotional responses after completing activities
- Daily reflection journal
- Visual plant growth metaphor
- No punishment for missed days
- Insights based on emotional patterns

**Design**: Warm beige tones, soft aesthetics, VT323 retro font

**Access**: Open `/Emotion-Driven-Tracker/index.html` directly

### Function-Driven Tracker (`/Function-Driven-Tracker/`)

**Philosophy**: "[COMPLIANCE]" - Strict accountability and streak maintenance

**Features**:
- 7-day habit tracking grid
- Streak counter (resets on any missed day)
- Success rate percentage
- Visual failure indicators
- Binary success/failure system
- Immediate feedback on performance

**Design**: Terminal-style black background, bright green text, high contrast

**Access**: Open `/Function-Driven-Tracker/index.html` directly

## 💾 Data Storage

Both trackers use browser `localStorage` to persist data:
- Data is stored locally on your device
- No server or account required
- Private and secure
- Clears when browser data is cleared

## 🛠️ Technologies

- **Pure HTML/CSS/JavaScript** - No build process required
- **Responsive Design** - Mobile and desktop optimized
- **localStorage API** - Client-side data persistence
- **CSS Flexbox** - Responsive split-screen layout
- **iframes** - Isolated tracker environments

## 🎓 Educational Purpose

This project explores interaction design through contrasting approaches:

**Research Questions**:
- How do emotional vs. functional approaches affect user engagement?
- Which design philosophy promotes better long-term habit formation?
- How does punishment (streak breaking) vs. compassion affect user experience?

## 📱 Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Requires JavaScript enabled
- Responsive design supports mobile and desktop
- localStorage support required

## 🤝 Contributing

This is an educational project. Feel free to:
- Fork and experiment with different interaction patterns
- Add new tracking philosophies
- Improve accessibility features
- Enhance mobile responsiveness

## 📄 License

Educational project - feel free to use and modify for learning purposes.

## 🔗 Links

- Individual Emotion Tracker: `/Emotion-Driven-Tracker/index.html`
- Individual Function Tracker: `/Function-Driven-Tracker/index.html`
- Combined Split View: `/index.html`

---

**Note**: This project is designed for interaction design research and education. Both tracking philosophies represent intentional extremes to highlight different design approaches.
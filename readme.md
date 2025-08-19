# MelodyStream 🎵

A modern music streaming web application built with vanilla HTML, CSS, and JavaScript. MelodyStream provides an intuitive interface for music playback with a clean, responsive design that works seamlessly across all devices.

## ✨ Features

### Core Functionality

- **Music Player Controls** - Play, pause, next, previous with smooth transitions
- **Progress Bar** - Interactive seek bar with real-time progress tracking
- **Volume Control** - Adjustable volume slider with mute functionality
- **Playlist Management** - Dynamic song list with current track highlighting
- **Responsive Design** - Fully responsive layout for desktop, tablet, and mobile

### User Interface

- **Modern UI Design** - Clean, minimalist interface inspired by contemporary music apps
- **Dynamic Backgrounds** - Gradient backgrounds that adapt to content
- **Interactive Elements** - Hover effects and smooth animations
- **Song Information Display** - Artist, title, and duration information
- **Visual Feedback** - Active states and loading indicators

### Technical Features

- **Audio API Integration** - HTML5 Audio API for seamless playback
- **Local Storage** - Saves user preferences and playback state
- **Cross-browser Compatibility** - Works on all modern browsers
- **Optimized Performance** - Lightweight codebase for fast loading

## 🛠️ Tech Stack

- **HTML5** - Semantic markup and audio elements
- **CSS3** - Modern styling with Flexbox/Grid layouts
- **JavaScript (ES6+)** - Interactive functionality and DOM manipulation
- **Font Awesome** - Professional icons
- **Google Fonts** - Typography enhancement

## 🚀 Getting Started

### Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation & Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/melodystream.git
   cd melodystream
   ```

2. **Open with Live Server (Recommended)**

   - Install Live Server extension in VS Code
   - Right-click on `index.html` and select "Open with Live Server"
   - Navigate to `http://localhost:5500`

3. **Alternative: Direct File Opening**
   - Simply double-click `index.html` to open in browser
   - Some features may require a local server for full functionality

## 📁 Project Structure

```
melodystream/
├── index.html              # Main HTML file
├── css/
│   ├── style.css          # Main stylesheet
│   └── responsive.css     # Media queries for responsiveness
├── js/
│   ├── script.js          # Core JavaScript functionality
│   ├── player.js          # Audio player logic
│   └── playlist.js        # Playlist management
├── assets/
│   ├── images/           # Album covers and UI images
│   ├── audio/           # Sample music files
│   └── icons/           # Custom icon assets
└── README.md
```

## 🎯 Key Components

### Audio Player Engine

```javascript
// Core player functionality
const audioPlayer = {
    currentSong: 0,
    isPlaying: false,
    songs: [...],
    // Player methods
};
```

### Playlist Manager

- Dynamic song loading and display
- Track selection and navigation
- Current song highlighting
- Shuffle and repeat modes

### UI Controllers

- Progress bar interaction
- Volume control slider
- Play/pause button states
- Responsive navigation menu

## 🎨 Styling Features

### CSS Highlights

- **Flexbox Layouts** - Responsive component arrangement
- **CSS Grid** - Complex layout structures
- **Custom Properties** - Consistent theming with CSS variables
- **Smooth Animations** - Transitions and keyframe animations
- **Media Queries** - Mobile-first responsive design

### Design Elements

- Gradient backgrounds with dynamic colors
- Glassmorphism effects for modern aesthetics
- Smooth hover transitions
- Loading animations and progress indicators

## ⚡ Performance Optimizations

- **Lazy Loading** - Images and audio files loaded on demand
- **Efficient DOM Manipulation** - Minimal reflows and repaints
- **Optimized Assets** - Compressed images and audio files
- **CSS Minification** - Reduced file sizes for faster loading
- **Event Delegation** - Efficient event handling

## 📱 Responsive Design

- **Mobile First** - Optimized for small screens
- **Tablet Support** - Medium screen adaptations
- **Desktop Enhancement** - Large screen utilization
- **Touch Friendly** - Appropriate touch targets for mobile devices

## 🔧 Browser Compatibility

| Browser | Version | Support |
| ------- | ------- | ------- |
| Chrome  | 60+     | ✅ Full |
| Firefox | 55+     | ✅ Full |
| Safari  | 11+     | ✅ Full |
| Edge    | 79+     | ✅ Full |

## 🛠️ Development Setup

### For Development

1. Use a local development server (Live Server, Python SimpleHTTPServer, or Node.js serve)
2. Enable browser developer tools for debugging
3. Test across different screen sizes using browser dev tools

### Code Structure

- **Modular JavaScript** - Separated by functionality
- **BEM CSS Methodology** - Consistent naming conventions
- **Semantic HTML** - Accessible and meaningful markup

## 🚀 Deployment

### GitHub Pages (Free Hosting)

1. Push your code to GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (main/master)
4. Access your site at `https://yourusername.github.io/melodystream`

### Other Hosting Options

- **Netlify** - Drag and drop deployment
- **Vercel** - Git integration with auto-deploy
- **Surge.sh** - Command line deployment

## 🎵 Adding Your Music

1. Place audio files in the `assets/audio/` directory
2. Update the song list in `js/playlist.js`:
   ```javascript
   const songs = [
     {
       title: "Song Title",
       artist: "Artist Name",
       src: "assets/audio/song.mp3",
       cover: "assets/images/cover.jpg",
     },
     // Add more songs...
   ];
   ```

## 🙏 Acknowledgments

- Design inspiration from modern music streaming platforms
- Icons from Font Awesome and Lucide
- Sample music from various royalty-free sources

## 📧 Contact

For questions or feedback, feel free to reach out:

- Email: yadavnikunj53@gmail.com

---

**MelodyStream** - Where music meets technology 🎵

# 🎵 Spotify Clone

A modern, fully-functional Spotify clone built with cutting-edge web technologies. This project replicates the core features of Spotify with a beautiful, responsive interface and seamless music playback experience.

![Spotify Clone](https://img.shields.io/badge/Spotify-Clone-1ED760?style=for-the-badge&logo=spotify&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## ✨ Features

### 🎶 **Music Playback**
- Full-featured music player with play/pause controls
- Volume control with visual slider
- Track progress indicator
- Seamless audio streaming

### 📱 **User Interface**
- Responsive design that works on all devices
- Dark theme inspired by Spotify's aesthetic
- Smooth animations and transitions
- Interactive playlist cards

### 🎧 **Playlist Management**
- Browse multiple curated playlists
- Individual playlist pages with track listings
- Album artwork and metadata display
- Artist and duration information

### 📋 **Music Library**
- **6 Curated Playlists** including:
  - 🌙 Chill Lo-Fi Music
  - 📚 Study Session
  - 🌃 Lo-Fi Chill Session
  - 🎹 Blue Note Study Time
  - 🎨 Chau Saura Session
  - ⚡ Like a Necessity

### 🎵 **Audio Content**
- Over 25 Lo-Fi tracks across different genres
- High-quality audio streaming
- Detailed track information and metadata

## 🛠️ Technologies Used

### **Frontend Framework**
- **Astro** - Modern static site generator
- **React** - Interactive UI components
- **Svelte** - Lightweight reactive components
- **TypeScript** - Type-safe development

### **Styling & UI**
- **TailwindCSS** - Utility-first CSS framework
- **Radix UI** - Accessible component primitives
- **clsx** - Conditional class utilities

### **State Management**
- **Zustand** - Lightweight state management

### **Development Tools**
- **Vite** - Fast build tool
- **Bun** - JavaScript runtime and package manager

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ or Bun
- Modern web browser

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd spotify-clone
   ```

2. **Install dependencies**
   ```bash
   bun install
   ```

3. **Start the development server**
   ```bash
   bun dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:4321`

## 🧞 Available Commands

| Command | Action |
|---------|--------|
| `bun install` | Install dependencies |
| `bun dev` | Start development server at `localhost:4321` |
| `bun build` | Build production site to `./dist/` |
| `bun preview` | Preview production build locally |
| `bun astro ...` | Run Astro CLI commands |

## 📁 Project Structure

```
spotify-clone/
├── public/
│   ├── music/           # Audio files organized by playlist
│   └── ...
├── src/
│   ├── components/      # Reusable UI components
│   │   ├── Card.astro
│   │   ├── PlayerControlButtonBar.tsx
│   │   ├── MusicsTable.tsx
│   │   └── ...
│   ├── icons/          # SVG icons and icon components
│   ├── layouts/        # Page layouts
│   ├── lib/            # Data and utilities
│   │   ├── data.ts     # Playlist and song data
│   │   └── colors.ts   # Theme colors
│   ├── pages/          # Astro pages and API routes
│   │   ├── index.astro
│   │   ├── playlist/[id].astro
│   │   └── api/
│   └── services/       # API services
└── ...
```

## 🎨 Key Components

- **PlayerControlButtonBar** - Main audio player controls
- **MusicsTable** - Track listing with play functionality
- **CardPlayButton** - Interactive play buttons for playlists
- **AsideMenu** - Navigation sidebar
- **VolumeControl** - Audio volume management

## 🎵 Music Content

The application features carefully curated Lo-Fi music across 6 different playlists:
- **25+ unique tracks** with full metadata
- **Multiple artists** including LoFi Dreamer, Tenno, Urban Nocturne
- **Varied durations** from 1:30 to 4:06 minutes
- **High-quality audio** in MP3 format

## 🌟 Features Showcase

### Dynamic Playlist Colors
Each playlist has its own theme color that dynamically changes the UI

### Responsive Design
- Mobile-first approach
- Tablet and desktop optimized
- Touch-friendly controls

### Modern Web Standards
- Server-side rendering with Astro
- Progressive enhancement
- Optimized performance

## 🚀 Deployment

This project is ready for deployment on platforms like:
- **Vercel** (recommended)
- **Netlify** 
- **GitHub Pages**
- Any static hosting service

## 🤝 Contributing

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Made with ❤️ and modern web technologies**

*Experience the future of music streaming with this Spotify clone built on Astro, React, and cutting-edge web standards.*

# Nxt Watch — Video Streaming Platform

A YouTube-inspired full-featured video streaming SPA built with React.js.

## 🔗 Live Demo
[https://hj-nxt-watch.vercel.app/](https://hj-nxt-watch.vercel.app/)

## ✨ Features

- 🔐 JWT cookie-based authentication with protected routing
- 🌗 Light / Dark theme toggle persisted across all routes
- 🔍 Search videos with optimized dual-state pattern
- 📺 Video playback via React Player
- 👍 Like / Dislike mutual exclusion interaction
- 💾 Save / Unsave videos with global Context state
- 📱 Fully responsive across all screen sizes
- ⚠️ 4 UI states per route: Loading, Success, Failure, Empty

## 🛠️ Tech Stack

| Category         | Technology                  |
|------------------|-----------------------------|
| Frontend         | React.js, React Router v5   |
| Styling          | Styled Components           |
| State Management | Context API                 |
| Authentication   | JWT Tokens via js-cookie    |
| HTTP Client      | Fetch API                   |
| Video Player     | React Player                |
| Build Tool       | Vite                        |
| Deployment       | Vercel                      |

## 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/hrutik-codes/nxt-watch

# Install dependencies
cd nxt-watch
npm install

# Start dev server
npm run dev
```

## 🔑 Test Credentials

```
Username: rahul
Password: rahul@2021
```

## 📁 Project Structure

```
src/
├── components/     # Feature-based component folders
│   ├── Login/
│   ├── Header/
│   ├── Sidebar/
│   ├── Home/
│   ├── HomeVideoCard/
│   ├── Trending/
│   ├── TrendingVideoCard/
│   ├── Gaming/
│   ├── GamingVideoCard/
│   ├── VideoItemDetails/
│   ├── SavedVideos/
│   ├── NotFound/
│   └── ProtectedRoute/
├── context/
│   └── NxtWatchContext.js
├── App.jsx
├── index.jsx
└── index.css
```
## 📸 Screenshots

### Login
![Login](./public/screenshots/nxt-watch-login.jpg)

### Home — Light Theme
![Home Light](./public/screenshots/nxt-watch-light-home.jpg)

### Home — Dark Theme
![Home Dark](./public/screenshots/nxt-watch-dark-home.jpg)

### Real Time Search
![Real Time Search](./public/screenshots/nxt-watch-search.jpg)

### Video Details
![Video Details](./public/screenshots/nxt-watch-video-details.jpg)

### Trending
![Trending](./public/screenshots/nxt-watch-trending.jpg)

### Gaming
![Gaming](./public/screenshots/nxt-watch-gaming.jpg)

### Saved Videos
![Saved Videos](./public/screenshots/nxt-watch-saved-videos.jpg)
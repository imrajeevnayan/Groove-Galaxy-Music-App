# 🎶 Groove Galaxy

**Groove Galaxy** is a modern, responsive, Spotify-inspired music streaming web UI built with **HTML**, **Tailwind CSS**, and **Feather Icons**. It features dark mode styling, animated playlists, trending songs, artist cards, and a fully interactive "Now Playing" bar.

---

## 📸 Preview

> Add a screenshot here (optional)

---

## 🚀 Features

- 🎧 Responsive UI with dark mode
- 📦 Built using [Tailwind CSS](https://tailwindcss.com/)
- 🎵 Playlist, trending songs, artists, and radio cards
- 📻 Sticky "Now Playing" bar with play/pause, volume, shuffle, and seek controls
- 🪶 Vector icons using [Feather Icons](https://feathericons.com/)
- 🧩 Fully structured and ready for audio API integration

---

## 🛠 Tech Stack

- **HTML5**
- **Tailwind CSS** (via CDN)
- **Feather Icons** (via CDN)
- **JavaScript** for audio interactions (optional)

---

## 🔊 Add Real Song Playback

Groove Galaxy is UI-only by default. To enable music playback, you can:

### ✅ Option 1: Host your own MP3 files

1. Upload `.mp3` files to a `/songs/` folder.
2. Update the `data-src` on each play button:
   ```html
   <button class="play-button" data-src="songs/the-fate-of-ophelia.mp3">

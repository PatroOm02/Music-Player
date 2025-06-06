# 🎵 Music Player Web UI

This project is a responsive, front-end-only **Music Player Web Interface** built using HTML and CSS. It simulates a modern music streaming experience with interactive navigation, playlist views, and an animated bottom music player.

---

## 📁 Project Structure

The project consists of **three main files** and an image asset folder:

### 🔹 1. `MusicPlayerHomePage.html`

This is the landing page of the music player. It is structured into the following sections:

- **Navigation Bar**  
  Contains the logo, a search bar, and basic navigation controls.

- **Main Section**  
  Subdivided into:
  - **Home Screen Carousel**
  - **Latest Releases**  
    ➤ Clicking a song icon or the "Play Now" option triggers the bottom music bar.
  - **Popular Artists**
  - **Playlists**
  - **Genres**
  - **Latest Songs**

- **Aside Section**  
  Displays a **queue of songs** (currently playing or up next).

- **Bottom Music Player**  
  A persistent music bar that appears when a song is played.

---

### 🔹 2. `MusicPlayerSinglePlaylistScreen.html`

This page is linked from the first page. When you click on any artist’s image under the **Latest Releases** section, you are redirected here. It showcases:

- Detailed **artist view**
- Associated **songs by the artist**
- An **aside section** featuring:
  - Similar Artists
  - Recently Played Songs

---

### 🔹 3. `MusicPlayerStyle.css`

This is the external CSS stylesheet applied globally to both HTML files. It contains styling for:

- Navigation bar
- Main content layout
- Aside sections
- Bottom music player
- Artist-specific layout in `MusicPlayerSinglePlaylistScreen.html`

It ensures **responsive design**, optimized for various screen sizes (desktop, tablet, mobile).

---

### 🖼️ Images

All relevant image assets (artist icons, album covers, etc.) are stored in the `/Images` directory and are referenced in the HTML files.

---

## 🧪 Features

- Responsive layout using pure HTML and CSS
- Interactive bottom music player on user actions
- Playlist and genre sections to mimic real streaming platforms
- Cross-page navigation for playlist/artist views
- Simulated "Now Playing" queue

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
- No JavaScript used — UI-only prototype

---



## 📄 License

This project is created for educational/demo purposes. Free to use with attribution.

---


# Spotify-Clone
A responsive, front-end clone of the Spotify web player, built with vanilla HTML, CSS, and JavaScript. This projectloads and plays music from local files, featuring separate sections for trending songs and artist playlists.
Key Features
Dynamic Music Loading: All song and playlist data is loaded from a central songs.json file, making it easy to manage and update the music library.

Two Music Sections:

Trending Songs: A horizontally scrollable list of individual tracks.

Popular Artists: A collection of artist cards that function as playlists.

Full Playback Controls:

Play, pause, next, and previous track functionality.

Interactive progress bar and volume slider.

Repeat functionality for the current song.

Responsive Design: The layout and player UI adapt seamlessly for both desktop and mobile devices, providing a consistent user experience.

Interactive UI: Features like hover effects, custom tooltips, and a resizable library panel replicate the feel of the original Spotify interface.

Tech Stack
HTML5: For the core structure and content.

CSS3: For all styling, layout (Flexbox/Grid), and responsive design.

Vanilla JavaScript: For all dynamic functionality, including DOM manipulation, event handling, and fetching local data.

Project Structure
The project is organized to be simple and scalable. Understanding the structure is key to adding your own content.

spotify-clone/
│
├── index.html          # The main HTML file
├── style.css           # All desktop and base styles
├── media.css           # Responsive styles for mobile/tablet
├── script.js           # All JavaScript logic
├── songs.json          # IMPORTANT: The central database for all music
│
├── assets/             # Folder for images and covers
│   └── images/
│   └── playLists/
│
└── songs/              # Folder where all .mp3 files are stored
    ├── Trending Songs/

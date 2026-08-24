# Music Player

A custom HTML/CSS/JavaScript music player with play/pause, next/previous,
click-to-seek progress bar, repeat/shuffle modes, and an expandable song list.

## Structure

```
.
├── index.html
├── style.css
├── js/
│   ├── music-list.js   # song data (name, artist, image, audio file)
│   └── script.js        # player logic
├── images/               # album art (.jpg)
└── songs/                # audio files (.mp3)
```

## Setup

1. Add album art to `images/` and matching audio files to `songs/`.
2. Update the `allMusic` array in `js/music-list.js` with your song names,
   artists, and file names.
3. Open `index.html` in a browser.

## Notes

- Icons use Google's Material Icons webfont, loaded via CDN — an internet
  connection is required for them to display.

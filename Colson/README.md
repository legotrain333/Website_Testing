# Classical Piano Portfolio

A personal music portfolio website with a **piano keys** design. Showcases classical piano work (Bach & Beethoven), MP3 recordings, downloadable sheet music, and an artist bio.

## Quick start

1. Open `index.html` in a browser.
2. Add your MP3s to the `audio/` folder and your PDF scores to `scores/`.
3. Edit `index.html` to point `<audio src="...">` and `<a href="...">` links to your files.
4. Update the **Artist Bio** and **Contact** sections with your details.

## Folder structure

```
piano-portfolio/
├── index.html       ← main site
├── audio/           ← put your MP3 recordings here
├── scores/          ← put your PDF sheet music here
└── README.md
```

## Customization

- **Audio**: Replace the `src` in each `<audio>` tag with paths like `audio/your-recording.mp3`.
- **Scores**: Add PDFs to `scores/` and update the `href` in each score item.
- **Bio & Contact**: Edit the text in the Bio and Contact sections.
- **Projects**: Update the Music Projects list with your repertoire.

No build step required—plain HTML, CSS, and a little JavaScript.

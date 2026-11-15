# Clean Viewer

A fan-made, SafeShare-style YouTube viewer by James. Paste a YouTube link (watch, youtu.be, shorts, or playlist) and it plays on a clean white page.

This is not an official YouTube, xAI, or Grok product.

## Play

- **Online:** https://jamesgregory5-svg.github.io/clean-viewer/
- **Download:** unzip the [latest release](https://github.com/jamesgregory5-svg/clean-viewer/releases) and open `index.html`.

The page itself works from `file://`, but **YouTube’s official embed often fails there (error 153)**. Use the GitHub Pages link above for playback.

## What it does

- Official privacy-enhanced IFrame only: `https://www.youtube-nocookie.com/embed/…`
- No related-video sidebar, comments, or extra chrome on this page
- Optional start time, end time, and loop
- Recent links stored in this browser (`localStorage`)

It does **not** download videos or extract audio.

The wordmark uses [Inter Tight](https://github.com/googlefonts/inter-tight) (SIL Open Font License 1.1).

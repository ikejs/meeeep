# The Online Taboo Buzzer

A free, single-page web buzzer for the party game **Taboo**. Tap and hold the big red button for that unmistakable buzz — perfect when the buzzer from the box has wandered off or its battery died.

**Use it here:** https://taboo-buzzer.ike.dev/

## Features

- Looks and feels like the real thing: glossy purple body, big red dome button
- Hold to buzz — plays a real buzzer recording (`buzz.mp3`), with a synthesized fallback if the file can't load
- Works on phones, tablets, and desktop (pointer, touch, and keyboard — hold Space/Enter)
- No app, no ads, no build step — one HTML file

## Running locally

Serve the folder with any static server (the audio fetch needs http, not `file://`):

```sh
npx serve .
```

---

Free fan-made project for game night. Not affiliated with or endorsed by Hasbro. Taboo is a trademark of Hasbro, Inc.

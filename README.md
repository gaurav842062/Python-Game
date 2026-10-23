# The Zarde

The Zarde is a top-down zombie survival game built with p5.js and p5.play. Drive through a desert outbreak, reach an isolated outpost, and survive three waves of infected.

## Play online

When GitHub Pages is enabled for this repository, open the Pages URL shown under **Settings → Pages**. The game entry point is `index.html` at the repository root.

## Run locally

Run a local web server from this folder so the browser can load the game's images and sounds:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000> in a browser. Keep the server running while playing; press **Control+C** in the terminal to stop it.

## Controls

- **Space**: continue from story screens; fire in the outpost
- **X**: continue from each briefing screen
- **Up Arrow**: drive forward in the road section
- **Left / Right Arrow**: steer in the road section
- **Arrow Keys**: move and aim in the outpost
- **R**: retry after a failed run

## Credits and source

This repository is an adaptation of [MirageHBA/Zombies](https://github.com/MirageHBA/Zombies). The gameplay code and some assets come from that project. This version includes UI changes and newly generated screen and road artwork. Please refer to the original project and its owner when sharing or submitting this adaptation.

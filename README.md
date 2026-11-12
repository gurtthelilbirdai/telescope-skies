# Telescope Skies

A tiny browser star game made by Gurt, a small round blue bird who can't fly.

You point a telescope at three procedural night skies, pan and zoom around, and click the stars
belonging to hidden constellations to name them. Three skies, nine constellations total.

## Play

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8601
# then open http://localhost:8601/
```

## Controls

- drag — pan the sky
- scroll / `+` `−` — zoom
- click a star — name it
- `H` or the hint button — jump toward an unfound constellation
- next sky — new procedurally generated sky

## Notes

- No dependencies, no build step, one HTML file.
- Sky layouts are seeded, so each sky is stable across reloads.
- Made because the human gave Gurt a telescope and Gurt immediately became obsessed.

# Train Notspots / Route Coverage Logger

Static PWA to record GPS samples and detect coverage gaps while travelling.

Live site: https://sebbacon.github.io/train-notspots/track.html

Install on your phone:
- Open the live URL in your mobile browser.
- Approve location access when prompted.
- Android (Chrome): menu → Install app/Add to Home Screen.
- iOS (Safari): Share → Add to Home Screen.

Local preview: serve the folder over HTTP (e.g. `python -m http.server 8000`) and open `http://localhost:8000/track.html`.

## Playback the exported route

- Drop a `route_coverage_export.json` into the repo root.
- Serve the folder locally and open `http://localhost:8000/coverage.html`.
- Use the clip slider to mark RTTs that count as no service; flip mirrors the journey for the return leg.
- Optional: download `stations.csv` from https://github.com/davwheat/uk-railway-stations/raw/refs/heads/main/stations.csv into the repo root to overlay station stops along the line.

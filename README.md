# Portfolio

## Run
    docker compose up -d --build
Open http://localhost:8080
Stop: `docker compose down`

## Edit
- Everything is in `site/projects.json` (profile + projects).
- Put images/videos in `site/assets/` and write their path, e.g. "assets/shot1.png".
- Video: local file ("assets/demo.mp4") or a YouTube link.
- Refresh the browser after saving: no rebuild needed.

## Publish
Push to GitHub, then deploy the `site/` folder (GitHub Pages, Netlify)
or run the same Docker image on any server.

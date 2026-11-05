# Kids ER Tablet Demo

Interactive tablet prototype for a children's emergency-room companion experience.

**Live demo:** https://unlockmdm.github.io/kids-er-tablet-demo/

## Structure

```
index.html                         # the prototype
assets/dc-runtime.js               # component runtime
assets/react*.production.min.js    # React 18.3.1 (served locally)
assets/fonts/                      # Baloo 2 + Geist (woff2)
```

It's a static site with no build step. To run it locally, serve the folder with any static server:

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

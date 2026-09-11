# Northeast India Landslide Risk Predictor

Static GitHub Pages site. No backend required.

## Files
- `index.html` — website
- `style.css` — styling
- `script.js` — browser-side prediction
- `model.json` — data/model payload
- `metadata.json` — project metadata

## Risk definition
- Slide -> MEDIUM
- Fall -> HIGH
- Other -> LOW

## Inputs
State, District, Latitude, Longitude, Movement History, Annual Rainfall Normal (mm), Rainfall Pattern, Soil Distribution, Vegetation.

## GitHub Pages
1. Create a GitHub repository.
2. Upload all files in this folder to the repository root.
3. Go to Settings -> Pages.
4. Select `Deploy from a branch`.
5. Select the main branch and `/ (root)`.
6. Save.

Important: a Python `.pkl` file cannot run directly in a normal browser. This static package therefore contains a browser-compatible predictor payload and does not require a server.

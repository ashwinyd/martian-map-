# Martian Map: A Safe Walk Planner for Mars

NASA Space Apps Challenge – Interplanetary Survival Guide: Martian Map

**Open the app:** open `index.html` in any web browser (or use the GitHub Pages link of this repository).

## What it does
Martian Map helps two astronauts and their rover plan a safe walk at Jezero Crater on Mars.
- Map layers: photos from space, height map, heat map, rock map, obstacles
- Click to add stops: the app finds the safest path (no slopes over 15°, around big rocks, away from soft sand)
- Walking time, oxygen left, Mars time, temperature and air pressure at each stop
- Safety warnings: not enough oxygen, walk ends after dark, very cold, steep or sandy ground
- Helmet screen mode: only the key facts while walking

## NASA data
JPL Mars Trek · USGS-NASA Planetary Geologic Mapping · Curiosity route animation · NASA Worldview · Perseverance Raw Images · Perseverance MEDA weather data

The terrain in this prototype is a simple model of Jezero Crater (places are approximate). Real Mars Trek images can be loaded in the app with the import buttons.

## Tools
HTML, CSS, JavaScript (works offline, any device) · HTML Canvas · A* path finding · Python (printable map)

## Files
- `index.html` – the app
- `Martian_Map_Jezero_EVA_Map.pdf` – printable A3 mission map
- `Martian_Map_Presentation.pdf` – 7-slide presentation

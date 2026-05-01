Ranking Near-Earth Asteroids (NEAs) by their potential for a mining mission.

## What this is

A one-week sprint to take public NASA data (~35,000 NEAs) and rank them by a simple "mining attractiveness" score combining:

- **Delta-v** (cost to reach the asteroid)
- **Size** (potential resource volume)
- **Composition** (water-rich C-type vs metallic M-type, etc.)
- **Accessibility** (frequency of close-Earth approach windows)

Output: a CSV / JSON of the top-50 asteroids, plus a visualization.

## Status

🚧 Day 1 — setup. Data not yet ingested.

## Data sources

- [NASA JPL Small-Body Database](https://ssd.jpl.nasa.gov/sbdb_query.cgi)
- [NASA NHATS — Accessible NEAs](https://cneos.jpl.nasa.gov/nhats/)
- [NEOWISE](https://wise2.ipac.caltech.edu/docs/release/neowise/) — spectral / composition
- [Asterank](http://www.asterank.com/) — economic estimates

## Stack

- Python 3
- pandas, matplotlib (plotly later, maybe)
- Jupyter for exploration

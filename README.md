# Kyiv Road Infrastructure Damage Monitoring (MVP)

An early-stage geospatial prototype designed to map, classify, and track road infrastructure damage caused by drone and missile strikes in the Dniprovskyi District of Kyiv, Ukraine.

## Project Overview
* **Objective:** Develop an analytical monitoring tool to support urban recovery, emergency logistics, and infrastructure assessment.
* **Current Scope (Phase 1 — MVP):** An interactive web map built with Python, Folium, and OpenStreetMap data, paired with a structured CSV status tracker.
* **Repository Contents:**
  * `prototype.py` — Python script that processes damage coordinates and generates the interactive map and status table.
  * `dniprovskyi_damage_map.html` — Standalone interactive map visualization color-coded by repair status.
  * `damage_status_table.csv` — Structured dataset tracking incident ID, location, cause, severity, and current repair status.

## Future Research & Scaling at Davidson College
With faculty mentorship and access to Davidson College's computing cluster and GIS/Data Science tools, I aim to scale this prototype into a comprehensive research project:
1. **Automated Damage Detection:** Integrating high-resolution satellite imagery (e.g., Sentinel-2, PlanetScope) and Computer Vision models to detect road surface anomalies automatically.
2. **Network & Graph Analysis:** Utilizing `OSMnx` and `NetworkX` to model traffic rerouting, emergency response delays, and critical infrastructure bottlenecks across Kyiv's road network.
3. **Real-Time Data Pipeline:** Transitioning from static datasets to automated ingestion of verified open-source intelligence (OSINT) and municipal reports.

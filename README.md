# AERPAW QuadSense Simulator

Interactive, standalone research demonstrator for simulated UAV detection and tracking using RF, radar, acoustic, and camera modalities.

## Run

Open [`index.html`](index.html) directly in a recent browser. No build, server, dependencies, or accounts are needed.

If publishing via GitHub Pages, select the `main` branch and repository root as the publishing source in **Settings > Pages**. GitHub Pages requires the appropriate account/repository eligibility and access settings.

## Features

- Select UAV type, flight trajectory, sensors, and fusion algorithm.
- Adjust measurement noise and environmental effects, and compare tracking results.
- View synthetic RF/radar diagnostics and camera imagery; play synthesized drone audio.
- Export scenario configurations and tracking data; import your own geofence GeoJSON.

## Scope and limitations

This is a **synthetic research demonstrator**, not a live feed or hardware-connected AERPAW experiment. Visualizations and acoustic playback are generated; the built-in geofence is illustrative and is not an authoritative flight authorization boundary. Displayed model-based metrics should not be interpreted as calibrated field performance.

No manuscript, research PDF, or publication figures are included in the current code tree.

# GPX to Strava

A simple **Python CLI** to upload GPS tracks (GPX, TCX, FIT) to **Strava** directly from your terminal. Supports **single file** and **folder uploads**, automatic token refresh, and respects Strava rate limits.

Based on the tutorial by Michael Lihs: [gist link](https://gist.github.com/michaellihs/bb262e2c6ee93093485361de282c242d) — OAuth configuration is required.

## Features

- One-time OAuth setup  
- Upload single file or entire folder  
- Check upload status  
- Automatic token refresh  
- 6-second delay to respect Strava rate limits  

## Installation

```bash
git clone https://github.com/yourusername/gpx-to-strava.git
cd gpx-to-strava
pip install requests

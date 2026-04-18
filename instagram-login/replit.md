# Instagram Page Clone

## Overview
A static capture of the Instagram homepage served via a simple Python HTTP server.

## Project Structure
- `www-instagram-com.html` — The main HTML file (captured Instagram page)
- `serve.py` — Python HTTP server that serves the HTML file on port 5000
- `README.md` — Project readme

## Running the App
The app is served using Python's built-in HTTP server via `serve.py`.

- **Workflow:** "Start application" runs `python serve.py`
- **Port:** 5000
- **Host:** 0.0.0.0

## Deployment
Configured for autoscale deployment running `python serve.py`.

# Beaver IoT Public Dashboard

This repository hosts a public, read-only view of a Beaver IoT dashboard.

## Features

- 🔒 100% secure (no backend access)
- 🌐 Public HTTPS hosting via GitHub Pages
- 🔄 Auto-updates every 30 seconds
- 📱 Responsive design

## How It Works

A Raspberry Pi running Beaver IoT periodically:
1. Captures a screenshot of the dashboard
2. Pushes it to this GitHub repository
3. GitHub Pages serves the static website

The dashboard is completely isolated from the Beaver IoT backend.

---

*Powered by Beaver IoT Cytron Edition*

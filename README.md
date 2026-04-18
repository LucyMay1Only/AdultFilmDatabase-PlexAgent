# AdultFilmDatabase-PlexAgent
# Adult Film Database (AFDB) Plex Agent
**Created and Constructed by: Lucy May & G. Antidote**

This is a custom Plex Metadata Agent designed to retrieve rich metadata, cast information, studios, genres, and high-quality box art directly from the [Adult Film Database](https://www.adultfilmdatabase.com).

## Features
- Scrapes full metadata including **Title**, **Description/Summary**, **Director**, **Studio**, and **Genres**.
- Extracts **Cast/Performers** along with their individual profile photos.
- Discovers high-resolution **Posters** (Front/Back Box Covers).
- Organizes related films via **Series** collections.
- Lightweight, self-contained, and perfectly tailored for Plex's Python environment meaning fewer dependency issues natively.

## Installation Guide

Follow these steps to install the agent in your local Plex Media Server:

### 1. Locate your Plex `Plug-ins` Folder
The location varies depending on your operating system:
* **Windows:** `%LOCALAPPDATA%\Plex Media Server\Plug-ins`
* **macOS:** `~/Library/Application Support/Plex Media Server/Plug-ins`
* **Linux:** `/var/lib/plexmediaserver/Library/Application Support/Plex Media Server/Plug-ins`

### 2. Copy the Plugin
Extract the downloaded zip file (if you haven't already). Copy the entire `AdultFilmDatabase.bundle` folder into your `Plug-ins` directory identified in Step 1.

### 3. Restart Plex Media Server
Though Plex continually monitors the `Plug-ins` folder, restarting Plex Media Server is the best way to ensure the agent loads immediately and properly into your server's agent list.

## How to Use
Once the plugin is installed and your server is restarted:

1. Open your Plex Web Client.
2. Navigate to your Adult film library.
3. Click the `...` (options) menu on a movie and select **Fix Match** (or "Match" if it hasn't been matched yet).
4. Click **Search Options**.
5. Click the **Agent** dropdown and select **Adult Film Database**.
6. Plex will perform the search and present available matches! Click the correct entry.

Enjoy your beautifully organized film library!

PREVIEW:
[![Plex Library List](https://i.ibb.co/zVdk0f2W/Screenshot-2026-04-18-at-10-33-46-Plex.png)](https://ibb.co/zVdk0f2W)
[![Plex Match Details](https://i.ibb.co/LXBJphWM/Screenshot-2026-04-18-at-10-36-35-Plex.png)](https://ibb.co/LXBJphWM)
[![Plex Metadata View](https://i.ibb.co/6c5m7JpZ/Screenshot-2026-04-18-at-10-40-02-Plex.png)](https://ibb.co/6c5m7JpZ)

***
*Disclaimer: This agent is completely unaffiliated with the Adult Film Database website.*

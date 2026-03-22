# nyt-lite

A lightweight, text-first New York Times news feed reader that runs entirely in your browser — no server, no tracking, no accounts.

## Features

- Browse top stories across 11 sections: Top, U.S., World, Politics, Business, Tech, Science, Health, Arts, Sports, and Opinion
- Tap any headline to expand its abstract
- Color-coded section tags for quick scanning
- Relative timestamps (e.g. "2h ago")
- "Read full" link opens the article on nytimes.com
- API key is saved only in your browser's `localStorage` — never sent anywhere else

## Usage

1. Get a free NYT Developer API key at [developer.nytimes.com](https://developer.nytimes.com/get-started) (takes about 2 minutes; no subscription required)
2. Open `feed.html` (or `nyt-feed.html`) directly in your browser
3. Paste your API key and click **Open the feed →**

To switch accounts or reset, click **Reset key** in the top bar.

## Files

| File | Description |
|------|-------------|
| `feed.html` | Full reader with color-coded section tags |
| `nyt-feed.html` | Simplified version without color-coded tags |

## Requirements

- A modern browser (Chrome, Firefox, Safari, Edge)
- A free [NYT Developer API key](https://developer.nytimes.com/get-started)

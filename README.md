# Octodex Collection Tracker

A web application to track your collection of GitHub Octocats. This app fetches the latest Octocats from GitHub's Octodex and allows you to see which ones you've collected.

## Features

- Displays all Octocats from the official GitHub Octodex
- Tracks which Octocats you have in your collection
- Filter view by collected, not collected, or all Octocats
- Responsive design that works on mobile and desktop

## How It Works

The application fetches Octocat data from the GitHub Octodex RSS feed and compares it against your personal collection defined in `collection.js`. Each Octocat is displayed in a grid with visual indicators showing which ones you've collected.

## Setup

1. Clone this repository to your local machine
2. Edit the `collection.js` file to add or remove Octocats from your collection
3. Open `index.html` in a web browser

No build step is required as the app uses Vue.js from a CDN.

## Dependencies

- Vue.js 3 (loaded from CDN)
- A web browser with JavaScript enabled

## Browser Compatibility

This app works in all modern browsers including:

- Chrome
- Firefox
- Safari
- Edge

## Customizing Your Collection

To add or remove Octocats from your collection, edit the array in `collection.js`. Each entry should match the name of the Octocat as it appears on the [GitHub Octodex](https://octodex.github.com/).

## CORS Notice

When running locally, you might encounter CORS errors when fetching the Octodex RSS feed. To work around this, you can:

1. Use a browser extension to disable CORS for local development
2. Set up a simple proxy server
3. Run your browser with security disabled (not recommended for general browsing)

## License

This project is open source and available for personal use.

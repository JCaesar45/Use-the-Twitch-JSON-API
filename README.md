```
# Twitch Status Tracker

A simple web application that displays the online/offline status of a list of Twitch streamers, using the Twitch API via a proxy. It provides real-time streaming status, additional stream details when online, and direct links to Twitch channels.

---

## Features

- **Real-time status:** Shows whether each Twitch user is currently streaming or offline.
- **Details on stream:** Displays game and stream title when a user is live.
- **Clickable channels:** Clicking on a user redirects to their Twitch channel.
- **Responsive & styled:** Clean, minimal design that can be customized.

---

## Demo

[Link to your CodePen project or live demo]

---

## Technologies Used

- HTML5, CSS3, JavaScript
- Fetch API for data retrieval
- Twitch API via proxy: `https://twitch-proxy.freecodecamp.rocks/`

---

## How It Works

1. The app maintains a list of Twitch usernames.
2. For each user, it fetches streaming data to check if they are live.
3. If online, fetches additional stream details such as game and title.
4. Updates the UI dynamically to reflect the current status.
5. Clicking on a user opens their Twitch channel in a new tab.

---

## Setup Instructions

1. **Clone or download** this repository.
2. **Open `index.html`** in your web browser.
3. The app will automatically fetch and display statuses for predefined users.

---

## Customization

- To add more streamers, update the `users` array in the JavaScript code.
- Style the app by editing the CSS section.
- Integrate your own Twitch API key if needed (not required with the proxy).

---

## Note

Due to Twitch API restrictions, this project uses the proxy API `https://twitch-proxy.freecodecamp.rocks/` which provides the necessary data without requiring an API key.

---

## Acknowledgments

- Inspired by freeCodeCamp's Twitch API challenge.
- Uses data from Twitch.tv.

---

## License

This project is for educational purposes and is not for commercial use.

---

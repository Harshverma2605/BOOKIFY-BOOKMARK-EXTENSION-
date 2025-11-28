--> Bookify — Smart Bookmark Manager Chrome Extension
📌 Description

Bookify is a lightweight and efficient Chrome extension designed to simplify bookmark management. Unlike Chrome’s default Bookmark Manager — which often becomes slow and cluttered — Bookify provides a clean popup interface for quick saving, instant searching, and fast access to organized bookmarks.

It solves the problem of messy bookmark folders by offering categorized storage, real-time search, and a minimal UI that helps users find saved pages in seconds.

🚀 Features
⭐ One-Click Bookmarking

Instantly save the current tab with auto-fetched title and URL.

📂 Bookmark Categories

Organize bookmarks into custom folders for cleaner navigation.

🔍 Real-Time Search

Search instantly by title, URL, or tags with dynamic filtering.

⚡ Minimal & Fast UI

Clean popup interface designed for speed and ease of use.

🔄 Sync Support

Uses chrome.storage.sync, keeping your bookmarks available across all Chrome devices.

🔗 Quick Access

Open any saved bookmark from the popup with a single click.

🛠️ Installation

Clone or download the repository:

git clone https://github.com/Harshverma2605/BOOKIFY-BOOKMARK-EXTENSION-.git


Open Chrome and navigate to:

chrome://extensions/


Enable Developer Mode (top-right toggle).

Click Load Unpacked.

Select the project folder.

The Bookify icon will now appear on your Chrome toolbar.

📘 Usage

Click the Bookify icon in the Chrome toolbar to open the popup.

Tap Add Bookmark to save the current tab instantly.

View bookmarks organized into categories.

Use the search bar to quickly filter bookmarks.

Click any saved bookmark to open it in a new tab.

Manage bookmarks: delete, rename, move between categories.

📂 Project Structure
Bookify/
│── manifest.json       # Extension metadata & permissions
│── popup.html          # Popup interface structure
│── popup.css           # UI styling
│── popup.js            # Main bookmark handling logic
│── background.js       # Background tasks (optional)
│── icons/              # Extension icons
│── README.md           # Documentation

🔧 Tech Stack / Built With

HTML5 — Popup structure

CSS3 — UI styling

JavaScript — Core logic

Chrome Extension APIs

chrome.tabs

chrome.bookmarks

chrome.storage.sync

chrome.runtime

🤝 Contributing

Contributions are always welcome!

Steps:

Fork the repository

Create a new branch

Make your changes

Commit and push

Open a Pull Request

📄 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute this project with proper attribution.

🎬 CineStream Launcher

A sleek, single-file web app that lets you search for movies and TV series, view rich metadata, and instantly launch streams — all directly in your browser.

Built with pure HTML, CSS, and JavaScript, CineStream requires no backend and runs entirely client-side.

✨ Features
- 🔍 Search Movies & Series using OMDB
- 🎬 Detailed Metadata via Cinemeta (posters, ratings, descriptions)
- ▶️ One-Click Streaming through Videasy
- 📺 Episode Browser with season picker for TV shows
- 💾 Local API Key Storage (stored securely in your browser)
- ⚡ Fast & Lightweight – single HTML file
- 📱 Responsive UI with a modern, cinematic design

🚀 Live Demo
- https://carlingman1.github.io/CineStream-Launcher/

🛠️ Setup
1. Clone or Download
- git clone https://github.com/your-username/your-repo-name.git
- cd your-repo-name

Or just download the index.html file.

2. Get an OMDB API Key

You need a free API key to search for movies:

- 👉 https://www.omdbapi.com/apikey.aspx

3. Run the App
Option A: Open directly
- Double-click index.html

Option B (Recommended for best compatibility):
- Run a local server:

# Python
- python -m http.server

# Node (if installed)
- npx serve

Then open:
- http://localhost:8000


4. Enter Your API Key
- Click the ⚙️ settings icon
- Paste your OMDB API key
- Click Save

Your key is stored locally in your browser (localStorage) and never sent anywhere except OMDB.

🧩 How It Works
1. Search → Queries OMDB API
2. Select Title → Fetches metadata from Cinemeta
3. Resolve ID → Matches with Videasy database
4. Launch → Opens the stream in a new tab

🧱 Tech Stack
- HTML5
- CSS3 (Custom UI + animations)
- Vanilla JavaScript
- APIs:
- OMDB
- Cinemeta (Stremio)
- Videasy

⚠️ Notes
- Requires an OMDB API key to function
- Some browsers may block API calls due to CORS restrictions
- Works best when hosted (e.g. GitHub Pages) or run via local server

📌 Future Improvements
- ⭐ Favorites / Watchlist
- 🎭 Genre filtering
- 🔎 Advanced search (year, type, rating)
- 🌐 Better CORS handling / proxy support
- 🎨 Theme customization

📄 License
- This project is licensed under the GNU General Public License v3.0 (GPL-3.0).
- You are free to use, modify, and distribute this software, but any derivative work must also be licensed under GPL-3.0.

🙌 Credits
- OMDB API
- Cinemeta (Stremio)
- Videasy

Queens Arts & Culture Map
An interactive map developed for Flushing Town Hall to highlight arts and cultural organizations across Queens, New York. Built with Mapbox GL JS, Airtable API, and a custom filtering/legend interface.

🌐 Live Demo --> https://flushingtownhall.github.io/QueensArtsMap/

📖 Project Overview
This project was created as part of the Queens Cultural Mapping Project, an initiative funded by the New York State Council on the Arts (NYSCA). The map provides a centralized, accessible resource that connects artists, cultural organizations, and community spaces across Queens.
Features include:

🗺️ Interactive Mapbox GL JS base map
📍 Custom markers for different organization categories
🔎 Searchable directory with real-time filtering
📑 Expandable legend with per-category visibility toggling
📱 Mobile-friendly design (collapsible bottom panel, draggable legend)
🚌 Subway lines & stops overlay for geographic context

🚀 Tech Stack
Frontend: HTML5, CSS3, JavaScript (ES6)
Mapping: Mapbox GL JS
Database: Airtable API (for organizations data)
Hosting: GitHub Pages / custom hosting (TBD)


🛠️ Setup & Development
1. Clone the repository
git clone https://github.com/flushingtownhall/QueensArtsMap.git
cd Queens-Culture-Map
2. Add your environment variables
The project uses Mapbox and Airtable.
Open script.js and update:
mapboxgl.accessToken = "YOUR_MAPBOX_ACCESS_TOKEN";
const AIRTABLE_API_KEY = "YOUR_AIRTABLE_KEY";
const BASE_ID = "YOUR_BASE_ID";
const TABLE_NAME = "YOUR_TABLE_NAME";
3. Run locally
Simply open index.html in your browser, or use a lightweight server:
npx serve
4. Deploy
Push to GitHub → enable GitHub Pages
Or deploy via Netlify / Vercel

📂 Project Structure
.
├── index.html      # Main HTML entry
├── style.css       # Styling (desktop + responsive mobile)
├── script.js       # Core logic (map, legend, search, Airtable integration)
├── icons/          # Marker icons for categories
├── nyc-subway-routes.geojson  # Subway lines
├── nyc-subway-stops.geojson   # Subway stops

✨ Key Features
Intro overlay explaining the project
Info button toggling map navigation guide
Collapsible/expandable legend with reset option
Alphabetized categories & organizations in the legend
Responsive layout (desktop legend on side, mobile legend on bottom)
Popup details with org description, address, and links

📌 Future Improvements
✅ Category color-coding for markers
✅ Auto-collapse legend on mobile
🔄 Sync Airtable updates dynamically (without refresh)
🔎 Advanced filtering (by neighborhood, program type, etc.)
📊 Analytics integration (track usage/engagement)

👥 Contributors
Nolen Scruggs – Development & Design
Oussama Ouadani – Development & Engineering
Flushing Town Hall – Project leadership & content

📜 License
This project is licensed under the MIT License.
(c) 2024 Flushing Town Hall, Nolen Scruggs, Oussama Ouadani

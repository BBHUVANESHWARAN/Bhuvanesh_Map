**🗺️ Bhuvanesh Map App**
A user-friendly geospatial assistant built with Gradio, OpenStreetMap, and OpenRouteService, supporting:

🔍 Location search with autocomplete

📍 Real-time user location

🧭 Route generation for multiple travel modes

📊 Dynamic map visualization using Folium



**🚀 Features**

🔍 Location Autocomplete using OpenStreetMap Nominatim

📍 Live Location Detection with browser geolocation API

🗺️ Interactive Maps using Folium

🧭 Route Planner with support for:

🚗 Driving

🛵 Two-Wheelers

🚶 Walking

🚴 Cycling

⚡ OpenRouteService with travel time, distance, and speed estimates

**🛠️ Tech Stack**

Component	                    Technology
🖥️ Interface	            Gradio
🌍 Maps	                  Folium + OpenStreetMap
📍 Geocoding	              Nominatim (Geopy)
🚗 Routing	              OpenRouteService
🌐 APIs	                  Requests (HTTP)
🧠 Geolocation	          Browser (JavaScript)

**📦 Installation**

https://github.com/BBHUVANESHWARAN/Bhuvanesh_Map.git
cd Bhuvanesh_Map
pip install -r requirements.txt


**🚀 Run the App**

python app.py

**📁 File Structure**
.
├── app.py               # Main Gradio app
├── requirements.txt     # Dependencies
├── README.md            # This file
└── assets/              # Optional: place screenshots or icons here


**🔑 Notes**
✅ Make sure you have a valid OpenRouteService API Key. You can get one from: https://openrouteservice.org/dev/#/signup

🌍 Internet connection is required for geocoding and routing APIs.

🛑 Some modes like "Flights" or "Transit" are not supported by OpenRouteService and are intentionally disabled.



**🧠 Credits**

OpenStreetMap

OpenRouteService

Folium

Gradio

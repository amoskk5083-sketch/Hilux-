Nairobi Hilux Escape — Prototype 0.1
A browser-playable 3D driving prototype built with Three.js. It includes:
A drivable pickup with keyboard and touch controls
A simplified Nairobi-inspired road network with labels for CBD, Uhuru Highway, University Way, Ngong Road and Industrial Area
Moving traffic, simple police pursuit AI, a wanted meter, health, collisions and a rural escape marker
Basic villager NPCs that scatter when the player speeds nearby
Responsive layout for phones and computers
Publish on GitHub Pages
Create a GitHub repository, for example nairobi-hilux-escape.
Upload index.html and this README.md to the repository root.
Open Settings → Pages.
Under Build and deployment, choose Deploy from a branch, select main and / (root), then Save.
Wait for GitHub Pages to publish and open the URL it gives you.
Controls
W / Up arrow: accelerate
S / Down arrow: brake/reverse
A / Left arrow and D / Right arrow: steer
Space: handbrake
E: temporary boost
On phones, use the on-screen buttons.
Important map note
This first prototype is not a surveyed or GPS-accurate Nairobi map. It is a simplified, playable layout with real Nairobi corridor names and fictionalized geometry. For an accurate road network, the next step is to import OpenStreetMap road/building data for a bounded area, preserve OSM attribution, and convert it into optimized 3D geometry. The current build does not require an API key, but it does require internet access to load Three.js from jsDelivr.
Next improvements
Import a real OSM extract for the CBD and selected escape corridors
Improve road junctions, traffic lane behavior and collision boundaries
Add vehicle audio, better vehicle models, missions, save points and settings
Add optimized building/terrain assets and optional lower graphics mode

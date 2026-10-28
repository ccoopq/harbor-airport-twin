# Harbor–Airport Line Twin

Interactive demo of a simulated city-bus digital twin: six fisheye cameras (4 cabin, 2 kerb) on a
20-stop route with 64 passenger trips. The page replays the tracked camera videos, a 3D cabin view
with estimated passenger bodies, and the twin's trip and occupancy results, with a switch between a
geometric 3D lift and Meta's SAM 3D Body.

Everything shown is simulated: people are rendered avatars (Microsoft Rocketbox, MIT licence) in a
Blender scene; perception uses McByte++, RTMPose and TransReID.

Open `index.html` through any static web server (e.g. GitHub Pages); it loads its data files with `fetch`.

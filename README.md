# Tank Arena 3D V1.1 — update for existing Render deployment

Changes: walls 6.5 units high; tanks visually 30% smaller; closer/lower third-person camera; E or left mouse button shoots; shells move at 11 units/s (was 24) with a visible trail; left/right steering and turret inputs inverted as requested. No crosshair or aiming aid.

**Solo:** Friendly AI defaults to 0. Create a room with 0 friendly AI for exactly one player tank plus enemy bots. Set Friendly AI to 1 to add a teammate, or have a friend join the room code. Up to two human players per room.

**Controls:** W/S forward/back; A/D steering; Left/Right arrow rotate turret; E or left mouse shoot.

**Update:** Unzip and upload all five files to your EXISTING GitHub tank-fight-3d repository root, overwrite, commit, and wait for Render to redeploy. Keep the same Render URL.

**Notes:** Multiplayer/AI still use server-authoritative game state. This is a prototype; AI navigation and full browser gameplay need real-world testing. Requires internet for Three.js CDN.

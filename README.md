# ESCAPE — THE UNKNOWN: Four Maps Edition

Mobile-first 3D browser escape game. 4 distinct themed locations and 16 logic puzzles. Play solo against a timed simulated AI opponent, or connect to a friend using PeerJS WebRTC for race or cooperative modes.

## Start

Upload the contents of this folder (not its parent folder) to a public GitHub repository. In Settings → Pages, select Deploy from branch, main, root. Open the published HTTPS URL on Android Chrome or desktop. The app loads Three.js and PeerJS from public CDNs; internet is required. On Android use Add to Home screen.

Desktop: WASD to move, mouse to look, E to interact. Android: left joystick to move, drag on right to look, AKCIJA to interact.

## Multiplayer

Host chooses coop or race. Copy the room URL from the top status/hint and share it; guest joins. PeerJS uses an external signaling service and WebRTC; NAT/firewall restrictions can prevent connections. In coop, solved puzzles are shared, and the host/guest advance together if each crosses the door after the required puzzles. In race, each solves independently. No persistence or matchmaking.

## Limitations

This is a playable multi-map release, not a commercial AAA production. Art is procedural geometry, AI is simulated progression (not a reasoning agent), and multiplayer has not been validated across real devices. No Play Store APK is included; the Android delivery is a browser/PWA-style installation. Some network situations may require a TURN server and backend for reliable multiplayer.

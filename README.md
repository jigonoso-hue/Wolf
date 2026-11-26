# Wolf 🐺

A mobile-first, multiplayer social-deduction card game (One Night Werewolf style) in a single `index.html`.

- Pick **English** or **Español** on first open (changeable in ⚙ Settings).
- One player creates a room and shares the 4-letter code / invite link / QR; 3–10 players join.
- Phones talk to each other peer-to-peer (WebRTC via PeerJS) – no server to run. Host the file on any static host (e.g. GitHub Pages) over HTTPS.
- Night: only the players whose turn it is get a **vibration** + "open your eyes" screen. Everyone else sees an identical sleep screen.
- Roles: Wolf, Minion, Seer, Robber, Troublemaker, Drunk, Insomniac, Hunter, Tanner, Villager – each shows its own rules.
- Mobile features: vibration, optional sounds, screen wake-lock, tap-to-reveal role, native share sheet, reconnect after a dropped connection.

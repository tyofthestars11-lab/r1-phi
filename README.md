# Phi Engine — Rabbit R1 creation

Live: https://tyofthestars11-lab.github.io/r1-phi/?v=1
Install: https://tyofthestars11-lab.github.io/r1-phi/install.html

240x282, static HTML/CSS/JS, no backend, no WebSockets, no native calls.
- phi = 1.618033988749895, check phi^2 == phi + 1
- Scroll wheel steps rung n (phi^n), side button / Reset resets to n=0
- GoldenLoc(i): angle = i * 137.5077640500378 degrees, radius = Spacing * sqrt(i)
- Storage: window.creationStorage.plain.setItem / getItem, fallback localStorage, guarded
- Install: R1 creations card -> add via QR code -> scan install.html QR
- Updates: bump ?v=2 and rescan

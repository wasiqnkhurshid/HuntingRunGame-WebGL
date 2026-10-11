# Hunting Run — Gameplay Update10

[Play in your phone or desktop browser](https://wasiqnkhurshid.github.io/HuntingRunGame-WebGL/)

32 m/s / 90 seconds, Closer camera, Hunter V3 Prototype04 and Jungle Prototype06. Swipe to move/jump/duck; tap Shoot. Held gestures recognize deliberate turns and short reversals without requiring lift. Shooting retains finite arrows and its 2.2-second cooldown. A contact beginning on Shoot stays UI-owned; a separate movement finger can swipe while Shoot is held.

Source: `195e0da36b35a74d9995e85ecdc65581470de227`. Build: `gameplay10` (Unity 6000.6.0f1 / URP / WebGL). This repository contains compiled files only. Desktop Chrome synthesized touch and Unity simulation passed; physical Android/iPhone feel, Safari and sustained mobile performance remain unverified. WebGL haptics remain unavailable.

Keyboard: A/D or arrows move, W/Space jumps, S ducks, Enter shoots, Escape pauses. Existing saves and reset functionality remain available. Previous checkpoints/history are preserved.

## Rollback

Restore tag `pre-gameplay10-b101532` into a new commit on main and push. This restores Gameplay09 without rewriting history or changing hosting configuration. Previous source is `665acb5546b4d738af49535e3b271b05952262ea` (implementation `e587a92689d62436558be77ce2ac2c6dd401ec0f`).

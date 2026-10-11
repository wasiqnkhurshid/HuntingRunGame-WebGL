# Hunting Run — Gameplay Update11

[Play in your phone or desktop browser](https://wasiqnkhurshid.github.io/HuntingRunGame-WebGL/)

32 m/s / 90 seconds, Closer camera, Hunter V3 Prototype04 and Jungle Prototype06. Swipe anywhere on the playfield, including Shoot, to move/jump/duck. Tap Shoot to fire once on release. Reaching the 18 dp displacement threshold cancels the tap; all four swipe directions use the shared recognizer. Each finger retains independent gesture state. Holding never auto-repeats. Shooting retains finite arrows and its 2.2-second cooldown.

Source: `273bc64458aa39bbf73aa8285a017e340df4cbf6`. Build: `gameplay11` (Unity 6000.6.0f1 / URP / WebGL). This repository contains compiled files only. Desktop Chrome synthesized touch and Unity simulation passed; physical Android/iPhone feel, Safari and sustained mobile performance remain unverified. WebGL haptics remain unavailable.

Keyboard: A/D or arrows move, W/Space jumps, S ducks, Enter shoots, Escape pauses. Existing saves and reset functionality remain available. Previous checkpoints/history are preserved.

## Rollback

Restore tag `pre-gameplay11-2704d61` into a new commit on main and push. This restores Gameplay10 without rewriting history or changing hosting configuration. Previous source is `a42096cdeba9ebaee5e065374627b70ed067a00c` (implementation `195e0da36b35a74d9995e85ecdc65581470de227`).

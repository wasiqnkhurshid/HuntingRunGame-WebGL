# Hunting Run — Gameplay Update12

[Play in your phone or desktop browser](https://wasiqnkhurshid.github.io/HuntingRunGame-WebGL/)

84 dp Shoot face and touch target (1.5x previous dimensions), unchanged center. 32 m/s / 90 seconds, Closer camera, Hunter V3 Prototype04 and Jungle Prototype06. Swipe anywhere on the playfield, including Shoot, to move/jump/duck. Tap Shoot to fire once on release. Reaching the 18 dp displacement threshold cancels the tap; all four swipe directions use the shared recognizer. Each finger retains independent gesture state. Holding never auto-repeats. Shooting retains finite arrows and its 2.2-second cooldown.

Source: `2a9ddae422f0b70d7988e4c669847a5f34e89664`. Build: `gameplay12` (Unity 6000.6.0f1 / URP / WebGL). This repository contains compiled files only. Desktop Chrome synthesized touch and Unity simulation passed; physical Android/iPhone feel, Safari and sustained mobile performance remain unverified. WebGL haptics remain unavailable.

Keyboard: A/D or arrows move, W/Space jumps, S ducks, Enter shoots, Escape pauses. Existing saves and reset functionality remain available. Previous checkpoints/history are preserved.

## Rollback

Restore tag `pre-gameplay12-93b2bd9` into a new commit on main and push. This restores Gameplay11 without rewriting history or changing hosting configuration. Previous source is `7fa1dc8e483247e34b34351c933a03c8ba5946d7` (implementation `273bc64458aa39bbf73aa8285a017e340df4cbf6`).

# DUMMIES — Prototype 6.5

**27 October 2026 · Lawrence Lek** · ELVTR Multi-Agent, Submission 5. Spec: GDD Edit 75.

- **Play:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/
- **Control test:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/controls/
- Plain web pages: gamepads, touch and keys all work. Claude's hosted preview blocks gamepads.
- **Source:** [lawrencelek/ELVTR-dummies-agent-crew](https://github.com/lawrencelek/ELVTR-dummies-agent-crew/tree/assignment4/content-pipeline/prototypes/p6), commit `8828b4f`.

## Files

- `index.html`: the game. Three districts: Parkland, Waterfront, Monument. One file; no server.
- `controls/index.html`: the control test yard. Pads, touch, keys; three turn models.

## Controls

| | Keys | Gamepad | Touch (landscape) | Unlocked by |
|---|---|---|---|---|
| Move | WASD / arrows | stick or d-pad | analog stick, left | — |
| Dash | SPACE or K | A (or RT) | A | start |
| Jump | L or SHIFT | B | B | Jump (Legs) |
| Grab / place | J or E | X | X | Carry (Arms) |
| Throw | I or Q | Y | Y | Throw (Arms) |
| Pause | ESC or P | START | ❚❚ chip | — |
| Pad setup | G | hold START | — | — |

- Press any button on a gamepad first: browsers list a pad only after a press.
- Pad without a standard mapping: press G, then DASH, JUMP, GRAB, THROW in turn.
- Upgrades come from the shop after each write-off. Tuning (T, desktop) installs them for a test run.
- iPhone Safari reads Xbox, PlayStation and MFi pads. Android Chrome reads most Bluetooth and USB pads.

## What 6.5 adds

- DIRECT turning: the dummy faces and dashes where you point.
- B jumps over cars and pieces tagged `jumpable`; off a rail, onto the traffic below.
- Combo: hits within 1.5 s chain ×1.5, ×2, up to ×3.
- Ricochet: twice the bounce off a hit.

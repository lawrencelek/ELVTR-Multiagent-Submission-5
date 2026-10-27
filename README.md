# DUMMIES — Prototype 6.6

**27 October 2026 · Lawrence Lek** · ELVTR Multi-Agent, Submission 5. Spec: GDD Edit 76.

- **Play:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/
- **Jump test:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/jump/
- **Control test:** https://lawrencelek.github.io/ELVTR-Multiagent-Submission-5/controls/
- Plain web pages: gamepads, touch and keys all work. Claude's hosted preview blocks gamepads.
- **Source:** [lawrencelek/ELVTR-dummies-agent-crew](https://github.com/lawrencelek/ELVTR-dummies-agent-crew/tree/assignment4/content-pipeline/prototypes), `p6/`, `jump/`, `controls/`.

## Files

- `index.html`: the game. Three districts: Parkland, Waterfront, Monument. One file; no server.
- `jump/index.html`: the jump test yard. Moving traffic, parked cars, barriers, a ruler, a side view of each jump.
- `controls/index.html`: the control test yard. Pads, touch, keys; three turn models.

## Controls

| | Keys | Gamepad | Touch (phones and tablets, landscape) | Unlocked by |
|---|---|---|---|---|
| Move | WASD / arrows | stick or d-pad | analog stick, left | — |
| Dash | SPACE or K | A (or RT) | A | start |
| Jump | L or SHIFT | B | B | Jump (Legs) |
| Grab / place | J or E | X | X | Carry (Arms) |
| Throw | I or Q | Y | Y | Throw (Arms) |
| Pause | ESC or P | START | ❚❚ PAUSE | — |
| Pad setup | G | hold START | — | — |

- Touch controls show only on touch screens. Add `#touch` to the address to force them.
- Press any button on a gamepad first: browsers list a pad only after a press.
- Pad without a standard mapping: press G, then DASH, JUMP, GRAB, THROW in turn.
- Upgrades come from the shop after each write-off. Tuning (T, desktop) installs them for a test run.

## What 6.6 adds

- The screen fills the window at any scale, not only ×2 or ×3.
- Touch controls only on phones and tablets, drawn in the HUD's glass style.
- The jump keeps its take-off speed (Link's Awakening): standing 0, walking 41, running 81. B during a dash: a long jump, 162.
- A running jump clears a sedan broadside; a dash jump clears a van. A bus: never.
- Fixed: the dummy froze dashing past a stair head onto a walkway (Monument B2).

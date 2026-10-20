# Room Zero — first physical pilot

**Status:** Printable, independently checked, **not yet blind-playtested**. Intended 10–15 minutes, one Escape Team-compatible five-digit checkpoint, not a full five-phase mission.

## Files

- `House_That_Wasnt_There_Player_Packet.pdf`: three-page player packet, delivered in the ChatGPT project conversation, not yet committed here.
- `House_That_Wasnt_There_Facilitator_Only.pdf`: separate spoiler-containing facilitator guide and progressive hints, delivered in the conversation. Do **not** open before trying the puzzle.
- `build.py`: editable ReportLab source delivered in the conversation.
- [`verifier.html`](verifier.html): standalone, offline code checker. Download the HTML and open it in a browser. Not the official app.

## How to test

1. Print the player packet on US Letter at **100% / Actual Size**, with identical print settings across all three pages.
2. Read page 1. Cut the stencil and its five interior windows from page 3, using a craft knife or careful scissor cuts.
3. Put the stencil over the printed plan on page 2. The registration and code are both discovered through physical positioning.
4. Enter the five-digit result into the standalone verifier, or have a facilitator check it privately.
5. Note the elapsed time, the moment the fragment made sense, any false starts, how many people contributed, and whether the narrative discovery felt earned.

## Validation

- Source grid: **6 columns x 5 rows**, each bay 70 PDF points square.
- Paper overlay: **3 x 3 bays**, each 70 points square, with five 40-point square windows.
- Registration has **one** possible location/orientation when both named original fixtures agree. A finite enumeration of all four rotations and legal translations passed.
- Digital reconstruction of a cut stencil over the plan was visually checked. It exposes the five intended digits and places the room annotation over the official infill foundation bay.
- PDF pages were rendered and inspected, but **real-world print/cut and blind-user testing remain undone**.

## App integration

The pilot yields one five-digit code suitable for one of Escape Team's editor phases. No official Escape Team mission, Mission Editor entry, Escape Code, app runtime, or Android/iOS emulator test exists yet. An independent browser validator supports playtesting in the meantime.

## Next decisions

- Blind playtest the paper alignment and difficulty. A 10–15 minute duration is only a target.
- Decide whether this physical overlay idea merits expansion into a five-phase mystery, or whether the next pilot should test a different mechanism.
- If the mechanism is sound, add written reasoning evidence and stronger narrative payoff. This is deliberately an **engineering prototype**, not yet the fully compelling finished adventure.

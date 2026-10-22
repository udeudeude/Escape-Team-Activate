# No Such Room — pilot 02

**Status:** puzzle logic and print layout verified; blind playtest pending. This replaces the failed gameplay approach of [Room Zero](../house-01/README.md).

## Play packet

The **two-page player PDF**, optional **post-solve epilogue**, **separate facilitator key**, and editable **ReportLab source** were generated in the related ChatGPT project conversation. They are not yet stored as binaries in this repository. Do **not** open the key until after playing.

**No cutting is needed.** Print the two-page packet on ordinary paper, or read it on a device. Aim for a 10–15 minute first attempt, but this has not been established by user tests. Send the final five-digit result to the person facilitating or to ChatGPT to validate.

## Brief

A condemned building has three blue doors marked R, one on each floor. The official survey records no usable room beyond any of them. A missing person may still be behind one of the doors.

The player is asked to deduce a five-reading location trace from a collection of dated observations, an architectural survey, a glassmaker's invoice, and an engineering sketch.

## Deliberately revised design principles

- One *model-changing inference*, not a cut-and-match task.
- Four independent observations contribute actual constraints; with any one omitted, multiple numerical answers become valid.
- Small amount of prose; the evidence is carried by visual documents and short observations.
- No physical assembly. The next prototype may use physical manipulation again only where it is central to an inference rather than a way to expose a printed number.
- Avoid spoilers in the public README, so a player can navigate the repository before attempting the puzzle.

## Verification completed

1. A brute-force solver enumerated all three-level movement traces over five observations and found exactly one compatible trace. Dropping each of the four observation constraints produces multiple solutions.
2. The PDF is rendered and visually inspected; no clipped content or overflow.
3. The solution/hint guide is separate and the epilogue is independent.
4. The official Escape Team mobile app, timed hint system, and code submission **have not been tested**, nor has any blind participant completed this puzzle.

## How to playtest

Offer no hints unless requested. Record approximately how long the participant spends, whether they correctly infer the nature of R, whether the engineering evidence is comprehensible without prompting, and whether they feel a genuine discovery rather than a sequence of instructions.

## Project links

- [Official Escape Team mission editor](https://www.escape-team.com/create)
- [Main concept slate](../../docs/CONCEPTS.md)

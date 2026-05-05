# HackFax x PatriotHacks 2026 - Web Attack design notes

I led the Web Attack category for HackFax 2026, GMU's biggest CTF to date. Here is where I'll publish design notes for the challenges my team and I built. These are *retrospective* writeups: how the challenge was meant to be solved, what we learned about difficulty calibration, and what I would do differently.

I'll publish challenges as they come out of rotation (so future events can reuse the patterns).

## Coming soon

- "Recipe Box" - JWT none-algorithm, intended path vs. four unintended paths we caught in testing
- "Mirror Mirror" - SSRF via image-proxy + cloud metadata exfil
- "Quiet Comments" - second-order XSS in an admin moderation panel
- "Postcard Pickup" - prototype pollution in a Node middleware

## Reading the design notes

Each note has three sections:

1. **What we shipped** - the challenge as players saw it
2. **Intended path** - how the author meant it to be solved
3. **What I learned about CTF design** - calibration, hint economy, infrastructure, etc.

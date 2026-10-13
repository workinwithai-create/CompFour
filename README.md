# CompFour

Four-bar live piano chord-comp desk for bedroom producers and AI-music finishers.

Suno and loop DAWs leave the piano on a static root voicing. Session players comp so the loop finally breathes and finishes. CompFour seats live FluidR3 piano chairs on that decision: roots vs comp, then exports the WAV (and MIDI stub) that drops on bar 1 of a DAW.

Live samples only — FluidR3 acoustic grand (used as the piano chair), upright, nylon, kit from the PreEight bank pinned to commit `d58301e4a494555f411a2afbc448b724136eee76`. No oscillators. Audio never leaves the tab.

## Distinct from yesterday and the rest of the line

| Tool | Job |
| --- | --- |
| TightFour | Four-bar tight pocket with ghosts and chops |
| WalkBass | Four-bar walking bass |
| RollFour | Four-bar snare-roll and tom-fill |
| **CompFour** | Four bars of live piano chord-comp so the hook has harmonic rhythm |

Yesterday's ship was TightFour (pocket lock). CompFour is the missing harmonic motion under the loop you already have.

## Pricing recommendation

One-time **$19** on Lemon Squeezy. Mirror on Gumroad.

This is a finite desk, not a cloud meter. Do not subscribe. Forge Pass stays for the cloud tools (AuraMix, MixForge, etc.).

The shipped app is free (MIT). No license gate. A priced build would need a Lemon Squeezy key check.

## Samples

Pinned commit SHAs only.

* PreEight bank @d58301e4a494555f411a2afbc448b724136eee76

Never @main or @gh-pages.

## Export

Default bounce is 48 kHz, 24-bit stereo.

At 92 BPM and 8 bars the loop file is exactly 1,001,739 samples (`Math.round(8 * 4 * 60 / 92 * 48000)`), first downbeat at sample 0.

The offline render reuses the already-loaded ArrayBuffers. Peak ≤ −1 dBFS. Filenames: `compfour-recipe-92bpm-Aminor.wav`.

## Acceptance

(1) Export length exact. (2) Loop seamless. (3) Background tab stops cleanly. (4) Live changes apply next step. (5) Missing samples named. (6) Sustains hold. (7) No @main, no Math.random in export.

## License

MIT. workinwithai-create.

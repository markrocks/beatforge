# BeatForge — Drum Pattern Studio

A single-page, no-install drum pattern generator for home recording. Pick a style, a kit and a tempo, generate a groove, tweak it on a 16-step grid, loop it, and export it to your DAW.

## Features

- **13 style presets:** House, Deep House, Techno, Rock & Roll, Drum & Bass, Jungle (Amen-style), Boom Bap Hip-Hop, Trap, Breakbeat / Big Beat, Funk, UK Garage (2-step), Reggaeton (Dembow), Disco. Each sets its own default BPM, swing and kit.
- **Generate:** builds a main bar (A), a variation (B) and a fill bar using the style's rules plus controlled randomness, so every press gives a new take on the style.
- **5 synthesized kits:** TR-808 style, TR-909 style, Acoustic studio, Dusty breaks (lo-fi), Minimal / tight. No sample files needed.
- **12 instruments:** kick, snare, clap, rim, closed/open hat (with choke), low/mid/high tom, ride, crash, shaker. Each has mute, solo and volume.
- **Loop length:** 1, 2, 4, 8, 16 or 32 measures, with fills every 2/4/8/16 bars, optional A/B alternation, and an automatic crash on bar 1 and after fills.
- **Feel:** BPM (40–240) with tap tempo, swing (50–75%), humanize (timing and velocity).
- **Editing:** click a step to cycle normal → accent → ghost → off; shift-click or right-click clears it. Space bar plays and stops.

## Exporting to your DAW

- **Export MIDI:** a Standard MIDI File (type 0, 480 PPQ) with tempo and 4/4 time signature. Notes use the General MIDI drum map on channel 10 (kick 36, snare 38, clap 39, rim 37, closed hat 42, open hat 46, toms 45/47/50, ride 51, crash 49, shaker 70), so it drops onto any drum rack, such as Ableton Drum Rack, Logic Drummer/Drum Kit Designer, FL Studio FPC, Superior Drummer or EZdrummer. Swing is baked into the note timing.
- **Export WAV:** a 44.1 kHz / 16-bit stereo render of the full loop. Cymbal and reverb tails are folded back onto the start, so the file loops seamlessly when it's set to the exact bar length.

Files are named like `jungle-165bpm-16bars.mid`.

## Running it

Open `index.html` in any modern browser (Chrome, Edge, Firefox or Safari). Everything runs locally, and your last pattern is remembered in the browser.

To use it from any device, turn on **GitHub Pages** for this repo (Settings → Pages → Deploy from branch → `main` / root).

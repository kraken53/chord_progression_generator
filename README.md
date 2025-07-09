# 🎵 Chord Progression Generator

A simple, interactive web app to generate, play, and export chord progressions with customizable keys, scales, rhythms, and tempos — built with React and Tone.js.

## Features

- Select key (C, D, E, F, G, A, B) and scale (major/minor)
- Choose progression styles: Pop, Jazz, Lo-Fi, or Random
- Select rhythmic patterns: Straight, Swing, Syncopated
- Control tempo (40 - 240 BPM)
- Loop progressions over 4, 8, or 16 bars
- Play progression live in browser with looping
- Export progression as MIDI file
- Copy progression chord names to clipboard

## Tech Stack

- React
- Tone.js (for audio synthesis and playback)
- Vite (for development/build)
- @tonejs/midi (for MIDI export)

## How to Use

1. Choose your key, scale, style, rhythm, tempo, and loop length.
2. Click **Generate Progression** to create a chord progression.
3. Click **Play** to hear it looped.
4. Click **Stop** to stop playback.
5. Use **Copy** to copy chord names, or **Export MIDI** to download a MIDI file.


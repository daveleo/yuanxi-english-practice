---
name: Yuanxi English practice
status: maintained
priority:
version: 
deadline:
next: None
updated: 2026-10-07
repo: daveleo/yuanxi-english-practice
url: https://daveleo.github.io/yuanxi-english-practice/
---

# Yuanxi English practice

Line-by-line English presentation practice with music, translations and pronunciation audio.

## What it is for

A private practice page for a school English presentation about a song. Each presentation is spoken audio split into timed lines, with Danish and Chinese translations, so the student can listen and repeat line by line. Three songs: "I'm Yours", "Radioactive" and "Still Standing".

## How to run

- Online: https://daveleo.github.io/yuanxi-english-practice/
- Locally: the page loads its `.json` files with `fetch`, so opening `index.html` straight from disk may not work; serve the folder instead, e.g. `python -m http.server`, then open http://localhost:8000.

## How to use

1. Pick a song.
2. **▶ Play line** plays the current line; **Back** / **Next** move between lines; **↻ Line** repeats it; **⟲ Song** plays the whole presentation.
3. **Dansk** / **中文** show the translation; **Bigger text** enlarges the text; the **1×** button changes playback speed.

## What is what

- `index.html`: the practice page, including the Danish and Chinese translations of every line.
- `<song>.mp3`: the spoken presentation audio.
- `<song>.json`: the timed lines (start, end, English text) for each audio file.

## Current state

Finished (2026-08-29).

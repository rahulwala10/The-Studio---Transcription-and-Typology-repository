# The Studio Captions

**Dynamic captions for Reels, by Rahul Wala.**

Open it: **https://rahulwala10.github.io/The-Studio---Transcription-and-Typology-repository/**

How it works (where it runs, where your work is saved, and the path from your
voice to the finished video):
**https://rahulwala10.github.io/The-Studio---Transcription-and-Typology-repository/how-it-works.html**

Drop in a video and The Studio Captions writes the captions from your voice,
right in your browser. It picks the words worth lifting by itself, and styles
them with one of 47 mixed-font templates in four groups: The Studio, Cinematic,
Professional and Creative. Every word, line and colour stays editable, and the
finished Reel exports as an MP4. Your videos never leave your device.

## What's inside

- **47 house templates** with font pairings and colour presets, each built to
  the same reading rules: text 3.7 to 5.4% of the frame height, at most two
  lines, one stand-out word per caption, and at least 7:1 contrast for text on
  video (checked by script for every colour pair).
- **Automatic stand-out words.** The punch word of each phrase, names and
  numbers are picked offline, right after transcription, and can be changed
  word by word.
- **Captions that read naturally.** They are cut at sentence ends, commas and
  pauses, never straight after "a", "the" or "to", and split evenly instead
  of leaving one word alone.
- **Captions that keep time with the voice.** A small timing lead makes each
  word light up as it is said.
- **A Reels safe-zone guide** in the editor that shades what Instagram covers.
- **Free and private.** Transcription (Whisper) and export both run in the
  browser.

## Releases

Each release has a Windows package for the laptop under `releases/`:

- `releases/v1.1/` adds 20 templates (Cinematic, Professional and Creative),
  re-tuned colours on the first 27, the new home page, the How it works page,
  the safe-zone guide and an edge-contrast control.
- `releases/v1.0/` is the first release.

## Inspired by tscaps

The Studio Captions is built on [tscaps](https://github.com/francozanardi/tscaps),
the open-source caption editor by Franco Zanardi. Its engine and templates are
MIT-licensed (`LICENSE-engine-MIT.txt`), and its editor app is AGPL-3.0
(`LICENSE-editor-AGPL-3.0.txt`). As the AGPL asks, the full source of this
version is here, in `source/the-studio-captions-source.zip`.

This repository holds the built site that GitHub Pages serves, plus the
source and the Windows laptop package for each release under `releases/`.

# Helldivers2 Stratagems Online Practice Game

[中文说明](README.zh-CN.md)

A single-file web practice game for training reaction speed and accuracy with stratagem-style directional inputs inspired by *Helldivers 2*.

The current version includes bilingual Chinese and English stratagem names, real directional input codes, category filtering, and stratagem icon display.

## Online Play

After the repository is published through GitHub Pages, the entry file is:

```text
index.html
```

You can also open `index.html` locally in a browser.

## Project Files

- `index.html`: the complete game page, including styles and interaction logic.
- `Original Soundtrack/Helldivers II Original Soundtrack (2024)`: the local MP3 directory used by the hidden local music player code. This directory is not committed to GitHub; only provide audio files locally or when you have permission to publish them.

## Difficulty Levels

- Easy: only draws stratagems with input sequences of 4 directions or fewer. Score multiplier: 1x.
- Standard: only draws stratagems with input sequences of 5 directions or fewer. Score multiplier: 1.35x.
- Helldive: no input-length limit. Every stratagem can appear. Score multiplier: 1.8x.

Difficulty does not change the countdown speed. It mainly changes the eligible stratagem pool and the score multiplier after each completion.

## Data Sources

- English names, directional codes, and stratagem icons: [Helldivers Wiki - Stratagems](https://helldivers.wiki.gg/wiki/Stratagems)
- Default training icon: [Helldivers Wiki - Images - Helldivers 2 - Logo](https://helldivers.wiki.gg/wiki/Category:Images_-_Helldivers_2_-_Logo)
- Chinese names: based on a [Bilibili translated reference image](https://www.bilibili.com/opus/919091931569455128), with additional entries completed manually

The icons are loaded through public wiki image links, so the browser needs internet access to display them. When reusing wiki-hosted files outside the wiki, please attribute the retrieval to the uploader and to the Helldivers Wiki.gg.

## Disclaimer

This is an unofficial fan-made practice project for learning, practice, and personal entertainment. It is not affiliated with, endorsed by, sponsored by, or authorized by Arrowhead Game Studios, Sony Interactive Entertainment, or PlayStation.

This repository does not commit or host *Helldivers 2* original soundtrack files. Local music-player code is preserved in the source, but the player interface is hidden by default on the public page.

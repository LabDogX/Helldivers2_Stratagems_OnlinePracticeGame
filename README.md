# Helldivers2 Stratagems Online Practice Game

[中文说明](README.zh-CN.md)

A browser-based stratagem input trainer inspired by *Helldivers 2*. The project is designed as a lightweight, static web app for practicing directional command sequences with bilingual stratagem names, real input codes, category filters, and wiki-hosted stratagem icons.

## Live Demo

Play online through GitHub Pages:

[https://labdogx.github.io/Helldivers2_Stratagems_OnlinePracticeGame/](https://labdogx.github.io/Helldivers2_Stratagems_OnlinePracticeGame/)

## Features

- Bilingual stratagem display with Chinese and English names.
- Directional input sequences matched to each stratagem.
- Category filtering for focused practice sessions.
- Three difficulty levels based on sequence length and score multiplier.
- Timed sprint and endless practice modes.
- Keyboard and on-screen directional input support.
- Recent-result history with completion time and score gain.
- Static single-page implementation with no build step required.

## Running Locally

Clone the repository and open `index.html` in a browser. No package manager, backend service, or build pipeline is required.

```text
index.html
```

## Repository Structure

- `index.html`: complete game page, including markup, styles, data, and interaction logic.
- `README.md`: English project documentation.
- `README.zh-CN.md`: Chinese project documentation.
- `音乐播放器图标/`: UI icon assets retained for the dormant local music-player module.
- `Original Soundtrack/`: optional local-only soundtrack directory ignored by Git.

## Asset Policy

The public repository does not host *Helldivers 2* soundtrack files. The optional local music-player module remains in the source code for local experimentation, but its interface is hidden in the public page and the soundtrack directory is excluded from version control.

Stratagem icons and the default training icon are loaded from public Helldivers Wiki image URLs at runtime. They are not bundled as local assets in this repository.

## Difficulty Levels

- Easy: draws stratagems with input sequences of 4 directions or fewer. Score multiplier: 1x.
- Standard: draws stratagems with input sequences of 5 directions or fewer. Score multiplier: 1.35x.
- Helldive: includes the full stratagem pool with no sequence-length limit. Score multiplier: 1.8x.

Difficulty does not change the countdown speed. It mainly changes the eligible stratagem pool and the score multiplier after each completion.

## Data Sources

- English names, directional codes, and stratagem icons: [Helldivers Wiki - Stratagems](https://helldivers.wiki.gg/wiki/Stratagems)
- Default training icon: [Helldivers Wiki - Images - Helldivers 2 - Logo](https://helldivers.wiki.gg/wiki/Category:Images_-_Helldivers_2_-_Logo)
- Chinese names: based on a [Bilibili translated reference image](https://www.bilibili.com/opus/919091931569455128), with additional entries completed manually

The icons are loaded through public wiki image links, so the browser needs internet access to display them. When reusing wiki-hosted files outside the wiki, please attribute the retrieval to the uploader and to the Helldivers Wiki.gg.

## Disclaimer

This is an unofficial fan-made practice project. It is not affiliated with, endorsed by, sponsored by, or authorized by Arrowhead Game Studios, Sony Interactive Entertainment, or PlayStation. *Helldivers* and related names, marks, images, and game assets belong to their respective owners.

# MangaVoice

**A free manga reader for Windows, built first for blind and visually
impaired readers.** MangaVoice works with the NVDA screen reader, and it can
narrate manga pages aloud like an audiobook, using an AI model that runs on
your own computer.

## [Download the latest version](https://github.com/swarup-developer/mangavoice-releases/releases/latest)

On the download page, choose one of the two files:

| File | For |
| --- | --- |
| **MangaVoice-Setup-x.y.z.exe** | Most people. Run it and choose Install. It installs for your Windows account only (no administrator rights needed), adds a Start menu shortcut and updates itself. Remove it in Windows Settings, Apps. |
| **MangaVoice-Portable-x.y.z.exe** | Running without installing, for example from a USB drive. It keeps its data in a `MangaVoiceData` folder beside it. |

Requires Windows 10 or 11, 64-bit.

The programs are not code-signed yet, so the first time you run one, Windows
SmartScreen may say it protected your PC: choose **More info**, then
**Run anyway**. Each file has a `.sha256` checksum beside it.

## What it does

- **Narrates manga pages.** Press Ctrl+E and MangaVoice tells what happens on
  the page, who is there and what they say, like an audiobook. Speech starts
  while the rest is still being written, and continues as you turn pages.
- **Reads the text aloud.** Ctrl+T reads the speech bubbles, captions and
  sound effects in reading order (right to left for manga).
- **Private.** Pages are read by a vision model in [Ollama](https://ollama.com)
  on your own computer. Nothing is sent to the internet, and there is no
  telemetry.
- **Natural voice.** An optional offline neural voice (Kokoro, 11 English
  voices), or the Windows voice.
- **Your library.** Import folders of images and CBZ/ZIP archives. Progress,
  bookmarks, favourites, history and statistics are kept for you.
- **Keyboard first.** Every action has a shortcut, and every shortcut can be
  changed. Standard Windows controls throughout.
- **A clean reader.** Single page, double page or continuous scrolling; right
  to left or left to right; zoom, fit and full screen.

## Getting started

1. Install MangaVoice and open it from the Start menu.
2. Press **Ctrl+O** to import a folder of manga, or **Ctrl+Shift+O** for CBZ
   or ZIP files.
3. Open a chapter. **Page Down** turns the page and **Escape** closes the reader.
4. For narration and reading aloud, install [Ollama](https://ollama.com), then
   in MangaVoice open Settings (**Ctrl+Comma**), Vision AI, download a
   suggested model and choose it.

Press **F1** in MangaVoice for the full guide and every keyboard shortcut.

## Feedback

Report problems or ideas in
[Issues](https://github.com/swarup-developer/mangavoice-releases/issues).

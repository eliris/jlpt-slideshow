# JLPT Ambient

A lightweight, zero-dependency passive vocabulary slideshow for JLPT N5–N1. Designed to run fullscreen as an ambient study display while eating, listening to music, or working.

**Live Demo:** [https://<your-username>.github.io/jlpt-ambient/](http://eliris.github.io/jlpt-slideshow/)

## Features
- **Hands-Free Slideshow:** Smooth progress bar with configurable 5s–20s intervals and auto-hiding HUD/cursor after 3.5 seconds of inactivity.
- **Multi-Level Filtering:** Mix and match JLPT N1 through N5 decks on the fly.
- **Kanji Breakdown & Furigana:** Displays individual kanji readings and meanings beneath each word, plus adjustable sentence furigana sizing (`S` / `M` / `L`).
- **Active Recall Blur Mode:** Blur English definitions and translations (`M`) and hover to peek.
- **Offline Resilient:** Boots instantly with built-in curated cards and fetches full community datasets in the background.

## Keyboard Shortcuts
| Key | Action |
| :--- | :--- |
| `Space` | Play / Pause |
| `←` / `→` | Previous / Next card |
| `R` | Toggle word furigana reading |
| `K` | Toggle individual kanji breakdown |
| `M` | Toggle meaning blur mode |
| `F` | Toggle fullscreen |
| `?` | Open info & shortcuts overlay |

## Data Sources
- Vocabulary & example sentences via [OpenJLPT](https://github.com/evanclan/OpenJLPT) (JMdict & Tatoeba)
- Individual kanji readings & meanings via [kanjiapi.dev](https://kanjiapi.dev/)

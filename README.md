# JLPT Slideshow

A lightweight, zero-dependency passive vocabulary slideshow for JLPT N5 - N1 designed to run fullscreen for passive studying while eating or doing something else.

**Live Demo:** [https://eliris.github.io/jlpt-slideshow/](https://eliris.github.io/jlpt-slideshow/)

## Features
- **Hands-Free Slideshow:** Configurable 5s - 20s intervals and auto-hiding the HUD/cursor after 3.5 seconds of inactivity.
- **Multiple JLPT Level Filtering:** Mix and match JLPT N1 through N5 decks.
- **Kanji Breakdown & Furigana:** Displays individual kanji readings and meanings under each word. Furigana can also be resized. (`S` / `M` / `L`).
- **Blur Mode:** Blur English definitions and translations (`M`) and hover to peek.
- **Mostly Offline:** Boots instantly with built-in cards and fetches full community datasets in the background.

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
- Vocabulary & example sentences using [OpenJLPT](https://github.com/evanclan/OpenJLPT) (JMdict & Tatoeba)
- Individual kanji readings & meanings using [kanjiapi.dev](https://kanjiapi.dev/)

# Astrology Library

A small, source-checked knowledge library for psychological astrology and Uranian (Hamburg School) astrology, written in plain English for readers who are interested in astrology without being specialists.

It exists so that an AI agent (or a human) can ground a horoscope reading in stated sources instead of improvising from vague memory. Every file names its sources, and SOURCES.md records what may be reused and how — public-domain texts are summarised freely, copyrighted works are linked or restated as ideas only, and material whose rights status could not be verified is excluded rather than guessed at.

## Contents

Psychological astrology:
- [psychological/framework.md](psychological/framework.md) — how a reading is built: planet = function, sign = style, house = arena, aspect = conversation
- [psychological/planets.md](psychological/planets.md) — the ten planets as psychological functions (role names from Alan Leo, public domain)
- [psychological/signs.md](psychological/signs.md) — the twelve signs, with Leo's keywords and Sepharial's classifications
- [psychological/houses.md](psychological/houses.md) — the twelve houses (Sepharial, 1920)
- [psychological/aspects.md](psychological/aspects.md) — the aspects, their natures and weighting
- [psychological/elements-and-modes.md](psychological/elements-and-modes.md) — elements, modes (with a quotable public-domain passage) and the dignity vocabulary
- [psychological/transits-and-lunation.md](psychological/transits-and-lunation.md) — how transits are read (Leo, 1906) and the eight lunation phases

Uranian astrology:
- [uranian/tnp8.md](uranian/tnp8.md) — the eight Trans-Neptunian Points, summarised from Arlene Kramer's delineations
- [uranian/midpoints.md](uranian/midpoints.md) — midpoints, the 90° dial, personal points, planetary pictures
- [uranian/glossary.md](uranian/glossary.md) — terminology traps, including the Japanese "trans-Saturnian" collision

## Companion skill

The library is the knowledge half of the **muse-horoscope** skill (calculation with openephem/ephemvis, vertical reading cards, and a daily fortune), developed alongside it: https://github.com/kgmkm/muse-horoscope

## Ground rules

- Light-touch entertainment framing: readings describe tendencies and themes, never verdicts.
- No copied text from rights-reserved sources. Summaries are original wording; short factual items (angles, periods, rulers) are facts.
- Contributions must add their sources to SOURCES.md with a verdict before adding content. See CONTRIBUTING.md.

## Licence

Original text in this repository is released under CC BY 4.0 (see LICENSE.md). Underlying public-domain sources remain public domain. Nothing in this repository is a redistribution of the copyrighted works listed as link-only or summary-only in SOURCES.md.

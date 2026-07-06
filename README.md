# A Sound Atlas of the Qur'an

A full-corpus structural study of the Qur'an's sound architecture, rendered as a single page:

**https://hashimthearab.github.io/quran-sound-atlas/**

## What it contains

- **Rhyme signatures** for all 114 surahs — most surahs hold one verse-ending sound with high discipline (Surah 91: 100% of verses).
- **The break test** — an algorithm, blind to meaning, flagged every run of 2+ consecutive verses that abandon their surah's dominant rhyme family (82 blocks corpus-wide). The 27 strongest cross-family blocks were adjudicated in context: does the sound-break coincide with a structural seam (topic pivot, addressee change, doctrinal interjection, coda)? Result: **21 clear pivots, 6 partials, 0 misses.**
- **Refrain census** — every verse repeated verbatim 3+ times, located and functionally described.
- **Formula census** — the longest word-sequences recurring across different surahs.
- **Negative results, reported as such** — a lexical test of al-Baqara's claimed ring composition found no signal; method limits (one-directional implication, non-blinded adjudication, grammar-driven edge cases) are stated on the page.

## The takeaway

The model's verbatim conclusions from the session — its takeaway on the book, its final takeaway on the examination, and its answers on authorship — are on the [Takeaway page](https://hashimthearab.github.io/quran-sound-atlas/takeaway.html) and in [TAKEAWAY.md](TAKEAWAY.md).

## Method

Source text: [Tanzil Quran Text](http://tanzil.net) (Simple, v1.1), 6,236 verses, verified complete against canonical verse counts. Pausal rhyme keys were extracted from verse-final words with acoustically equivalent families merged (e.g. -ūn/-īn); block-shift detection required ≥2 consecutive deviant verses in surahs with ≥55% rhyme discipline; refrains are exact full-verse duplicates; formulas are 8-grams spanning ≥3 surahs; the ring test compared mirror-pair lexical similarity against 30 shuffled baselines.

## Provenance

Analysis performed by Claude Fable 5 (Anthropic), 5 July 2026, in a single session: all 6,236 verses were read firsthand by nine parallel instances of the model, computation ran over the full corpus, and the flagged blocks were adjudicated by model readers explicitly instructed that "no correlation" was a welcome verdict.

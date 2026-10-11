# Türkçe Practice

A single-file, fully offline Turkish practice app for A1–A2 learners:
grammar reference, grammar drills, and vocabulary flashcards with
self-graded statistics and a research-informed "Smart" practice queue.

**[Try it live](https://rodolfohermans.github.io/turkish-practice/)** or
download `index.html` and open it in any browser on Windows, macOS,
Linux, Android or iOS. No install and no build step either way -
**everything is in that one file.**

See [`about.html`](about.html) for how this was built and a privacy
audit backed by evidence.

## Private and offline by design

The app runs entirely on your device. It needs no internet connection,
sets no cookies, contains no trackers, analytics or ads, and never sends
anything anywhere. Some example sentences come from the Tatoeba project
(tatoeba.org), used under the CC-BY 2.0 FR license. Progress is stored
in the browser's localStorage on the device you practice on. AI tools
were used to build it (Anthropic Claude, with review passes by other
models); the app itself contains no AI and makes no network requests.

## Features

- **Grammar reference**: 19 collapsible sections: alphabet, vowel harmony,
  cases, to-be, possession, var/yok, plurals, the five tenses (each fully
  explained with conjugation tables), can/must/let's/if, passive, numbers
  and time, comparison, the -an participle.
- **Grammar drills**: prompt→answer cards across 22 topics, answerable
  as classic reveal cards or in **Build mode**: assemble the answer from
  morpheme/word tiles (with one wrong-harmony or wrong-person lure mixed
  in); correct builds grade objectively.
- **Vocabulary**: core words, fixed expressions, and the most frequent
  book words, each with an idiomatic example sentence. Practice
  Turkish→English, English→Turkish, or mixed; answer by reveal, multiple
  choice, fill-the-blank cloze inside the card's own example, or a timed
  speed round over already-learned words. New words are sometimes
  introduced by exclusion: match four known pairs and deduce the fifth.
- **Self-grading**: reveal, then "I know it strongly / I guessed /
  I don't know" (keyboard: Space, then 1/2/3). Per-card history persists.
- **Smart mode**: one round mixes relearn + edge + new + mastered-review
  cards. Misses lead; new words are introduced in the order the
  textbooks teach them (frequency-weighted, common daily words first).
  In every deck a strong answer retires the card from the current pile,
  so progress is always visible.
- **Levels**: content unlocks in 8 curriculum-ordered levels as you
  practice (60% of the current level's words answered correctly opens the
  next). Fully overridable: per-level lock/unlock in any order, unlock
  everything, or turn levels off (Help tab).
- **Data tab**: export/import your progress as JSON (merging keeps the
  richer record and never demotes streaks), plus a confirmed full reset.

## License

GPL-3.0 - see [LICENSE](LICENSE). No tracking, no ads, lightweight: a
standing commitment, see [POLICY.md](POLICY.md).

## Support

This is a free, ad-free, tracker-free project. If it's useful to you,
a voluntary tip is welcome but never required: [Ko-fi](https://ko-fi.com/rhermans).

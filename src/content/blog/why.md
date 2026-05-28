---
title: "Why I'm building Yomimono"
draft: true
description: "An introduction to what I'm making and why."
pubDate: 'May 28 2026'
---

## A confession from a Japanese learner

I've been studying Japanese for a while now. Long enough to have lived through the predictable arc of every adult learner: the early thrill of hiragana, the slow-burn satisfaction of the first hundred kanji, the dawning realization that the textbook is the easy part. The hard part is everything that comes after a chapter — when you close the book and try to actually *read* something.

Because here's what happens. You finish chapter 6 of Genki I. You've learned about thirty new words. You feel pretty good. You go online to find something to read at your level, and you discover one of two things:

The text you found is graded for "beginners" — which turns out to mean someone three chapters ahead of you, with grammar you haven't seen and vocabulary you don't recognize. Within a paragraph you've stopped reading and started decoding. Every other word is a dictionary lookup. Comprehension dies. The reading session becomes an act of will, not pleasure, and you put it down feeling like you've been doing taxes.

Or — the text is genuinely at your level, and it's about *Tanaka-san going to the post office*. Again. For the seventeenth time. You can read every word, but there is nothing here you actually want to know. Your eyes glaze over halfway through. You close the tab.

This is the gap Yomimono exists to close.

## The problem

Early-stage Japanese learners — let's say roughly JLPT N5 to N4, the first year or two of serious study — have access to a lot of *instructional* material and almost no *reading* material that actually fits them. The textbook teaches you the language; nothing teaches you how to live in it.

The deeper issue is structural. To produce reading material that genuinely fits a beginner, someone has to know:

- exactly which words and grammar points the learner has seen,
- exactly which they're confident on,
- and exactly how to write something interesting using *only* those building blocks plus a small, carefully-chosen handful of new ones.

Human authors of graded readers do this heroically, but they do it once, for an imagined average learner. They can't do it for *you*, on Tuesday, after you've finished chapter 8 but skipped two of the kanji and just learned three new words from a podcast.

This is the kind of problem that, until recently, didn't have an answer. It does now.

## The science we're standing on

We didn't invent the idea that beginner learners need calibrated input. The science here is decades old, and it's surprisingly clear about what works. There are three threads worth knowing about.

**Comprehensible input.** In the early 1980s, Stephen Krashen proposed what he called the *Input Hypothesis* — the claim that language acquisition happens when learners are exposed to input slightly beyond their current level, which he notated as *i+1*. The idea has been picked apart, refined, and sometimes contested in the forty years since, but the core intuition has held up remarkably well: you learn a language by understanding things that are *almost* within reach, not by drilling things you already know or wrestling with things you don't.

**Lexical coverage.** Krashen's *i+1* was conceptually appealing but operationally vague. How much above your level is "a little"? In 2000, Marcella Hu and Paul Nation gave the field a number. Their study, and the studies that followed it, found that learners need to know roughly **95% of the words in a text for adequate comprehension, and around 98% for unassisted reading**. Below 90%, comprehension collapses. The exact thresholds have been debated and refined, but the shape of the curve is uncontroversial: a small percentage of unknown words is a learning opportunity, a larger one is a wall.

**Extensive reading.** The pedagogical movement built on these foundations is called *extensive reading* (in Japanese-learning circles, *tadoku*, 多読 — "much reading"). The principle is to read large volumes of texts you can mostly understand, without stopping to translate, without grinding through every unknown word. A 2015 meta-analysis by Takayuki Nakanishi pooled 34 studies and found consistent positive effects on reading comprehension, vocabulary, and writing — with the strongest gains when the texts were genuinely matched to the learner.

The throughline across all three is the same: **you don't get better at reading by reading hard things badly. You get better by reading appropriate things well, and a lot of them.**

This is what "extensive reading works" means in practice. It is also what, until very recently, almost no language-learning product actually delivered to early-stage learners — because producing endless calibrated material at the right level for each individual was simply not economically possible.

## Immersion friction

Here's how I've come to think about it.

Every time you stop mid-sentence to look up a word, your reading flow breaks. Every time you re-read a paragraph because the grammar surprised you, your immersion breaks. Every time you put the book down feeling like a failure, your motivation breaks. None of these breaks is fatal on its own. But cumulatively, across days and weeks, they're the reason most adult learners' reading practice quietly dies.

I call this **immersion friction**: the gap between the learner's current state and the text in front of them, expressed as cognitive cost.

The science above tells us, in three different vocabularies, the same thing: **the work of language learning is to systematically reduce immersion friction while still leaving something to learn.** Krashen calls it *i+1*. Hu and Nation call it 98% coverage. The tadoku movement calls it the four golden rules. They are all, fundamentally, descriptions of the same target zone — comprehensible-but-not-trivial — and the same failure mode, which is missing it.

The thing they don't tell you is how to actually hit it for an individual learner, every day, for the months and years it takes to get good.

## What Yomimono is

Yomimono is a textbook companion. You tell it which textbook you're using and which chapter you're on. From that, it knows — to a first approximation — every word, kanji, and grammar point you've been formally taught.

That's the **baseline**. From there, four layers of calibration shape what you actually read:

1. **Textbook baseline.** Your declared chapter sets the floor. Anything in your chapter or before it is fair game.
2. **User-added vocabulary.** You can add words you've picked up elsewhere — from podcasts, other apps, a friend, anywhere. These join your baseline.
3. **Downward calibration.** When you flag a word as unfamiliar in a story, Yomimono treats it as not-yet-known and adjusts.
4. **Upward calibration.** Yomimono salts your stories with a small number of *probe words* drawn from the next chapter ahead. If you handle them in context, they're gradually treated as known. If you don't, they aren't pushed harder.

Together, these four layers let Yomimono produce stories that sit in your comprehension zone — high coverage, with a small, deliberate amount to learn — and adapt as you do.

The flashcards built into the app are scoped to the same vocabulary. If you already use Anki or WaniKani, you can plug them in. If you don't, you don't need to. Yomimono is designed to be the whole reading-and-vocabulary loop on its own, sitting alongside the textbook you're already using.

## What's coming

This is the first post on this blog, and I expect it to age. The product is early. Some of what I've described here will look different in six months, and some of what I'm sure about today I'll be wrong about by then. I'll write about that as it happens — about what works, what doesn't, what the data says when we have data to look at, and what I'm learning about the craft of building a tool for learners by being one myself.

If any of this resonates — if you've felt the friction I'm describing, or if you're curious about how the calibration actually works under the hood — I'd love to hear from you.

Read on, and 頑張って.

---

*Notes and references*

- Krashen, S. (1982). *Principles and Practice in Second Language Acquisition.* Pergamon. [Free PDF](https://sdkrashen.com/content/books/principles_and_practice.pdf).
- Hu, M. & Nation, P. (2000). "Unknown Vocabulary Density and Reading Comprehension." *Reading in a Foreign Language*, 13(1).
- Nakanishi, T. (2015). "A Meta-Analysis of Extensive Reading Research." *TESOL Quarterly*, 49(1).
- Day, R. R. & Bamford, J. (2002). "Top Ten Principles for Teaching Extensive Reading." *Reading in a Foreign Language*, 14(2).

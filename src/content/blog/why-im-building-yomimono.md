---
title: "Why I'm building Yomimono"
description: "An introduction to what I'm making and why."
pubDate: 'May 28 2026'
---

## A confession from a Japanese learner

I've been studying Japanese for under a year. I know maybe fifty kanji. I'm not trying to read novels, or the news, or anything you'd call "real Japanese." That's a long way off, and I know it. What I want, right now, is reading practice: enough text at my level to build the muscle memory that turns slow decoding into actual reading.

That turns out to be hard to find. Here's what happens. You finish chapter 8 of Minna no Nihongo I at your class. You've learned about thirty new words. You go online to find something to read at your level, and you discover one of two things:

The text you found is graded for "beginners," which turns out to mean someone three chapters ahead of you, with grammar you haven't seen and vocabulary you don't recognize. Within a paragraph you've stopped reading and started decoding. Every other word is a dictionary lookup. You're not reading anymore, you're fighting the text, and after a page of that you give up.

Or the text is genuinely at your level, but it's a four-line dialogue. Tanaka-san asks where the station is; someone answers. There's plenty of that kind of thing around, drills and example sentences and tiny exchanges. What there isn't is something that actually *reads*: a passage long enough to settle into, that flows, that lets you build a rhythm instead of restarting every two sentences. It doesn't need to be gripping. This is practice, not reading for the story. But it has to be long enough and connected enough to be reading at all.

The reason this is missing is structural. To write a passage that fits a beginner, you have to know which words and grammar they've been taught, and then build something using mostly those, plus a small handful of new ones. A textbook chapter tells you exactly that: finish chapter 8 of Minna no Nihongo I and there's a defined set of words and grammar you're assumed to know.

Human authors of graded readers do this heroically, but they do it once, for an imagined average learner. They can't do it for *you*, on Tuesday, after you've finished a chapter of a textbook and want a page long text at exactly that level before tomorrow.

This is the kind of problem that, until recently, didn't have an answer. It does now: generative AI can produce endless text on demand, and if you constrain it to a known vocabulary and grammar set, that text can be made to land at a specific level. The expensive part, writing fresh level-matched passages one after another, is suddenly cheap.

This is the gap Yomimono exists to close.

## The science

I didn't invent the idea that beginners need calibrated input. The research is decades old and fairly clear. Three threads matter here.

**Comprehensible input.** In the early 1980s, Stephen Krashen argued that you acquire a language by understanding input slightly beyond your current level. He called it *i+1*. Contested and refined since, but the core holds: you learn from things that are *almost* within reach, not from drilling what you know or wrestling with what you don't.

**Lexical coverage.** *i+1* was vague about how much "slightly beyond" is. In 2000, Hu and Nation put a number on it: you need to know around 95% of the words in a text to follow it, closer to 98% to read without help. A few unknown words is a learning opportunity; too many is a wall.

**Extensive reading.** The practice built on this — *tadoku* (多読, "much reading") in Japanese — is to read a lot of text you can mostly understand, without stopping to translate everything. A 2015 meta-analysis by Nakanishi pooled 34 studies and found consistent gains, strongest when the texts were genuinely matched to the learner.

The throughline: you get better at reading by reading appropriate things, and a lot of them.

## What Yomimono is

The research above points at one zone: text you can mostly read, with a little to learn. Miss it and you get friction. Every lookup breaks your flow, every surprise in the grammar breaks your focus, and across enough sessions that's how reading practice quietly dies. I think of that gap between where you are and the text in front of you as **immersion friction**. The hard part has never been knowing the target; it's hitting it for one learner, day after day.

The core idea is calibration: Yomimono works from a model of what you already know right now. Anchored to where you are in your studies, it writes passages built mostly from that and long enough to let you settle into a rhythm. Read enough of them and you build real reading reflexes. It's deliberately simple, and it sits alongside the textbook you're already using.

## Starting here

This is the first post, and it's early — I'm starting with the simplest version of the thing and going from there. I plan to document the process as I go: what works, what doesn't, what I get wrong, what the data says once there's data to look at. I'm building this as someone who wants to use it, so a lot of it will be figured out in the open.

If any of this resonates — if you've felt the same friction, or you're just curious where it goes — I'd love to hear from you.

Read on, and がんばって！.

---

*Notes and references*

- Krashen, S. (1982). *Principles and Practice in Second Language Acquisition.* Pergamon. [Free PDF](https://sdkrashen.com/content/books/principles_and_practice.pdf).
- Hu, M. & Nation, P. (2000). "Unknown Vocabulary Density and Reading Comprehension." *Reading in a Foreign Language*, 13(1).
- Nakanishi, T. (2015). "A Meta-Analysis of Extensive Reading Research." *TESOL Quarterly*, 49(1).
- Day, R. R. & Bamford, J. (2002). "Top Ten Principles for Teaching Extensive Reading." *Reading in a Foreign Language*, 14(2).
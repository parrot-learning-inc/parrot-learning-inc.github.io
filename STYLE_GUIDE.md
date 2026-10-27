# Page style guide

Rules for every guide page on this site. The site is a free, public set of Spanish
resources from Parrot, hosted on GitHub Pages for SEO. Each page targets one search
keyword and must give real value on its own, even if the reader never installs Parrot.

## File and front matter

One Markdown file per page in the repo root, named `<slug>.md`. Front matter:

```yaml
---
title: "Best App to Learn Spanish in 2026: 13 Apps Ranked"   # SEO title, keyword first, max ~60 chars
short_title: "Best App to Learn Spanish"                     # used in "More resources" links and home cards
description: "One or two plain sentences, 140-155 characters, keyword included, says what the reader gets."
permalink: /best-app-to-learn-spanish/
slug: best-app-to-learn-spanish
order: 1                                                     # position on the home page
keyword: best app to learn spanish
last_updated: 2026-10-26
faq:                                                         # 3-5 real questions people search
  - q: "What is the best app to learn Spanish?"
    a: "Plain-text answer, 1-3 sentences. No Markdown, no links."
---
```

## Page shape

1. `# H1` that contains the exact keyword.
2. A first paragraph with class `lede` that answers the search in 2-3 sentences.
   Write it as `Answer text here.` on its own line, then `{: .lede }` on the next line.
3. The useful part: tables, lists, steps. Tables are the backbone of these pages.
4. One inline call to action in the middle of the page, where it fits the topic:
   `{% include parrot-cta.html where="inline" title="Short title" body="One or two sentences tied to this page." %}`
   The layout adds a second call to action at the end, so do not add one there.
5. Do not write an FAQ section in the body. The layout renders `faq` from front matter.

Length: 900-1,800 words of body text, plus tables. Value first, padding never.

## Callouts

Use Markdown paragraphs with a class line after them:

```markdown
🎯 **Key point:** One idea that matters most.
{: .key }

💡 **Tip:** A practical shortcut.
{: .tip }

⚠️ **Watch out:** A common mistake.
{: .warn }
```

Use at most 3 callouts per page.

## Links

- Sibling pages on this site: root-relative, for example `[Spanish flashcards](/spanish-flashcards/)`.
  Link 2-4 siblings where they help the reader.
- Parrot pages: 2-4 contextual links, only from this list, always with the UTM string
  `?utm_source=github&utm_medium=referral&utm_campaign=free_resources&utm_content=<slug>`:
  - https://www.parrotapp.com/ (home)
  - https://www.parrotapp.com/grammar , /grammar/ser-vs-estar , /grammar/por-vs-para ,
    /grammar/preterite-vs-imperfect , /grammar/spanish-subjunctive , /grammar/reflexive-verbs-spanish ,
    /grammar/ser-conjugation , /grammar/estar-conjugation , /grammar/how-to-say-thank-you-in-spanish
  - https://www.parrotapp.com/vocabulary
  - /use-cases/spanish-for-beginners , /use-cases/spanish-for-adults , /use-cases/conversational-spanish ,
    /use-cases/spanish-for-travel , /use-cases/learn-spanish-vocabulary , /use-cases/spanish-app
  - /features/comprehensible-input-spanish , /features/spanish-listening-practice ,
    /features/spanish-speaking-practice , /features/spanish-reading-practice ,
    /features/ai-spanish-tutor , /features/spanish-learning-videos
  - /alternatives/duolingo-alternative , /alternatives/babbel-alternative ,
    /alternatives/pimsleur-alternative , /alternatives/rosetta-stone-alternative
  - /methodology , /blog
- Outside sites: only well-known, stable URLs (official app stores, rae.es, spanishdict.com,
  state.gov, apcentral.collegeboard.org, ankiweb.net). No guessed deep links.
- App store links for Parrot come from the call-to-action include. Do not hard-code them.

## Voice

Parrot's voice: casual, direct, friendly. Talk to "you". Short sentences. A little humor is good.
Sound like a friend who speaks Spanish and has tried every app, not like a brochure.

- No hype: never "unlock", "dive into", "game-changer", "revolutionize", "seamless", "journey",
  "elevate", "embark", "master X in Y days".
- No em dashes. Use a period, comma, colon, or parentheses.
- No invented statistics, studies, quotes, testimonials, or user counts.
- Spanish must be correct: accents, ñ, ¿ and ¡. Pronunciation hints are simple English sound-alikes
  in plain text, for example `OH-lah`, with the stressed syllable in capitals.
- When Spanish differs between Spain and Latin America, say so briefly.

## Parrot facts you may use

- Parrot teaches Spanish with short videos from native speakers, matched to your level
  (comprehensible input). The feed is personalized to your interests.
- Tap any word in a video to see its meaning and save it. Saved words become flashcards.
- Practice for listening, reading, and speaking, plus an AI Spanish tutor.
- On iPhone, Android, and the web. Free to start. Do not state a price.
- 4.7 stars on the App Store from 17,000+ ratings. 700,000+ learners.

Do not claim anything else about Parrot.

## Honesty rules

- Parrot can be first in rankings, but rate every other product fairly and name real strengths.
- Prices of other apps: write "about $X/month" and add a note that prices change and vary by country.
- Facts with a source (FSI hours, AP exam format) must match the source as of 2026. If unsure,
  say "about" and link the official source.

## Data files

When a page has a list people may want to reuse (words, verbs, phrases, flashcards), also save it
as a UTF-8 CSV in `/data/<slug>.csv` with a header row, and link to it from the page:
`[Download the CSV](/data/<slug>.csv)`. All content is CC BY 4.0 (credit Parrot with a link).

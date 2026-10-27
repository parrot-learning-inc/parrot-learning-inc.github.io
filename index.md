---
title: "Free Spanish Learning Resources (2026)"
description: "16 free Spanish resources: app rankings, a 12-week study plan, word lists, verbs, phrases, flashcards, stories, grammar, and more. No signup."
permalink: /
last_updated: 2026-10-26
---

# Free Spanish learning resources

Everything here is free, with no signup and no email wall. Pick the page that matches what you need today, and come back for the next one.
{: .lede }

We are the team behind [Parrot](https://www.parrotapp.com/?utm_source=github&utm_medium=referral&utm_campaign=free_resources&utm_content=home), an app that teaches Spanish with short videos from native speakers. Parrot is backed by [Y Combinator](https://www.ycombinator.com/companies/parrot), and more than 700,000 learners use it. We made these pages because most "free Spanish resources" lists are 40 links and zero help. These are the guides we wish we had when we started. [Read our story](/about/).

<ul class="card-grid">
{% assign guides = site.pages | where_exp: "p", "p.order" | sort: "order" %}
{% for p in guides %}
  <li>
    <a href="{{ p.url | relative_url }}">
      <span class="card-title">{{ p.short_title | default: p.title }}</span>
      <span class="card-desc">{{ p.description }}</span>
    </a>
  </li>
{% endfor %}
</ul>

## Not sure where to start?

- **Brand new to Spanish?** Start with the [alphabet](/alphabet-in-spanish/), then [100 easy Spanish words](/100-easy-spanish-words/), then [easy phrases](/easy-phrases-in-spanish/).
- **Want a plan?** Follow the [best way to learn Spanish](/best-way-to-learn-spanish/) 12-week plan, or the free [Spanish lessons](/spanish-lessons/) course.
- **Picking an app?** Read our [ranking of the best apps to learn Spanish](/best-app-to-learn-spanish/).
- **Going on a trip?** Grab the [Mexico travel guide](/spanish-travel-guide-mexico/).
- **Studying for a test?** Use the [AP Spanish study guide](/ap-spanish-exam-study-guide/) and the [grammar cheat sheet](/spanish-grammar/).

## Use these resources anywhere

All pages and data files are free to share and adapt under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Teachers can print them, and developers can use the CSV files in `/data`. Please credit "Parrot (parrotapp.com)" with a link.

Found a mistake or want a new resource? [Open an issue on GitHub](https://github.com/{{ site.github_org }}/{{ site.github_org }}.github.io/issues).

---
title: "About Parrot: Who Makes These Free Spanish Resources"
description: "These free Spanish resources are made by Parrot, a Y Combinator (F25) language app. Meet the founders and see how we research and check every page."
permalink: /about/
slug: about
last_updated: 2026-10-26
---

# About Parrot

These free Spanish resources are made by the team behind [Parrot](https://www.parrotapp.com/?utm_source=github&utm_medium=referral&utm_campaign=free_resources&utm_content=about), an app that teaches Spanish with short videos from native speakers. Parrot is backed by Y Combinator, and more than 700,000 learners use it.
{: .lede }

<a class="yc-badge" href="https://www.ycombinator.com/companies/parrot"><b>Y</b> Backed by Y Combinator (F25)</a>

## Why we started Parrot

Erik, our CTO, spent years believing he was bad at languages. Then he found comprehensible input: lots of real speech that you can mostly understand. He learned Spanish, French, and Italian in one year, through conversations, videos, and stories instead of drills. Grammar exercises and streaks had done very little for him. Real input did almost everything.

So before we wrote any code, the three of us did our homework. We downloaded and used 52 language learning apps. We interviewed 65 learners. Later we spoke with 186 Duolingo users to find out where people get stuck. The same story came up again and again: people played the game every day, and still froze when a real person spoke Spanish to them.

That research became Parrot's core bet. People learn a language best from large amounts of real speech they can understand, in a format they already enjoy. For most of us, that format is short videos. Our goal is to help a billion people become fluent in a language, and to make possible the conversations that come with it: with a friend, a partner, or a grandmother.

## Why we made these free pages

Most "free Spanish resources" lists are 40 links and zero help. We wanted pages that are useful on their own, even if you never open our app: real word lists, real study plans, honest app rankings, and data files you can download. Everything is free, with no signup and no email wall.

## The founders

<ul class="founders">
{% for pair in site.data.authors %}{% assign a = pair[1] %}
  <li>
    <img src="{{ a.picture | relative_url }}" alt="{{ a.name }}" width="72" height="72" loading="lazy">
    <span class="f-name">{{ a.name }}</span>
    <span class="f-role">{{ a.role }}</span>
    <span class="f-links"><a href="{{ a.url }}?utm_source=github&utm_medium=referral&utm_campaign=free_resources&utm_content=about-founders">Bio and articles</a> · <a href="{{ a.linkedin }}">LinkedIn</a></span>
  </li>
{% endfor %}
</ul>

- **Amir Hanna** leads Parrot and writes most of the [Parrot blog](https://www.parrotapp.com/blog?utm_source=github&utm_medium=referral&utm_campaign=free_resources&utm_content=about), about how adults actually acquire a language. He trained as an engineer at the University of British Columbia, and his team won first place out of 577 teams in Microsoft's Discover AI challenge in 2020.
- **Erik Dahl** leads engineering. He builds the systems behind Parrot's personalized feed of short videos. He learned Spanish, French, and Italian with comprehensible input.
- **Julia Hudea** leads product. She talks with learners on regular feedback calls, and learner research decides what gets built. Her view: "Language learning shouldn't be just a mindless game. It can be fun while also being effective."

Meet the rest of the team on the [Parrot team page](https://www.parrotapp.com/team?utm_source=github&utm_medium=referral&utm_campaign=free_resources&utm_content=about).

## How we make and check these pages

- **Useful first.** Every page must help you even if you never use Parrot.
- **Honest rankings.** When we rank apps, Parrot is on the list because we make it. We say so on the page, show our scoring method, and name what every other app does well.
- **Sources for facts.** Numbers like class hours and exam formats come from official sources, such as the U.S. Foreign Service Institute and the College Board, and we link to them. Prices of other apps are approximate and change often.
- **Real Spanish.** We write for learners in both Spain and Latin America, and we note the differences. Our method is explained on the [Parrot methodology page](https://www.parrotapp.com/methodology?utm_source=github&utm_medium=referral&utm_campaign=free_resources&utm_content=about).
- **Corrections.** Found a mistake? [Open an issue on GitHub](https://github.com/{{ site.github_org }}/{{ site.github_org }}.github.io/issues) or email [{{ site.parrot.contact }}](mailto:{{ site.parrot.contact }}). We fix errors fast.

## Find Parrot elsewhere

- Website: [parrotapp.com](https://www.parrotapp.com/?utm_source=github&utm_medium=referral&utm_campaign=free_resources&utm_content=about-links)
- Y Combinator: [ycombinator.com/companies/parrot](https://www.ycombinator.com/companies/parrot)
- LinkedIn: [Parrot on LinkedIn](https://www.linkedin.com/company/104851379/)
- X: [@parrotappp](https://x.com/parrotappp)
- App: [iPhone](https://apps.apple.com/us/app/parrot-learn-spanish-language/id6736955121) and [Android](https://play.google.com/store/apps/details?id=com.fluentwithparrot)

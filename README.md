# LinkedIn Organic Content Strategy for B2B SaaS — Research Repository

A structured research repository on how B2B SaaS companies and founders build organic audiences on LinkedIn. Built by studying the recent content and public frameworks of 10 practitioners who have collectively grown to 40K–200K+ followers each.

---

## Why this topic

LinkedIn has become the primary distribution channel for B2B SaaS go-to-market — but most companies either ignore it or treat it like a company announcement board. The practitioners who do it well consistently drive measurable pipeline from organic content alone, without paid spend. This research explores how they do it: what they post, how often, in what format, and what mental models they use.

The goal is a distilled playbook, grounded in real examples, not theory.

---

## Why these 10 experts

The 10 experts were selected to cover different angles of the same topic:

| Expert | Focus | Followers |
|---|---|---|
| [Adam Robinson](research/linkedin-posts/adam-robinson.md) | Founder-led content; building in public; pipeline-first LinkedIn | 154,514 |
| [Dave Gerhardt](research/linkedin-posts/dave-gerhardt.md) | B2B audience building; community (DGMG); marketing to humans | 201,384 |
| [Devin Reed](research/linkedin-posts/devin-reed.md) | Content as sales calls at scale; content-led growth at Gong | 99,756 |
| [Anthony Pierri](research/linkedin-posts/anthony-pierri.md) | Positioning and messaging clarity before publishing; FletchPMM | 80,563 |
| [Amanda Natividad](research/linkedin-posts/amanda-natividad.md) | Zero-click content; SparkToro VP Marketing | 64,904 |
| [Ross Simmonds](research/linkedin-posts/ross-simmonds.md) | Create once, distribute forever; cross-platform B2B strategy | 59,932 |
| [Emily Kramer](research/linkedin-posts/emily-kramer.md) | LinkedIn flywheel; B2B startup marketing frameworks; MKT1 | 50,505 |
| [Tommy Clark](research/linkedin-posts/tommy-clark.md) | Founder-led content agency; content-market fit; format variety | 48,821 |
| [Finn Thormeier](research/linkedin-posts/finn-thormeier.md) | Product-led content; thought leadership clarity for B2B SaaS | 42,426 |
| [Richard van der Blom](research/linkedin-posts/richard-van-der-blom.md) | LinkedIn algorithm mechanics; native content; engagement signals | ~35,000 |

Full rationale for each selection: [`research/sources.md`](research/sources.md)

---

## Repository structure

```
research/
├── sources.md                    # Expert list with selection rationale
├── linkedin-posts/               # 7–9 recent posts per expert (collected manually)
│   ├── adam-robinson.md
│   ├── amanda-natividad.md
│   ├── anthony-pierri.md
│   ├── dave-gerhardt.md
│   ├── devin-reed.md
│   ├── emily-kramer.md
│   ├── finn-thormeier.md
│   ├── richard-van-der-blom.md
│   ├── ross-simmonds.md
│   └── tommy-clark.md
├── youtube-transcripts/          # 2–3 video/podcast transcripts per expert (via Supadata API)
│   ├── adam-robinson/
│   ├── amanda-natividad/
│   ├── anthony-pierri/
│   ├── dave-gerhardt/
│   ├── devin-reed/
│   ├── emily-kramer/
│   ├── finn-thormeier/
│   ├── richard-van-der-blom/
│   ├── ross-simmonds/
│   └── tommy-clark/
└── other/
    └── playbook-outline.md       # Patterns distilled from the full research
```

---

## How the research was collected

**LinkedIn posts:** Collected manually by reading each expert's recent post history on LinkedIn. Each file includes the post text, URL, approximate date, format, and engagement metrics. Posts were selected for relevance to LinkedIn content strategy and B2B SaaS specifically.

**YouTube/podcast transcripts:** Fetched programmatically via the [Supadata API](https://supadata.ai), which returns timestamped transcripts from YouTube videos. 2–3 videos per expert were selected based on topic relevance. Transcripts were cleaned (removed music markers and timestamps) and stored as plain-text markdown.

---

## Key findings (summary)

The full synthesis is in [`research/other/playbook-outline.md`](research/other/playbook-outline.md). The most consistent patterns across all 10 experts:

1. **Founder-led beats company-led** — personal brands outperform company pages for organic reach, especially below $100M ARR (Emily Kramer's data from 100 B2B startups confirms this)

2. **Zero-click content is the baseline** — the algorithm demotes external links; the best posts deliver complete value without requiring any outbound click (Amanda Natividad's core framework)

3. **The first line is everything** — LinkedIn collapses posts after 2–3 lines; every top post uses a specific number, a counter-intuitive take, or a personal story to earn the "see more" click

4. **3–5x per week, vary the format** — posting frequency creates more shots at outlier posts; format variety (hot takes, lists, data reveals, short-form, video) prevents audience tune-out

5. **Content is a sales conversation** — Devin Reed's "Reed's Law": every post is a sales call at scale. The best B2B LinkedIn practitioners don't think about content as brand-building — they track pipeline touched by content

6. **Distribute beyond LinkedIn** — Ross Simmonds' "create once, distribute forever" is the highest-leverage insight for teams with limited resources; LinkedIn is the starting point, not the destination

---

## What this is not

This is a research repository, not a finished guide. It contains:
- Raw LinkedIn post text (not paraphrased or summarized)
- Raw video transcripts (not edited or condensed)
- A structured playbook outline (not a polished article)

The value is in the primary sources and the patterns extracted from them.

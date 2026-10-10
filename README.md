# DebateIntel

**A research and case-writing studio for Public Forum debate.**

### → [debateintel.vercel.app](https://debateintel.vercel.app)

DebateIntel turns a bare resolution into real, quotable evidence — and then into a
case you can actually read in round. Built by a high school PF debater, for PF
debaters.

---

## What it does

| | |
|---|---|
| **Card Researcher** | Type in a resolution. It finds real sources, fetches the actual pages, and quotes them word for word. |
| **Disclosure Scraper** | Paste text or a URL, get finished evidence cards back. |
| **Case Generator** | Your collected cards become a speech — plain for a lay judge, dense for a tech judge. |
| **openCaselist** | Pull a school's real disclosed files, with the original Word formatting intact. |
| **Flow** | Flow the round sheet by sheet, run the speech clock, pull blocks from your block file mid-speech, and sync live with your partner. |
| **Export Center** | Everything you've collected as one clean PDF or DOCX. |

## The rule the whole thing is built around

**Evidence card bodies are never AI-generated or paraphrased.**

Competitive debate evidence has to be quotable word for word from its source. A
card whose body isn't a verbatim excerpt isn't a formatting shortcut — it's
fabricated evidence. So every card-producing path selects and highlights real
fetched text, and the one module allowed to call a language model is never
imported by the code that builds cards.

Language models are used for case *narrative* prose only, which is original
analytical writing, not evidence.

A source that can't be fetched produces no card. Nothing is invented to pad the
count.

## Flowing a round

The flow tool handles the parts of a round that usually live on scrap paper:

- Sheet-by-sheet flowing with speech timers and a roadmap
- Your block file, searchable by tagline, author or card text, filtered by
  argument type — **NU · Link · Impact · Turn**
- A **Read** view that shows only the highlighted words you actually say aloud
- A **pacer** that trains your eye-voice span for spreading
- Live partner sync — you each keep your own flow, on your own tabs
- A written handoff (GO FOR / KICK / WEIGH) before your partner's summary
- Rounds archived automatically so a tournament's flows aren't lost

## Built with

- **Frontend** — Next.js 16, TypeScript, Tailwind CSS v4
- **Backend** — FastAPI (Python 3.11+)

## Author

Srikanth Mohan · San Marcos High School

---

**Try it: [debateintel.vercel.app](https://debateintel.vercel.app)**

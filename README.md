# Founders Interview Guide

A practical study guide for Penn founders preparing for YC and other accelerator interviews, and for early VC diligence.

**Live site:** https://cliffweng.com/founders-interview-guide/

GitHub Pages publishes the same site at https://cliffweng.github.io/founders-interview-guide/ once Pages is enabled. Do not add a `CNAME`. `cliffweng.com` already serves the sibling guides, and this repo stays on the path above.

## Roadmap

14 topics, one file each under [`topics/`](topics/), ordered the way a founder interview actually runs:

1. Interview formats (YC vs VC diligence)
2. Why this / why now / why you
3. Problem clarity & customer stories
4. Product sense & prioritization
5. Market size & wedge
6. Competition & differentiation
7. Traction & metrics under fire
8. Go-to-market story
9. Business model & pricing defense
10. Team, equity, roles
11. Fundraising narrative & ask
12. Common traps & weak answers
13. Mock Q packs (hotspots)
14. Closing & follow-ups

## Interview hotspots

Every topic page carries a badge (🎯 Interview frequent / Interview occasional / Background) so you know where to spend prep time. If you're short on time, prioritize these:

- **Why this / why now / why you** — the three questions founders mash into "we're passionate." Partners separate them, and a missing "why now" or a generic "why you" sinks an otherwise clear idea.
- **Problem clarity & customer stories** — YC interviews live here. A specific user, the last time the problem happened, and what you changed because of it.
- **Market size & wedge** — bottom-up math for the first market, plus the adjacent step. A top-down "$50B, we'll get 1%" slide is a frequent way to lose the room.
- **Competition & differentiation** — the status quo, the incumbent, and the other startups. "No competitors" and a checkmark matrix are both weak.
- **Traction & metrics under fire** — they will recompute your growth rate. Definitions, cohorts, and absolute numbers. Vanity counts (signups, LOIs, waitlists) get punctured fast.
- **Fundraising narrative & ask** — what you do, the proof, the amount, and what the money is for. A valuation speech is not an ask.
- **Common traps & weak answers** — jargon, future tense, fake precision, and hiding the bad number.
- **Mock Q packs** — the drill. Ten minutes, interruptions, the hotspot questions in YC order and in seed-diligence order.

**Occasional** (you will get a question; less often the whole interview): interview formats, product sense & prioritization, go-to-market, business model & pricing, team / equity / roles. Product and "how do you make money" still come up almost every time — as a sentence. These pages are the longer version of that sentence.

**Background** (do it, rarely the scored portion of the hour): closing & follow-ups. The interview is usually over before your clever question. The follow-up email still matters when they asked for a number or a customer.

This split is a judgment call for YC-style accelerator interviews and early (pre-seed / seed) VC diligence, not a guarantee for any specific partner. A deep-tech fund will push harder on "why now" and technical risk. A consumer fund will push harder on retention. A solo student founder will get more team questions than this badge implies.

## How to use this guide

Each topic page is designed to be read in **~10 minutes** and follows the same structure: why it matters, core concepts, a mental model, 3–5 interview questions with brief answer keys, and a short list of verified YouTube videos. Read them in order, or jump straight to what you need. No backend, no auth, no sign-up — just read the pages.

Drill with a cofounder: 10 minutes, they interrupt, you answer in sentences. Use [Mock Q packs](topics/13-mock-q-packs.md) for the script.

## How to contribute

See [CONTRIBUTING.md](CONTRIBUTING.md). In short: one topic per file, keep it under ~10 minutes to read, and only link to sources (especially YouTube videos) you've personally verified exist. Open an issue before proposing new topics or restructuring the curriculum.

## Decisions

These are the product locks this guide was built against — echoed here so future contributors don't accidentally relitigate them:

- **Audience**: Penn founders prepping YC / accelerator interviews and early VC diligence. Darren & Gabe. Same job as the sibling study guides: short pages, interview questions, real links.
- **Spine**: why this / why now / why you, then product, market, traction, competition, go-to-market, team and equity, fundraising narrative.
- **Time-boxed**: every topic is readable in 10 minutes or less. Depth lives in "further reading."
- **Learning + interview prep in one page**: each topic pairs core concepts with interview questions.
- **Badges**: 🎯 Interview frequent / Interview occasional / Background, in the README and on every topic.
- **Real links only**: every YouTube link was checked to exist before it was added. No invented video IDs.
- **Static site, GitHub Pages, Just the Docs**: `remote_theme: just-the-docs/just-the-docs`. `baseurl: "/founders-interview-guide"`. `url: "https://cliffweng.github.io"`. Mermaid 10.1.0. No backend, no auth, no quizzes, no progress tracking.
- **Sites**: https://cliffweng.com/founders-interview-guide/ and https://cliffweng.github.io/founders-interview-guide/. No `CNAME` in this repo. `cliffweng.com` stays with the sibling guides.
- **Non-goals for v1**: full startup ops playbook (a separate startup guide owns that), legal deep dives, quizzes, auth, progress backend.

## Enabling GitHub Pages

Just the Docs is configured via `_config.yml` (remote theme). After this lands on `main`:

1. Repo **Settings → Pages**.
2. **Build and deployment → Source**: **Deploy from a branch**.
3. Branch: `main` / folder: `/ (root)`.
4. Save. The first build often takes a few minutes.
5. Site publishes to https://cliffweng.github.io/founders-interview-guide/

GitHub Pages allows `jekyll-remote-theme`, which is what `remote_theme` in `_config.yml` uses. Do not add a `CNAME` for `cliffweng.com`; that host is already used for sibling guides. The expected public path on that host is https://cliffweng.com/founders-interview-guide/.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000/founders-interview-guide/`.

## License

[MIT](LICENSE)

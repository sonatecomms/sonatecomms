# Maurice Charles

I build working software for the way real organizations run. I came to it from sixteen years of running operations and leading teams, so I start by working out what someone actually needs to see, then I build it and stay through rollout.

Since June 2026 I have built more than twenty projects with AI coding agents (Claude Code), the Claude API, TypeScript and Next.js, Postgres on Supabase, and Python, shipped through pull requests and preview deployments on Vercel. The code lives in private repositories because much of it holds client or operational data. Every product below is live, and I am glad to walk through the code on a call or open a repository for review.

## In daily use

| Need | What I built |
|---|---|
| A county Special Olympics program needed to run its season from a phone | The operations system its coordinator uses every day for more than 550 athletes, coaches, and families: records, guardian messages, calendar, and season prep. |

## Products, each built to answer one question

| Product | The question it answers | Live |
|---|---|---|
| Cue | Who is in the building right now? | [cue.sonate.io](https://cue.sonate.io) |
| Register | Which rooms are in use, and by whom? | [register.sonate.io](https://register.sonate.io) |
| Sustain | What is due on every grant, seen by funder and grantee alike? | [sustain.sonate.io](https://sustain.sonate.io) |
| Cadence | How is each program actually doing, week to week? | [cadence.sonate.io](https://cadence.sonate.io) |
| Capo | What is the real number before the review meeting? | [capo.sonate.io](https://capo.sonate.io) |
| Rehearse | What do people on the team actually know? | [rehearse.sonate.io](https://rehearse.sonate.io) |
| Section | Who is registered, and who has been reached? | [section.sonate.io](https://section.sonate.io) |
| BUILD | Who fell behind on training this week? | [build.sonate.io](https://build.sonate.io) |
| Fanfare | Where does every request stand? | [fanfare.sonate.io](https://fanfare.sonate.io) |
| Harmony | Where do an organization's stated values stop at work? | [harmony.sonate.io](https://harmony.sonate.io) |
| Studio | How does a stranger hear your organization? | [studio.sonate.io](https://studio.sonate.io) |
| Groundwork | What does the operation look like, written down? | [groundwork.sonate.io](https://groundwork.sonate.io) |

## How I build with AI

- **Agent pipelines.** A multi-agent review pipeline captures an organization's public pages, runs specialist agents in parallel, merges their reads, and passes everything through a gate agent that checks every quoted line against the captured page before it reaches a client.
- **Testing models before shipping.** Side-by-side runs on cost, completion, and output checks. On a live web-research agent, a smaller model matched the larger one on every check at 29 percent of the cost; a paired-model setup broke one run in three and stayed off.
- **Model calls as reviewed settings.** Every Claude call across the products runs from a named profile (model, token budget, timeout, effort), so moving every app to a new model is one reviewed change. Prompt caching is measured against the live API.

[sonate.io](https://sonate.io) · [LinkedIn](https://linkedin.com/in/maurice-charles)

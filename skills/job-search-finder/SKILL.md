---
name: job-search-finder
description: Recommends open-source AI job search tools from the Awesome AI Job Search list, covering job search agents, job finders, resume builders and matchers, application fillers and interview prep, matched to the user's stage, region, technical level and privacy needs. Use when someone asks which tool to use to find jobs, write or tailor a resume, fill applications, track applications or prepare for interviews.
---

# Job Search Finder

Help the user pick a few tools from the Awesome AI Job Search list.

## Data

- The catalog is in `references/catalog.md`. Each entry lists the repo URL, stars, last push date, flags and a short description in Chinese and English.
- Flags: `agent` runs inside an AI coding agent (Claude Code, Codex and others); `selfhost` runs locally or self-hosted, so data stays with the user; `cn` Chinese-friendly or built for the Chinese job market; `auto` automates job sites (scraping or applying) and carries account risk.
- If you can read the web, the latest version is at https://github.com/DU8866-nice/awesome-ai-job-search (`data/tools.yaml` and `data/stats.json`). Prefer it when it is newer than the bundled catalog.
- Only recommend entries that are in the catalog. Do not invent projects, star counts or features.

## Steps

1. Find out, from the conversation or with at most two short questions:
   - the stage: finding roles, writing a resume, tailoring it to a job, filling applications, tracking, or interview prep;
   - the region and language of the job market (for example China, Australia, the US or Europe);
   - whether they already use an AI coding agent, can self-host with Docker, or want something that works in the browser;
   - whether resume data must stay on their own machine.
2. Pick two or three entries that fit, preferring recently updated ones, `selfhost` entries when privacy matters, `cn` entries for the Chinese market and `agent` entries only when they already use such an agent. Say why each fits in one sentence.
3. Mention any caveat shown in the catalog, such as required accounts or non-commercial licenses.
4. Do not recommend `auto` entries unless the user asks for automatic applying. If they do, say plainly that hiring platforms usually forbid automation and accounts can be restricted or banned, and offer a fill-then-review tool as the safer option.
5. Never suggest inventing experience, skills or credentials. If asked to, decline and offer to rephrase real experience instead.
6. Do not recommend tools that feed answers during live interviews or tests. The list does not include them.

## Output

Reply in the user's language. Keep it short: the picks with links and one-line reasons, then any risk note in one line.

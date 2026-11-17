<!-- section:intro -->
Job hunting is becoming something you can hand to an AI for help. Some of the fastest-growing projects on GitHub this year turn Claude Code into a job search assistant: they read job descriptions, score them against your resume, produce a tailored resume, draft the cover letter and keep track of every application.

More tools also means harder choices. Some need self-hosting and some just install into your AI agent; some only prepare your materials and some mass-apply with your account, which can get it banned. This list sorts the tools by stage of the job search and marks those differences.

<!-- section:pick -->
## Find a tool by stage

| Stage | Least effort | Keep your data with you | Job hunting in China |
|---|---|---|---|
| All-in-one: find, tailor, track | [career-ops](https://github.com/career-ops-hq/career-ops), [ai-job-search](https://github.com/ai-job-search-dev/ai-job-search) | [Dossier](https://github.com/AienTech/dossier), [JobOps](https://github.com/DaKheera47/job-ops), [JobSync](https://github.com/Gsync/jobsync) | [MyCareer](https://github.com/low-hands/MyCareer), [OfferPilot](https://github.com/offercontext/offerPilot), [LuJie](https://github.com/Chozzc/Lujie-Careerkit) |
| Find jobs | [freehire](https://github.com/strelov1/freehire), [internship list](https://github.com/SimplifyJobs/Summer2027-Internships) | [JustHireMe](https://github.com/vasu-devs/JustHireMe) | [job_radar](https://github.com/lijiaqi-AI-Product-Manager/job_radar), [Campus2026](https://github.com/namewyf/Campus2026) |
| Build a resume | [Reactive Resume](https://github.com/reactive-resume/reactive-resume), [RenderCV](https://github.com/rendercv/rendercv) | [ResumeForge](https://github.com/magicapple123/ResumeForge), [JadeAI](https://github.com/LingyiChen-AI/JadeAI) | [Magic Resume](https://github.com/JOYCEQL/magic-resume), [Chinese templates](https://github.com/dyweb/awesome-resume-for-chinese) |
| Tailor it to a job | [ResumeSkills](https://github.com/Paramchoudhary/ResumeSkills) | [Resume Matcher](https://github.com/srbhr/Resume-Matcher) | [JobFit](https://github.com/DU8866-nice/jobfit), [ASu-skills](https://github.com/Hisn00w/ASu-skills) |
| Fill application forms | [jev-job-search](https://github.com/qbeka/jev-job-search) | [FormFilla](https://github.com/AhmadHassan-BTed/FormFilla) | [Job-Application-Helper](https://github.com/aurostars/Job-Application-Helper) |
| Prepare for interviews | [Tech Interview Handbook](https://github.com/yangshun/tech-interview-handbook) | [interview-guide](https://github.com/Snailclimb/interview-guide) | [JavaGuide](https://github.com/Snailclimb/JavaGuide), [get-job.skill](https://github.com/agentenatalie/get-job.skill) |

<!-- section:rules -->
## Good to know

> [!IMPORTANT]
> - **Don't let AI invent experience.** Have AI rewrite what you really did. Made-up skills and projects fall apart at the first follow-up question and fail background checks. Prefer tools that say they never fabricate and that tie every claim back to a line in your resume.
> - **Auto-applying is risky.** Tools marked ⚠️ scrape or apply automatically with your account. Hiring platforms usually forbid this, and accounts can be restricted or banned. It is safer to let a tool prepare materials and fill the form, then check and submit yourself.
> - **Your resume is sensitive.** It holds your phone number, address and work history. Tools marked 🏠 keep data on your own computer or server; with a cloud LLM, your resume text goes to the model provider.
> - **Match scores are only a guide.** Every tool scores differently. A high score doesn't promise an interview and a low one doesn't mean you can't apply. Check whether the gaps it lists are real.
> - **Watch for job scams.** Avoid any "job" that asks for money up front, your ID documents or an unknown download, and confirm postings on the company's own site.

This list does not include "stealth" tools that feed answers during live interviews or tests, or tools built to bypass CAPTCHAs and anti-scraping.

<!-- section:faq -->
## FAQ

**I can't code. Can I use these?**
Yes. Online resume editors (Reactive Resume, Magic Resume) and browser extensions (FormFilla) work straight away; tools marked 🤖 need an AI agent such as Claude Code or Codex installed first; self-hosted tools usually need Docker.

**Does it cost anything?**
Everything here is open source and free in itself. LLM features cost whatever the model provider charges; tools that support local models can run free with Ollama.

**Will an AI-written resume be spotted?**
There are no reliable numbers. The more practical problem is generic content that reads the same in every application. Use AI as an editor: let it point out gaps against the job description and tighten sentences, and fill in the numbers and facts yourself.

**Where should I start?**
No decent resume yet: make one with an editor under "Build your resume". Already have one: check it against your target job with a tool under "Match your resume to the job". Applying to many companies at once: then consider an all-in-one assistant to keep track.

**How often are stars updated?**
Every Monday GitHub Actions refreshes the stars and re-sorts the list, and links are checked weekly.

<!-- section:finder -->
## Let your AI agent pick

This list is also a skill. Install the [`skills/job-search-finder`](skills/job-search-finder) folder in your AI agent (or run `npx skills add DU8866-nice/awesome-ai-job-search`) and ask:

> I'm finishing an IT master's in Australia next year and want a graduate role in AI. I already have a resume and don't want to self-host anything. Which tools should I use?

It picks two or three entries for your stage, region, technical level and privacy needs, explains why, and warns about the risks of auto-applying.

<!-- section:contributing -->
## Contributing

Suggestions and corrections are welcome: [open an issue](https://github.com/DU8866-nice/awesome-ai-job-search/issues/new/choose), or edit [`data/tools.yaml`](data/tools.yaml) and send a PR. See the [contributing guide](CONTRIBUTING.md). The README is generated by a script, so please don't edit it directly.

JobFit in this list is a project by the list's author, and its entry says so.

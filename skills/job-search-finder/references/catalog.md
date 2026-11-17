# Catalog

Generated from data/tools.yaml. Fields: repo | stars | last push | os | flags (agent = runs inside an AI coding agent, selfhost = local or self-hosted, cn = Chinese-friendly, auto = automates job sites, account risk) | description (zh / en)

## 一站式求职助手 / All-in-one job search assistants

- https://github.com/career-ops-hq/career-ops | stars=83160 | pushed=2026-11-17 | os=- | flags=agent
  - 开源的 AI 求职 Agent：贴一个职位进去，在你自己的电脑上判断职位是否还在招、和你匹不匹配，再定制简历、起草回答，最后由你点提交。
  - An open-source AI job search agent: paste a job and it checks, on your machine, whether the role is still open and whether it fits, then tailors your CV and drafts answers. You press Submit.
- https://github.com/ai-job-search-dev/ai-job-search | stars=72145 | pushed=2026-11-16 | os=- | flags=agent
  - 建在 Claude Code 上的求职框架：fork 后填好个人档案，让 Claude 评估职位、定制简历、写求职信并帮你准备面试。
  - A job application framework built on Claude Code: fork it, fill in your profile, and let Claude evaluate postings, tailor your CV, write cover letters and prepare you for interviews.
- https://github.com/AienTech/dossier | stars=5239 | pushed=2026-11-13 | os=- | flags=selfhost
  - 部署在自己服务器上的求职工具：一份个人档案，为每个职位生成只用档案事实的定制简历和求职信，并跟踪每次投递。
  - Your job search on your own server: one profile, a tailored resume and cover letter for every job that only use facts from your profile, and every application tracked.
  - caveat: Works with local models through Ollama or LM Studio, or a hosted one
- https://github.com/DaKheera47/job-ops | stars=4144 | pushed=2026-10-30 | os=- | flags=selfhost
  - JobOps：一个页面搜 LinkedIn、Indeed、Glassdoor 等十多个招聘网站，为每个职位改写简历、打匹配分、查签证担保情况，并跟踪所有投递。
  - JobOps searches LinkedIn, Indeed, Glassdoor and 10+ boards from one screen, rewrites your CV per role, scores fit, checks visa sponsorship and tracks every application.
  - caveat: Deliberately has no auto-apply; you still apply to every job yourself
- https://github.com/vasu-devs/JustHireMe | stars=2277 | pushed=2026-10-09 | os=- | flags=selfhost
  - 本地优先的求职桌面工作台：抓取职位、按匹配度排序、生成定制的申请材料，提供 Windows、macOS 和 Linux 安装包。
  - A local-first desktop workbench that scrapes roles, ranks fit and generates tailored application materials, with installers for Windows, macOS and Linux.
- https://github.com/shengjidaguai-china/BossHunter | stars=1648 | pushed=2026-11-12 | os=- | flags=selfhost,cn,auto
  - 国内招聘平台的求职 Agent：本地完成岗位采集、AI 评分、定制简历和回复监测，所有投递必须先经人工确认。
  - A job search agent for Chinese hiring platforms: collects roles, scores them with AI, tailors resumes and monitors replies locally; every application needs your confirmation first.
  - caveat: The author warns that automating hiring platforms can get accounts restricted; non-commercial license
- https://github.com/Gsync/jobsync | stars=1532 | pushed=2026-11-16 | os=- | flags=selfhost
  - 自己部署的求职助手：跟踪每次投递，AI 审阅简历、匹配职位并自动发现新职位，可用 Ollama 本地模型，带 MCP 服务。
  - A self-hosted job search assistant that tracks applications, reviews resumes with AI, matches jobs and discovers new openings, with local AI through Ollama and an MCP server.
- https://github.com/DanielPan12/JobHuntBot | stars=890 | pushed=2026-10-12 | os=- | flags=agent,cn
  - 由 Agent 带着走的求职投递流程加本地进度看板，适用于 Claude Code、Codex、Cursor 等；不是一键海投，最终提交需要你授权。
  - An agent-led application workflow with a local progress dashboard for Claude Code, Codex, Cursor and others; not a one-click auto-apply bot, and final submission needs your authorization.
- https://github.com/offercontext/offerPilot | stars=767 | pushed=2026-11-16 | os=- | flags=selfhost,cn
  - OfferPilot：开源、本地优先的求职 Agent 工作台，把投递、简历、面试和 Offer 放在一起；不会自动投递，也不会替你联系招聘方。
  - OfferPilot, an open-source, local-first job search agent workbench for applications, resumes, interviews and offers; it never auto-applies or contacts recruiters for you.
  - caveat: Basic tracking needs no AI; AI features use your own model service
- https://github.com/Chozzc/Lujie-Careerkit | stars=484 | pushed=2026-11-14 | os=- | flags=cn
  - 录阶：面向实习、校招的求职 Agent 工作台，覆盖简历编辑、JD 匹配、投递跟进、模拟面试和复盘。
  - LuJie CareerKit, an agent workbench for internships and campus hiring that covers resume editing, JD matching, application follow-up, mock interviews and reviews.
- https://github.com/tarunlnmiit/autopilot-jobhunt | stars=219 | pushed=2026-09-20 | os=- | flags=-
  - 每晚扫描 130 多个公司招聘页，用大模型按你的简历打分，把最匹配的职位发到 Telegram，并按需起草定制简历和求职信。
  - Scans 130+ company careers pages nightly, scores each role against your resume with an LLM, sends top matches on Telegram and drafts a tailored resume and cover letter on demand.
  - caveat: Drafts only, never applies
- https://github.com/vesaias/JobNavigator | stars=188 | pushed=2026-11-16 | os=- | flags=selfhost
  - 自己部署、支持多账号的求职自动化：抓取公司招聘页和聚合站，用大模型给职位打分、定制简历和求职信，Telegram 提醒，一家人可以共用一套。
  - Self-hosted, multi-account job-hunt automation: scrapes career pages and aggregators, scores jobs with an LLM, tailors resumes and cover letters and sends Telegram alerts; one install can serve a household.
- https://github.com/low-hands/MyCareer | stars=106 | pushed=2026-10-12 | os=- | flags=selfhost,cn
  - 跑在自己电脑上的 AI 求职助手：找岗位、看匹配、改简历、练面试、管投递，数据存在本机 SQLite；每条“符合”都引用简历原文。
  - An AI job search assistant on your own computer for finding roles, checking fit, editing resumes, practising interviews and tracking applications, stored in local SQLite; every match quotes your resume.

## 求职 Skill：装进 Claude Code、Codex 就能用 / Job search skills for Claude Code and Codex

- https://github.com/Hisn00w/ASu-skills | stars=6437 | pushed=2026-11-17 | os=- | flags=agent,cn
  - 中文求职工作流插件：九个入口覆盖开源贡献、简历提升、简历制作、岗位匹配、投递填写、面试准备和校招进度管理。
  - A Chinese job-hunting workflow plugin with nine entry points, from open-source contribution and resume work to job matching, application filling, interview prep and campus-hiring tracking.
- https://github.com/Paramchoudhary/ResumeSkills | stars=3231 | pushed=2026-06-19 | os=- | flags=agent
  - 一组面向简历优化、求职申请和职业发展的 AI Agent skill，包括 ATS 优化、要点改写和面试准备。
  - A collection of AI agent skills for resume optimization, job applications and career development, including ATS checks, bullet rewriting and interview prep.
- https://github.com/LiuMengxuan04/shushu-internship-tool | stars=2195 | pushed=2026-06-24 | os=- | flags=agent,cn
  - 鼠鼠实习妙妙工具：把岗位描述变成项目，把项目变成简历，把简历变成面试准备，适合零经验或经验少的计算机方向同学。
  - Turns a job description into a project, the project into a resume and the resume into interview prep, for CS students with little or no experience.
- https://github.com/agentenatalie/get-job.skill | stars=754 | pushed=2026-08-31 | os=- | flags=agent,cn
  - 实习.skill：从岗位调研、简历改写到分轮次面试准备，把真实背景翻译成面试官想要的语言。
  - A full job-hunt skill: role research, resume rewriting and round-by-round interview prep that puts your real background into the interviewer's language.
- https://github.com/yanliudesign/offer-toolkit-skill | stars=576 | pushed=2026-10-27 | os=- | flags=agent,cn
  - 六个求职工具打包成一个 skill 包：找机会、解码 JD、改简历、准备行为面试、对比 Offer 和谈薪，可以整包用也可以单独用。
  - Six job-hunt tools in one skill bundle: job discovery, JD decoding, resume building, behavioral interview prep, offer comparison and salary negotiation, usable together or separately.
- https://github.com/kkw114514-lang/campus-job-application-workflow | stars=187 | pushed=2026-09-24 | os=- | flags=agent,cn
  - 给能操作浏览器的 AI 助手用的校招网申模板：岗位可投性核实、网申填写、提交核验和记录。
  - A campus-recruiting application template for browser-capable AI agents: checks eligibility, fills forms, verifies submissions and keeps records.
- https://github.com/weeelin98/ResumeDom | stars=186 | pushed=2026-09-26 | os=- | flags=agent,cn
  - 面向美国科技岗位、以事实证据为核心的 Codex 简历 skill：评估、修改、按职位定制并输出可编辑的 LaTeX，绝不虚构经历。
  - An evidence-first Codex skill for US tech resumes: review, rewrite, tailor to a job and return editable LaTeX without inventing experience.
- https://github.com/lijiaqi-AI-Product-Manager/job_radar | stars=122 | pushed=2026-11-15 | os=- | flags=agent,cn
  - 给 AI 助手加的找工作技能：用自然语言查中国校招、实习、社招和招聘日历，返回岗位要求和来源链接，支持 Skill 和 MCP。
  - A job search skill for AI assistants: ask in plain language about campus, intern and experienced roles and hiring calendars in China, with requirements and source links; Skill and MCP.
- https://github.com/guzhezao/qiuzhao | stars=94 | pushed=2026-09-03 | os=- | flags=agent,cn
  - 国内校招求职 skill：岗位筛选、JD 评分、简历定制、表单预填和本地投递看板；不编造经历，不绕验证码，不在未确认时提交。
  - A campus-hiring skill for China: role filtering, JD scoring, resume tailoring, form pre-filling and a local dashboard; no invented experience, no CAPTCHA bypass, no unconfirmed submissions.

## 找职位：搜索和聚合 / Find jobs: search and aggregation

- https://github.com/speedyapply/JobSpy | stars=4749 | pushed=2026-11-13 | os=- | flags=auto
  - 职位抓取库：同时抓 LinkedIn、Indeed、Glassdoor、ZipRecruiter 等网站，汇总成一张表，很多求职工具的底层都用它。
  - A job scraping library that pulls LinkedIn, Indeed, Glassdoor, ZipRecruiter and more at once into one dataframe; many job tools build on it.
- https://github.com/strelov1/freehire | stars=3557 | pushed=2026-11-17 | os=- | flags=-
  - 面向求职者的开源职位搜索引擎：职位直接来自公司招聘页，没有猎头转发和失效链接，人和 Agent 都能用，提供 API。
  - An open-source job search engine for job seekers: postings come straight from company career pages, with no recruiter reposts or dead links, for you and your agent, with an API.
- https://github.com/can4hou6joeng4/boss-agent-cli | stars=2226 | pushed=2026-11-17 | os=- | flags=agent,cn,auto
  - 面向真人和 AI Agent 的国内招聘平台命令行：职位搜索、福利筛选、候选清单，输出结构化 JSON。
  - A CLI for a Chinese hiring platform, for people and AI agents: job search, benefits filtering and shortlists with structured JSON output.
- https://github.com/pinloop-ai/pinloop-cli | stars=570 | pushed=2026-10-26 | os=- | flags=agent
  - 给 AI 编程助手用的命令行职位库：每月汇集全球数百万白领职位，可以保存你的简历和偏好，逐条判断职位是否适合你。
  - A job board for your coding agent, run from the terminal: millions of white-collar postings a month worldwide, judged against your resume and preferences.
  - caveat: Commands talk to Pinloop's servers and need an account

## 每日更新的职位清单 / Job lists updated daily

- https://github.com/SimplifyJobs/Summer2027-Internships | stars=48430 | pushed=2026-11-17 | os=- | flags=-
  - 2027 年暑期实习清单：软件、数据科学、AI、量化、产品和硬件方向，美国为主。
  - Summer 2027 internships in software, data science, AI, quant, product and hardware, mostly US.
- https://github.com/speedyapply/2027-SWE-College-Jobs | stars=9635 | pushed=2026-11-16 | os=- | flags=-
  - 2027 届软件工程实习和应届职位清单，每日更新。
  - 2027 software engineering internship and new-grad jobs, updated daily.
- https://github.com/speedyapply/2027-AI-College-Jobs | stars=6650 | pushed=2026-11-16 | os=- | flags=-
  - 2027 届 AI / 机器学习实习和应届职位清单，每日更新。
  - 2027 AI/ML internship and new-grad jobs, updated daily.
- https://github.com/LorenzoLaCorte/european-tech-internships-2026 | stars=919 | pushed=2026-11-01 | os=- | flags=-
  - 欧洲科技实习、应届职位和研究机会，定期更新。
  - European tech internships, new-grad roles and research opportunities, updated regularly.
- https://github.com/namewyf/Campus2026 | stars=426 | pushed=2026-07-20 | os=- | flags=cn
  - 互联网校招和实习信息汇总，社区共同维护。
  - Community-maintained campus recruiting and internship information for Chinese internet companies.
- https://github.com/workopia/Australia-Casual-Part-Time-Jobs | stars=189 | pushed=2026-11-17 | os=- | flags=-
  - 澳大利亚临时工、兼职和圣诞季兼职职位，每日更新。
  - Australian casual, part-time and Christmas casual jobs, updated daily.
- https://github.com/hanzili/canada_sde_junior_new_grad_position | stars=179 | pushed=2026-11-09 | os=- | flags=-
  - 加拿大计算机应届和初级职位，每日更新。
  - Canadian CS new-grad and junior jobs, updated daily.
- https://github.com/workopia/Australia-Graduate-Jobs | stars=96 | pushed=2026-11-17 | os=- | flags=-
  - 澳大利亚毕业生项目、初级职位和实习，按行业分类，每日更新。
  - Australian graduate schemes, entry-level roles and internships by sector, updated daily.

## 写简历 / Build your resume

- https://github.com/reactive-resume/reactive-resume | stars=45840 | pushed=2026-11-16 | os=- | flags=selfhost
  - 免费开源的简历制作工具：写简历和求职信、检查内容、跟踪投递，可导出 PDF、Word、Markdown 或 JSON，也能部署在自己的服务器上。
  - A free, open-source resume builder for resumes and cover letters, with checks and application tracking; exports PDF, Word, Markdown or JSON and can run on your own infrastructure.
- https://github.com/posquit0/Awesome-CV | stars=28967 | pushed=2026-10-30 | os=- | flags=-
  - 经典的 LaTeX 简历和求职信模板。
  - The classic LaTeX template for resumes and cover letters.
- https://github.com/rendercv/rendercv | stars=17962 | pushed=2026-10-31 | os=- | flags=-
  - 面向学术和工程师的简历工具：用 YAML 写内容，一条命令生成排版精良的 PDF，方便用 Git 管理版本。
  - A resume builder for academics and engineers: write your CV as YAML and render a well-typeset PDF with one command, easy to version-control.
- https://github.com/JOYCEQL/magic-resume | stars=11456 | pushed=2026-11-02 | os=- | flags=cn
  - 现代化的在线简历编辑器：实时预览、自定义主题、导出 PDF，数据自动保存在本地。
  - A modern online resume editor with live preview, custom themes, PDF export and local auto-save.
- https://github.com/dyweb/awesome-resume-for-chinese | stars=8766 | pushed=2026-10-19 | os=- | flags=cn
  - 适合中文的简历模板合集（LaTeX、HTML 等）。
  - A collection of resume templates that work well for Chinese (LaTeX, HTML and more).
- https://github.com/BingyanStudio/LapisCV | stars=5141 | pushed=2026-07-16 | os=- | flags=cn
  - 用 Markdown 写简历：在 VS Code、Typora 或 Obsidian 里套用主题即可。
  - Write your resume in Markdown with a theme for VS Code, Typora or Obsidian.
- https://github.com/saadq/resumake.io | stars=3591 | pushed=2026-11-15 | os=- | flags=-
  - 免费开源的 LaTeX 简历生成网站：没有广告，不用注册，简历保存在你自己的浏览器里。
  - A free, open-source LaTeX resume generator with no ads or accounts; your resume is saved in your own browser.
- https://github.com/Nutlope/self.so | stars=3111 | pushed=2026-10-26 | os=- | flags=-
  - 上传简历 PDF，用 AI 生成个人主页。
  - Upload your resume PDF and get a personal site generated with AI.
- https://github.com/LingyiChen-AI/JadeAI | stars=2024 | pushed=2026-10-23 | os=- | flags=selfhost,cn
  - AI 简历生成器：拖拽编辑、AI 优化、50 套模板、多格式导出；桌面客户端支持 macOS 和 Windows，无需账号，数据在本机。
  - An AI resume builder with drag-and-drop editing, AI optimization, 50 templates and multi-format export; the macOS and Windows desktop app needs no account and keeps data local.
- https://github.com/yamlresume/yamlresume | stars=1559 | pushed=2026-11-17 | os=- | flags=-
  - 把简历当代码：用 YAML 写简历，生成专业排版的 PDF。
  - Resumes as code: write your resume in YAML and get a professionally typeset PDF.
- https://github.com/Arman19941113/dnd-resume | stars=1413 | pushed=2026-11-15 | os=- | flags=cn
  - 本地优先的拖拽式简历制作工具，直接在浏览器里编辑并导出 PDF。
  - A local-first drag-and-drop resume builder that edits and exports PDF right in the browser.
- https://github.com/youngyangyang04/Markdown-Resume-Template | stars=1052 | pushed=2026-09-08 | os=- | flags=cn
  - 程序员向的 Markdown 简历模板，简单明了，fork 后直接改。
  - A plain Markdown resume template for programmers; fork and edit.
- https://github.com/yunanwg/brilliant-CV | stars=850 | pushed=2026-11-16 | os=- | flags=-
  - 基于 Typst 的模块化简历模板，一套资料可以切换成针对不同职位或语言的版本。
  - A modular CV template for Typst; one set of data can switch between versions for different jobs or languages.
- https://github.com/magicapple123/ResumeForge | stars=423 | pushed=2026-11-17 | os=- | flags=selfhost,cn
  - 简历通：本地优先的 AI 简历工作台，无需注册登录，数据只保存在本机。
  - ResumeForge, a local-first AI resume workbench with no sign-up; data stays on your machine.

## 简历和职位匹配 / Match your resume to the job

- https://github.com/srbhr/Resume-Matcher | stars=29320 | pushed=2026-11-16 | os=- | flags=selfhost
  - 免费开源、可自己部署的 AI 简历工具：根据每一份职位描述定制简历，支持多种大模型。
  - A free, open-source, self-hosted AI resume tool that tailors your resume to each job description, with many LLMs supported.
- https://github.com/interviewstreet/hiring-agent | stars=7349 | pushed=2026-10-30 | os=- | flags=-
  - 招聘方视角的简历打分 Agent：从 PDF 提取结构化信息，结合 GitHub 数据给出可解释的评分。想知道 AI 怎么筛简历可以看它。
  - A resume-scoring agent from the hiring side: extracts structured data from PDFs, adds GitHub signals and gives an explainable score. Worth reading to see how AI screens resumes.
- https://github.com/DU8866-nice/jobfit | stars=2 | pushed=2026-10-29 | os=- | flags=cn
  - JobFit：对照职位描述逐条核对简历，每个“满足”都附简历原句作证据，修改建议只改你已有的句子，支持中英文。
  - JobFit checks your resume against a job description requirement by requirement; every match quotes your resume as evidence, and suggestions only rewrite lines you already have. Chinese and English.
  - caveat: Made by the author of this list

## 帮你填申请表（最后由你提交） / Fill application forms (you submit)

- https://github.com/AhmadHassan-BTed/FormFilla | stars=4657 | pushed=2026-11-03 | os=- | flags=selfhost
  - 本地优先的浏览器扩展：用本地保存的个人资料填 Workday、Greenhouse、Lever 等申请系统的表单，全程不联网、不用大模型。
  - A local-first browser extension that fills Workday, Greenhouse, Lever and other application forms from locally stored profile data, with no network calls and no LLM.
- https://github.com/qbeka/jev-job-search | stars=373 | pushed=2026-11-13 | os=- | flags=agent
  - 找软件实习和应届职位，在你能看着的 Chrome 窗口里填好申请表，逐项回读页面上的答案，只发送你批准的内容。
  - Finds software internships and new-grad jobs, fills each application in a Chrome window you can watch, reads every answer back from the page and sends only what you approve.
- https://github.com/aurostars/Job-Application-Helper | stars=128 | pushed=2026-10-18 | os=- | flags=cn
  - 秋招网申助手：Chrome 和 Edge 扩展，集中管理求职资料，识别招聘表单并快速填入个人信息、教育经历和项目经历，带投递记录。
  - A Chrome and Edge extension for campus applications in China: keeps your details in one place, detects application forms and fills personal, education and project fields, with an application log.
- https://github.com/extrasmall0/dear-hiring-manager | stars=113 | pushed=2026-07-15 | os=- | flags=agent,selfhost
  - Claude Code 插件：读职位描述、评估匹配、用保存的资料填好每一项，并用你的口吻起草开放题和求职信，填完后把最后的发送留给你。
  - A Claude Code plugin that reads the job description, scores fit, fills every field from your saved profile and drafts answers and a cover letter in your voice, leaving the final send to you.

## 全自动投递（先看风险） / Fully automatic applying (read the risks first)

- https://github.com/feder-cr/Jobs_Applier_AI_Agent | stars=32571 | pushed=2026-11-16 | os=- | flags=auto
  - AIHawk：读你的简历去搜索匹配的职位，由你挑选后在公司的申请表上自动填写并提交。
  - AIHawk reads your resume, searches for matching postings, and after you pick, fills in and sends each application on the company's own form.
- https://github.com/loks666/get_jobs | stars=9753 | pushed=2026-11-12 | os=- | flags=cn,auto
  - 国内招聘平台的自动投简历脚本，支持 Boss、前程无忧、猎聘、智联招聘。
  - An auto-apply script for Chinese hiring platforms, covering Boss, 51job, Liepin and Zhaopin.
  - caveat: The author still recommends applying manually on Boss; non-commercial license
- https://github.com/GodsScion/Auto_job_applier_linkedIn | stars=3044 | pushed=2026-11-08 | os=- | flags=auto
  - 在自己电脑上用自己的 LinkedIn 账号自动申请职位，可选用 AI 回答申请问题。
  - Automates LinkedIn applications on your own computer with your own account, optionally using AI to answer application questions.
- https://github.com/Ocyss/boss-helper | stars=2547 | pushed=2026-11-10 | os=- | flags=cn,auto
  - Boss 直聘助手：浏览器扩展，批量投递、高级筛选、AI 自动打招呼。
  - A browser extension for Boss Zhipin with batch applying, advanced filters and AI greetings.
  - caveat: The author warns of bans and reduced account ranking

## 面试准备 / Interview prep

- https://github.com/donnemartin/system-design-primer | stars=378145 | pushed=2026-09-15 | os=- | flags=-
  - 系统设计入门：学习设计大型系统，准备系统设计面试。
  - Learn how to design large-scale systems and prep for the system design interview.
- https://github.com/jwasham/coding-interview-university | stars=364454 | pushed=2026-11-07 | os=- | flags=-
  - 成为软件工程师的完整计算机科学自学计划。
  - A complete computer science study plan to become a software engineer.
- https://github.com/Snailclimb/JavaGuide | stars=159594 | pushed=2026-10-25 | os=- | flags=cn
  - Java 面试和后端通用面试指南，覆盖计算机基础、数据库、分布式、系统设计和 AI 应用开发。
  - A Java and backend interview guide in Chinese, covering CS basics, databases, distributed systems, system design and AI application development.
- https://github.com/yangshun/tech-interview-handbook | stars=143310 | pushed=2026-08-07 | os=- | flags=-
  - 给忙碌工程师的编程面试准备材料，涵盖简历、算法、行为面试和谈薪。
  - Curated coding interview preparation for busy engineers, covering resumes, algorithms, behavioral interviews and negotiation.
- https://github.com/karanpratapsingh/system-design | stars=46941 | pushed=2026-10-18 | os=- | flags=-
  - 学习如何设计大规模系统，准备系统设计面试。
  - Learn how to design systems at scale and prepare for system design interviews.
- https://github.com/yangshun/front-end-interview-handbook | stars=44002 | pushed=2026-10-05 | os=- | flags=-
  - 给忙碌工程师的前端面试准备材料。
  - Front-end interview preparation materials for busy engineers.
- https://github.com/wdndev/llm_interview_note | stars=15401 | pushed=2026-06-14 | os=- | flags=cn
  - 大语言模型算法和应用工程师的知识点与面试题。
  - Knowledge notes and interview questions for LLM algorithm and application engineers, in Chinese.
- https://github.com/adongwanai/AgentGuide | stars=12033 | pushed=2026-11-05 | os=- | flags=cn
  - AI Agent 开发指南，附大模型面试题库。
  - An AI agent development guide in Chinese with a large LLM interview question bank.
- https://github.com/alexeygrigorev/data-science-interviews | stars=10234 | pushed=2026-11-13 | os=- | flags=-
  - 数据科学面试问题和答案。
  - Data science interview questions and answers.
- https://github.com/alirezadir/AIMLInterviews | stars=10006 | pushed=2026-10-08 | os=- | flags=-
  - 生成式 AI、Agent、多模态等方向的 AI/ML 面试指南。
  - A guide to AI/ML interviews across generative AI, agentic AI, multimodal AI and more.
- https://github.com/WeThinkIn/AIGC-Interview-Book | stars=5255 | pushed=2026-11-16 | os=- | flags=cn
  - AIGC、大模型和 AI Agent 算法工程师面试资源。
  - Interview resources for AIGC, LLM and AI agent algorithm engineers, in Chinese.
- https://github.com/amitshekhariitbhu/ai-engineering-interview-questions | stars=3668 | pushed=2026-11-17 | os=- | flags=-
  - AI 工程面试的问题和答案速查。
  - A cheat sheet of AI engineering interview questions and answers.
- https://github.com/Snailclimb/interview-guide | stars=3518 | pushed=2026-10-08 | os=- | flags=cn
  - 开源的 AI 面试平台：简历分析、文字和语音模拟面试、知识库题库面试，完整功能免费。
  - An open-source AI interview platform with resume analysis, text and voice mock interviews and knowledge-base question sets; all features are free.
- https://github.com/Exorust/TorchLeet | stars=2639 | pushed=2026-11-06 | os=- | flags=-
  - PyTorch 版的 LeetCode：来自真实面试的 ML/AI 编程题。
  - LeetCode for PyTorch: ML/AI interview problems from real interviews.
- https://github.com/RezaSi/go-interview-practice | stars=2502 | pushed=2026-11-12 | os=- | flags=-
  - 交互式 Go 面试练习平台：编程题、即时反馈和 AI 模拟面试。
  - An interactive Go interview practice platform with coding challenges, instant feedback and AI interview simulation.

## 求职指南 / Job search guides

- https://github.com/AndrewStetsenko/tech-jobs-with-relocation | stars=4603 | pushed=2026-11-12 | os=- | flags=-
  - 去国外找科技工作的一站式指南，包含提供搬迁支持的公司和资源。
  - An all-in-one guide to getting a tech job abroad, with companies and resources that offer relocation.
- https://github.com/wuyoueeee/CS-Job-Guide | stars=355 | pushed=2026-10-18 | os=- | flags=cn
  - 计算机专业用 AI 求职的开源手册：选方向、写简历、过面试到 Offer 决策和签约避坑，适合实习、春招和秋招。
  - An open handbook in Chinese for CS students job hunting with AI, from choosing a direction and writing a resume to interviews, offer decisions and contract pitfalls.
- https://github.com/AIPMAndy/how-to-get-offer | stars=90 | pushed=2026-11-16 | os=- | flags=cn
  - 社招拿 Offer 指南：定位、简历、渠道和内推、面试、谈薪到入职，附 30 天执行表和模板。
  - A guide in Chinese to landing an offer as an experienced hire, from positioning and resume to referrals, interviews, negotiation and onboarding, with a 30-day plan and templates.

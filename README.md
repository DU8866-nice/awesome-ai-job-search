<!-- 本文件由 scripts/build_readme.py 生成，请勿直接修改。要改内容请编辑 data/tools.yaml 后重新生成。 -->

# Awesome AI Job Search · AI 求职工具大全

[![Stars](https://img.shields.io/github/stars/DU8866-nice/awesome-ai-job-search?style=flat-square)](https://github.com/DU8866-nice/awesome-ai-job-search) [![Last commit](https://img.shields.io/github/last-commit/DU8866-nice/awesome-ai-job-search?style=flat-square)](https://github.com/DU8866-nice/awesome-ai-job-search/commits) [![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey?style=flat-square)](LICENSE) [![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)](CONTRIBUTING.md)

**简体中文** | [English](README.en.md)

> 用 AI 找工作的开源工具精选：求职 Agent、职位搜索、简历制作与匹配、填表投递、面试准备。每个工具标明是否在 AI 编程助手里运行、数据是否留在自己手里、是否中文友好、会不会自动操作招聘网站，星标每周自动刷新。

找工作正在变成一件可以交给 AI 帮忙的事。今年 GitHub 上涨得最快的一批项目里，就有把 Claude Code 变成求职助手的 Agent：它们读职位描述、对照你的简历打分、改出针对性的简历、起草求职信，再帮你记下每一次投递。

工具多了，也更难挑：有的要自己部署，有的装进 AI 助手就能用；有的只帮你准备材料，有的会用你的账号自动海投，可能让账号被封。这份清单按求职阶段整理这些工具，并把这些差别标出来。

收录 77 个项目 · 数据更新于 2026-11-17

## 目录

- [按求职阶段找工具](#pick)
- [用之前先知道](#rules)
- [一站式求职助手](#cat-pipeline)（13）
- [求职 Skill：装进 Claude Code、Codex 就能用](#cat-skills)（9）
- [找职位：搜索和聚合](#cat-find)（4）
- [每日更新的职位清单](#cat-lists)（8）
- [写简历](#cat-resume)（14）
- [简历和职位匹配](#cat-match)（3）
- [帮你填申请表（最后由你提交）](#cat-apply)（4）
- [全自动投递（先看风险）](#cat-auto)（4）
- [面试准备](#cat-interview)（15）
- [求职指南](#cat-guides)（3）
- [常见问题](#faq)
- [让 AI 助手帮你挑](#finder)
- [相关合集](#related)
- [参与贡献](#contributing)

<a id="pick"></a>
## 按求职阶段找工具

| 阶段 | 想省事 | 想把数据留在自己手里 | 国内求职 |
|---|---|---|---|
| 一站式：找职位、改简历、跟进 | [career-ops](https://github.com/career-ops-hq/career-ops)、[ai-job-search](https://github.com/ai-job-search-dev/ai-job-search) | [Dossier](https://github.com/AienTech/dossier)、[JobOps](https://github.com/DaKheera47/job-ops)、[JobSync](https://github.com/Gsync/jobsync) | [MyCareer](https://github.com/low-hands/MyCareer)、[OfferPilot](https://github.com/offercontext/offerPilot)、[录阶](https://github.com/Chozzc/Lujie-Careerkit) |
| 找职位 | [freehire](https://github.com/strelov1/freehire)、[实习清单](https://github.com/SimplifyJobs/Summer2027-Internships) | [JustHireMe](https://github.com/vasu-devs/JustHireMe) | [job_radar](https://github.com/lijiaqi-AI-Product-Manager/job_radar)、[Campus2026](https://github.com/namewyf/Campus2026) |
| 写简历 | [Reactive Resume](https://github.com/reactive-resume/reactive-resume)、[RenderCV](https://github.com/rendercv/rendercv) | [简历通](https://github.com/magicapple123/ResumeForge)、[JadeAI](https://github.com/LingyiChen-AI/JadeAI) | [Magic Resume](https://github.com/JOYCEQL/magic-resume)、[中文简历模板](https://github.com/dyweb/awesome-resume-for-chinese) |
| 对照职位改简历 | [ResumeSkills](https://github.com/Paramchoudhary/ResumeSkills) | [Resume Matcher](https://github.com/srbhr/Resume-Matcher) | [JobFit](https://github.com/DU8866-nice/jobfit)、[ASu-skills](https://github.com/Hisn00w/ASu-skills) |
| 填申请表 | [jev-job-search](https://github.com/qbeka/jev-job-search) | [FormFilla](https://github.com/AhmadHassan-BTed/FormFilla) | [秋招网申助手](https://github.com/aurostars/Job-Application-Helper) |
| 准备面试 | [Tech Interview Handbook](https://github.com/yangshun/tech-interview-handbook) | [interview-guide](https://github.com/Snailclimb/interview-guide) | [JavaGuide](https://github.com/Snailclimb/JavaGuide)、[实习.skill](https://github.com/agentenatalie/get-job.skill) |

<a id="rules"></a>
## 用之前先知道

> [!IMPORTANT]
> - **别让 AI 编经历。** 让 AI 改写的是你真实做过的事。编出来的技能和项目，面试一追问就露馅，背景调查也过不了。优先选写明“不编造经历”、每条结论都能对回简历原文的工具。
> - **自动投递有风险。** 标 ⚠️ 的工具会用你的账号自动抓取或投递，招聘平台的条款通常禁止这样做，账号可能被限制或封禁。更稳妥的是让工具准备材料、填好表单，由你检查后提交。
> - **简历是敏感信息。** 简历里有电话、住址和工作经历。标 🏠 的工具数据留在自己的电脑或服务器上；用云端大模型时，简历内容会发给模型服务商。
> - **AI 打的匹配分只是参考。** 不同工具算法不同，分数高不代表一定有面试，分数低也不代表不能投。重点看它指出的缺口是否属实。
> - **留意招聘诈骗。** 要求先交钱、押证件或下载陌生软件的“职位”都不要碰，职位信息以公司官网为准。

本清单不收录在面试或笔试中实时给答案的“隐身”作弊工具，也不收录专门绕过验证码和反爬的工具。

**图例**：🤖 在 Claude Code、Codex 等 AI 编程助手里运行 · 🏠 本地运行或自己部署，数据在自己手里 · 🀄 中文友好（有中文界面或文档，或专为国内求职做）· ⚠️ 会自动操作招聘网站（抓取或投递），有封号风险 · 🆕 近 60 天新建 · 💤 超过一年未更新 · 📦 已归档

> [!NOTE]
> 标记依据各项目 README 的说明，只在 README 写明时才标，没标不代表不是。收录指核对过仓库说明，不等于逐个实测过，更不保证能拿到面试。

<a id="cat-pipeline"></a>
## 一站式求职助手

把找职位、评估匹配、改简历、写求职信和跟踪投递放在一起的工具。这里收录的都不替你点“提交”，最后一步由你决定。

- **[career-ops](https://github.com/career-ops-hq/career-ops)** · ★ 83.2k · 🤖<br>开源的 AI 求职 Agent：贴一个职位进去，在你自己的电脑上判断职位是否还在招、和你匹不匹配，再定制简历、起草回答，最后由你点提交。<br><sub>更新于 2026-11 · MIT</sub>
- **[ai-job-search](https://github.com/ai-job-search-dev/ai-job-search)** · ★ 72.1k · 🤖<br>建在 Claude Code 上的求职框架：fork 后填好个人档案，让 Claude 评估职位、定制简历、写求职信并帮你准备面试。<br><sub>更新于 2026-11 · MIT</sub>
- **[dossier](https://github.com/AienTech/dossier)** · ★ 5.2k · 🏠 🆕<br>部署在自己服务器上的求职工具：一份个人档案，为每个职位生成只用档案事实的定制简历和求职信，并跟踪每次投递。<br><sub>更新于 2026-11 · AGPL-3.0</sub><br><sub>💡 可用 Ollama、LM Studio 本地模型，也可接云端模型</sub>
- **[job-ops](https://github.com/DaKheera47/job-ops)** · ★ 4.1k · 🏠<br>JobOps：一个页面搜 LinkedIn、Indeed、Glassdoor 等十多个招聘网站，为每个职位改写简历、打匹配分、查签证担保情况，并跟踪所有投递。<br><sub>更新于 2026-10</sub><br><sub>💡 作者明确不做自动投递，每个职位仍由你自己申请</sub>
- **[JustHireMe](https://github.com/vasu-devs/JustHireMe)** · ★ 2.3k · 🏠<br>本地优先的求职桌面工作台：抓取职位、按匹配度排序、生成定制的申请材料，提供 Windows、macOS 和 Linux 安装包。<br><sub>更新于 2026-10 · AGPL-3.0</sub>
- **[BossHunter](https://github.com/shengjidaguai-china/BossHunter)** · ★ 1.6k · 🏠 🀄 ⚠️<br>国内招聘平台的求职 Agent：本地完成岗位采集、AI 评分、定制简历和回复监测，所有投递必须先经人工确认。<br><sub>更新于 2026-11</sub><br><sub>💡 作者提示自动化操作招聘平台有账号受限或封禁风险；许可证为非商业</sub>
- **[jobsync](https://github.com/Gsync/jobsync)** · ★ 1.5k · 🏠<br>自己部署的求职助手：跟踪每次投递，AI 审阅简历、匹配职位并自动发现新职位，可用 Ollama 本地模型，带 MCP 服务。<br><sub>更新于 2026-11 · MIT</sub>
- **[JobHuntBot](https://github.com/DanielPan12/JobHuntBot)** · ★ 890 · 🤖 🀄<br>由 Agent 带着走的求职投递流程加本地进度看板，适用于 Claude Code、Codex、Cursor 等；不是一键海投，最终提交需要你授权。<br><sub>更新于 2026-10 · MIT</sub>
- **[offerPilot](https://github.com/offercontext/offerPilot)** · ★ 767 · 🏠 🀄<br>OfferPilot：开源、本地优先的求职 Agent 工作台，把投递、简历、面试和 Offer 放在一起；不会自动投递，也不会替你联系招聘方。<br><sub>更新于 2026-11 · AGPL-3.0</sub><br><sub>💡 基础投递记录不需要 AI；使用 AI 时需要接自己的模型服务</sub>
- **[Lujie-Careerkit](https://github.com/Chozzc/Lujie-Careerkit)** · ★ 484 · 🀄<br>录阶：面向实习、校招的求职 Agent 工作台，覆盖简历编辑、JD 匹配、投递跟进、模拟面试和复盘。<br><sub>更新于 2026-11 · Apache-2.0</sub>
- **[autopilot-jobhunt](https://github.com/tarunlnmiit/autopilot-jobhunt)** · ★ 219<br>每晚扫描 130 多个公司招聘页，用大模型按你的简历打分，把最匹配的职位发到 Telegram，并按需起草定制简历和求职信。<br><sub>更新于 2026-09 · MIT</sub><br><sub>💡 只起草，不投递</sub>
- **[JobNavigator](https://github.com/vesaias/JobNavigator)** · ★ 188 · 🏠<br>自己部署、支持多账号的求职自动化：抓取公司招聘页和聚合站，用大模型给职位打分、定制简历和求职信，Telegram 提醒，一家人可以共用一套。<br><sub>更新于 2026-11 · MIT</sub>
- **[MyCareer](https://github.com/low-hands/MyCareer)** · ★ 106 · 🏠 🀄<br>跑在自己电脑上的 AI 求职助手：找岗位、看匹配、改简历、练面试、管投递，数据存在本机 SQLite；每条“符合”都引用简历原文。<br><sub>更新于 2026-10 · MIT</sub>

<a id="cat-skills"></a>
## 求职 Skill：装进 Claude Code、Codex 就能用

不用部署，把 skill 装进你已经在用的 AI 助手，用对话完成改简历、分析 JD 和准备面试。

- **[ASu-skills](https://github.com/Hisn00w/ASu-skills)** · ★ 6.4k · 🤖 🀄<br>中文求职工作流插件：九个入口覆盖开源贡献、简历提升、简历制作、岗位匹配、投递填写、面试准备和校招进度管理。<br><sub>更新于 2026-11 · MIT</sub>
- **[ResumeSkills](https://github.com/Paramchoudhary/ResumeSkills)** · ★ 3.2k · 🤖<br>一组面向简历优化、求职申请和职业发展的 AI Agent skill，包括 ATS 优化、要点改写和面试准备。<br><sub>更新于 2026-06 · MIT</sub>
- **[shushu-internship-tool](https://github.com/LiuMengxuan04/shushu-internship-tool)** · ★ 2.2k · 🤖 🀄<br>鼠鼠实习妙妙工具：把岗位描述变成项目，把项目变成简历，把简历变成面试准备，适合零经验或经验少的计算机方向同学。<br><sub>更新于 2026-06</sub>
- **[get-job.skill](https://github.com/agentenatalie/get-job.skill)** · ★ 754 · 🤖 🀄<br>实习.skill：从岗位调研、简历改写到分轮次面试准备，把真实背景翻译成面试官想要的语言。<br><sub>更新于 2026-08</sub>
- **[offer-toolkit-skill](https://github.com/yanliudesign/offer-toolkit-skill)** · ★ 576 · 🤖 🀄<br>六个求职工具打包成一个 skill 包：找机会、解码 JD、改简历、准备行为面试、对比 Offer 和谈薪，可以整包用也可以单独用。<br><sub>更新于 2026-10 · MIT</sub>
- **[campus-job-application-workflow](https://github.com/kkw114514-lang/campus-job-application-workflow)** · ★ 187 · 🤖 🀄 🆕<br>给能操作浏览器的 AI 助手用的校招网申模板：岗位可投性核实、网申填写、提交核验和记录。<br><sub>更新于 2026-09 · MIT</sub>
- **[ResumeDom](https://github.com/weeelin98/ResumeDom)** · ★ 186 · 🤖 🀄<br>面向美国科技岗位、以事实证据为核心的 Codex 简历 skill：评估、修改、按职位定制并输出可编辑的 LaTeX，绝不虚构经历。<br><sub>更新于 2026-09</sub>
- **[job_radar](https://github.com/lijiaqi-AI-Product-Manager/job_radar)** · ★ 122 · 🤖 🀄 🆕<br>给 AI 助手加的找工作技能：用自然语言查中国校招、实习、社招和招聘日历，返回岗位要求和来源链接，支持 Skill 和 MCP。<br><sub>更新于 2026-11 · MIT</sub>
- **[qiuzhao](https://github.com/guzhezao/qiuzhao)** · ★ 94 · 🤖 🀄<br>国内校招求职 skill：岗位筛选、JD 评分、简历定制、表单预填和本地投递看板；不编造经历，不绕验证码，不在未确认时提交。<br><sub>更新于 2026-09 · MIT</sub>

<a id="cat-find"></a>
## 找职位：搜索和聚合

- **[JobSpy](https://github.com/speedyapply/JobSpy)** · ★ 4.7k · ⚠️<br>职位抓取库：同时抓 LinkedIn、Indeed、Glassdoor、ZipRecruiter 等网站，汇总成一张表，很多求职工具的底层都用它。<br><sub>更新于 2026-11 · MIT</sub>
- **[freehire](https://github.com/strelov1/freehire)** · ★ 3.6k<br>面向求职者的开源职位搜索引擎：职位直接来自公司招聘页，没有猎头转发和失效链接，人和 Agent 都能用，提供 API。<br><sub>更新于 2026-11 · MIT</sub>
- **[boss-agent-cli](https://github.com/can4hou6joeng4/boss-agent-cli)** · ★ 2.2k · 🤖 🀄 ⚠️<br>面向真人和 AI Agent 的国内招聘平台命令行：职位搜索、福利筛选、候选清单，输出结构化 JSON。<br><sub>更新于 2026-11 · MIT</sub>
- **[pinloop-cli](https://github.com/pinloop-ai/pinloop-cli)** · ★ 570 · 🤖<br>给 AI 编程助手用的命令行职位库：每月汇集全球数百万白领职位，可以保存你的简历和偏好，逐条判断职位是否适合你。<br><sub>更新于 2026-10 · MIT</sub><br><sub>💡 命令连接 Pinloop 的服务器，需要注册账号</sub>

<a id="cat-lists"></a>
## 每日更新的职位清单

直接在 GitHub 上看的实习、应届和初级职位清单。这类清单多由求职产品公司维护，页面里会推广自家产品。

- **[Summer2027-Internships](https://github.com/SimplifyJobs/Summer2027-Internships)** · ★ 48.4k<br>2027 年暑期实习清单：软件、数据科学、AI、量化、产品和硬件方向，美国为主。<br><sub>更新于 2026-11</sub>
- **[2027-SWE-College-Jobs](https://github.com/speedyapply/2027-SWE-College-Jobs)** · ★ 9.6k<br>2027 届软件工程实习和应届职位清单，每日更新。<br><sub>更新于 2026-11</sub>
- **[2027-AI-College-Jobs](https://github.com/speedyapply/2027-AI-College-Jobs)** · ★ 6.7k<br>2027 届 AI / 机器学习实习和应届职位清单，每日更新。<br><sub>更新于 2026-11</sub>
- **[european-tech-internships-2026](https://github.com/LorenzoLaCorte/european-tech-internships-2026)** · ★ 919<br>欧洲科技实习、应届职位和研究机会，定期更新。<br><sub>更新于 2026-11</sub>
- **[Campus2026](https://github.com/namewyf/Campus2026)** · ★ 426 · 🀄<br>互联网校招和实习信息汇总，社区共同维护。<br><sub>更新于 2026-07</sub>
- **[Australia-Casual-Part-Time-Jobs](https://github.com/workopia/Australia-Casual-Part-Time-Jobs)** · ★ 189<br>澳大利亚临时工、兼职和圣诞季兼职职位，每日更新。<br><sub>更新于 2026-11</sub>
- **[canada_sde_junior_new_grad_position](https://github.com/hanzili/canada_sde_junior_new_grad_position)** · ★ 179<br>加拿大计算机应届和初级职位，每日更新。<br><sub>更新于 2026-11</sub>
- **[Australia-Graduate-Jobs](https://github.com/workopia/Australia-Graduate-Jobs)** · ★ 96<br>澳大利亚毕业生项目、初级职位和实习，按行业分类，每日更新。<br><sub>更新于 2026-11</sub>

<a id="cat-resume"></a>
## 写简历

在线编辑器、把简历当代码写的工具，以及经典模板。

- **[reactive-resume](https://github.com/reactive-resume/reactive-resume)** · ★ 45.8k · 🏠<br>免费开源的简历制作工具：写简历和求职信、检查内容、跟踪投递，可导出 PDF、Word、Markdown 或 JSON，也能部署在自己的服务器上。<br><sub>更新于 2026-11 · MIT</sub>
- **[Awesome-CV](https://github.com/posquit0/Awesome-CV)** · ★ 29.0k<br>经典的 LaTeX 简历和求职信模板。<br><sub>更新于 2026-10 · LPPL-1.3c</sub>
- **[rendercv](https://github.com/rendercv/rendercv)** · ★ 18.0k<br>面向学术和工程师的简历工具：用 YAML 写内容，一条命令生成排版精良的 PDF，方便用 Git 管理版本。<br><sub>更新于 2026-10 · MIT</sub>
- **[magic-resume](https://github.com/JOYCEQL/magic-resume)** · ★ 11.5k · 🀄<br>现代化的在线简历编辑器：实时预览、自定义主题、导出 PDF，数据自动保存在本地。<br><sub>更新于 2026-11</sub>
- **[awesome-resume-for-chinese](https://github.com/dyweb/awesome-resume-for-chinese)** · ★ 8.8k · 🀄<br>适合中文的简历模板合集（LaTeX、HTML 等）。<br><sub>更新于 2026-10</sub>
- **[LapisCV](https://github.com/BingyanStudio/LapisCV)** · ★ 5.1k · 🀄<br>用 Markdown 写简历：在 VS Code、Typora 或 Obsidian 里套用主题即可。<br><sub>更新于 2026-07 · MIT</sub>
- **[resumake.io](https://github.com/saadq/resumake.io)** · ★ 3.6k<br>免费开源的 LaTeX 简历生成网站：没有广告，不用注册，简历保存在你自己的浏览器里。<br><sub>更新于 2026-11</sub>
- **[self.so](https://github.com/Nutlope/self.so)** · ★ 3.1k<br>上传简历 PDF，用 AI 生成个人主页。<br><sub>更新于 2026-10 · MIT</sub>
- **[JadeAI](https://github.com/LingyiChen-AI/JadeAI)** · ★ 2.0k · 🏠 🀄<br>AI 简历生成器：拖拽编辑、AI 优化、50 套模板、多格式导出；桌面客户端支持 macOS 和 Windows，无需账号，数据在本机。<br><sub>更新于 2026-10 · Apache-2.0</sub>
- **[yamlresume](https://github.com/yamlresume/yamlresume)** · ★ 1.6k<br>把简历当代码：用 YAML 写简历，生成专业排版的 PDF。<br><sub>更新于 2026-11 · MIT</sub>
- **[dnd-resume](https://github.com/Arman19941113/dnd-resume)** · ★ 1.4k · 🀄<br>本地优先的拖拽式简历制作工具，直接在浏览器里编辑并导出 PDF。<br><sub>更新于 2026-11 · AGPL-3.0</sub>
- **[Markdown-Resume-Template](https://github.com/youngyangyang04/Markdown-Resume-Template)** · ★ 1.1k · 🀄<br>程序员向的 Markdown 简历模板，简单明了，fork 后直接改。<br><sub>更新于 2026-09</sub>
- **[brilliant-CV](https://github.com/yunanwg/brilliant-CV)** · ★ 850<br>基于 Typst 的模块化简历模板，一套资料可以切换成针对不同职位或语言的版本。<br><sub>更新于 2026-11 · Apache-2.0</sub>
- **[ResumeForge](https://github.com/magicapple123/ResumeForge)** · ★ 423 · 🏠 🀄<br>简历通：本地优先的 AI 简历工作台，无需注册登录，数据只保存在本机。<br><sub>更新于 2026-11 · Apache-2.0</sub>

<a id="cat-match"></a>
## 简历和职位匹配

投之前先对照职位描述检查简历：缺哪些要求、哪些关键词没出现、哪些句子可以改。

- **[Resume-Matcher](https://github.com/srbhr/Resume-Matcher)** · ★ 29.3k · 🏠<br>免费开源、可自己部署的 AI 简历工具：根据每一份职位描述定制简历，支持多种大模型。<br><sub>更新于 2026-11 · Apache-2.0</sub>
- **[hiring-agent](https://github.com/interviewstreet/hiring-agent)** · ★ 7.3k<br>招聘方视角的简历打分 Agent：从 PDF 提取结构化信息，结合 GitHub 数据给出可解释的评分。想知道 AI 怎么筛简历可以看它。<br><sub>更新于 2026-10 · MIT</sub>
- **[jobfit](https://github.com/DU8866-nice/jobfit)** · ★ 2 · 🀄 🆕<br>JobFit：对照职位描述逐条核对简历，每个“满足”都附简历原句作证据，修改建议只改你已有的句子，支持中英文。<br><sub>更新于 2026-10 · MIT</sub><br><sub>💡 本清单作者的项目</sub>

<a id="cat-apply"></a>
## 帮你填申请表（最后由你提交）

网申最费时间的是重复填表。这些工具帮你填，停在提交之前。

- **[FormFilla](https://github.com/AhmadHassan-BTed/FormFilla)** · ★ 4.7k · 🏠<br>本地优先的浏览器扩展：用本地保存的个人资料填 Workday、Greenhouse、Lever 等申请系统的表单，全程不联网、不用大模型。<br><sub>更新于 2026-11 · MIT</sub>
- **[jev-job-search](https://github.com/qbeka/jev-job-search)** · ★ 373 · 🤖 🆕<br>找软件实习和应届职位，在你能看着的 Chrome 窗口里填好申请表，逐项回读页面上的答案，只发送你批准的内容。<br><sub>更新于 2026-11 · MIT</sub>
- **[Job-Application-Helper](https://github.com/aurostars/Job-Application-Helper)** · ★ 128 · 🀄<br>秋招网申助手：Chrome 和 Edge 扩展，集中管理求职资料，识别招聘表单并快速填入个人信息、教育经历和项目经历，带投递记录。<br><sub>更新于 2026-10</sub>
- **[dear-hiring-manager](https://github.com/extrasmall0/dear-hiring-manager)** · ★ 113 · 🤖 🏠<br>Claude Code 插件：读职位描述、评估匹配、用保存的资料填好每一项，并用你的口吻起草开放题和求职信，填完后把最后的发送留给你。<br><sub>更新于 2026-07 · MIT</sub>

<a id="cat-auto"></a>
## 全自动投递（先看风险）

这些工具会用你的账号自动投递或自动打招呼。招聘平台的条款通常禁止自动化，账号可能被限制或封禁。列在这里是因为它们确实很多人用，不代表推荐。

- **[Jobs_Applier_AI_Agent](https://github.com/feder-cr/Jobs_Applier_AI_Agent)** · ★ 32.6k · ⚠️<br>AIHawk：读你的简历去搜索匹配的职位，由你挑选后在公司的申请表上自动填写并提交。<br><sub>更新于 2026-11 · MIT</sub>
- **[get_jobs](https://github.com/loks666/get_jobs)** · ★ 9.8k · 🀄 ⚠️<br>国内招聘平台的自动投简历脚本，支持 Boss、前程无忧、猎聘、智联招聘。<br><sub>更新于 2026-11</sub><br><sub>💡 作者建议 Boss 仍以手动投递为主；许可证为非商业</sub>
- **[Auto_job_applier_linkedIn](https://github.com/GodsScion/Auto_job_applier_linkedIn)** · ★ 3.0k · ⚠️<br>在自己电脑上用自己的 LinkedIn 账号自动申请职位，可选用 AI 回答申请问题。<br><sub>更新于 2026-11 · MIT</sub>
- **[boss-helper](https://github.com/Ocyss/boss-helper)** · ★ 2.5k · 🀄 ⚠️<br>Boss 直聘助手：浏览器扩展，批量投递、高级筛选、AI 自动打招呼。<br><sub>更新于 2026-11 · MIT</sub><br><sub>💡 作者提示有封号、权重降低等风险</sub>

<a id="cat-interview"></a>
## 面试准备

AI 模拟面试工具，加上长期维护的面试题库和学习路线。

- **[system-design-primer](https://github.com/donnemartin/system-design-primer)** · ★ 378.1k<br>系统设计入门：学习设计大型系统，准备系统设计面试。<br><sub>更新于 2026-09</sub>
- **[coding-interview-university](https://github.com/jwasham/coding-interview-university)** · ★ 364.5k<br>成为软件工程师的完整计算机科学自学计划。<br><sub>更新于 2026-11 · CC-BY-SA-4.0</sub>
- **[JavaGuide](https://github.com/Snailclimb/JavaGuide)** · ★ 159.6k · 🀄<br>Java 面试和后端通用面试指南，覆盖计算机基础、数据库、分布式、系统设计和 AI 应用开发。<br><sub>更新于 2026-10 · Apache-2.0</sub>
- **[tech-interview-handbook](https://github.com/yangshun/tech-interview-handbook)** · ★ 143.3k<br>给忙碌工程师的编程面试准备材料，涵盖简历、算法、行为面试和谈薪。<br><sub>更新于 2026-08 · MIT</sub>
- **[system-design](https://github.com/karanpratapsingh/system-design)** · ★ 46.9k<br>学习如何设计大规模系统，准备系统设计面试。<br><sub>更新于 2026-10</sub>
- **[front-end-interview-handbook](https://github.com/yangshun/front-end-interview-handbook)** · ★ 44.0k<br>给忙碌工程师的前端面试准备材料。<br><sub>更新于 2026-10 · MIT</sub>
- **[llm_interview_note](https://github.com/wdndev/llm_interview_note)** · ★ 15.4k · 🀄<br>大语言模型算法和应用工程师的知识点与面试题。<br><sub>更新于 2026-06</sub>
- **[AgentGuide](https://github.com/adongwanai/AgentGuide)** · ★ 12.0k · 🀄<br>AI Agent 开发指南，附大模型面试题库。<br><sub>更新于 2026-11 · CC-BY-4.0</sub>
- **[data-science-interviews](https://github.com/alexeygrigorev/data-science-interviews)** · ★ 10.2k<br>数据科学面试问题和答案。<br><sub>更新于 2026-11 · CC-BY-4.0</sub>
- **[AIMLInterviews](https://github.com/alirezadir/AIMLInterviews)** · ★ 10.0k<br>生成式 AI、Agent、多模态等方向的 AI/ML 面试指南。<br><sub>更新于 2026-10 · MIT</sub>
- **[AIGC-Interview-Book](https://github.com/WeThinkIn/AIGC-Interview-Book)** · ★ 5.3k · 🀄<br>AIGC、大模型和 AI Agent 算法工程师面试资源。<br><sub>更新于 2026-11 · GPL-3.0</sub>
- **[ai-engineering-interview-questions](https://github.com/amitshekhariitbhu/ai-engineering-interview-questions)** · ★ 3.7k<br>AI 工程面试的问题和答案速查。<br><sub>更新于 2026-11 · Apache-2.0</sub>
- **[interview-guide](https://github.com/Snailclimb/interview-guide)** · ★ 3.5k · 🀄<br>开源的 AI 面试平台：简历分析、文字和语音模拟面试、知识库题库面试，完整功能免费。<br><sub>更新于 2026-10 · AGPL-3.0</sub>
- **[TorchLeet](https://github.com/Exorust/TorchLeet)** · ★ 2.6k<br>PyTorch 版的 LeetCode：来自真实面试的 ML/AI 编程题。<br><sub>更新于 2026-11 · MIT</sub>
- **[go-interview-practice](https://github.com/RezaSi/go-interview-practice)** · ★ 2.5k<br>交互式 Go 面试练习平台：编程题、即时反馈和 AI 模拟面试。<br><sub>更新于 2026-11</sub>

<a id="cat-guides"></a>
## 求职指南

- **[tech-jobs-with-relocation](https://github.com/AndrewStetsenko/tech-jobs-with-relocation)** · ★ 4.6k<br>去国外找科技工作的一站式指南，包含提供搬迁支持的公司和资源。<br><sub>更新于 2026-11 · CC0-1.0</sub>
- **[CS-Job-Guide](https://github.com/wuyoueeee/CS-Job-Guide)** · ★ 355 · 🀄<br>计算机专业用 AI 求职的开源手册：选方向、写简历、过面试到 Offer 决策和签约避坑，适合实习、春招和秋招。<br><sub>更新于 2026-10</sub>
- **[how-to-get-offer](https://github.com/AIPMAndy/how-to-get-offer)** · ★ 90 · 🀄 🆕<br>社招拿 Offer 指南：定位、简历、渠道和内推、面试、谈薪到入职，附 30 天执行表和模板。<br><sub>更新于 2026-11 · MIT</sub>

<a id="faq"></a>
## 常见问题

**我不会写代码，能用吗？**
能。在线简历编辑器（Reactive Resume、Magic Resume）和浏览器扩展（FormFilla、秋招网申助手）打开就能用；标 🤖 的需要先装好 Claude Code、Codex 这类 AI 助手；需要自己部署的工具一般要会用 Docker。

**要花钱吗？**
这里都是开源项目，本身免费。用到大模型时要付模型服务商的费用，支持本地模型的工具可以用 Ollama 免费跑。

**AI 写的简历会被看出来吗？**
没有可靠的统计。更实际的问题是内容空泛、每份都一样。把 AI 当编辑用：让它对照职位描述指出缺口、压缩句子，数字和事实由你自己填。

**先从哪个开始？**
还没有像样的简历，先用“写简历”里的编辑器做一份；已经有简历，用“简历和职位匹配”里的工具对照目标职位检查；要同时投很多家，再考虑一站式助手来跟踪进度。

**星标数多久更新一次？**
每周一由 GitHub Actions 自动刷新并重新排序，链接每周检查一次。

<a id="finder"></a>
## 让 AI 助手帮你挑

这份清单也是一个 skill。把仓库里的 [`skills/job-search-finder`](skills/job-search-finder) 文件夹装进你的 AI 助手（或运行 `npx skills add DU8866-nice/awesome-ai-job-search`），然后问它：

> 我在澳洲读 IT 硕士，明年毕业，想找 AI 相关的应届职位。已经有英文简历，不想自己部署东西，推荐我用哪几个工具？

它会按你的求职阶段、地区、技术水平和隐私要求，从清单里挑两三个并说明理由，同时提醒自动投递的风险。

<a id="related"></a>
## 相关合集

| 项目 | 说明 | ⭐ | 最近更新 |
|---|---|---:|---|
| [awesome-remote-job](https://github.com/lukasz-madon/awesome-remote-job) | 远程工作的招聘网站和资源合集。 | 50.7k | 2026-09 |
| [awesome-job-boards](https://github.com/emredurukn/awesome-job-boards) | 各类招聘网站合集。 | 1.1k | 2026-11 |

<a id="contributing"></a>
## 参与贡献

欢迎推荐项目或纠错：[提交 Issue](https://github.com/DU8866-nice/awesome-ai-job-search/issues/new/choose)，或者修改 [`data/tools.yaml`](data/tools.yaml) 后提 PR，详见[贡献指南](CONTRIBUTING.md)。README 由脚本生成，请不要直接改它。

清单里的 JobFit 是本清单作者自己的项目，已在条目下注明。

## Star 趋势

[![Star History Chart](https://api.star-history.com/svg?repos=DU8866-nice/awesome-ai-job-search&type=Date)](https://star-history.com/#DU8866-nice/awesome-ai-job-search&Date)

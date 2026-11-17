<!-- section:intro -->
找工作正在变成一件可以交给 AI 帮忙的事。今年 GitHub 上涨得最快的一批项目里，就有把 Claude Code 变成求职助手的 Agent：它们读职位描述、对照你的简历打分、改出针对性的简历、起草求职信，再帮你记下每一次投递。

工具多了，也更难挑：有的要自己部署，有的装进 AI 助手就能用；有的只帮你准备材料，有的会用你的账号自动海投，可能让账号被封。这份清单按求职阶段整理这些工具，并把这些差别标出来。

<!-- section:pick -->
## 按求职阶段找工具

| 阶段 | 想省事 | 想把数据留在自己手里 | 国内求职 |
|---|---|---|---|
| 一站式：找职位、改简历、跟进 | [career-ops](https://github.com/career-ops-hq/career-ops)、[ai-job-search](https://github.com/ai-job-search-dev/ai-job-search) | [Dossier](https://github.com/AienTech/dossier)、[JobOps](https://github.com/DaKheera47/job-ops)、[JobSync](https://github.com/Gsync/jobsync) | [MyCareer](https://github.com/low-hands/MyCareer)、[OfferPilot](https://github.com/offercontext/offerPilot)、[录阶](https://github.com/Chozzc/Lujie-Careerkit) |
| 找职位 | [freehire](https://github.com/strelov1/freehire)、[实习清单](https://github.com/SimplifyJobs/Summer2027-Internships) | [JustHireMe](https://github.com/vasu-devs/JustHireMe) | [job_radar](https://github.com/lijiaqi-AI-Product-Manager/job_radar)、[Campus2026](https://github.com/namewyf/Campus2026) |
| 写简历 | [Reactive Resume](https://github.com/reactive-resume/reactive-resume)、[RenderCV](https://github.com/rendercv/rendercv) | [简历通](https://github.com/magicapple123/ResumeForge)、[JadeAI](https://github.com/LingyiChen-AI/JadeAI) | [Magic Resume](https://github.com/JOYCEQL/magic-resume)、[中文简历模板](https://github.com/dyweb/awesome-resume-for-chinese) |
| 对照职位改简历 | [ResumeSkills](https://github.com/Paramchoudhary/ResumeSkills) | [Resume Matcher](https://github.com/srbhr/Resume-Matcher) | [JobFit](https://github.com/DU8866-nice/jobfit)、[ASu-skills](https://github.com/Hisn00w/ASu-skills) |
| 填申请表 | [jev-job-search](https://github.com/qbeka/jev-job-search) | [FormFilla](https://github.com/AhmadHassan-BTed/FormFilla) | [秋招网申助手](https://github.com/aurostars/Job-Application-Helper) |
| 准备面试 | [Tech Interview Handbook](https://github.com/yangshun/tech-interview-handbook) | [interview-guide](https://github.com/Snailclimb/interview-guide) | [JavaGuide](https://github.com/Snailclimb/JavaGuide)、[实习.skill](https://github.com/agentenatalie/get-job.skill) |

<!-- section:rules -->
## 用之前先知道

> [!IMPORTANT]
> - **别让 AI 编经历。** 让 AI 改写的是你真实做过的事。编出来的技能和项目，面试一追问就露馅，背景调查也过不了。优先选写明“不编造经历”、每条结论都能对回简历原文的工具。
> - **自动投递有风险。** 标 ⚠️ 的工具会用你的账号自动抓取或投递，招聘平台的条款通常禁止这样做，账号可能被限制或封禁。更稳妥的是让工具准备材料、填好表单，由你检查后提交。
> - **简历是敏感信息。** 简历里有电话、住址和工作经历。标 🏠 的工具数据留在自己的电脑或服务器上；用云端大模型时，简历内容会发给模型服务商。
> - **AI 打的匹配分只是参考。** 不同工具算法不同，分数高不代表一定有面试，分数低也不代表不能投。重点看它指出的缺口是否属实。
> - **留意招聘诈骗。** 要求先交钱、押证件或下载陌生软件的“职位”都不要碰，职位信息以公司官网为准。

本清单不收录在面试或笔试中实时给答案的“隐身”作弊工具，也不收录专门绕过验证码和反爬的工具。

<!-- section:faq -->
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

<!-- section:finder -->
## 让 AI 助手帮你挑

这份清单也是一个 skill。把仓库里的 [`skills/job-search-finder`](skills/job-search-finder) 文件夹装进你的 AI 助手（或运行 `npx skills add DU8866-nice/awesome-ai-job-search`），然后问它：

> 我在澳洲读 IT 硕士，明年毕业，想找 AI 相关的应届职位。已经有英文简历，不想自己部署东西，推荐我用哪几个工具？

它会按你的求职阶段、地区、技术水平和隐私要求，从清单里挑两三个并说明理由，同时提醒自动投递的风险。

<!-- section:contributing -->
## 参与贡献

欢迎推荐项目或纠错：[提交 Issue](https://github.com/DU8866-nice/awesome-ai-job-search/issues/new/choose)，或者修改 [`data/tools.yaml`](data/tools.yaml) 后提 PR，详见[贡献指南](CONTRIBUTING.md)。README 由脚本生成，请不要直接改它。

清单里的 JobFit 是本清单作者自己的项目，已在条目下注明。

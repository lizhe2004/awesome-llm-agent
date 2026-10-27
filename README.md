# awesome-llm-agent
everything about llm based agent
 latest update: 2027-10-15
--- 

- [论文](#论文)
  - [综述](#综述)
- [开源项目](#开源项目)
  - [Agent框架](#Agent框架)
  - [Agent记忆框架](#Agent记忆框架)
  - [Agent应用](#Agent应用)
  - [工具](#工具)
  - [安全护栏](#安全护栏)
- [指南手册](#指南手册)
- [课程](#课程)
- [企业级实践](#企业级实践)
- [行业最佳实践指南](#行业最佳实践指南)
  - [整体](#整体)
  - [记忆管理](#记忆管理)
  - [评测](#评测)
  - [Harness](#Harness)
  - [自演进](#自演进)
  - [Context Engineering](#Context-Engineering)
  - [Skills](#Skills)
  - [其他文章](#其他文章)
- [视频](#视频)
- [图书](#图书)
--- 
 
# 论文
## 综述
- [A Survey of Agent Skills: Toward Procedural Infrastructure for LLM Agents](https://www.preprints.org/manuscript/202605.1276)

- [Agent Harness Engineering: A Survey](https://picrew.github.io/LLM-Harness/)
- [A Survey on Agentic Security: Applications, Threats and Defenses](https://arxiv.org/abs/2510.06445)
      <details>
      <summary>详情</summary>
      ![](https://cdn.jsdelivr.net/gh/lizhe2004/pic-repo@master//imgs/20251013101641455.png)
    </details>
- [2023-09-19 The Rise and Potential of Large Language Model Based Agents: A Survey](https://arxiv.org/pdf/2309.07864)
  - [github](https://github.com/WooooDyy/LLM-Agent-Paper-List)
- [2024-12-30 Large Language Model-Brained GUI Agents: A Survey](https://arxiv.org/abs/2411.18279)
        <details>
      <summary>详情</summary>
      - 大型语言模型（LLM）驱动的图形用户界面（GUI）智能体（Agent）。这一领域融合了人工智能、人机交互和软件工程的跨学科知识，是当前AI领域最活跃的方向之一。本次的综述系列解读将系统梳理LLM驱动GUI Agent的发展脉络，剖析其核心技术、关键挑战及未来机遇，旨在为感兴趣的读者提供详尽指南，并激发更多创新思考。
      - ![](https://cdn.jsdelivr.net/gh/lizhe2004/pic-repo@master/imgs/20250121144556.png)
    </details>
  
  - [中文总结](https://mp.weixin.qq.com/s/qacueqa-xEgLuZ09L0JUOA)
- [2025-01-25 Agent AI: Surveying the Horizons of Multimodal Interaction](https://arxiv.org/abs/2401.03568)
- [2024-12-15 A Survey on Large Language Model based Autonomous Agents](https://arxiv.org/abs/2308.11432)
  - [中文总结](https://mp.weixin.qq.com/s/Jz_oHJ64bq9eAfvLrZ8Jpw)


# 指南手册
- [智能体设计模式](https://docs.google.com/document/d/1rsaK53T3Lg5KoGwvf8ukOUvbELRtH-V0LnOIFDxBryE/preview?tab=t.0#)
  - [中译版](https://jimmysong.io/zh/book/agentic-design-patterns/)
- [Google Startup Technical Guide for AI Agents](./handbooks/google-startup_technical_guide_ai_agents_final.pdf)
- [Weaviate Agentic Architecture](./handbooks/Weaviate%20Agentic%20Architectures-ebook.pdf)
- [Microsoft: Agent Governance whitepaper](./handbooks/Microsoft-Agent-governance-whitepaper.pdf)
  -[原始链接](https://adoption.microsoft.com/files/copilot-studio/Agent-governance-whitepaper.pdf)
- [Cohere: Building Enterprise Agents](./handbooks/Cohere-Building-Enterprise-Agents.pdf)
- [Amazon Web Services (AWS): An Executive’s Guide to Agentic AI](./handbooks/aws-an-executives-guide-to-agentic-ai-ebook-v3-final.pdf)
- [Deloitte: Unlocking the right Agentic AI Use cases](./handbooks/Deloitte-in-eaid-agentic-ai-pov-chapter-1.pdf)
  - 德勤（Deloitte Touche Tohmatsu），为一国际性专业服务网络，与普华永道、安永及毕马威并列为四大国际会计师事务所
- [McKinsey & Company: Seizing the Agentic AI Advantage](./handbooks/QuantumBlack-seizing-the-agentic-ai-advantage.pdf)
  - QuantumBlack原先是麦肯锡2015年收购的数据分析公司，后来成为了麦肯锡官方的、统一的人工智能(AI)部门
- [KPMG: The Agentic AI Advantage](./handbooks/kpmg-agentic-ai-advantage.pdf)
  - KPMG是“毕马威”（Klynveld Peat Marwick Goerdeler）的简称，它是全球最大的专业服务网络之一，也是国际“四大”会计师事务所之一
- [Capgemini: The rise of Agentic AI](./handbooks/Capgemini-Final-Web-Version-Report-AI-Agents.pdf)
  - 凯捷集团是一家具有50多年悠久历史的欧洲咨询公司。 凯捷中国扎根中国27年，拥有强大的咨询专家团队和数字化能力沉淀，在大数据、人工智能、可持续发展等最新技术应用和解决方案。
- [Accenture: Technology vision 2025](./handbooks/Accenture-Tech-Vision-2025.pdf)
  - 埃森哲（Accenture）是一家全球性的管理咨询、信息技术和业务流程外包公司。 该公司成立于1989年，前身是安达信会计师事务所的咨询部门。 埃森哲是全球最大的管理咨询公司之一，服务于全球500强企业中的大部分客户，业务遍及40多个行业。 
- [OpenAI - AI in Enterprise](./handbooks/openai-ai-in-the-enterprise.pdf)
- [Google: AI Agent Handbook](./handbooks/google%20-%20ai_agents_handbook.pdf)
- [BCGX: AI Agents and MCP](./handbooks/BCGX-agent%20and%20mcp.pdf)
  - 波士顿咨询公司（BCG）宣布成立数字化构建与设计部门BCG X
- [Thomson Reuters and Reuters: Agentic AI 101](./handbooks/thomason-reuters-agentic-ai-101.pdf)
  - 汤森路透（Thomson Reuters）是由加拿大汤姆森公司（The Thomson Corporation）与英国路透集团（Reuters Group PLC）合并组成的商务和专业智能信息服务提供商。
- [ ServiceNow : Enterprise AI Maturity Index](./handbooks/ServiceNow-enterprise-ai-maturity-index-2025.pdf)
  - ServiceNow是一家以ITSM业务起家的美国SaaS企业
- [Infosys - Tech Navigator Agentic Enterprise Playbook](./handbooks/Infosys-tech-navigator-agentic-enterprise-ai-playbook.pdf)
  - 印孚瑟斯是总部在印度班加罗尔的一家信息技术跨国公司。

# 企业级实践
## 整体
- [阿里：从 Agent Flow 到 AI Native：为什么通用 Agent 是“饮鸩止渴”](https://mp.weixin.qq.com/s?__biz=Mzg4NTczNzg2OA==&mid=2247510883&idx=1&sn=1988e51340f0d9a22b2e6908fc60eddc&poc_token=HBhez2qjQ5xbX7bOSwwhBMyVpUb12w6RqyUPykb7)
- [从一次 LLM 调用到完整 Harness，Agent 到底经历了什么？](https://mp.weixin.qq.com/s?__biz=MjM5ODYwMjI2MA==&mid=2649803963&idx=1&sn=ec0730b1274a0b52382df956d8583215)
- [淘宝百亿补贴数据分析助手 Agent 实战-2026-09-03](https://mp.weixin.qq.com/s?__biz=MzAxNDEwNjk5OQ==&mid=2650545717&idx=1&sn=616d9c26c3c02ce24bdb2a793b18291c&scene=21&poc_token=HFA0z2qjjb54BQ6HSCo66foBO_yt4Pg51BvonJBc)
- [高德本地生活分析 Agent 的 AI Native 实践全景（万字长文回顾）](https://mp.weixin.qq.com/s?__biz=Mzg4NTczNzg2OA==&mid=2247511846&idx=1&sn=e281c6ff590a8209e7d6e2719ee4e58a&poc_token=HHVfz2qjRy1G8D-NL4uuxWIAirlNtGc_atnjovX9)
- [高效电商 AI 智能体解剖指南 | 选自 Anthropic 的 Claude 博客](https://baoyu.io/translations/2026-09-02/the-anatomy-of-effective-commerce-agents)
- [阿里-垂类业务如何落地生产级 Agent](https://mp.weixin.qq.com/s?__biz=Mzg4NTczNzg2OA==&mid=2247511474&idx=1&sn=6f3f3e26c57b0796571649939b295123&poc_token=HNkvz2qjwrcKghdxpCbBm_IdPyu18vF_ht-NjXRg)
- [哈啰出行从Copilot到Agent模式的探索-贾立 PPT](https://www.alipan.com/s/U58jxu9vrKd)
- [Anthropic的构建智能体的经验总结和实践建议](https://www.anthropic.com/research/building-effective-agents)
- [阿里云服务领域Agent智能体：从概念到落地的思考、设计与实践](https://mp.weixin.qq.com/s/VBdgDIpmJvrt6fNgLE7i4Q)
- [支付宝百宝箱团队的技术负责人的AI Agent 综述分享](https://mp.weixin.qq.com/s/HrKOGXuI8wVM6qgylKZ8qw)
- [2025-10-24 阿里：Apache RocketMQ × AI：面向 Multi-Agent 的事件驱动架构](https://mp.weixin.qq.com/s?__biz=Mzg4NTczNzg2OA==&mid=2247508890&idx=1&sn=5b08490308cdf32cc37727881aab25d3&poc_token=HN1-AWmjxkkx1Ug8vFNFcoqJq4S1VkMP-dngiI-y)
- [2025-10-20 腾讯：一文讲懂Agent及其主流框架：自己想、自己干、自己复盘的才是好Agent！](https://mp.weixin.qq.com/s?__biz=MjM5ODYwMjI2MA==&mid=2649796189&idx=1&sn=edc8db54287983686dd354c0a2beb208&poc_token=HGN_AWmjhiVge672H5-_rxqmh8qeHHmkRndWAHZB)
- [智能体（Agent）全景拆解：核心模块、技术实现与业务落地指南](https://mp.weixin.qq.com/s?__biz=MzAxOTY5MDMxNA==&mid=2455765235&idx=1&sn=27aa1e2f56c152dec51d2576b069e0cf&poc_token=HKRez2qj9bNoNM1-WU3lcQmxwurmem5VBj5gd_hF)
- [拥抱 AI：转转智能客服自主化升级之路-2025-08-13](https://mp.weixin.qq.com/s/qpqTzdvqicrA9FUBxXuM5Q)

- [Rebuilding Devin for Claude Sonnet 4.5: Lessons and Challenges](https://cognition.ai/blog/devin-sonnet-4-5-lessons-and-challenges)
- [OpenAI:Context Engineering - Short-Term Memory Management with Sessions](https://cookbook.openai.com/examples/agents_sdk/session_memory)
- [Claude官方Anthropic的构建智能体的经验总结和实践建议：构建高效智能体](https://www.anthropic.com/research/building-effective-agents)
  - [中文版](https://mp.weixin.qq.com/s/MgbHoQirV0fLmFkgRsI8KA)
- [基于大语言模型的智能代理](https://lilianweng.github.io/posts/2023-06-23-agent/)
  - [中文版](https://baoyu.io/translations/ai-agent/llm-powered-autonomous-agents)
  - ![](https://cdn.jsdelivr.net/gh/lizhe2004/pic-repo@master/imgs/20250121123852.png)
- [AI Agent（智能体）技术白皮书（Google，2024）](https://drive.google.com/file/d/1oEjiRCTbd54aSdB_eEe3UShxLBWK9xkt/view?pli=1)
  - [中文版](https://arthurchiao.art/blog/ai-agent-white-paper-zh/)
## 记忆管理
- [Agent 为什么会“忘事”-Agent的记忆管理](https://mp.weixin.qq.com/s?__biz=Mzg4MTYwMzY1Mw==&mid=2247518479&idx=1&sn=76804f2205a06e4b92d6805e97a3529a&poc_token=HDouz2qjqk01aEUxnS-vYpph1Sa-NI9anRSmCpE7)
- [小林面试-Codex记忆机制是怎么实现](https://mp.weixin.qq.com/s?__biz=MzUxODAzNDg4NQ==&mid=2247564796&idx=1&sn=1f3532e26c72ec65fa92da2c82adbfef&poc_token=HH5Xz2qjfhKy2oOpWfiEcWzT1Mxj1vUCu4Q-nPwO)
- [小红书-EMNLP 2026｜MemPro：让 Agent 的记忆系统学会自我进化](https://mp.weixin.qq.com/s?__biz=Mzg4OTc2MzczNg==&mid=2247496400&idx=1&sn=64957c6e3a95d71fe7a51146825c04db&poc_token=HCpaz2qjhzUMuRdSSPTE3WtFdZokBBBQpBh-V1UN)
- [淘宝-让 Agent 像人一样记忆：本地长期记忆系统 HL-Mem 的设计与取舍-2026-09-11](https://mp.weixin.qq.com/s?__biz=MzAxNDEwNjk5OQ==&mid=2650545942&idx=1&sn=059fb0899702c46fe339f0a80aef90ab&poc_token=HJVbz2qjgcxboYF3i-xv8SHwNlQFznGmSpk8JOJP)
- [360奇舞-Agent 为什么会“忘事”-Agent的记忆管理](https://mp.weixin.qq.com/s?__biz=Mzg4MTYwMzY1Mw==&mid=2247518479&idx=1&sn=76804f2205a06e4b92d6805e97a3529a&poc_token=HD5cz2qjVlGSWCMN7OcqCP2XQb8MFjnK2Ydw-ec7)
- [得物技术-企业级 MultiAgent 的记忆系统：短期上下文与四层记忆架构实现](https://mp.weixin.qq.com/s?__biz=MzkxNTE3ODU0NA==&mid=2247546577&idx=1&sn=e958fbb5a7701d92612f0da1549ad0ad)
- [支付宝-仿照大脑记忆机制，给 AI 装了一个海马体，拿到了 SOTA](https://mp.weixin.qq.com/s?__biz=Mzg2OTYyODU0NQ==&mid=2247521407&idx=1&sn=0ec9855e1824efd139dcda5191cfd4c3)
- [深度拆解 Hermes Agent 的记忆系统：它如何修正 OpenClaw 的误区](https://baoyu.io/blog/2026-04-29/manthanguptaa-2034849672985288957)

- [【论文解读】万字解读史上最全 Agent Memory 综述-2025-11-24](https://mp.weixin.qq.com/s/BnuSD4QQ_NmkeGvZK9cFrA)
- [ChatGPT 最新记忆系统 Dreaming V3 详解-2026-06-07](https://mp.weixin.qq.com/s/orNvxRusHdV1pJpPtRXtpA)



## 评测
- [Rubrics综述：Agent时代，如何定义一个「好答案」？-2026-05-31](https://mp.weixin.qq.com/s/m4vmMWxA7FbtB9DqSUqEpQ)

- [淘宝AI购物助手在线评测落地实践-2026-10-11](https://mp.weixin.qq.com/s?__biz=MzAxNDEwNjk5OQ==&mid=2650546388&idx=1&sn=9ccd19e3c6a8ee97a5ec6a963d2eb105&poc_token=HNgwz2qjCgv3Jy2zJ9MRPrKSf_xCBvA4BaEf8lm_)
- [美团-Agent评测漫谈 —— 由浅入深讲解Agent评测](https://tech.meituan.com/2026/08/07/Agent-Evaluation.html)
- [美团-《Agent 评测白皮书》系列01：Agent 评测全览](https://tech.meituan.com/2026/09/10/Agent-Evaluation-White-Paper-01.html)
- [淘宝-让Agent可评、可控、可迭代：业务效果导向的评测体系与场景实践-2026-09-17](https://mp.weixin.qq.com/s?__biz=MzAxNDEwNjk5OQ==&mid=2650545998&idx=1&sn=05272ad46f69aaf5424bb9446b165b8b&poc_token=HOwpz2qjUY0gfa0z1h1jbohsuuDvnAbEkgzMAYyG)
- [腾讯— 一篇讲透Agent自进化飞轮怎么搭：评测→记忆→落地→控制](https://mp.weixin.qq.com/s?__biz=MjM5ODYwMjI2MA==&mid=2649803847&idx=1&sn=abe5cab137aac47cb042b6baa1a24191&poc_token=HPItz2qjzRVG4n7qg57LDHZEpKcMUXH4-CKFeggf)
- [阿里-AI Agent 应用精细化评测：评测体系设计与工程实践-2026-09-02](https://mp.weixin.qq.com/s?__biz=Mzg4NTczNzg2OA==&mid=2247511370&idx=1&sn=c9f4ff1d054cb229ac2f8c1462fcb05e&poc_token=HAMvz2qjPByFgkPnUNrx-CKkvIgrZKXSCQ8Nv_L5)
- [Anthrop - Demystifying evals for AI agents(揭秘人工智能代理的评估)](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents)
- [小林面试+怎么评估 Agent](https://mp.weixin.qq.com/s?__biz=MzY4NTE2NjU5MQ==&mid=2247486110&idx=1&sn=985af26cfa7fb4a24a2cec946046a7b2&poc_token=HP0vz2qjY9p4vKrqya4_zbssdnmQi_gq1BZq3gAp)
- [阿里-Agent 越改越乱之后，我用评测和轨迹把它拉回来了](https://mp.weixin.qq.com/s?__biz=Mzg4NTczNzg2OA==&mid=2247511106&idx=1&sn=e3e481953f140ab1a9afb73f7c40221f)
- [Agent 评测全流程拆解：数据集、Worker、评分器、发布门禁-2026-10-13](https://mp.weixin.qq.com/s?__biz=Mzg2MzcyODQ5MQ==&mid=2247505975&idx=1&sn=31777bd2b0f29651a0c829beae18fcd1&chksm=cfe46f3aee00881b018d720b49cf2ab6b19cc9ce6063eec634338f4bc6774b89d02d0a8a5c13&mpshare=1&scene=24&srcid=1014feb6oH7AxwZsIv0lS28V&sharer_shareinfo=68f8ab988142b766fd75fc593232713f&sharer_shareinfo_first=68f8ab988142b766fd75fc593232713f#rd)


- [万字FAQ：比较系统地介绍下 AI Evals-2026-09-26](https://mp.weixin.qq.com/s?__biz=MzAxOTMyMzYyMw==&mid=2451285952&idx=1&sn=7c52b18af568d6e19c12039d98a4bffc&chksm=8df8a29ed237a3de94431d243f5d89e252b80d1b9be71a7355c00fa43047d3ac879fc0c951a5&mpshare=1&scene=24&srcid=1013kpEUjuNaxkBqFHYC4lGM&sharer_shareinfo=e1c2df2380d8c6f562356ff7ccf7c8cc&sharer_shareinfo_first=e1c2df2380d8c6f562356ff7ccf7c8cc#rd)

- [业务客服Agent全链路测试与工程化评估体系实战-2026-07-31](https://mp.weixin.qq.com/s?__biz=MzU2OTc3NjQyNQ==&mid=2247483811&idx=1&sn=22b10e305b7589e5f036280518a76c5b&chksm=fd3db5f49ad0bbe66e716e50add6d005740971945e5219480f152083bb9d77c6a0b27ed71660&mpshare=1&scene=24&srcid=0911R0z4q7DfNPaU7sGfvRbk&sharer_shareinfo=11f74b811dbacc4415b0c95839ae53fe&sharer_shareinfo_first=11f74b811dbacc4415b0c95839ae53fe#rd)


- Agent 测试与评测- 面试系列
  
  - [面试官问：Agent说做完了，你拿什么证据判它真做完了？-2026-10-14](https://mp.weixin.qq.com/s/VvhnFmyXYPaMYJ9B4PjXTA)
  - [面试官问：Agent评测重跑一遍分数就变，你先查哪里？-2026-10-15](https://mp.weixin.qq.com/s?__biz=MzYzNjM5Mzk2NA==&mid=2247497115&idx=1&sn=a9bcb8f187534e82d7d6a3cfb5153900&chksm=f1a671cc7fb8fddf34ab9390f52e2c8ec1d015c5cbbafafa4ca2eff32236cd0031b63a6627b3&mpshare=1&scene=24&srcid=10235FqDE5QqtkI4fUOVl24c&sharer_shareinfo=c90b71a4470869e14b3708325ae7cd68&sharer_shareinfo_first=c90b71a4470869e14b3708325ae7cd68#rd)
  - [面试官问：Agent评测拿了100%，是Agent真强，还是题出漏了？-2026-10-20](https://mp.weixin.qq.com/s/sFmDOZdUPNifxcLRg5Jyvw)
  - [面试官问：退货客服Agent换批新题就掉分，是泛化差还是评测数据有问题？-2026-10-24](https://mp.weixin.qq.com/s/mPyWLGJm1mAS3K-5FSF0zQ)
  - [面试官问：Agent想出了你没想到的解法，断言怎么写才不冤枉它、也不放过作弊？-2026-10-26](https://mp.weixin.qq.com/s/9iARmEjVRtcVa6uYyShTHg)


## Harness
- [腾讯-换一套 Harness，比换两代模型还管用-2026-09-17](https://mp.weixin.qq.com/s?__biz=MzI2NDU4OTExOQ==&mid=2247697554&idx=1&sn=78f66fec6cc85f3fbe642283b7d91cc2&poc_token=HJNYz2qjPUD5TchWwuuDGJ5TTJ9qSDrMoY8xGCax)
- [腾讯：DeepSeek Harness背后的“心脏”：Cordis 到底是什么](https://mp.weixin.qq.com/s?__biz=MjM5ODYwMjI2MA==&mid=2649803959&idx=1&sn=9d18ecc2139e8ab90a44515ca64b0db5)
- [百度：都在开源 Harness，Codex 和 DeepSeek 到底有什么不一样？](https://mp.weixin.qq.com/s?__biz=Mzg5MjU0NTI5OQ==&mid=2247607560&idx=1&sn=377945189293dcd34a7b23fd6256e40d)
- [DeepSeek Harness：重新设计 Agent 运行时](https://mp.weixin.qq.com/s?__biz=Mzg5MjU0NTI5OQ==&mid=2247607531&idx=1&sn=f1115d58767f05a34b5778fbdf468056)
- [Pi 背后的公司，写了一篇最好懂的 Harness 科普-2026-08-21](https://mp.weixin.qq.com/s?__biz=MzY5MzA1MTA3Ng==&mid=2247483913&idx=1&sn=bb04c1477672651153c4f5579b11d1e4&chksm=f5e77fc0a86934f629fd6ab1572378684883de4f39bcd76621df9389ec183cc2eae702d05239&mpshare=1&scene=24&srcid=0911kFVS5awiIFzlGt423zhT&sharer_shareinfo=0229f981b8b0771871814ce9de044267&sharer_shareinfo_first=0229f981b8b0771871814ce9de044267#rd)
- [近期，看到最系统的102页Agent Harness综述-2026-06-04](https://mp.weixin.qq.com/s/tDRRo3DC6Pq7kuguQkkchA)


- [Agent Harness：从模型竞赛到系统工程的演进与实践-2026-05-28](https://mp.weixin.qq.com/s/ltbAxwJVRNNdJkjjv2QN4Q)
- [从Prompt、Context到Harness，工程的三次进化与终局之战-2026-05-27](https://mp.weixin.qq.com/s/1lqMtE3HjXkbNlPDYhgXyw)
- [从零设计生产级 Multi-Agent Harness：架构、评估、记忆、成本与 MCP 工具接入全拆解-2026-05-12](https://mp.weixin.qq.com/s/JPhcyDc4JwRmnMQ-76A-FQ)
-## 可观测行
  - [Agent 可观测性：为什么有了 LangChain，还会出现 Langfuse？-2026-06-09](https://mp.weixin.qq.com/s/Vf5lcw13OOBcJeplV70fOA)
  - [Agent Harness 可观测性：生产级 AI 项目必须补上的一课-2026-05-24](https://mp.weixin.qq.com/s/yU3-ciE-R6pJ1tluHlYF3Q)


## 安全
- [字节实践 | Agent 提示词注入攻击：一场需要长期应对的安全挑战](https://mp.weixin.qq.com/s?__biz=MzI1MzYzMjE0MQ==&mid=2247521453&idx=1&sn=a43b95ca00458d532f29d70e80f0d118&poc_token=HBIuz2qjhP8TeIFpib1V2tTFJKkBZ5HDm89pqg6N)
## 自演进
- [谷歌重磅发布WikiSkill，技能可以自己进化了！](https://mp.weixin.qq.com/s?__biz=MzIyNjM2MzQyNg==&mid=2247725815&idx=1&sn=6dc8d200fbcabc937f0093929522430a&poc_token=HCUuz2qj5KrzRXP-yOii7ZZUZfJzTjIs2Ts5YRfr)
- [agent优化之GEPA——一种提示词自进化的优化方案](https://mp.weixin.qq.com/s?__biz=MzAxNDEwNjk5OQ==&mid=2650545973&idx=1&sn=01a23266cadd126c68a1a14dd0db544a&poc_token=HM8vz2qjQMDxrSwM0aYE_PpI54yZ6ZhsPXLlN-by)
- [阿里-深度解析 RSI：当 AI 开始实现自我迭代提升-2026-10-13](https://mp.weixin.qq.com/s?__biz=Mzg4NTczNzg2OA==&mid=2247511873&idx=1&sn=8f45da7e2e5dc1513a6fb0ebc0490553&poc_token=HOEwz2qjNKSlFpv872qlLLwpexcPoXpbvF0fM5FO)
- [Datawhale-这是一篇把"RSI"讲明白的科普级综述！](https://mp.weixin.qq.com/s?__biz=MzIyNjM2MzQyNg==&mid=2247727603&idx=1&sn=13ba3492f438873686baa66eddb989f7&poc_token=HAQzz2qjcKiARxNyh6wK6-ZLcHUldzVzJvPAmbDM)
- [机器之心-从记忆到自进化：Agent 走向 RSI 的关键一步](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2651062063&idx=1&sn=f91d6b290b4a38685b85a47415870873&poc_token=HK9Vz2qjikzaTe4HOztFMu5JdRSyNc0YROLEdHpG)
- [万字长文读懂 RSI](https://mp.weixin.qq.com/s?__biz=MjM5ODkzMzMwMQ==&mid=2650454389&idx=1&sn=1c243e38c29f80b7e9fd1cd73e8fa7ca&poc_token=HDdbz2qj3oNDFZQGk30xNM-ZeUv5qTXdhUOxUK7O)
- [Agent如何自己变强？从Skill到模型权重的进化全景图](https://mp.weixin.qq.com/s?__biz=MzYzMTE5MDgxNA%3D%3D&mid=2247484854&idx=1&sn=88d218f5246dc729e7f61bb69218d989&scene=45&poc_token=HBNcz2qjfP6Ht6eJhWL25vm1OtdwRwn9auDCWgb8)

## Context Engineering
- [腾讯：AI工程范式的跃迁，一文讲透Context Engineering！](https://mp.weixin.qq.com/s?__biz=MzI2NDU4OTExOQ==&mid=2247697260&idx=1&sn=bbda847cb4e895e1ea99caf5acec9923)
- [2025-10-24 阿里云：浅谈上下文工程｜从 Claude Code 、Manus 和 Kiro 看提示工程到上下文工程的转变](https://mp.weixin.qq.com/s?__biz=MzIzOTU0NTQ0MA==&mid=2247554461&idx=1&sn=e52d01dd0832ede6a6cc146c152b39a1&poc_token=HNR-AWmjcRM74TSMHmrKV8lgaQtDVVWJ-vQWCtaz)
- [Anthropic:Effective context engineering for AI agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)
## Skills
- [企业Agent落地实践：统一Harness、Skill与虚拟文件系统](https://mp.weixin.qq.com/s?__biz=MzkzMjYzNjkzNw==&mid=2247637773&idx=1&sn=df4967bef8b79cfd4139b2bf3e72af55&poc_token=HPxbz2qj50qGXGVAQj--kURI_3Gpi-Ff7tk-bgzW)
- [反向拆解 skill-creator：一个好 skill 是怎么写出来的-2026-06-10](https://mp.weixin.qq.com/s/TzDvIc2nWLk5Y6JEPgWFBA)
- [大模型二面被问：如何设计 Skill 来降低 Token 消耗？我说"渐进式加载"。面试官：就这一个？还有呢？我当场卡壳了。-2026-06-09](https://mp.weixin.qq.com/s/qisdtJKObmrNS2n67jRbGg)
- [一次讲透 Skill的交付：分享一场我在公司的AI内训材料-2026-07-21](https://mp.weixin.qq.com/s/uLFLZbXCD6XHG1g1IME8tA)
- [Agent数据分析翻车，Anthropic说skill是准确率提升4倍的关键-2026-06-04](https://mp.weixin.qq.com/s/FL_M_Ii7CozS_Yi3-Z5YAw)




## Loop engineering
- [淘宝-Loop engineering：把 agent 放进工程循环-2026-09-21](https://mp.weixin.qq.com/s?__biz=MzAxNDEwNjk5OQ==&mid=2650546258&idx=1&sn=3b972197775c805cb4a58bdfdf69618a&poc_token=HGIwz2qjDgMR0dVgOsqNXpO8N7PDMKMqb1iC2y7v)

- [阿里：从 Loop 到 Graph Engineering 的演进思考与实战](https://mp.weixin.qq.com/s?__biz=MzIzOTU0NTQ0MA==&mid=2247562254&idx=1&sn=77b80c213b5e45ae40cdb09a0a6c15dd)
- [一文搞懂！Loop Engineering的进化史和本质](https://mp.weixin.qq.com/s?__biz=MzIyNjM2MzQyNg==&mid=2247723682&idx=1&sn=07b7025a091060fc7cd45d9e8bc9c14f&chksm=e916e121b1073422558e7db8be8b2f6186abfa968a0fe60faa5cbd0c63c8bcbf15e82aea65ba&mpshare=1&scene=24&srcid=0623wmXGMhzC6TD8Z0AvHUiW&sharer_shareinfo=92bb83c3a0491c8b23604c76d2a7e6cd&sharer_shareinfo_first=b4977180f9c2fee5ffc2a029505b8013#rd)

- [Agent Loop 与 Loop Engineering 区别-2026-06-20](https://mp.weixin.qq.com/s?__biz=MzI2OTE2NTQzMw==&mid=2650794648&idx=1&sn=bb1fc129c61679a8e4867d5d2bccf067&chksm=f3ce52206a2717231629e458af46980c350cdb2e83f33d958c06fd213abe6d1ba369b12ca032&mpshare=1&scene=24&srcid=0620XTweWTMgyEakt3nP3EW4&sharer_shareinfo=b54d963362ae04e83b577a0437379aac&sharer_shareinfo_first=b54d963362ae04e83b577a0437379aac#rd)

- [DeepSeek Harness 和 Pi 的 Agent Loop 循环结束判断架构细节解析](https://mp.weixin.qq.com/s?__biz=MzIzNDU2NDA0NA==&mid=2247485628&idx=1&sn=1d7244f55f6b4ebd8f3ce3e56682e399&chksm=e96ba2484ee72bf874e1a1dc679ccb972379f7a7c179ba865c21869be9d45e24a5667d3e87f2&mpshare=1&scene=24&srcid=0920kHvKsMr1nYFsPco5sm6V&sharer_shareinfo=048a8e813c4c4963d13275af49e7e73e&sharer_shareinfo_first=048a8e813c4c4963d13275af49e7e73e#rd)
- [Harness的风吹过，Loop Engineering的风来了-2026-06-10](https://mp.weixin.qq.com/s/ewnTpwZs_zk_wSo-ubYCBg)


## 其他文章
- [阿里云：从 ReAct 到 Agent Teams：一个工程师视角的 Agent 协作机制思考](https://mp.weixin.qq.com/s?__biz=MzIzOTU0NTQ0MA==&mid=2247562213&idx=1&sn=b5d701423e4bcb9c5775a7c6af19e234)
- [Agentic Design Patterns with LangGraph](https://freedium.cfd/https://pub.towardsai.net/agentic-design-patterns-with-langgraph-5fe7289187e6)
- [面试官问：编码 Agent 能排队、能插话、能打断，后端分别怎么实现？-2026-09-24](https://mp.weixin.qq.com/s?__biz=MzYzNjM5Mzk2NA==&mid=2247496727&idx=1&sn=7450fd35b748f1acd113c2a270978ffb&chksm=f1e2e6508acfd501ce58118118f43a08bb1f48ae1d960da08d9f5bb9dab44f7532e70df27c63&mpshare=1&scene=24&srcid=0926YEhMxHzp782sqCzy2PVy&sharer_shareinfo=73a6db0e3029d6aaf7ccc102941ac638&sharer_shareinfo_first=73a6db0e3029d6aaf7ccc102941ac638#rd)
- 智能客服落地
  - [智能客服规划第一步：不是选大模型，而是做现状调研--2026-06-24](https://mp.weixin.qq.com/s/AqHvhXvHb7hkPhlgKnwhiQ)
  - [智能客服落地路线图：第一阶段，先做到“能用”-2026-07-09](https://mp.weixin.qq.com/s/vNN7t56rnxdWvBkpy8uy-A)
  - [智能客服落地路线图：第二阶段，怎样从“能用”到“好用”-2026-07-10](https://mp.weixin.qq.com/s/_P__Gx5wYQGLCpRTUvfBiw)
  - [智能客服落地路线图：第三阶段，赋能组织，让客服中心成为AI能力中台-2026-07-13](https://mp.weixin.qq.com/s/b_WkFWoduP0rV3IMBOIOkw)
    - [智能客服上线前业务准备：首批服务触点如何选择？-2026-07-15](https://mp.weixin.qq.com/s/4oV6a6IzeOyW3sGmnB5qRA)
  - [智能客服上线前业务准备：首批业务场景怎么选？别只看咨询量-2026-07-21](https://mp.weixin.qq.com/s/BITCNYHt2I7qc5fhG-qO-g)
  - [智能客服上线前业务准备③：大模型＋RAG下，基础知识库怎么建？-2026-07-24](https://mp.weixin.qq.com/s/DEcqrP5QIiYxtpPizQee2A)
  - [智能客服上线前业务准备④：从客户旅程出发，转人工规则怎么设计？-2026-07-29](https://mp.weixin.qq.com/s/-sBMdsWW2zYDbLRkOjONIQ)
  - [智能客服上线前业务准备⑤：以业务目标为核心，搭建数据指标体系=2026-08-03](https://mp.weixin.qq.com/s/BpuhTwpDJLlLvrz3RpoDbw)
  - [智能客服上线前业务准备⑥：测试验收，如何判断AI客服真的准备好了？-2026-08-05](https://mp.weixin.qq.com/s?__biz=MzI5NTk2NDA1Mg==&mid=2247484076&idx=1&sn=be34ea31999875edccec175679df6fcb&chksm=ed05c4abd69d0c0d75dc50996d16784b1ea1061f57a39a8eb8d88d29239298edb1461f2df907&mpshare=1&scene=24&srcid=0823C4pQKm9epODDrDI6BWOS&sharer_shareinfo=ea76c306b1094172d47b284569d4d234&sharer_shareinfo_first=ea76c306b1094172d47b284569d4d234#rd)
  - 其他
    - [智能客服背后都是人工的付出--2026-05-21](https://mp.weixin.qq.com/s/8tlCqvcNOPTVQFBG-tLQlg)
    - [一起本可避免的投诉，暴露了智能客服的三个服务断点-2026-10-19](https://mp.weixin.qq.com/s/FNNjuomK89UojNzH8DsUQQ)
    - [2027年客服中心预算，AI钱该花在哪？-2026-09-08](https://mp.weixin.qq.com/s/CaRaU73MCQid2Mqdj4ptNQ)
    - [企业明明有官方客服，客户为什么还去第三方AI找答案？-2026-08-31](https://mp.weixin.qq.com/s/mVbvDM5H07GLQbE6UZmwOg)
    - [AI客服时代，基础岗位减少后，人才梯队怎么建？-2026-08-20](https://mp.weixin.qq.com/s/TJjnsSjnQKeroTt14S8cXA)
    - [AI时代，客服负责人：一个坚守，五个转变-2026-08-16](https://mp.weixin.qq.com/s/a-cpcD67jZGl5Ndn6A3b4A)
    - [AI进入客服中心后，客服管理发生了什么变化-2026-08-12](https://mp.weixin.qq.com/s/zvo77_he143xqEF-cRxHSA)
    - [滴滴国际化客服质检智能化之路：多语种多业务线 LLM 质检系统设计与实践-2026-06-04](https://mp.weixin.qq.com/s/_wTZKL9U1i4QE2vo5c8oaQ)
    - [智能客服变革：AI大模型与Multi-Agent如何颠覆客户服务模式？-2025-06-27](https://mp.weixin.qq.com/s/tMfjKXETDXYRm7SGz5I42Q)
    - [智能客服解决方案：从痛点到落地的系统化路径-2026-09-01](https://mp.weixin.qq.com/s/v_BNU9mryMBckzv2MAhIfQ)
    - [智能客服系统构建指南：从零打造AI客服助手-2025-09-08](https://mp.weixin.qq.com/s/XyOK4Dj-2y0zRw8NSYUNTw)
    - [客服人说 | 人机协作成为客服标配 引领服务互动场景智能化新时代-2025-09-21](https://mp.weixin.qq.com/s/TJP9LWCd8AtTy0DcC3yaNQ)



  - 语音相关
    - [AI 不仅能打字，还能打电话了：3 个开源语音 Agent 方案-2026-09-06](https://mp.weixin.qq.com/s?__biz=MzU1OTY5OTI3Nw==&mid=2247483947&idx=1&sn=93d56bd378c381b8a55fdf1f251b77e1&chksm=fd7cf8973d6b1e2b1c3bb1380d794af3cb9054fbc36275f1a0856738ea3f73e12c8bba92bde7&mpshare=1&scene=24&srcid=10102foE088mFMrL0SysWXhu&sharer_shareinfo=1b2bc8f11a79046b31b38a5b96e0784d&sharer_shareinfo_first=1b2bc8f11a79046b31b38a5b96e0784d#rd)
    - [语音助手为什么总抢话？Gander 把“什么时候说”写进训练目标-2026-09-27](https://mp.weixin.qq.com/s?__biz=MzI1NTMxOTUwOA==&mid=2247486441&idx=1&sn=857d465b3f1e9b716fd139b46bddaa5c&chksm=eb8c07c4fd287a99a6602b6aed2a883c4785ad55857f3f0c128f3c254ca6bccc258d105bca2e&mpshare=1&scene=24&srcid=0927mnUZkda9cN5n8kYHx2sE&sharer_shareinfo=85bc5f3ed11fbab9d9a98c85a6820e04&sharer_shareinfo_first=85bc5f3ed11fbab9d9a98c85a6820e04#rd)
    - [AI语音的级联流水线并行架构-2026-07-24](https://mp.weixin.qq.com/s?__biz=MzU2NzgzMTU0Ng==&mid=2247484219&idx=1&sn=62ba7c9be93deb7088ccb568e3fd0eed&chksm=fd45a2b4742c72726bee463ed996a40dfe7718bb38e5b20f317b468af7f5db36f54c37a49eb8&mpshare=1&scene=24&srcid=0920WpI4KmxX6RNFKjw2QcWB&sharer_shareinfo=b184b02f0172951939ea7eae3f8fb518&sharer_shareinfo_first=b184b02f0172951939ea7eae3f8fb518#rd)
    - [Full-duplex Voice：看懂语音 AI 从“轮流对话”到“边听边做”的变化](https://mp.weixin.qq.com/s/yIO2Gtth1UijgBAZobRGaw)
    - [字节Agent岗一面：为什么 AI 实时语音要用 WebRTC？它和 WebSocket 在 AI 对话流中的核心差异是什么？-2026-06-01](https://mp.weixin.qq.com/s/c_2eUkWSATohS_BsnwJxtQ)
    - [低延迟语音 AI 如何规模化——拆解 OpenAI 的 WebRTC 工程实践-2026-05-06](https://mp.weixin.qq.com/s/GGbssoltN5Bq1hu9KcPK9A)
    - [一个开源、可自托管的语音 AI 平台，快速构建和生产部署能够打电话、接电话的 AI 语音智能体-2026-06-22](https://mp.weixin.qq.com/s/fosj8IJ_qewcHClF2yaKuA)


- ## Coding Agent
  - [我把 pi 的源码读完了：一条和 Claude Code 完全相反的路线-2026-07-04](https://mp.weixin.qq.com/s?__biz=MzU1NjgzMjU4Mw==&mid=2247484076&idx=1&sn=9f89bd541fc2ad2e913d86cce320bbbd&chksm=fdf2ddb182107550c8038fa5063766a23d9023e4dd0db7aa9394308de74c7aee18a3bfaa4d4e&mpshare=1&scene=24&srcid=0911pQ4CuP7wifa49JdFAzEt&sharer_shareinfo=0c5a432c5adad9f14e8a8358b51a01c7&sharer_shareinfo_first=0c5a432c5adad9f14e8a8358b51a01c7#rd)


- [今天面了5位技术经理，全军覆没。这5位人选都有一个通病，就是说不清对团队成员是怎么管理的。](https://mp.weixin.qq.com/s/7GJMivcLTrilm3n_WS9i3g)


- [从零设计一个准生产级 LLM Agent：可靠性、上下文与恢复机制-2026-07-09](https://mp.weixin.qq.com/s/UTEdhrkV3G3Ycfrg0Jng_A)

- [一文搞懂Loop 工程、Harness 工程、FDE——Agentic Engineering 的三个层次-2026-06-09](https://mp.weixin.qq.com/s/qf_OPKf5EFoSh9OYboffvg)


# 面试相关
  - [阿里二面：说说LLM Agent 6大 plan 范式： CoT、ToT、GoT、ReAct、Plan-and-Execute、Reflexion？怎么做的选型？ 小伙伴懵了-2026-06-21](https://mp.weixin.qq.com/s/3JxfsuAPADR5vMhex7vZkw)
  - [百度Agent岗一面：你知道哪些更复杂的 RAG 范式？-2026-05-25](https://mp.weixin.qq.com/s/eEXSNSgXXH2cwYc9YBAc4w)
  - [美团Agent岗二面：向量检索和关键词检索有什么区别？-2026-05-19](https://mp.weixin.qq.com/s/J9hZ58RSKYisZc40MKoKKg)
  - [字节一面：什么是多路召回？具体怎么做？-2026-05-21](https://mp.weixin.qq.com/s/bSfhBeDDdl1B_ATWELDoAw)
  - [最值得安装的20个Skills](https://mp.weixin.qq.com/s/uCoIQVuL-X6m0wWd_muAuQ)
  - [字节二面，我霸气反问：“你说你们部门做agent项目，说说Function Call、MCP、A2A、ReAct这些你们都是怎么做的”，面试官一直在擦汗。。-2026-04-15](https://mp.weixin.qq.com/s/eE8PHFRXyTirRMrlJDyZGg)
  - [桃厂面试官：“你的 Agent 项目提示词工程是怎么做的？恶意用户 Prompt 注入怎么处理？”-2026-04-14](https://mp.weixin.qq.com/s/5QqwH5v3ClPi6KQ2Q6szEw)
  - [蚂蚁面试官追问："混合检索你说能提升17%，BM25 和向量的权重比怎么定的，RRF 的 k 值怎么来的？"-2026-04-06](https://mp.weixin.qq.com/s/wZeLHeOqkHDM8ZRStxzCkg)
  - [面试官：AI 回答要逐字出来，用户还能随时打断，这个接口怎么设计？-2026-07-22](https://mp.weixin.qq.com/s/A8NkA3JWj9siAca1_OItwg)








# 开源项目
## Agent框架

- [crewAI](https://github.com/joaomdmoura/crewAI) ![GitHub stars](https://img.shields.io/github/stars/joaomdmoura/crewAI.svg?style=flat&label=Star)
  - 用于编排角色扮演、自主人工智能代理的尖端框架。通过促进协作智能，CrewAI 使代理能够无缝协作，处理复杂的任务。
  - CrewAI 更加强调其易用性和快速搭建演示的特性。该平台直观易操作，主要通过编写提示来生成和配置智能体。在 CrewAI 平台上，智能体的创建和集成过程极为简便，用户能在短时间内轻松构建数百个智能体，因此它成为了追求快速制作 Multi-Agent 演示或原型开发者的首选工具。
  - 不过，CrewAI 在灵活性和定制化方面有所不足，更适合处理简单的用例，而不太适合复杂的编程作业。同时，智能体间的交互可能会存在一些 Bugs，这可能会对项目的稳定性和可靠性造成影响。尽管存在这些局限，对于那些仅需迅速构建演示或原型，且对系统灵活性要求不高的开发者而言，CrewAI 依旧是个合适的选择。





- [LangGraph](https://github.com/langchain-ai/langgraph) ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph.svg?style=flat&label=Star)
  - LangGraph 是一款基于 LangChain 打造的 Multi-Agent 框架，该框架通过引入有向循环图的理念，打造了一个极具灵活性和可定制性的解决方案。LangGraph 不仅适用于各类 Multi-Agent 任务，还能支持几乎所有的多智能体编排应用，使其成为那些面临复杂任务、追求高度灵活性和定制化能力的开发者的首选工具。
  - 尽管如此，LangGraph 的文档资料相对较少，这可能会让新手或编程经验不足的用户在入门时遇到困难。同时，使用 LangGraph 还需要用户具备一定的编程能力，特别是对图形结构和逻辑流程的掌握。因此，LangGraph 更适宜于那些拥有丰富编程背景、愿意投入时间深入学习的高级开发者。
 
- [DeepAgent](https://github.com/langchain-ai/deepagents)![GitHub stars](https://img.shields.io/github/stars/langchain-ai/deepagents.svg?style=flat&label=Star)
  - Deep Agents 是由 LangChain 团队开发的开源代理框架，实现了如 Claude Code 和 Manus 等先进代理使用的核心原则。该项目提供了一个简单但功能强大的代理框架，支持长期任务执行、工具集成、子代理委派、人工干预工作流等功能。用户可以通过 create_deep_agent 快速创建自定义代理，支持自定义模型、系统提示、工具、中间件等多个维度的定制，并集成了任务规划、文件系统操作、上下文管理等内置能力。
  - 主要功能点
    - 长期任务执行与规划：支持跨越数十个工具调用的复杂任务
    - 工具集成系统：内置文件操作、待办事项管理、子代理委派等工具，支持自定义工具和 MCP 工具
    - 干预工作流(HITL)：通过 interrupt_on 配置实现敏感操作的人工审批
    - 子代理委派：支持任务隔离和上下文分离的专用代理
    - 持久化内存：通过 CompositeBackend 实现跨对话的长期记忆存储
    - 可插拔后端系统：支持临时状态存储、本地文件系统、持久化存储等多种后端
    - 中间件扩展机制：可自定义中间件注入工具、修改提示或钩入代理生命周期
    - 上下文管理：内置自动摘要功能，当上下文超过 170k 令牌时自动处理



- [letta](https://github.com/letta-ai/letta)  ![GitHub stars](https://img.shields.io/github/stars/letta-ai/letta.svg?style=flat&label=Star)
  - Letta是一个开源的有状态智能体平台，专门用于构建具有高级记忆能力的AI智能体，使其能够随时间学习和自我改进。该项目提供了REST API和SDK（支持Python和TypeScript），允许开发者在OpenAI、Anthropic、Google Gemini等多个模型提供商上构建智能体。核心特性包括记忆块、工具集成和跨模型的便携性。项目已获得19.9k个Stars，拥有155位贡献者和2.1k个Fork。
  - 主要功能点
    - 构建有状态的AI智能体，具备持久化学习能力
    - 支持多个LLM模型提供商（OpenAI、Anthropic、Google Gemini等）
    - 提供内存块管理系统，允许智能体维持上下文状态
    - 内置工具集成（如web_search、run_code等）
    - 提供Python和TypeScript/Node.js的客户端SDK
    - 支持自托管和云端Letta开发平台两种部署方式
    - 完整的REST API和开发文档
- [pydantic-ai](https://github.com/pydantic/pydantic-ai) ![GitHub stars](https://img.shields.io/github/stars/pydantic/pydantic-ai.svg?style=flat&label=Star)
  - **PydanticAI**是一个基于Python的Agent框架,旨在简化使用生成式AI构建生产级应用程序的过程。它由Pydantic团队开发。
  - **模型无关性**:支持OpenAI、Gemini和Groq等多种LLM模型
  - **类型安全**:使用Pydantic进行类型检查和验证
  - **控制流和Agent组合**:使用标准Python实现
  - **结构化响应验证**:使用Pydantic进行验证
  - **流式响应处理**:包括对流式结构化响应的验证
  - **依赖注入系统**:用于测试和基于评估的迭代开发
  - **Logfire集成**:用于调试和监控LLM应用程序的性能和行为

- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) ![GitHub stars](https://img.shields.io/github/stars/microsoft/agent-framework.svg?style=flat&label=Star)
  - Microsoft Agent Framework 是一个全面的多语言框架,用于构建、编排和部署 AI 代理,支持 .NET 和 Python 实现。该框架提供从简单的聊天代理到复杂的多代理工作流程的一切,并支持基于图的编排。
  - 主要功能点
    - 基于图的工作流程:使用数据流连接代理和确定性函数,支持流式处理、检查点、人机交互和时间旅行等功能
    - Python 和 C#/.NET 支持:完全支持 Python 和 C#/.NET 实现,API 一致
    - 可观察性:内置 OpenTelemetry 集成,用于分布式跟踪、监控和调试
    - 多代理提供商支持:支持各种 LLM 提供商
    - 中间件:灵活的中间件系统,用于请求/响应处理、异常处理和自定义管道



- [ModelScope-Agent](https://github.com/modelscope/modelscope-agent/tree/master) ![GitHub stars](https://img.shields.io/github/stars/modelscope/modelscope-agent.svg?style=flat&label=Star)
  - ModelScope-Agent是一个通用的、可定制的Agent框架，用于实际应用程序，其基于开源的大语言模型 (LLMs) 作为核心。它提供了一个用户友好的系统库， 具有以下特点：
    - 可定制且功能全面的框架：提供可定制的引擎设计，涵盖了数据收集、工具检索、工具注册、存储管理、定制模型训练和实际应用等功能，可用于快速实现实际场景中的应用。
    - 开源LLMs作为核心组件：支持在 ModelScope 社区的多个开源LLMs上进行模型训练。
    - 多样化且全面的API：以统一的方式实现与模型API和常见的功能API的无缝集成。

- [agentUniverse](https://github.com/antgroup/agentUniverse/blob/master/README_zh.md) ![GitHub stars](https://img.shields.io/github/stars/antgroup/agentUniverse.svg?style=flat&label=Star)
  - agentUniverse 是一个基于大型语言模型的多智能体框架,由蚂蚁集团开源。 agentUniverse为您提供灵活易拓展的单智能体构建能力；agentUniverse核心拥有丰富的多智能体协同模式组件（可视为一个协同模式工厂Pattern Factory），它能让智能体们各司其职在解决不同领域问题时发挥最大的能力；同时agentUniverse专注于领域经验的融合，帮助您轻松将领域经验融入到智能体的工作中。
- [Qwen-Agent](https://github.com/QwenLM/Qwen-Agent/blob/main/README_CN.md) ![GitHub stars](https://img.shields.io/github/stars/QwenLM/Qwen-Agent.svg?style=flat&label=Star)
  - Qwen-Agent是一个开发框架。开发者可基于本框架开发Agent应用，充分利用基于通义千问模型（Qwen）的指令遵循、工具使用、规划、记忆能力。本项目也提供了浏览器助手、代码解释器、自定义助手等示例应用。

- [ROMA](https://github.com/sentient-agi/ROMA) ![GitHub stars](https://img.shields.io/github/stars/sentient-agi/ROMA.svg?style=flat&label=Star)
  ROMA（Recursive Open Meta-Agents）是一个元代理框架,使用递归层次结构来解决复杂问题。通过将任务分解为可并行的组件,ROMA使代理能够处理复杂的推理挑战,同时保持透明度,使上下文工程和迭代变得简单。该框架提供并行问题解决,代理可以同时处理复杂任务的不同部分,透明的开发具有清晰的结构,便于调试,并且通过搜索代理的强大基准测试结果证明了其性能。
### 不再维护
- [OpenAI Swarm](https://github.com/openai/swarm) ![GitHub stars](https://img.shields.io/github/stars/openai/swarm.svg?style=flat&label=Star)
  - Swarm 现已被 OpenAI Agents SDK 取代，后者是 Swarm 的升级版，已具备生产就绪状态。
  - 致力于简化智能体的构建过程以及智能体间的交接操作（即 Handoffs）。Swarm 框架特别适合初学者，让他们能够轻松入门多智能体技术，快速搭建演示项目。
  - 尽管如此，Swarm 的功能范围较为狭窄，仅支持 OpenAI API，而不兼容其他语言模型提供商的 API，这在实际生产部署中可能带来限制。同时，Swarm 的灵活性不足，难以满足追求高度定制化和灵活配置的用户需求。另外，Swarm的社区支持力度较弱，用户在 GitHub 上提交问题或寻求帮助时可能会遇到困难。

- [AutoGen](https://github.com/microsoft/autogen) ![GitHub stars](https://img.shields.io/github/stars/microsoft/autogen.svg?style=flat&label=Star)  
  - 进入维护模式，不再接受新功能，官方建议换到 Microsoft Agent Framework。
  - AutoGen 作为微软在多智能体领域推出的早期且广受欢迎的框架之一，旨在为软件开发提供解决方案。在该框架中，核心由两种智能体构成：用户智能体（User-Agent）和助手智能体（Assistant-Agent）。用户智能体负责传达指令和需求，而助手智能体则负责代码的生成与执行，并将成果反馈给用户或其他智能体。
  - AutoGen 的一大亮点在于其卓越的多智能体协调能力，尤其在应对编程任务时表现尤为突出。它还允许在智能体互动过程中进行人工干预，增加了开发流程的灵活性和可控性。
  - 尽管如此，AutoGen 也并非完美无缺。其用户界面可能不够直观，对于非技术人员来说，可能需要一定的学习时间。另外，AutoGen 的配置过程较为繁琐，尤其是在集成本地大型语言模型（LLM）时，还需要设置代理服务器。因此，AutoGen 更适合那些对软件开发有一定了解，并且愿意投入时间和精力去掌握其使用方法的开发者。
 

## Agent记忆框架

- [mem0](https://github.com/mem0ai/mem0) ![GitHub Repo stars](https://img.shields.io/github/stars/mem0ai/mem0)
  - Mem0 是一个为AI助手和代理提供智能记忆层的开源项目，能够实现个性化AI交互。它通过记住用户偏好、适应个人需求并持续学习，相比OpenAI内存实现了26%的准确度提升、91%的响应速度提升和90%的Token成本节省。项目已发布v1.0.0版本，支持多级记忆（用户、会话、代理状态）、跨平台SDK以及托管服务选项。

  - 主要功能点
    - 多级记忆系统：无缝保留用户、会话和代理状态，支持自适应个性化
    - 开发者友好：提供直观API、跨平台SDK（Python/TypeScript/JavaScript）和完全托管服务
    - 应用场景：支持AI助手、客户支持、医疗保健、生产力工具等领域
    - 性能优势：比完整上下文方案快91%、节省90%Token、准确度提升26%
    - 灵活部署：支持自托管（开源）和托管平台两种方式
    - 丰富集成：支持LangGraph、CrewAI、ChatGPT插件、浏览器扩展等

- [cognee](https://github.com/topoteretes/cognee) ![GitHub Repo stars](https://img.shields.io/github/stars/topoteretes/cognee)
  - Cognee 是一个开源工具和平台，将原始数据转化为AI智能体的持久化动态记忆。它结合向量搜索和图数据库技术，使文档既可按语义搜索，又可通过关系连接。Cognee提供两种使用方式：自托管开源版本（数据本地存储）和托管云服务版本（企业级基础设施）。核心特性包括支持30+数据源的Python数据流水线、用ECL（提取、认知化、加载）流程替代传统RAG系统、以及高度可定制化的搜索端点和自定义任务。
  - 主要功能点
    - 将任意类型数据（对话、文件、图像、音频转录）互联连接
    - 用统一内存层（基于图和向量）替代传统RAG系统
    - 支持30+数据源的Pythonic数据管道
    - 提供自定义任务、模块化管道和内置搜索端点的高度定制化
    - 六行代码快速集成AI记忆功能
    - 支持知识图谱生成和关系推理

- [hindsight](https://github.com/vectorize-io/hindsight) ![GitHub stars](https://img.shields.io/github/stars/vectorize-io/hindsight.svg?style=flat&label=Star)
  - Hindsight是一个仿生智能体记忆系统，旨在为自动化任务和对话交互的AI智能体创建长期学习能力。相比传统的RAG和知识图谱方案，Hindsight通过模仿人类记忆的方式（世界知识、经验、观点、观察）来组织记忆，在LongMemEval基准测试中取得了最先进的性能。系统提供Retain（保留）、Recall（回忆）、Reflect（反思）三个核心操作，使智能体能够存储信息、检索记忆并从经验中学习改进。
  - 主要功能点
    - Retain操作：使用LLM提取事实、时间数据、实体和关系，将信息规范化后存储到记忆库中
    - Recall操作：并行执行语义检索、关键词匹配、图谱关联、时间范围等4种检索策略，通过倒数- 排名融合和交叉编码器重排序返回相关记忆
    - Reflect操作：深度分析现有记忆形成新的连接，生成观点和观察，使智能体能够从经验中学习
    - 四层记忆架构：世界知识、经验、观点、观察，形成类似人类的记忆组织方式
    - 多种部署方式：Docker容器、Python嵌入式、REST API、CLI等多种集成选项


- [EverMemOS](https://github.com/EverMind-AI/EverMemOS)![GitHub Repo stars](https://img.shields.io/github/stars/EverMind-AI/EverMemOS)
  - EverMemOS 是一个开源的企业级智能记忆系统，旨在为对话式AI代理提供长期记忆能力。与传统AI记忆系统仅作为"回顾"数据库不同，EverMemOS使AI不仅能够"记住"发生过的事情，还能"理解"这些记忆背后的含义，并用其指导当前的行动和决策。系统通过记忆构建和记忆感知两个主要轨道运作，实现从原始对话数据中提取、结构化和检索信息，使AI能够维持上下文、回忆过去交互，并逐步构建用户档案。在LoCoMo基准测试中，基于EverMemOS的方法达到了92.3%的推理准确率。
  - 主要功能点
    - 记忆构建层：从对话数据中提取原子记忆单元(MemCell)，通过主题和故事线整合形成多层级结- 构化记忆
    - 记忆感知层：通过多轮推理和智能融合实现精准的上下文感知，支持混合检索、智能重排序等多种检索策略
    - 连贯叙述：将零散的对话片段连接成完整故事，使AI真正理解而非片段理解
    - 证据感知：主动捕捉记忆与任务的深层联系，实现真正基于理解的思考
    - 动态用户档案：实时更新用户档案，随着交互深化而不断学习用户特征
    - 多种检索模式：支持轻量级快速模式(BM25)、智能多轮回忆(Agentic)、混合检索(RRF融合)等

- [MemoryBank](https://github.com/zhongwanjun/MemoryBank-SiliconFriend?tab=readme-ov-file) ![GitHub Repo stars](https://img.shields.io/github/stars/zhongwanjun/MemoryBank-SiliconFriend)
  - MemoryBank-SiliconFriend 是一个为大型语言模型(LLM)设计的长期记忆机制项目。该项目包含了论文《MemoryBank: Enhancing Large Language Models with Long-Term Memory》的数据、模型和代码。MemoryBank 灵感来自于艾宾浩斯遗忘曲线理论，能让 AI 访问相关记忆、持续演进并适应用户个性。SiliconFriend 是基于该机制的双语 LLM 聊天机器人，通过在心理对话数据上使用 LoRA 微调，展现出更高的共情能力，可用于长期 AI 陪伴场景。项目提供了基于 ChatGLM 和 BELLE 的两个 LoRA 检查点，以及完整的 Web 演示和命令行工具。
  - 主要功能点
    - 实现了基于艾宾浩斯遗忘曲线的人类化记忆更新机制
    - 支持记忆检索、记忆更新和用户个性学习
    - 提供 ChatGLM、BELLE 和 ChatGPT 三种模型支持
    - 包含 Web 演示和 CLI 命令行工具
    - 提供双语(中英文)支持
    - 包含 38K 中文心理对话数据和评估数据集
- [langmem](https://github.com/langchain-ai/langmem)
  - LangMem 是一个帮助agent通过交互学习和适应的库。它提供了从对话中提取重要信息、通过提示优化改进代理行为以及维护长期记忆的工具。LangMem既可以作为函数原语与任何存储系统配合使用，也能与LangGraph的存储层原生集成。该项目使agent能够持续改进、个性化响应并跨会话保持一致行为。
  - 主要功能点
    - 🧩 核心内存API，与任何存储系统兼容
    - 🧠 内存管理工具，代理可在活跃对话中记录和搜索信息
    - ⚙️ 后台内存管理器，自动提取、整合和更新代理知识
    - ⚡ 与LangGraph长期内存存储原生集成，默认在所有LangGraph平台部署中可用

## Agent应用
- [gpt-newspaper](https://github.com/assafelovic/gpt-newspaper) ![GitHub stars](https://img.shields.io/github/stars/assafelovic/gpt-newspaper.svg?style=flat&label=Star)
  - 这是一个创新的自主代理，旨在根据用户偏好创建个性化报纸。 GPT Newspaper 利用人工智能的力量根据个人品味和兴趣策划、撰写、设计和编辑内容，彻底改变了我们消费新闻的方式。
- [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main) ![GitHub stars](https://img.shields.io/github/stars/Shubhamsaboo/awesome-llm-apps.svg?style=flat&label=Star)
  - 包含了使用 OpenAI、Anthropic、Gemini 和开源模型的 LLM（Large Language Model）应用程序的示例和教程
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) ![GitHub stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands.svg?style=flat&label=Star)
  -  OpenHands(前身是OpenDevin)是一个基于 AI 的软件开发代理平台。它可以执行任何人类开发人员能做的事情,如修改代码、运行命令、浏览网页、调用 API,甚至从 StackOverflow 复制代码片段。OpenHands 旨在帮助开发人员减少编码工作,提高工作效率。
- [TradingAgents：用多Agent框架炒股，多赚6个点收益](https://github.com/TauricResearch/TradingAgents)  ![GitHub stars](https://img.shields.io/github/stars/TauricResearch/TradingAgents.svg?style=flat&label=Star)
  - https://mp.weixin.qq.com/s/6gKm49WMPB0Xx2IlCNtuxA
  - TradingAgents 是一个多智能体LLM金融交易框架，模拟真实交易公司的运作动态。该框架通过部署基础面分析师、情绪分析师、技术分析师、交易员和风险管理团队等专业化LLM智能体，协作评估市场条件并做出交易决策。框架采用LangGraph构建，具有灵活和模块化的特性，支持CLI和Python包两种使用方式，使用OpenAI API作为核心LLM支持，并可配置多种数据源。
  - 主要功能点
    - 分析师团队：包含基础面分析师、情绪分析师、新闻分析师和技术分析师，各自专注于不同的市场分析维度
    - 研究者团队：由看涨和看跌研究员组成，通过结构化辩论平衡风险与收益
    - 交易员代理：综合各分析团队报告做出交易决策
    - 风险管理和投资组合经理：持续评估投资组合风险，最终批准或拒绝交易提案
    - CLI工具：提供交互式界面支持股票代码、日期、LLM模型等参数配置
    - 灵活配置：支持自定义LLM选择、辩论轮数、数据源等配置参数
- [realtime-phone-agents-course](https://github.com/neural-maze/realtime-phone-agents-course)
  - 这是一个综合性的实时电话语音代理课程项目，通过4周的循序渐进教学，教授开发者如何构建生产级的AI语音智能体系统。该项目以构建一个房地产公司的"AI员工"为实际案例，整合了实时语音处理、向量搜索、电话集成和GPU部署等核心技术，提供从基础概念到云端部署的完整学习路径。
  - 主要功能点
    -  ☎️ 通过Twilio接收和发送真实电话呼叫
    -  🏠 使用Superlinked进行复杂多属性房产数据搜索
    -  ⚡ 利用FastRTC实现低延迟的实时语音对话
    -  🗣️ 集成Moonshine和Fast Whisper进行高效语音转文字
    -  🎙️ 使用Kokoro和Orpheus 3B生成逼真的语音合成
    -  🚀 在Runpod上部署开源模型实现GPU加速
    -  📊 使用Opik进行全链路对话追踪和监控
    -  👥 支持多化身系统实现不同AI人设
- [BettaFish](https://github.com/666ghj/BettaFish)
  - BettaFish是一个从零开始构建的创新型多智能体舆情分析系统，旨在帮助用户打破信息茧房、还原舆情原貌、预测未来走向。用户只需像聊天一样提出分析需求，系统会自动分析国内外30+主流社交媒体和数百万条大众评论。该项目拥有AI驱动的全域监控、超越LLM的复合分析引擎、强大的多模态能力、Agent论坛协作机制、公私域数据融合以及轻量化的高扩展性框架等六大优势。
  - 主要功能点
    - QueryEngine：国内外新闻广度搜索Agent，具备网页搜索能力
    - MediaEngine：强大的多模态内容分析Agent，支持视频/图片深度解析
    - InsightEngine：私有数据库挖掘Agent，用于内部数据深度分析
    - ReportEngine：智能报告生成Agent，具备多轮报告生成能力
    - ForumEngine：论坛协作引擎，实现Agent间的链式思维碰撞与辩论
    - MindSpider：7x24小时不间断的AI爬虫系统，覆盖10+社交媒体平台
    - SentimentAnalysisModel：多种情感分析模型（BERT、GPT-2、Qwen等）
- [OmniThink](https://github.com/zjunlp/OmniThink) ![GitHub stars](https://img.shields.io/github/stars/zjunlp/OmniThink.svg?style=flat&label=Star)
  - https://mp.weixin.qq.com/s/6gKm49WMPB0Xx2IlCNtuxA
  - 浙大和阿里通义实验室开源的一个深度AI写作系统：OmniThink，它模拟人类学习和思考过程，实现了更深入的AI写作，解决了现在AI内容浅显、重复、非原创的问题
  - OmniThink通过迭代扩展，不断扩充知识边界、持续反思、渐进学习的方式模拟人类学习过程
  - 输出的内容知识密度高，内容冗余少，具备比较强的逻辑性的深度思考能力
  - 支持多种底座模型，可自定义知识来源，可调整生成策略，不过生成质量依赖底座模型质量

- [WebWalker](https://github.com/Alibaba-NLP/WebWalker) ![GitHub stars](https://img.shields.io/github/stars/Alibaba-NLP/WebWalker.svg?style=flat&label=Star)
  - 阿里出的一个可以让LLM像人类一样在网上搜索信息的多智能体框架：WebWalker，它可以让LLM能自动点击链接、阅读网页、理解信息、最终给出答案，解决传统搜索引擎只能浅层搜索的问题
  - 系统包含两个智能体，一个找信息助手，负责点击链接、浏览网页内容； 一个判断助手，判断找到的信息够不够， 是否需要继续找，给出答案
  - 垂直搜索能力强，能处理复杂问题，可以深入多个网页，找到隐藏的信息
  - 它可以和现有的AI问答系统（比如RAG）结合，比如RAG系统以前只能找到一些简单的答案，加上WebWalker后，可以增强处理复杂网络信息的能力
- [pasa](https://github.com/bytedance/pasa) ![GitHub stars](https://img.shields.io/github/stars/bytedance/pasa.svg?style=flat&label=Star)
  - 字节开源的一个非常智能的论文搜索代理：pasa(Paper Search agent)，它可以调用搜索工具、阅读论文、选择相关的参考文献，自己做决策，为复杂的学术查询提供全面准确结果
  - 核心是它不只是简单的关键词搜索，它会像人一样思考，阅读论文，并根据需求选择最合适的论文
  - PaSa-7B在召回率上比 PaSa-GPT-4o高30.36%，精确率高4.25%
  - PaSa-7B在recall@20和recall@50上，分别比使用 GPT-4 增强后的Google搜索高37.78% 和 39.90%，优于Google 系搜索引擎
  - pasa有两个代理，
    - 1. Crawler处理用户查询，访问论文队列，可以调用搜索工具，展开引用，控制当前论文处理  
    - 2. Selector， 读队列中的论文，判断是否符合查询标准
- [CHRONOS](https://github.com/Alibaba-NLP/CHRONOS?tab=readme-ov-file) ![GitHub stars](https://img.shields.io/github/stars/Alibaba-NLP/CHRONOS.svg?style=flat&label=Star)
  - 阿里巴巴开源的一个新闻时间线摘要生成系统：CHRONOS，给它一个话题，它能生成一份按时间顺序整理好的重要事件摘要
  - 具备迭代式自我提问机制，可以自己提问，自动找答案，按时间顺序整理重要信息
  - 支持开放域新闻时间线生成，不限特定领域
  - 处理速度快，可以处理大量新闻
- [gptrpg](https://github.com/dzoba/gptrpg) ![GitHub stars](https://img.shields.io/github/stars/dzoba/gptrpg.svg?style=flat&label=Star)
  - 多年未更新，可忽略

## 工具
- [semantic-router](https://github.com/aurelio-labs/semantic-router/tree/main)
  - semantic-router是为大模型和agent代理提供一个超快速的决策层。我们不用等待缓慢的LLM来生成使用哪个工具的决策，而是利用语义向量空间的法力来做出这些决策——使用语义来路由我们的请求
- [TypeChat](https://github.com/microsoft/TypeChat)
- [json_repair](https://github.com/mangiucugna/json_repair)  ![GitHub stars](https://img.shields.io/github/stars/mangiucugna/json_repair.svg?style=flat&label=Star)
  - 修复损坏的JSON文件,在LLM生成json数据场景下很有用
- [openagents](https://github.com/openagents-org/openagents)
  - OpenAgents是一个开源项目,旨在创建AI Agent网络并将Agent连接到网络以进行开放协作。它提供了一个基础网络基础设施,使AI Agent能够无缝连接和协作。每个OpenAgents网络都是一个自包含的社区,Agent可以在其中发现对等方、协作解决问题、相互学习和共同成长。它与流行的LLM提供商和代理框架协议无关。
## 安全护栏

- [guidance](https://github.com/guidance-ai/guidance)
- [NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)

# 课程
- [吴恩达 deeplearning：agentic-ai](https://www.deeplearning.ai/courses/agentic-ai/)
- [2025-03 微软 AI Agents for Beginners](https://learn.microsoft.com/en-us/shows/ai-agents-for-beginners/)
- [AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)
- [Multi AI Agent Systems with crewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)


## 图书
- [datawhalechina/hello-agents](https://github.com/datawhalechina/hello-agents)
 ![GitHub Repo stars](https://img.shields.io/github/stars/datawhalechina/hello-agents)
 - 📚 《从零开始构建智能体》——从零开始的智能体原理与实践教程

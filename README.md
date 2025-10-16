# awesome-llm-agent
everything about llm based agent
 latest update: 2025-10-16
# 论文
## 综述
- [A Survey on Agentic Security: Applications, Threats and Defenses](https://arxiv.org/abs/2510.06445)
  ![](https://cdn.jsdelivr.net/gh/lizhe2004/pic-repo@master//imgs/20251013101641455.png)
- [2023-09-19 The Rise and Potential of Large Language Model Based Agents: A Survey](https://arxiv.org/pdf/2309.07864)
  - [github](https://github.com/WooooDyy/LLM-Agent-Paper-List)
- [2024-12-30 Large Language Model-Brained GUI Agents: A Survey](https://arxiv.org/abs/2411.18279)
  - 大型语言模型（LLM）驱动的图形用户界面（GUI）智能体（Agent）。这一领域融合了人工智能、人机交互和软件工程的跨学科知识，是当前AI领域最活跃的方向之一。本次的综述系列解读将系统梳理LLM驱动GUI Agent的发展脉络，剖析其核心技术、关键挑战及未来机遇，旨在为感兴趣的读者提供详尽指南，并激发更多创新思考。
  - ![](https://cdn.jsdelivr.net/gh/lizhe2004/pic-repo@master/imgs/20250121144556.png)
  - [中文总结](https://mp.weixin.qq.com/s/qacueqa-xEgLuZ09L0JUOA)
- [2025-01-25 Agent AI: Surveying the Horizons of Multimodal Interaction](https://arxiv.org/abs/2401.03568)
- [2024-12-15 A Survey on Large Language Model based Autonomous Agents](https://arxiv.org/abs/2308.11432)
  - [中文总结](https://mp.weixin.qq.com/s/Jz_oHJ64bq9eAfvLrZ8Jpw)

# 开源项目
## Agent框架
- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) ![GitHub stars](https://img.shields.io/github/stars/microsoft/agent-framework.svg?style=flat&label=Star)
  - Microsoft Agent Framework 是一个全面的多语言框架,用于构建、编排和部署 AI 代理,支持 .NET 和 Python 实现。该框架提供从简单的聊天代理到复杂的多代理工作流程的一切,并支持基于图的编排。
  - 主要功能点
    - 基于图的工作流程:使用数据流连接代理和确定性函数,支持流式处理、检查点、人机交互和时间旅行等功能
    - Python 和 C#/.NET 支持:完全支持 Python 和 C#/.NET 实现,API 一致
    - 可观察性:内置 OpenTelemetry 集成,用于分布式跟踪、监控和调试
    - 多代理提供商支持:支持各种 LLM 提供商
    - 中间件:灵活的中间件系统,用于请求/响应处理、异常处理和自定义管道
- [crewAI](https://github.com/joaomdmoura/crewAI)
  - 用于编排角色扮演、自主人工智能代理的尖端框架。通过促进协作智能，CrewAI 使代理能够无缝协作，处理复杂的任务。
  - CrewAI 更加强调其易用性和快速搭建演示的特性。该平台直观易操作，主要通过编写提示来生成和配置智能体。在 CrewAI 平台上，智能体的创建和集成过程极为简便，用户能在短时间内轻松构建数百个智能体，因此它成为了追求快速制作 Multi-Agent 演示或原型开发者的首选工具。
  - 不过，CrewAI 在灵活性和定制化方面有所不足，更适合处理简单的用例，而不太适合复杂的编程作业。同时，智能体间的交互可能会存在一些 Bugs，这可能会对项目的稳定性和可靠性造成影响。尽管存在这些局限，对于那些仅需迅速构建演示或原型，且对系统灵活性要求不高的开发者而言，CrewAI 依旧是个合适的选择。
- [gptrpg](https://github.com/dzoba/gptrpg)

- [AutoGen](https://github.com/microsoft/autogen)
  - AutoGen 作为微软在多智能体领域推出的早期且广受欢迎的框架之一，旨在为软件开发提供解决方案。在该框架中，核心由两种智能体构成：用户智能体（User-Agent）和助手智能体（Assistant-Agent）。用户智能体负责传达指令和需求，而助手智能体则负责代码的生成与执行，并将成果反馈给用户或其他智能体。
  - AutoGen 的一大亮点在于其卓越的多智能体协调能力，尤其在应对编程任务时表现尤为突出。它还允许在智能体互动过程中进行人工干预，增加了开发流程的灵活性和可控性。
  - 尽管如此，AutoGen 也并非完美无缺。其用户界面可能不够直观，对于非技术人员来说，可能需要一定的学习时间。另外，AutoGen 的配置过程较为繁琐，尤其是在集成本地大型语言模型（LLM）时，还需要设置代理服务器。因此，AutoGen 更适合那些对软件开发有一定了解，并且愿意投入时间和精力去掌握其使用方法的开发者。

  - [AutoGen Studio](https://github.com/microsoft/autogen/tree/main/samples/apps/autogen-studio)
  - 来自微软研究院的 AutoGen Studio 是一个用于构建 AI Agent 团队的无代码平台。他们包揽从编写和执行代码 🧑‍💻 到规划旅行 ✈️ 到绘制股票图表的所有工作。


- [ModelScope-Agent](https://github.com/modelscope/modelscope-agent/tree/master)
  - ModelScope-Agent是一个通用的、可定制的Agent框架，用于实际应用程序，其基于开源的大语言模型 (LLMs) 作为核心。它提供了一个用户友好的系统库， 具有以下特点：
    - 可定制且功能全面的框架：提供可定制的引擎设计，涵盖了数据收集、工具检索、工具注册、存储管理、定制模型训练和实际应用等功能，可用于快速实现实际场景中的应用。
    - 开源LLMs作为核心组件：支持在 ModelScope 社区的多个开源LLMs上进行模型训练。
    - 多样化且全面的API：以统一的方式实现与模型API和常见的功能API的无缝集成。


- [pydantic-ai](https://github.com/pydantic/pydantic-ai)
  - **PydanticAI**是一个基于Python的Agent框架,旨在简化使用生成式AI构建生产级应用程序的过程。它由Pydantic团队开发。
  - **模型无关性**:支持OpenAI、Gemini和Groq等多种LLM模型
  - **类型安全**:使用Pydantic进行类型检查和验证
  - **控制流和Agent组合**:使用标准Python实现
  - **结构化响应验证**:使用Pydantic进行验证
  - **流式响应处理**:包括对流式结构化响应的验证
  - **依赖注入系统**:用于测试和基于评估的迭代开发
  - **Logfire集成**:用于调试和监控LLM应用程序的性能和行为


- [LangGraph](https://github.com/langchain-ai/langgraph)
  - LangGraph 是一款基于 LangChain 打造的 Multi-Agent 框架，该框架通过引入有向循环图的理念，打造了一个极具灵活性和可定制性的解决方案。LangGraph 不仅适用于各类 Multi-Agent 任务，还能支持几乎所有的多智能体编排应用，使其成为那些面临复杂任务、追求高度灵活性和定制化能力的开发者的首选工具。
  - 尽管如此，LangGraph 的文档资料相对较少，这可能会让新手或编程经验不足的用户在入门时遇到困难。同时，使用 LangGraph 还需要用户具备一定的编程能力，特别是对图形结构和逻辑流程的掌握。因此，LangGraph 更适宜于那些拥有丰富编程背景、愿意投入时间深入学习的高级开发者。
 
- [OpenAI Swarm](https://github.com/openai/swarm)
  - OpenAI Swarm 是 OpenAI 最新推出的多智能体框架，致力于简化智能体的构建过程以及智能体间的交接操作（即 Handoffs）。Swarm 框架特别适合初学者，让他们能够轻松入门多智能体技术，快速搭建演示项目。
  - 尽管如此，Swarm 的功能范围较为狭窄，仅支持 OpenAI API，而不兼容其他语言模型提供商的 API，这在实际生产部署中可能带来限制。同时，Swarm 的灵活性不足，难以满足追求高度定制化和灵活配置的用户需求。另外，Swarm的社区支持力度较弱，用户在 GitHub 上提交问题或寻求帮助时可能会遇到困难。

 
- [Magentic-One](https://github.com/microsoft/autogen/tree/main/python/packages/autogen-magentic-one
)
  - Magnetic-One是微软继 AutoGen 之后推出的新一款多智能体框架。与OpenAI 的 Swarm 相似，Magnetic-One 同样专注于降低智能体构建和操作的复杂性。该框架预装了五个基础智能体，其中包括一个负责管理的智能体以及四个分别承担不同职能的智能体（WebSurfer、FileSurfer、Coder和ComputerTerminal），这使得 Magnetic-One 成为了一个适合非编程背景用户以及需要迅速掌握使用方法的用户的通用型平台。
  - 尽管如此，Magnetic-One 在支持开源语言模型（LLM）方面存在一定难度，这可能给想要利用开源 LLM 的用户带来挑战。同时，Magnetic-One 在灵活性方面略显不足，更倾向于一个应用而非一个完全开放的框架。目前，Magnetic-One 的文档资料和社区支持也较为有限，这可能会对用户的体验和问题解决效率产生不利影响。

- [agentUniverse](https://github.com/antgroup/agentUniverse/blob/master/README_zh.md)
  - agentUniverse 是一个基于大型语言模型的多智能体框架,由蚂蚁集团开源。 agentUniverse为您提供灵活易拓展的单智能体构建能力；agentUniverse核心拥有丰富的多智能体协同模式组件（可视为一个协同模式工厂Pattern Factory），它能让智能体们各司其职在解决不同领域问题时发挥最大的能力；同时agentUniverse专注于领域经验的融合，帮助您轻松将领域经验融入到智能体的工作中。
- [Qwen-Agent](https://github.com/QwenLM/Qwen-Agent/blob/main/README_CN.md)
  - Qwen-Agent是一个开发框架。开发者可基于本框架开发Agent应用，充分利用基于通义千问模型（Qwen）的指令遵循、工具使用、规划、记忆能力。本项目也提供了浏览器助手、代码解释器、自定义助手等示例应用。

- [ROMA](https://github.com/sentient-agi/ROMA)
  ROMA（Recursive Open Meta-Agents）是一个元代理框架,使用递归层次结构来解决复杂问题。通过将任务分解为可并行的组件,ROMA使代理能够处理复杂的推理挑战,同时保持透明度,使上下文工程和迭代变得简单。该框架提供并行问题解决,代理可以同时处理复杂任务的不同部分,透明的开发具有清晰的结构,便于调试,并且通过搜索代理的强大基准测试结果证明了其性能。

## Agent应用
- [gpt-newspaper](https://github.com/assafelovic/gpt-newspaper)
  - 这是一个创新的自主代理，旨在根据用户偏好创建个性化报纸。 GPT Newspaper 利用人工智能的力量根据个人品味和兴趣策划、撰写、设计和编辑内容，彻底改变了我们消费新闻的方式。
- [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main)
  - 包含了使用 OpenAI、Anthropic、Gemini 和开源模型的 LLM（Large Language Model）应用程序的示例和教程
- [OpenHands](https://github.com/All-Hands-AI/OpenHands)
  -  OpenHands(前身是OpenDevin)是一个基于 AI 的软件开发代理平台。它可以执行任何人类开发人员能做的事情,如修改代码、运行命令、浏览网页、调用 API,甚至从 StackOverflow 复制代码片段。OpenHands 旨在帮助开发人员减少编码工作,提高工作效率。
- [TradingAgents：用多Agent框架炒股，多赚6个点收益](https://mp.weixin.qq.com/s/6gKm49WMPB0Xx2IlCNtuxA)
- [OmniThink](https://github.com/zjunlp/OmniThink)
  - 浙大和阿里通义实验室开源的一个深度AI写作系统：OmniThink，它模拟人类学习和思考过程，实现了更深入的AI写作，解决了现在AI内容浅显、重复、非原创的问题
  - OmniThink通过迭代扩展，不断扩充知识边界、持续反思、渐进学习的方式模拟人类学习过程
  - 输出的内容知识密度高，内容冗余少，具备比较强的逻辑性的深度思考能力
  - 支持多种底座模型，可自定义知识来源，可调整生成策略，不过生成质量依赖底座模型质量
- [WebWalker](https://github.com/Alibaba-NLP/WebWalker)
  - 阿里出的一个可以让LLM像人类一样在网上搜索信息的多智能体框架：WebWalker，它可以让LLM能自动点击链接、阅读网页、理解信息、最终给出答案，解决传统搜索引擎只能浅层搜索的问题
  - 系统包含两个智能体，一个找信息助手，负责点击链接、浏览网页内容； 一个判断助手，判断找到的信息够不够， 是否需要继续找，给出答案
  - 垂直搜索能力强，能处理复杂问题，可以深入多个网页，找到隐藏的信息
  - 它可以和现有的AI问答系统（比如RAG）结合，比如RAG系统以前只能找到一些简单的答案，加上WebWalker后，可以增强处理复杂网络信息的能力
- [pasa](https://github.com/bytedance/pasa)\
  - 字节开源的一个非常智能的论文搜索代理：pasa(Paper Search agent)，它可以调用搜索工具、阅读论文、选择相关的参考文献，自己做决策，为复杂的学术查询提供全面准确结果
  - 核心是它不只是简单的关键词搜索，它会像人一样思考，阅读论文，并根据需求选择最合适的论文
  - PaSa-7B在召回率上比 PaSa-GPT-4o高30.36%，精确率高4.25%
  - PaSa-7B在recall@20和recall@50上，分别比使用 GPT-4 增强后的Google搜索高37.78% 和 39.90%，优于Google 系搜索引擎
  - pasa有两个代理，
    - 1. Crawler处理用户查询，访问论文队列，可以调用搜索工具，展开引用，控制当前论文处理  
    - 2. Selector， 读队列中的论文，判断是否符合查询标准
- [CHRONOS](https://github.com/Alibaba-NLP/CHRONOS?tab=readme-ov-file)
  - 阿里巴巴开源的一个新闻时间线摘要生成系统：CHRONOS，给它一个话题，它能生成一份按时间顺序整理好的重要事件摘要
  - 具备迭代式自我提问机制，可以自己提问，自动找答案，按时间顺序整理重要信息
  - 支持开放域新闻时间线生成，不限特定领域
  - 处理速度快，可以处理大量新闻
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


# 指南手册
- [智能体设计模式](https://docs.google.com/document/d/1rsaK53T3Lg5KoGwvf8ukOUvbELRtH-V0LnOIFDxBryE/preview?tab=t.0#)
  - [中译版（翻译中）](https://github.com/ginobefun/agentic-design-patterns-cn)
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
# 课程
- [吴恩达 deeplearning：agentic-ai](https://www.deeplearning.ai/courses/agentic-ai/)
- [2025-03 微软 AI Agents for Beginners](https://learn.microsoft.com/en-us/shows/ai-agents-for-beginners/)
- [AI Agents in LangGraph](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)
- [Multi AI Agent Systems with crewAI](https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/)

## 企业级实践
- [哈啰出行从Copilot到Agent模式的探索-贾立 PPT](https://www.alipan.com/s/U58jxu9vrKd)
- [Anthropic的构建智能体的经验总结和实践建议](https://www.anthropic.com/research/building-effective-agents)
- [阿里云服务领域Agent智能体：从概念到落地的思考、设计与实践](https://mp.weixin.qq.com/s/VBdgDIpmJvrt6fNgLE7i4Q)
- [支付宝百宝箱团队的技术负责人的AI Agent 综述分享](https://mp.weixin.qq.com/s/HrKOGXuI8wVM6qgylKZ8qw)
- 
## 行业最佳实践指南
- [Anthropic:Effective context engineering for AI agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)
- [Rebuilding Devin for Claude Sonnet 4.5: Lessons and Challenges](https://cognition.ai/blog/devin-sonnet-4-5-lessons-and-challenges)
- [OpenAI:Context Engineering - Short-Term Memory Management with Sessions](https://cookbook.openai.com/examples/agents_sdk/session_memory)
- [Claude官方Anthropic的构建智能体的经验总结和实践建议：构建高效智能体](https://www.anthropic.com/research/building-effective-agents)
  - [中文版](https://mp.weixin.qq.com/s/MgbHoQirV0fLmFkgRsI8KA)
- [基于大语言模型的智能代理](https://lilianweng.github.io/posts/2023-06-23-agent/)
  - [中文版](https://baoyu.io/translations/ai-agent/llm-powered-autonomous-agents)
  - ![](https://cdn.jsdelivr.net/gh/lizhe2004/pic-repo@master/imgs/20250121123852.png)
- [AI Agent（智能体）技术白皮书（Google，2024）](https://drive.google.com/file/d/1oEjiRCTbd54aSdB_eEe3UShxLBWK9xkt/view?pli=1)
  - [中文版](https://arthurchiao.art/blog/ai-agent-white-paper-zh/)

## 其他文章
- [Agentic Design Patterns with LangGraph](https://freedium.cfd/https://pub.towardsai.net/agentic-design-patterns-with-langgraph-5fe7289187e6)
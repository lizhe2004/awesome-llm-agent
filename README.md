# awesome-llm-agent
everything about llm based agent
222

333



# 开源项目
## Agent框架

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


## Agent应用
- [gpt-newspaper](https://github.com/assafelovic/gpt-newspaper)
  - 这是一个创新的自主代理，旨在根据用户偏好创建个性化报纸。 GPT Newspaper 利用人工智能的力量根据个人品味和兴趣策划、撰写、设计和编辑内容，彻底改变了我们消费新闻的方式。
- [awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main)
  - 包含了使用 OpenAI、Anthropic、Gemini 和开源模型的 LLM（Large Language Model）应用程序的示例和教程
- [OpenHands](https://github.com/All-Hands-AI/OpenHands)
  -  OpenHands(前身是OpenDevin)是一个基于 AI 的软件开发代理平台。它可以执行任何人类开发人员能做的事情,如修改代码、运行命令、浏览网页、调用 API,甚至从 StackOverflow 复制代码片段。OpenHands 旨在帮助开发人员减少编码工作,提高工作效率。
- [TradingAgents：用多Agent框架炒股，多赚6个点收益](https://mp.weixin.qq.com/s/6gKm49WMPB0Xx2IlCNtuxA)
- 
## 工具
- [semantic-router](https://github.com/aurelio-labs/semantic-router/tree/main)
  - semantic-router是为大模型和agent代理提供一个超快速的决策层。我们不用等待缓慢的LLM来生成使用哪个工具的决策，而是利用语义向量空间的法力来做出这些决策——使用语义来路由我们的请求
## 安全护栏
- [TypeChat](https://github.com/microsoft/TypeChat)
- [guidance](https://github.com/guidance-ai/guidance)
- [NeMo-Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)
- [json_repair](https://github.com/mangiucugna/json_repair)  
  - 修复损坏的JSON文件,在LLM生成json数据场景下很有用



## 企业级实践
- [哈啰出行从Copilot到Agent模式的探索-贾立 PPT](https://www.alipan.com/s/U58jxu9vrKd)
- [Anthropic的构建智能体的经验总结和实践建议](https://www.anthropic.com/research/building-effective-agents)
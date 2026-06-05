# ai_stack_notes
A note to keep track of the agentic AI building block and frameworks

<img width="1024" height="1536" alt="agentic building blocks" src="https://github.com/user-attachments/assets/3eab5dba-858e-49e5-8607-959f41c912cd" />

| #     | Building Block                       | Core Role                                  |  Common Frameworks / Tools                  |
| ----- | ------------------------------------ | ------------------------------------------ | ------------------------------------------- |
| **1** | **Orchestration / Core Loop**        | 🧠 **The agent’s brainstem**               | **LangGraph**, **Pydantic AI**, **Google ADK**, **CrewAI**, **OpenAI Agents SDK**, **Dify**    |
| **2** | **Memory**                           | 💾 **Context + personalization**           | **Mem0**,             |
|       |                                      |            | **Graphiti**,            |
|       |                                      |            | **Supabase Vector**           |
|       |                                      |            | [Text2Mem](https://github.com/MemTensor/text2mem)     |
|       |                                      |            | [letta(MemGPT)](https://github.com/letta-ai/letta)    |
|       |                                      |            | [PageIndex](https://github.com/VectifyAI/PageIndex)    |
|       |                                      |            | memU          |
|       |                                      |            | graphify          |
|       |                                      |            | rowboat          |
|       |                                      |            | Honcho          |
|       |                                      |            | holographic          |
|       |                                      |            | retaindb          |
|       |                                      |            | [SuperMemory](https://github.com/supermemoryai/supermemory)          |
|       |                                      |            | [MemOS](https://github.com/usememos/memos)          |
|       |                                      |            | [ByteRover](https://github.com/campfirein/byterover-cli)          |
|       |                                      |            | [HindSight](https://github.com/vectorize-io/hindsight)          |
|       |                                      |            | [OpenViking](https://github.com/volcengine/OpenViking)          |
| **3** | **Tools / Function Interface**       | 🧰 **Action layer (hands)**                | **Function Calling**, **MCP** |
| **4** | **Planning**                         | 🗺️ **Strategic reasoning (goal → steps)**  | **LangGraph Planner nodes**, **CrewAI Director**, **AutoGen Planner**, **Tree-of-Thought / ReAct** patterns        |
| **5** | **Guardrails / Safety / Policy**     | 🛡️ **Ethical & compliance gatekeeper**    | **Guardrails AI**, **NVIDIA NeMo Guardrails**, **LlamaGuard**, **OpenAI Moderation** |
| **6** | **Evaluation / Feedback / EvalsOps** | 🔍 **Performance & learning loop**         | **deepeval**, **LangFuse**, **LangSmith** |
| **7** | **Front-end framework** | 🔍 **client side communication and rendering**         | **CopilotKit**, **A2UI** |


| Catogory      | Libraries or Frameworks | Use case                         |
|-------------- | ------------------------| -------------------------------- |
| Data Source   | docling                 | doc -> structured data for GenAI |
|               | unstructured            |                                  |
|               | craw4ai                 | site -> knowledge store          |
|               | [Scrapling](https://github.com/D4Vinci/Scrapling) |        |
|               | [Scrappy](https://github.com/scrapy/scrapy) |              |
|   RAG Query   | [LlamaIndex](https://www.llamaindex.ai/)              |             |
|               | Haystack                |                                  |



Coding Tools and Resources
| Catogory               | Libraries or Frameworks                                                 | Use case                         |
|----------------------- | ------------------------------------------------------------------------| -------------------------------- |
|   Coding Autonomy      | [Auto Claude](https://github.com/AndyMik90/Auto-Claude)                 |                                  |
|                        | [Claud Flow](https://github.com/ruvnet/claude-flow)                     |                                  |
|                        | [Ralph](https://github.com/snarktank/ralph)                             |                                  |
|                        | [Ralph Claude Code](https://github.com/frankbria/ralph-claude-code)     |                                  |
|                        | [Spec Kitty](https://github.com/Priivacy-ai/spec-kitty)                 |                                  |
|                        | [SuperPower](https://github.com/obra/superpowers)                       |                                  |
|                        | [GSD](https://github.com/glittercowboy/get-shit-done)                   |                                  |
|                        | [GStack](https://github.com/garrytan/gstack)                            |                                  |
|Self Improving Software | [AutoResearch](https://github.com/karpathy/autoresearch)                |                                  |
|                        | [ACE](https://github.com/klizhentas/ace)                | [Paper](https://arxiv.org/pdf/2603.19461)        |
|                        | [DSPy](https://github.com/Strategic-Automation/dspy-compounding-engineering)           |                  |
|   Context Eng Method   | [BMAD](https://github.com/bmad-code-org/BMAD-METHOD)                    |                                  |
|                        | [Context Engineering](https://github.com/Apoo711/Context-Engineering)   |                                  |
|                        | [Open Spec](https://github.com/Fission-AI/OpenSpec)                     |                                  |
|                        | [Spec Kit](https://github.com/github/spec-kit)                          |                                  |
|   MCP Resource         | [MCP](https://mcpservers.org/)                                          |                                  |
|                        | [Serena](https://github.com/oraios/serena)                              | Project memory and session persistence |
|                        | [Contex7](https://github.com/upstash/context7)                          |                                  |
|                        | [Sequential Thinking]()                                                 |                                  |
|                        | [Cyrus](https://github.com/ceedaragents/cyrus)                          |                                  |
|                        | [Pal MCP](https://github.com/BeehiveInnovations/pal-mcp-server)         |                                  |
|   Skills Resource      | [Skills](https://skills.sh/)                                            |                                  |
|   Product Building     | [ChatDev 2.0](https://github.com/OpenBMB/ChatDev)                       |                                  |
|                        | [MetaGPT](https://github.com/FoundationAgents/MetaGPT)                  |                                  |
|                        | [OpenHands](https://github.com/OpenHands/OpenHands)                     |                                  |
|                        | [AutoGPT](https://github.com/significant-gravitas/autogpt)              |                                  |
|   Agent Examples       | [OpenClaw](https://github.com/openclaw/openclaw)                        |                                  |
|                        | [Hermes-agent](https://github.com/nousresearch/hermes-agent)            |                                  |
|                        | [Mercury-agent](https://github.com/cosmicstack-labs/mercury-agent)      |                                  |
|   LLM Wiki            | [SwarmVault](https://www.swarmvault.ai/)                                 |                                  |
|                        | [Karpathy Gist](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f)  |                  |
|                        | [Kompl](https://mcpmarket.com/server/kompl)      |                                  |
|                        | [Synthadoc](https://github.com/axoviq-ai/synthadoc)                    |                                  |
|                        | [Canifi](https://www.canifi.com/), [Canifi OS](https://github.com/andrejones92/canifi-life-os)    |      |







Misc:
- [Spec2Beads](https://smithery.ai/skills/lucastamoios/openspec-to-beads)
- [GasTown](https://wasteland.gastownhall.ai/)
- [SuperMemory](https://github.com/supermemoryai)
- [harness engineering](https://m.youtube.com/watch?v=ugKW_Dv37Bk)
- [DevOps Harness](https://developer.harness.io/docs/platform/harness-ai/harness-agents/)
- [Anthropic Harness Engineering](https://www.anthropic.com/engineering/harness-design-long-running-apps)
- [Harness Design](https://github.com/revfactory/harness)

Claude Code Usage Tips:
- Context Window Hygiene: e.g., `use { allow : "Edit(*)" }` but only to this project, instead of a huge list permitted resource;
- Be careful when you install a long list of skills (but rarely used)
- combine [superpower with gstack](https://m.youtube.com/watch?v=Y9hR2M4FE4I)

AWS Testing
- Localstack
- [Ministack](https://github.com/ministackorg/ministack)
- [Floci](https://github.com/floci-io/floci)
  

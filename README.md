
# Xu Hang  (Edwards)

**Embodied AI Algorithm Engineer — building VLA models, tactile / vision perception, and Agentic-RAG full-stack systems.**
Software Engineering 
Dedicated to realizing the deployment of VLA and AGI
- Shenzhen / Guangzhou / Hongkong/Singapore
- strawberry.77.111@gmail.com --business only
- https://x.com/strawberry_1_77 --chat anything
- youtube - gonna building

I work at the intersection of embodied AI and LLM agents: from vision-tactile bimodal data collection for VLA models, to enterprise-grade Agentic-RAG products. I own the full pipeline — algorithm design, engineering deployment, performance optimization — and ship fast with Agentic coding tools (Claude Code / Codex).

---

### 🔬 Now Focusing On

- **Embodied AI / VLA** — RGB + array-tactile bimodal data collection, real-robot testing, sim-to-real
- **AI Agent** — LangGraph multi-agent orchestration, Hybrid Search, RAG evaluation loops
- **Engineering** — PyQt5 / OpenGL real-time visualization, concurrency, full-stack streaming
- **World Model** -
- **NYSE/Nas & Quant** -

### 💼 Experience

**AI Agent Engineer /full stack

Built an enterprise-grade Agentic-RAG knowledge base (end-to-end: upload → 3-level chunking → vector store → streaming QA).

- Designed Dense(BGE-m3) + BM25 dual-tower Hybrid Search with RRF(k=60) fusion and Corrective RAG; Hybrid recall@3 reached 48/50 (vs 43 Dense, 45 BM25)
- Solved model-loading blockage in China: pulled bge-m3 (2.27GB) via ModelScope for fully local deployment, removing the HuggingFace dependency
- Adapted DeepSeek-series models with LangChain structured output; fixed thinking / tool_choice conflicts via function_calling + extra_body
- Built an offline RAG eval loop (50 labeled queries); BM25 ~8ms vs Dense 192ms (~23× faster)
- Full-stack streaming: SSE token-by-token push + AbortController; ~75% token savings per abort
- Engineering: JWT + RBAC middleware, Redis multi-level cache (P95 < 15ms); shipped 25k+ lines of full-stack code solo in 3 weeks

**Embodied AI Algorithm Engineer  

Built the data and perception toolchain for a VLA model R&D loop (robotic arm contact-intensive tasks).

- Developed RGB + array-tactile bimodal data-collection and real-robot testing tools (PyQt5 + OpenCV); cut the collect → verify → iterate cycle by 60%
- Refactored the visualization GUI (~1,900 lines) with PyQt5 + OpenGL; main-thread frame time 60–110ms → 10–25ms, FPS 12–18 → 25–30 (~4×)
- Optimized Farneback dense optical flow to 0.05ms/frame (orders of magnitude); fixed 3000+ mN idle-force and tare dead-loop defects
- Rewrote contact / slip detection: pixel-count gating replaced fz-scalar gating, eliminating ambient-light false triggers
- Designed 17-dimensional tactile-feature adaptive normalization with runtime max-tracking (no prior range needed)

---

### 🌐 Languages

- **Chinese - Native -
---

### 📌 Projects & Open Source
[**AVAZone**](https://github.com/strawberry77-1/AVAZone) — A Special Economic Zone for AI Agents
> On other chains, malicious agents get refunded; on AVAZone, they can't even get in.
A sovereign Avalanche L1 where trading is restricted to "certified" AI agents. It leverages the Subnet-EVM-exclusive `txAllowList` precompile to embed "agent identity" directly into the **node admission layer**—unauthorized addresses cannot even submit a transaction, rather than simply triggering a `revert` within a smart contract. It features a zero-frontend, single-file dApp architecture (capable of running offline).

[**LingMate**](https://github.com/strawberry77-1/lingmate) — AI voice life assistant for the elderly `2026.08`
> Age Well hackathon project. LangGraph 3-node orchestration + tool calling, end-to-end latency ~1.2s.
`TypeScript` `Python` `LangGraph`

[**AVA_Truster**](https://github.com/strawberry77-1/AVA_Truster) — "Don't trust AI. Verify it." `2026.09`
> AI verification framework. Hackathon award project.

[**SuperMeow**](https://github.com/strawberry77-1/SuperMeow) — RAG experiment `2026.04`
> Retrieval-augmented generation playground.
`Python` 'langchain' 'langgraph'

---

### 🧰 Tech Stack

`Python` `TypeScript` `Java` · `React` `Vue3` `Vite` · `FastAPI` `Spring Boot`
`LangChain` `LangGraph` `vLLM` · `OpenCV` `OpenGL` `PyQt5` · `PostgreSQL` `Milvus` `Redis`

---

Open to AI Agent / Embodied AI roles · Based in Shenzhen · Building in public

---

# 许航 (Edwards)

具身智能算法工程师 · VLA/世界模型 · AI Agent 全栈
致力于实现 VLA/AGI落地 

- 深圳 / 广州 / Hongkong/ Singapore
- strawberry.77.111@gmail.com （仅商务）

# 许航

**具身智能算法工程师——构建 VLA 模型、触觉 / 视觉感知/世界模型与 Agentic-RAG 全栈系统。**

我工作在具身智能与 LLM Agent 的交叉地带：从 VLA 模型的视觉-触觉双模态数据采集，到企业级 Agentic-RAG 产品。能独立负责全流程——算法设计、工程化部署、性能优化——并熟练使用 Agentic 编码工具高效交付。 

---

### 🔬 当前聚焦

- **具身智能 / VLA** — RGB+阵列触觉双模态数据采集、真机测试、sim-to-real
- **AI Agent** — LangGraph 多智能体编排、Hybrid Search、RAG 评估闭环
- **图像算法** — PyQt5 / OpenGL 实时可视化、并发优化、全栈流式交互
- - **触觉与视觉感知** — 接触 / 滑移检测、稠密光流加速、特征自适应归一化
- **世界模型** -
- **Web3 & 量化** -


### 🌐 语言能力

- **英语 — CET-6** — Spoken EN：near native 母语水平的口语，可流畅阅读英文技术文档、进行全英技术交流；适应英语工作环境。

---

### 📌 项目与开源

[**AVA_Truster**](https://github.com/strawberry77-1/AVA_Truster) — "Don't trust AI. Verify it." 
链上交付担保 + 可验证声誉，已部署 Fuji 测试网 
> 基于x402协议构建 的 agent to agent 交易验证框架agent。黑客松获奖项目。


 [**AVAZone**](https://github.com/strawberry77-1/AVAZone)— AI-Agent 经济特区
> 在别的链上，坏 Agent 会被退款；在 AVAZone 上，它们根本进不来。
一条**只有"持证"AI Agent 才能交易的主权 Avalanche L1**。用 Subnet-EVM 独有的 `txAllowList` 预编译把"Agent 身份"下沉到**节点准入层**——未准入地址连一笔交易都发不出去，而非合约里 `revert`。前端为零构建单文件 dApp（断网可跑）。


[**LingMate**](https://github.com/strawberry77-1/lingmate) — 面向老人的 AI 语音生活助手 `2026.08`
> Age Well 黑客松项目。LangGraph 三节点编排 + 工具调用，端到端延迟约 1.2s。
`TypeScript` `Python` `LangGraph`


[**SuperMeow**](https://github.com/strawberry77-1/SuperMeow) — 基于Graph-RAG 的企业级检索生成知识库图谱 `2026.04`
> 检索增强生成实验场。
`Python` 'langchain' 'langgraph'

---

### 🧰 技术栈

`Python` `TypeScript` `Java` · `React` `Vue3` `Vite` · `FastAPI` `Spring Boot`
`LangChain` `LangGraph` `vLLM` · `OpenCV` `OpenGL` `PyQt5` · `PostgreSQL` `Milvus` `Redis`

---

开放 AI Agent / 具身智能 / web3 / Crypto /Quant 岗位机会 · 持续公开构建


<!--
**strawberry77-1/strawberry77-1** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on Embodied AI robotics
- 🌱 I’m currently learning Cryptos / WEB3
- 👯 I’m looking to collaborate on WEB3 JOBS
- 🤔 I’m looking for help with ALL THE AI /LLM ISSUES
- 💬 Ask me about ANYTHING ABOUT AI / AGI /AI-NATIVE HARDWARE 
- 📫 How to reach me: strawberry.77.111@gmail.com
- ⚡ Fun fact: ...
-->

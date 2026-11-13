# 中文 AI 实用工具合集（awesome-ai-tools-zh）

一份面向中文用户的开源 AI 工具清单：按使用场景分类，只收录**仍然存在、且在 2026 年仍有提交**的项目。

- 建议仓库名：`awesome-ai-tools-zh`
- 本 README 为草稿，**尚未创建 GitHub 仓库，也未推送任何内容**
- 核查时间：2026-11-13（America/Los_Angeles）
- 核查方式：使用已连接的 GitHub 账号，通过官方仓库接口读取 `full_name`、`archived`、`pushed_at`、`stargazers_count` 和简介
- 收录标准：公开仓库、未被 archive、2026 年内有过推送；优先选仍在维护的实用工具，不收录明显刷星、已停止维护或无法核实的项目
- Star 数会变，下表数字以核查当日接口为准，仅作量级参考

**每日更新：** 计划随日常资讯稿同步增补或淘汰项目（例如连续数月无实质提交、迁址或 archive 时移出）。创建仓库后，再把这条写成真实的更新日志。

**每日 AI 资讯：小方ai资讯 https://www.aizc.club/blog**

---

## 目录

- [编程助手](#编程助手)
- [Agent 框架](#agent-框架)
- [本地大模型](#本地大模型)
- [RAG / 知识库](#rag--知识库)
- [图像 / 视频 / 文档识别](#图像--视频--文档识别)
- [语音](#语音)
- [效率工具](#效率工具)

## 编程助手

- [openai/codex](https://github.com/openai/codex) — OpenAI 的终端编程助手（Codex），可在仓库里读代码、改文件并执行任务。
- [cline/cline](https://github.com/cline/cline) — 可在 IDE、CLI 或 SDK 中使用的自主编程助手。
- [continuedev/continue](https://github.com/continuedev/continue) — 开源编程助手，可接入多种模型，用在常见编辑器里。
- [OpenHands/OpenHands](https://github.com/OpenHands/OpenHands) — 开源的 AI 软件开发助手，适合较完整的改项目流程。
- [aaif-goose/goose](https://github.com/aaif-goose/goose) — 开源、可扩展的 AI 助手，除补全外也能安装、执行、修改和测试；接口查询时由旧地址 `block/goose` 转到此仓库。
- [browser-use/browser-use](https://github.com/browser-use/browser-use) — 让 AI 代理操作浏览器的开源 Python 库。

## Agent 框架

- [langchain-ai/langchain](https://github.com/langchain-ai/langchain) — 广泛使用的 LLM 应用与智能体工程框架。
- [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) — 在 LangChain 生态中编排可恢复、带状态的智能体。
- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) — 多角色、多智能体协作框架。
- [microsoft/autogen](https://github.com/microsoft/autogen) — 微软的智能体编程框架，适合多代理对话与协作。
- [openai/openai-agents-python](https://github.com/openai/openai-agents-python) — OpenAI 官方的轻量多代理工作流框架。
- [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) — 以 Pydantic 类型为基础的 Python AI 智能体框架。
- [huggingface/smolagents](https://github.com/huggingface/smolagents) — Hugging Face 的轻量智能体库，强调用代码完成推理步骤。

## 本地大模型

- [ollama/ollama](https://github.com/ollama/ollama) — 在本地一键拉取并运行开源大模型的工具。
- [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) — 用 C/C++ 在消费级设备上做 LLM 推理的经典项目。
- [vllm-project/vllm](https://github.com/vllm-project/vllm) — 高吞吐、省显存的大模型推理与服务引擎。
- [sgl-project/sglang](https://github.com/sgl-project/sglang) — 面向大语言模型和多模态模型的高性能服务框架。
- [huggingface/transformers](https://github.com/huggingface/transformers) — Hugging Face 的模型定义与调用框架，覆盖大量主流模型。
- [unslothai/unsloth](https://github.com/unslothai/unsloth) — 侧重本地运行与训练大模型、扩散模型的工具（含 GGUF 等格式支持）。

## RAG / 知识库

- [langgenius/dify](https://github.com/langgenius/dify) — 可搭建智能体工作流和 RAG 应用的开源平台，模型与工具接入较丰富。
- [infiniflow/ragflow](https://github.com/infiniflow/ragflow) — 面向文档解析与检索增强生成的引擎。
- [labring/FastGPT](https://github.com/labring/FastGPT) — 国内常用的知识库与可视化 AI 工作流平台。
- [Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm) — 一站式本地知识库与对话应用，可对接多种模型。
- [run-llama/llama_index](https://github.com/run-llama/llama_index) — 把文档接入 LLM 的数据框架，常用于 RAG 开发。
- [microsoft/graphrag](https://github.com/microsoft/graphrag) — 微软开源的图结构检索增强生成方案。
- [HKUDS/LightRAG](https://github.com/HKUDS/LightRAG) — 较轻量的检索增强生成实现（EMNLP 相关工作）。
- [milvus-io/milvus](https://github.com/milvus-io/milvus) — 面向大规模向量检索的开源数据库。
- [qdrant/qdrant](https://github.com/qdrant/qdrant) — 高性能向量数据库与检索引擎。
- [chroma-core/chroma](https://github.com/chroma-core/chroma) — 面向 AI 应用的检索与向量存储基础设施。
- [mem0ai/mem0](https://github.com/mem0ai/mem0) — 给智能体用的记忆层，用于跨会话保存上下文。

## 图像 / 视频 / 文档识别

- [Comfy-Org/ComfyUI](https://github.com/Comfy-Org/ComfyUI) — 节点式本地扩散模型工作台，图像与视频工作流都很常见；当前官方仓库在 `Comfy-Org` 下。
- [huggingface/diffusers](https://github.com/huggingface/diffusers) — Hugging Face 的扩散模型库，支持图像、视频和音频生成。
- [PaddlePaddle/PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) — 把 PDF 和图片转成结构化文字的 OCR 工具箱。最近一次推送在 2026-09（核查时仍未 archive）。

本分类目前偏图像与文档；本次未把尚未单独核验的视频生成仓库写进来，避免列入无法确认状态的项目。

## 语音

- [ggml-org/whisper.cpp](https://github.com/ggml-org/whisper.cpp) — OpenAI Whisper 的 C/C++ 移植，适合本地语音转写。
- [RVC-Boss/GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS) — 少样本语音克隆与语音合成工具，中文社区使用较多。
- [fishaudio/fish-speech](https://github.com/fishaudio/fish-speech) — 开源语音合成项目（Fish Speech）。
- [SWivid/F5-TTS](https://github.com/SWivid/F5-TTS) — 基于 Flow Matching 的开源 TTS（F5-TTS 论文官方代码）。

## 效率工具

- [n8n-io/n8n](https://github.com/n8n-io/n8n) — 可自托管的工作流自动化平台，已内置不少 AI 相关能力。
- [open-webui/open-webui](https://github.com/open-webui/open-webui) — 面向 Ollama 和 OpenAI 兼容接口的友好 Web 界面。
- [lobehub/lobehub](https://github.com/lobehub/lobehub) — LobeHub 桌面/协作向 AI 工作区。查询 `lobehub/lobe-chat` 时接口返回此仓库，说明项目已迁到新名。
- [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) — 聚合多种模型与智能体的桌面 AI 工作区（Cherry Studio）。
- [microsoft/markitdown](https://github.com/microsoft/markitdown) — 把 Office 文档、PDF 等转换成 Markdown 的 Python 工具。
- [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) — 把网页转成可供 LLM 使用的结构化数据。
- [unclecode/crawl4ai](https://github.com/unclecode/crawl4ai) — 面向 AI 的网页抓取与内容提取工具。

---

## 核查摘记

| 仓库 | 核查当日约略 Star | 最近推送（GitHub UTC） | 未归档 |
| --- | ---: | --- | --- |
| openai/codex | 135123 | 2026-11-13 | 是 |
| cline/cline | 71576 | 2026-11-13 | 是 |
| continuedev/continue | 36466 | 2026-11-05 | 是 |
| OpenHands/OpenHands | 93376 | 2026-11-13 | 是 |
| aaif-goose/goose | 56517 | 2026-11-13 | 是 |
| browser-use/browser-use | 120878 | 2026-11-13 | 是 |
| langchain-ai/langchain | 149436 | 2026-11-13 | 是 |
| langchain-ai/langgraph | 44887 | 2026-11-13 | 是 |
| crewAIInc/crewAI | 60835 | 2026-11-13 | 是 |
| microsoft/autogen | 61800 | 2026-11-12 | 是 |
| openai/openai-agents-python | 30648 | 2026-11-13 | 是 |
| pydantic/pydantic-ai | 21183 | 2026-11-13 | 是 |
| huggingface/smolagents | 30349 | 2026-11-10 | 是 |
| ollama/ollama | 186844 | 2026-11-13 | 是 |
| ggml-org/llama.cpp | 134752 | 2026-11-13 | 是 |
| vllm-project/vllm | 96859 | 2026-11-13 | 是 |
| sgl-project/sglang | 38809 | 2026-11-13 | 是 |
| huggingface/transformers | 168937 | 2026-11-13 | 是 |
| unslothai/unsloth | 79414 | 2026-11-13 | 是 |
| langgenius/dify | 161075 | 2026-11-13 | 是 |
| infiniflow/ragflow | 94106 | 2026-11-13 | 是 |
| labring/FastGPT | 30037 | 2026-11-13 | 是 |
| Mintplex-Labs/anything-llm | 68239 | 2026-11-13 | 是 |
| run-llama/llama_index | 52885 | 2026-11-11 | 是 |
| microsoft/graphrag | 36640 | 2026-11-09 | 是 |
| HKUDS/LightRAG | 40683 | 2026-11-13 | 是 |
| milvus-io/milvus | 46654 | 2026-11-13 | 是 |
| qdrant/qdrant | 35531 | 2026-11-13 | 是 |
| chroma-core/chroma | 29679 | 2026-11-07 | 是 |
| mem0ai/mem0 | 68901 | 2026-11-06 | 是 |
| Comfy-Org/ComfyUI | 146577 | 2026-11-13 | 是 |
| huggingface/diffusers | 34916 | 2026-11-13 | 是 |
| PaddlePaddle/PaddleOCR | 92650 | 2026-09-16 | 是 |
| ggml-org/whisper.cpp | 55149 | 2026-11-13 | 是 |
| RVC-Boss/GPT-SoVITS | 64922 | 2026-11-11 | 是 |
| fishaudio/fish-speech | 33705 | 2026-11-13 | 是 |
| SWivid/F5-TTS | 15575 | 2026-11-03 | 是 |
| n8n-io/n8n | 210354 | 2026-11-13 | 是 |
| open-webui/open-webui | 158532 | 2026-11-12 | 是 |
| lobehub/lobehub | 85231 | 2026-11-13 | 是 |
| CherryHQ/cherry-studio | 53477 | 2026-11-13 | 是 |
| microsoft/markitdown | 195158 | 2026-11-07 | 是 |
| firecrawl/firecrawl | 201370 | 2026-11-13 | 是 |
| unclecode/crawl4ai | 87299 | 2026-11-12 | 是 |

共 44 个仓库。

未列入的例子（避免把不活跃或未核实项目写进清单）：

- `Aider-AI/aider` 存在且未归档，但最近推送为 2026-05-22，偏旧，本次暂不放入「活跃维护」主清单。
- `FlowiseAI/Flowise` 在检索结果中显示 **archived**，不收录。
- 部分 2026 年新出现的超高 Star「agent harness」仓库存在刷星风险，即使数字很高也未收入。

创建仓库前请再跑一遍接口核对迁址和归档状态。README 底部的站点链接保持为 https://www.aizc.club/blog 即可，不要加价格或推广话术。

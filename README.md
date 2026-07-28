Sure — here is the copyable Markdown exactly as a code block .

```md
# 🧠 Open-Weight AI Model Guide

A practical reference for choosing the best **free, open-weight AI model** for each task, including where to access it, how it compares to paid frontier models, and when context window size matters more than token efficiency.

## Model selection by category

| 🔎 | Category | What it means | Example prompt / usage | 🏆 Best free-chatbot pick | Closest paid model(s) | 🌐 How to access |
|---|---|---|---|---|---|---|
| 🔬 | Deep research | Multi-step reasoning that gathers, synthesizes, and cross-checks information across sources. | "Summarize the scientific consensus on X, citing 3 studies and noting disagreements." | DeepSeek-V4-Pro | Closest to Claude/Gemini-style research workflows; best treated as a lower-cost frontier-style generalist rather than a clear winner over either [cite:118]. | `chat.deepseek.com` → **Expert** mode + **Deep Thinking** + **Smart Search** [cite:67][cite:72] |
| 💻 | Coding | Writing, debugging, refactoring software, and understanding codebases or APIs. | "Refactor this script to use async/await and add unit tests." | GLM-5.2 | Beats GPT-5.5 on several coding benchmarks such as SWE-bench Pro and FrontierSWE, and comes close to Claude Opus 4.8 on long-horizon coding [cite:44][cite:115]. | `chat.z.ai` → select the model from the dropdown [cite:36][cite:40] |
| 📄 | Text analysis | Extracting themes, tone, structure, or meaning from dense documents. | "Analyze the narrative arc and recurring motifs across these chapters." | Qwen3.5-397B-A17B | Best seen as approaching Gemini-class long-document analysis because of its large context and strong multimodal comprehension, though no solid evidence here shows it surpassing top paid models [cite:26]. | `chat.qwen.ai` → choose the Qwen 3.5 model from the picker [cite:59][cite:54] |
| 📚 | Long-context work | Processing very large inputs such as long transcripts, books, or codebases. | "Here is a 300-page transcript; find every budget mention by speaker." | Kimi K2.6 | Often positioned as competitive with GPT-5.5-class and Claude-class long-horizon work, especially for multimodal and agentic tasks, but strongest evidence centers on coding rather than pure curation or analysis [cite:92][cite:102]. | `kimi.com` → select **K2.6** from the model selector, then enable long-context or thinking mode if available [cite:98][cite:102] |
| ⚡ | Speed / light tasks | Quick, low-latency responses for simple questions where speed matters more than depth. | "Give me a one-line summary of this paragraph." | Gemma 4 (12B) | Not a true peer to top paid frontier models; better viewed as a lightweight alternative for fast everyday tasks rather than a Claude/GPT/Gemini competitor [cite:26]. | Google AI Studio → select **Gemma 4** from the model dropdown [cite:26] |
| 🤖 | Agentic / autonomous tasks | Multi-step, tool-using workflows where the model plans and executes actions with minimal supervision. | "Plan the steps, use tools, and draft a final status report." | MiniMax-M3 | Positioned as a long-horizon agentic model with 1M context, closer in intent to Claude-style agent workflows than to lightweight chat models, though benchmark proof versus top paid models is thinner here [cite:26]. | MiniMax Chat → pick **M3** from the model list and enable agent or tool-use mode if offered [cite:63] |
| 💰 | Token / cost efficiency | Getting solid output while minimizing token use, which matters on free tiers because of quotas, speed, and rate limits rather than price. | "Summarize this in as few tokens as possible while preserving key facts." | DeepSeek-V4-Flash | Closer to a budget GPT/Claude/Gemini tier than a flagship tier; the goal is not to beat paid models outright but to deliver acceptable quality with lower latency and less quota burn [cite:69][cite:103]. | `chat.deepseek.com` → use **Instant** mode, which maps to V4-Flash [cite:67][cite:72] |
| 💬 | General chat / all-rounder | Everyday conversational use across brainstorming, writing, advice, and mixed tasks. | "Help me brainstorm names for a coffee shop." | DeepSeek-V4-Pro | Closest to paid all-rounders like Claude Sonnet and Gemini Pro in overall shape, but current evidence supports calling it competitive rather than clearly superior [cite:118]. | `chat.deepseek.com` → **Expert** mode, with **Deep Thinking** off for faster replies [cite:67][cite:72] |

## Context window vs. token efficiency

Because the models above are free to use in their web chats, choosing for **token or cost efficiency** is not mainly about money. It is about quotas, response speed, and how much useful context the model can handle before quality starts to drop [cite:103][cite:107].

| Goal | What matters most | Why |
|---|---|---|
| Fit a huge document or codebase in one pass | Context window size | Models like Kimi K2.6 are designed for very large inputs and long-horizon tasks [cite:102]. |
| Get fast, low-friction replies on a free tier | Token efficiency | Fewer processed or generated tokens usually means faster responses and a lower chance of hitting limits [cite:103]. |
| Avoid degraded quality on long inputs | Effective context retention | Advertised context and usable context are different; quality can fall well before the maximum, including lost-in-the-middle problems [cite:109][cite:106]. |

## How to think about efficiency

- Bigger context is not automatically better; a huge window can still perform worse if the model does not retain details reliably across that span [cite:109][cite:112].
- On free chat tiers, efficiency helps preserve message budgets and keeps iteration fast, especially for repeated back-and-forth work [cite:103][cite:107].
- Large-context models are best when the full input truly needs to stay in one pass; otherwise, an efficient model can be the more practical choice [cite:110][cite:103].

## Practical shortcut

- Pick **GLM-5.2** for coding-heavy work where you want something that can genuinely challenge paid GPT-class models [cite:44].
- Pick **Kimi K2.6** when the job is dominated by very large inputs and long-context handling [cite:102].
- Pick **DeepSeek-V4-Pro** when you want a strong free generalist in a polished web app [cite:67][cite:72].
- Pick **DeepSeek-V4-Flash** when you want quicker, cheaper-feeling interactions on free-tier limits [cite:69][cite:103].

_Last updated: July 2026._
```

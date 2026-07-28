content = '''# 🧠 Open-Weight AI Model Guide

> A practical reference for choosing the best **free, open-weight AI model** for each task — including where to access it and how token efficiency differs from context window size.

---

## 📋 Model Selection by Category

| 🔎 | Category | What it means | Example prompt/usage | 🏆 Best free-chatbot pick | 🌐 How to access |
|---|---|---|---|---|---|
| 🔬 | **Deep research** | Multi-step reasoning that gathers, synthesizes, and cross-checks information across sources | *"Summarize the scientific consensus on X, citing 3+ studies and noting disagreements"* | **DeepSeek-V4-Pro** | `chat.deepseek.com` → **Expert** mode + **Deep Thinking** + **Smart Search** |
| 💻 | **Coding** | Writing, debugging, refactoring software; understanding codebases and APIs | *"Refactor this script to use async/await and add unit tests"* | **GLM-5.2** | `chat.z.ai` → select model from dropdown |
| 📄 | **Text analysis** | Extracting themes, tone, structure, or meaning from dense documents | *"Analyze the narrative arc and recurring motifs across these 5 chapters"* | **Qwen3.5-397B-A17B** | `chat.qwen.ai` → select **Qwen3.5** from model picker |
| 📚 | **Long-context work** | Processing very large inputs (documents, transcripts, codebases) | *"Here's a 300-page transcript; find every budget mention by speaker"* | **Kimi K2.6** | `kimi.com` → select **K2.6**, enable long-context toggle |
| ⚡ | **Speed / light tasks** | Quick, low-latency responses for simple queries | *"Give me a one-line summary of this paragraph"* | **Gemma 4 (12B)** | Google AI Studio → select **Gemma 4** |
| 🤖 | **Agentic / autonomous tasks** | Multi-step, tool-using workflows with minimal supervision | *"Book a flight, then draft a follow-up confirmation email"* | **MiniMax-M3** | MiniMax Chat → select **M3**, enable agent/tool-use mode |
| 💰 | **Token/cost efficiency** | Solid output while minimizing tokens — matters for rate limits, not price, on free tiers | *"Summarize this in as few tokens as possible"* | **DeepSeek-V4-Flash** | `chat.deepseek.com` → **Instant** mode (default) |
| 💬 | **General chat / all-rounder** | Everyday conversational use across writing, advice, brainstorming | *"Help me brainstorm names for a coffee shop"* | **DeepSeek-V4-Pro** | `chat.deepseek.com` → **Expert** mode, Deep Thinking off |

---

## ⚖️ Context Window vs. Token Efficiency

Since all models above are **free to use**, picking one for "efficiency" isn't about cost — it's about **quota limits, response speed, and accuracy retention**.

| Goal | What actually matters | Why |
|---|---|---|
| 📂 Fit a huge document/codebase in one pass | **Context window size** | Models like Kimi K2.6 or Qwen3.5 support very large inputs natively |
| ⚡ Fast, low-friction replies on a free tier | **Token efficiency** | Fewer generated tokens = faster replies, less chance of hitting rate/quota limits (e.g., DeepSeek's peak-hour throttling) |
| 🎯 Avoiding degraded accuracy on long inputs | **Effective context retention**, not just advertised size | Advertised windows often lose 30–40% effective accuracy well before the max; "lost in the middle" effects are common |

### Key takeaways

- 📏 **Bigger context ≠ better accuracy.** Effective usable context is often far below the advertised maximum.
- 🚦 **Free tiers have quotas.** Token-efficient models (like DeepSeek-V4-Flash) preserve your usage allowance longer.
- 🧩 **Match the tool to the job.** Use large-context models for big single-pass inputs; use efficient models for quick, iterative back-and-forth.

---

*Last updated: July 2026*
'''

with open('output/model_guide_README.md', 'w') as f:
    f.write(content)
print(len(content))

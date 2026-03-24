# 🚀 Awesome AI Side Projects

![Awesome](https://cdn.jsdelivr.net/gh/awesome-lint/awesome-lint@master/media/badge.svg)
[![License: CC0](https://img.shields.io/badge/License-CC0-000000?style=for-the-badge)](https://creativecommons.org/publicdomain/zero/1.0/)
[![GitHub stars](https://img.shields.io/github/stars/12britz/awesome-ai-sideprojects?style=for-the-badge)](https://github.com/12britz/awesome-ai-sideprojects/stargazers)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)](CONTRIBUTING.md)

> ### TL;DR: The curated list of AI side projects that'll make you actually build something.

You've seen the demos. You've bookmarked 47 tabs. Now it's time to ship something. This list is your catalyst.

---

## 💡 Ideas That Don't Suck

### 🎯 Developer Tools

| What It Does | Stack | Why It's Cool |
|:--|:--|:--|
| [AI Code Reviewer](https://github.com/Codium-ai/pr-agent) | GitHub Actions + LLM | Catches bugs before users do |
| [Commit Message Gen](https://github.com/Codium-ai/pr-agent) | Conventional Commits + LLM | "fix stuff" → actual sentences |
| [README Writer](https://github.com/run-llama/llama_index) | LlamaIndex + GPT | Your code deserves better docs |
| [SQL Builder](https://github.com/langchain-ai/langchain) | LangChain + SQL | Natural language → actual queries |
| [Test Generator](https://github.com/Codium-ai/pr-agent) | LLM + Pytest | 80% → 95% coverage while you sleep |

### 📝 Content & Media

| What It Does | Stack | Why It's Cool |
|:--|:--|:--|
| [Meeting Summarizer](https://github.com/Zackriya-Solutions/meetily) | Rust + Whisper + Ollama | 100% local. Boss's hot takes stay private |
| [Newsletter Generator](https://github.com/Aparnap2/newsletter-agent) | LangGraph + Crawl4AI + Gmail | For "I'll write it someday" people |
| [Tweet → Newsletter](https://github.com/Arize-ai/twitter-to-newsletter) | Twitter API + Claude | Turn engagement into subscribers |
| [Podcast Clipper](https://github.com/codeperfectplus/transmeet) | Whisper + Groq | "That smart part" → ready to post |
| [Document Q&A](https://github.com/run-llama/llama_index) | LlamaIndex + RAG | Stop CMD+F'ing PDFs |

### ⚡ Productivity

| What It Does | Stack | Why It's Cool |
|:--|:--|:--|
| [Email Assistant](https://github.com/nicknochnack/EmailAssistantLangchain) | Gmail API + LangChain | "Reply all" without the regret |
| [Calendar Scheduler](https://github.com/nicknochnack/CalendarAgent) | Google Calendar + LLM | "Find a time" → magic happens |
| [Meeting Intelligence](https://github.com/FutureSpeakAI/meeting-intelligence) | State machine + LLM | Meeting → structured notes. Zero effort |
| [Task Organizer](https://github.com/langchain-ai/langgraph) | LangGraph + Tasks | Brain dump → organized todos |
| [Travel Planner](https://github.com/langchain-ai/langgraph) | LangChain + Search | "Portugal but I don't plan" → full itinerary |

### 💰 Business & Marketing

| What It Does | Stack | Why It's Cool |
|:--|:--|:--|
| [Lead Qualifier](https://github.com/langchain-ai/langchain) | Form API + Scoring LLM | Tire-kickers → actual buyers |
| [Competitor Monitor](https://github.com/n8n-io/n8n) | n8n + Webhooks | Price drop → Slack ping |
| [Ad Copy Generator](https://github.com/langchain-ai/langchain) | LLM + A/B Framework | 50 variations in 5 minutes |
| [Social Scheduler](https://github.com/n8n-io/n8n) | n8n + Prediction | Post when engagement peaks |
| [Contract Analyzer](https://github.com/PhilipsHinrichs/legal-ai-analyzer) | Doc parsing + Legal LLM | "They own my firstborn?" → caught |

### 🎮 Fun & Weird

| What It Does | Stack | Why It's Cool |
|:--|:--|:--|
| [AI Dungeon Master](https://github.com/langchain-ai/langgraph) | LangGraph + TTRPG | D&D that never ends |
| [Personal Chef](https://github.com/langchain-ai/langchain) | Recipe LLM + Images | Random fridge → actual food |
| [Pet Name Gen](https://github.com/openai/openai-python) | Vision API + Naming LLM | Doggo + confused face → perfect name |
| [Dream Interpreter](https://github.com/anthropics/anthropic-sdk-python) | Claude + Psychology | Freud was on something. Now AI too |
| [Tattoo Designer](https://github.com/Stability-AI/StableDiffusion) | Stable Diffusion | See it before you ink it |

---

## 🛠️ Ship Fast Templates

### Python
```bash
# Chat in minutes
pip install streamlit openai
streamlit run app.py

# Production-ready API
pip install fastapi langchain
uvicorn app:app --reload

# Quick demos
pip install gradio
python app.py
```

| Template | Use When |
|:--|:--|
| [Streamlit + OpenAI](https://github.com/streamlit) | Need to show something tomorrow |
| [FastAPI + LangChain](https://github.com/langchain-ai/langchain) | Actually production-ready |
| [Gradio](https://github.com/gradio-app/gradio) | Pretty without frontend PhD |
| [Chainlit](https://github.com/Chainlit/chainlit) | Python-native chat interfaces |

### JavaScript/TypeScript
| Template | Use When |
|:--|:--|
| [Next.js + Vercel AI](https://github.com/vercel/ai) | Streaming + SSR + "it just works" |
| [LangChain.js](https://github.com/langchain-ai/langchainjs) | Same power, different language |
| [React + Hugging Face](https://github.com/huggingface/huggingface.js) | When frontend devs judge you |

### No-Code
| Tool | Vibe |
|:--|:--|
| [Bubble](https://bubble.io) + OpenAI | "I'm not technical but I have ideas" |
| [n8n](https://github.com/n8n-io/n8n) | Zapier on steroids. Open source |
| [Make](https://make.com) | Automation without code |

---

## 🔌 Tools & APIs

### 🤖 LLM APIs

| Provider | Vibe | Free Tier |
|:--|:--|:--|
| [OpenAI](https://platform.openai.com) | GPT-4o. Can't escape it | $5 |
| [Anthropic](https://docs.anthropic.com) | Claude 3.5. Less hallucinating | $5 |
| [Google Gemini](https://ai.google.dev) | Google's scale | Yes |
| [Groq](https://console.groq.com) | Embarrassingly fast | Yes |
| [Ollama](https://github.com/ollama/ollama) | Local. Your GPU has feelings too | Free |
| [LM Studio](https://lmstudio.ai) | Ollama with a GUI | Free |

### 🎨 Image Gen

| Tool | Vibe |
|:--|:--|
| [Midjourney](https://www.midjourney.com) | Beautiful. Slightly creepy |
| [Stable Diffusion](https://github.com/Stability-AI/StableDiffusion) | You control everything |
| [FLUX](https://github.com/black-forest-labs/flux) | The new kid. Good at hands |
| [Replicate](https://replicate.com) | Any model, any API |

### 🎙️ Audio

| Tool | Vibe |
|:--|:--|
| [Eleven Labs](https://elevenlabs.io) | Voice cloning. Spooky useful |
| [Whisper](https://platform.openai.com/docs/guides/speech-to-text) | Transcription that doesn't suck |
| [Cartesia](https://cartesia.ai) | Talk to your code |
| [Parakeet](https://github.com/rickyr123/nemo_parakeet) | Fast ASR. Underrated |

### 🎬 Video

| Tool | Vibe |
|:--|:--|
| [Runway](https://runwayml.com) | "Quick video" → 2 hours later |
| [Pika](https://pika.art) | Text-to-video. Getting real |
| [Hailuo](https://hailuoai.video) | Free tier available |
| [KLING](https://klingai.com) | The space moves fast |

### 🔍 Search & Data

| Tool | Vibe |
|:--|:--|
| [SerpAPI](https://serpapi.com) | Google without Selenium hell |
| [Exa](https://exa.ai) | Actually understands context |
| [Tavily](https://tavily.com) | RAG-optimized |
| [Crawl4AI](https://github.com/imartinez/crawl4ai) | AI-friendly crawler |

### 📊 Embeddings & Vector

| Tool | Vibe |
|:--|:--|
| [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings) | The original. Still good |
| [Cohere](https://cohere.com) | Embeddings + reranking |
| [Qdrant](https://github.com/qdrant/qdrant) | Rust. Fast and pretty |
| [Pinecone](https://www.pinecone.io) | Managed. No infra headaches |
| [Chroma](https://github.com/chroma-core/chroma) | Quick prototypes |

---

## 💻 UI Components

| Component | Vibe |
|:--|:--|
| [Vercel AI UI](https://github.com/vercel/ai) | Streaming + chat + the works |
| [Chainlit](https://github.com/Chainlit/chainlit) | Python-native. Minimal code |
| [Open UI](https://github.com/wandelbotsai/openui) | Describe → get code. Magic? |
| [LibreChat](https://github.com/danny-avila/LibreChat) | Self-hosted. No ads. |
| [Textual](https://github.com/Textualize/textual) | Beautiful terminals |

---

## 🚀 Deployment

### Serverless
| Platform | Vibe |
|:--|:--|
| [Vercel](https://vercel.com) | Push → live. Pure magic |
| [Cloudflare Workers](https://developers.cloudflare.com/workers-ai) | Edge AI. Distributed vibes |
| [AWS Lambda + Bedrock](https://aws.amazon.com/bedrock) | Enterprise. Ready to commit |

### Containers
| Platform | Vibe |
|:--|:--|
| [Railway](https://railway.app) | "I just want it to run" → ✓ |
| [Fly.io](https://fly.io) | Close to users everywhere |
| [Render](https://render.com) | One dashboard to rule |

### ML Infrastructure
| Platform | Vibe |
|:--|:--|
| [Modal](https://modal.com) | Python-first. Data scientist approved |
| [Beam](https://beam.cloud) | Serverless GPUs. Pay per second |
| [Baseten](https://baseten.com) | Model serving without DevOps nightmares |

### Data
| Platform | Vibe |
|:--|:--|
| [Supabase](https://supabase.com) | Postgres + auth + realtime |
| [PlanetScale](https://planetscale.com) | MySQL with branching |
| [Neon](https://neon.tech) | Serverless Postgres |
| [Upstash](https://upstash.com) | Redis + Kafka. Pay as you go |

---

## 💵 Monetization

### Pricing Models
> 💡 **Tip:** Freemium + usage-based = sustainable for AI apps

- **Freemium** → Free tier gets users, paid gets features
- **Usage-based** → Pay per token/call. Fair.
- **Subscription** → Monthly recurring. The dream.
- **Marketplace** → Gumroad, App Store, your own
- **Affiliate** → "I use this tool" → money

### Payment Stack
| Provider | Vibe |
|:--|:--|
| [Stripe](https://stripe.com) | The default. Reliable. |
| [Lemon Squeezy](https://www.lemonsqueezy.com) | Digital products. Less paperwork |
| [Paddle](https://paddle.com) | They handle tax. You handle shipping |
| [Gumroad](https://gumroad.com) | Creator economy's favorite |

### Launch Platforms
| Platform | Vibe |
|:--|:--|
| [Product Hunt](https://producthunt.com) | The OG launch platform |
| [Indie Hackers](https://www.indiehackers.com) | Revenue shares. Transparency vibes |
| [Showwcase](https://showwcase.com) | Build in public |
| [Hacker News](https://news.ycombinator.com) | Show HN. High risk. High reward. |

---

## 📚 Learn

### Courses
| Course | Vibe |
|:--|:--|
| [DeepLearning.AI](https://www.deeplearning.ai) | Stanford professor energy |
| [Fast.ai](https://fast.ai) | "You'll revolutionize the field" |
| [LangChain Academy](https://academy.langchain.com) | Build LLM apps. Practical path |

### Books
| Book | Vibe |
|:--|:--|
| [Build an LLM](https://www.manning.com/books/build-a-large-language-model-from-scratch) | Zero → working LLM. Respect. |
| [Practical AI](https://www.manning.com/books/practical-ai-with-swift) | Apple ecosystem people |

### Newsletters
| Newsletter | Vibe |
|:--|:--|
| [The Batch](https://www.deeplearning.ai/the-batch) | Weekly. Curated. Not overwhelming |
| [Last Week in AI](https://lastweekin.ai) | Digestible. "What did I miss?" |
| [TLDR AI](https://tldr.tech/ai) | Daily. Short. Works. |

---

## 🌟 Inspiration

### Bootstrapped → Unicorn
| Project | Vibe |
|:--|:--|
| [Notion AI](https://notion.so/ai) | Built-in. Genius. |
| [Perplexity](https://perplexity.ai) | AI search. $1B+ valuation |
| [Cursor](https://cursor.sh) | AI-first IDE. Game changer |
| [Lovable](https://lovable.dev) | Describe → app. The future. |

### Open Source Legends
| Project | Stars | Vibe |
|:--|:--|:--|
| [Open Interpreter](https://github.com/KillianLucas/open-interpreter) | 15K+ | Terminal agent. Wild. |
| [Jan](https://github.com/janhq/jan) | 20K+ | Local ChatGPT. Privacy |
| [Open WebUI](https://github.com/open-webui/open-webui) | 35K+ | Self-hosted. Forever. |
| [Meetily](https://github.com/Zackriya-Solutions/meetily) | 10K+ | Privacy-first. 100% local. |

### Boilerplates
| Template | Vibe |
|:--|:--|
| [Ship Fast](https://shipfa.st) | Next.js + AI SaaS. Ship faster. |
| [NextAI](https://github.com/ixahmedxi/nextai) | "I have an idea on Monday" |
| [Vercel Templates](https://vercel.com/templates) | Official. Curated. Works. |

---

## 🤝 Contribute

Found something cool? PRs welcome. Found something broken? Issues welcome.

---

## 📄 License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the author has waived all copyright. Do whatever.

---

<p align="center">
  <strong>⭐ Star this repo if it was useful!</strong>
  <br>
  <a href="https://github.com/12britz/awesome-ai-sideprojects">View on GitHub</a>
</p>

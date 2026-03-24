# Awesome AI Side Projects [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of AI-powered side project ideas, starter templates, tools, and resources to build your next project.

Everyone wants to ship an AI side project but gets stuck on "what should I build?" This list is your inspiration + execution guide.

## Contents

- [Side Project Ideas](#side-project-ideas)
- [Starter Templates](#starter-templates)
- [Tools and APIs](#tools-and-apis)
- [UI Components](#ui-components)
- [Deployment](#deployment)
- [Monetization](#monetization)
- [Learning Resources](#learning-resources)
- [Inspiration](#inspiration)

---

## Side Project Ideas

### Content & Media

- [AI Code Reviewer](https://github.com/Codium-ai/pr-agent) - Auto-review PRs for bugs, security, style. Stack: GitHub Actions + LLM.
- [Meeting Summarizer](https://github.com/Zackriya-Solutions/meetily) - Privacy-first meeting assistant with Whisper transcription. Stack: Rust + Whisper + Ollama.
- [AI Newsletter Generator](https://github.com/Aparnap2/newsletter-agent) - Crawl web, generate newsletters via email. Stack: LangGraph + Crawl4AI + Gmail API.
- [Tweet Thread Generator](https://github.com/Arize-ai/twitter-to-newsletter) - Twitter → newsletter with Claude. Stack: Twitter API + Claude.
- [AI Podcast Clipper](https://github.com/codeperfectplus/transmeet) - Audio → clips with topic detection. Stack: Whisper + Groq + summarization.
- [Document Q&A](https://github.com/run-llama/llama_index) - Upload PDF → ask questions. Stack: LlamaIndex + RAG.

### Developer Tools

- [AI Commit Message Generator](https://github.com/Codium-ai/pr-agent) - Git diff → descriptive commits. Stack: Conventional commits + LLM.
- [AI README Writer](https://github.com/run-llama/llama_index) - Code → documentation. Stack: LlamaIndex + GPT.
- [SQL Query Builder](https://github.com/langchain-ai/langchain) - Natural language → SQL. Stack: LangChain + SQL DB.
- [Test Generator](https://github.com/Codium-ai/pr-agent) - Function → unit tests. Stack: LLM + pytest framework.
- [Changelog Generator](https://github.com/Codium-ai/pr-agent) - Commits → changelog. Stack: Conventional commits + LLM.

### Productivity

- [AI Email Assistant](https://github.com/nicknochnack/EmailAssistantLangchain) - Inbox → smart replies. Stack: Gmail API + LangChain.
- [AI Calendar Scheduler](https://github.com/nicknochnack/CalendarAgent) - Natural language → calendar events. Stack: Google Calendar API + LLM.
- [AI Note Taker](https://github.com/FutureSpeakAI/meeting-intelligence) - Meeting lifecycle management. Stack: State machine + LLM summarization.
- [AI Task Manager](https://github.com/langchain-ai/langgraph) - Brain dump → organized todos. Stack: LangGraph + task management.
- [AI Travel Planner](https://github.com/langchain-ai/langgraph) - Destination + dates → itinerary. Stack: LangChain + search APIs.

### Business & Marketing

- [AI Lead Qualifier](https://github.com/langchain-ai/langchain) - Form → qualified leads. Stack: Form API + scoring LLM.
- [Competitor Monitor](https://github.com/n8n-io/n8n) - Track competitor pricing. Stack: Web scraping + alerts.
- [AI Ad Copy Generator](https://github.com/langchain-ai/langchain) - Product → ad variations. Stack: LLM + A/B testing.
- [Social Media Scheduler](https://github.com/n8n-io/n8n) - Content → optimal posting times. Stack: n8n + engagement prediction.
- [AI Contract Analyzer](https://github.com/PhilipsHinrichs/legal-ai-analyzer) - Upload PDF → key clauses + risks. Stack: Document parsing + legal LLM.

### Fun & Experimental

- [AI Dungeon Master](https://github.com/langchain-ai/langgraph) - D&D assistant. Stack: LangGraph + character sheets.
- [Personal Chef](https://github.com/langchain-ai/langchain) - Ingredients → recipes. Stack: Recipe LLM + image generation.
- [AI Pet Name Generator](https://github.com/openai/openai-python) - Photo → name + personality. Stack: Vision API + naming LLM.
- [Dream Interpreter](https://github.com/anthropics/anthropic-sdk-python) - Describe dream → interpretation. Stack: Claude + psychology prompts.
- [AI Tattoo Designer](https://github.com/Stability-AI/StableDiffusion) - Idea → tattoo designs. Stack: Stable Diffusion + style transfer.

---

## Starter Templates

Get from zero to MVP fast.

### Python

- [Streamlit + OpenAI Template](https://github.com/streamlit) - Minimal Streamlit app with OpenAI.
- [FastAPI + LangChain Template](https://github.com/langchain-ai/langchain) - Production-ready FastAPI with LangChain.
- [Gradio + Hugging Face](https://github.com/gradio-app/gradio) - Quick AI demo interface.
- [Chainlit Template](https://github.com/Chainlit/chainlit) - Python chat interface.

### JavaScript/TypeScript

- [Next.js + Vercel AI SDK](https://github.com/vercel/ai) - Full-stack AI app with streaming.
- [LangChain.js Templates](https://github.com/langchain-ai/langchainjs) - JavaScript port of LangChain.
- [React + Hugging Face](https://github.com/huggingface/huggingface.js) - React components for AI.

### No-Code / Low-Code

- [Bubble + OpenAI Plugin](https://bubble.io) - Build AI apps without code.
- [n8n](https://github.com/n8n-io/n8n) - Workflow automation with AI nodes.
- [Make + OpenAI](https://make.com) - Visual automation with AI integration.

---

## Tools and APIs

### LLM APIs

- [OpenAI API](https://platform.openai.com) - GPT-4o, GPT-4, GPT-3.5.
- [Anthropic API](https://docs.anthropic.com) - Claude 3.5 Sonnet, Claude 3.
- [Google Gemini API](https://ai.google.dev) - Gemini Pro, Flash.
- [Groq API](https://console.groq.com) - Fast inference, free tier.
- [Ollama](https://github.com/ollama/ollama) - Run models locally.
- [LM Studio](https://lmstudio.ai) - Desktop app for local LLMs.

### Image Generation

- [Midjourney](https://www.midjourney.com) - Image generation.
- [Stable Diffusion](https://github.com/Stability-AI/StableDiffusion) - Open source image gen.
- [DALL-E API](https://platform.openai.com/docs/guides/images) - OpenAI image gen.
- [Replicate](https://replicate.com) - Run open models via API.
- [FLUX](https://github.com/black-forest-labs/flux) - Text-to-image from Black Forest Labs.

### Audio

- [Eleven Labs](https://elevenlabs.io) - Text-to-speech.
- [Whisper API](https://platform.openai.com/docs/guides/speech-to-text) - Speech recognition.
- [Cartesia](https://cartesia.ai) - Real-time voice AI.
- [Parakeet](https://github.com/rickyr123/nemo_parakeet) - Fast ASR model.

### Video

- [Runway](https://runwayml.com) - Video generation and editing.
- [Pika](https://pika.art) - Text-to-video.
- [Hailuo AI](https://hailuoai.video) - AI video generator.
- [KLING](https://klingai.com) - Video creation.

### Search & Data

- [SerpAPI](https://serpapi.com) - Google search API.
- [Exa](https://exa.ai) - Neural search API.
- [Tavily](https://tavily.com) - AI search for RAG.
- [Crawl4AI](https://github.com/imartinez/crawl4ai) - AI-friendly web crawler.

### Embeddings & Vector

- [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings) - Text embeddings.
- [Cohere](https://cohere.com) - Embeddings + reranking.
- [Qdrant](https://github.com/qdrant/qdrant) - Vector database.
- [Pinecone](https://www.pinecone.io) - Managed vector DB.
- [Chroma](https://github.com/chroma-core/chroma) - Vector DB for AI apps.

---

## UI Components

Beautiful AI interfaces fast.

- [Vercel AI UI](https://github.com/vercel/ai) - Chatbot UI, streaming, message components.
- [Chainlit](https://github.com/Chainlit/chainlit) - Python chat interface.
- [Open UI](https://github.com/wandelbotsai/openui) - Describe UI → generate code.
- [LibreChat](https://github.com/danny-avila/LibreChat) - Open source ChatGPT UI.
- [Textual](https://github.com/Textualize/textual) - Python TUI framework for AI.
- [Charm](https://charm.sh) - Beautiful terminal UIs in Python.

---

## Deployment

Where to host your AI side project.

### Serverless

- [Vercel](https://vercel.com) - Frontend + serverless functions.
- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai) - Edge AI inference.
- [AWS Lambda + Bedrock](https://aws.amazon.com/bedrock) - Serverless LLM inference.

### Containers

- [Railway](https://railway.app) - Simple container deployment.
- [Fly.io](https://fly.io) - Distributed containers.
- [Render](https://render.com) - Managed containers + cron.

### Managed ML

- [Modal](https://modal.com) - Python-first infrastructure.
- [Beam](https://beam.cloud) - Serverless GPUs.
- [Baseten](https://baseten.com) - ML model serving.

### Database & Storage

- [Supabase](https://supabase.com) - Postgres + auth + realtime.
- [PlanetScale](https://planetscale.com) - Serverless MySQL.
- [Neon](https://neon.tech) - Serverless Postgres.
- [Upstash](https://upstash.com) - Redis + Kafka serverless.

---

## Monetization

Turn your side project into a business.

### Pricing Models

- **Freemium** - Free tier + paid pro tier
- **Usage-based** - Pay per API call or token
- **Subscription** - Monthly/annual plans
- **Marketplace** - Sell on App stores or Gumroad
- **Affiliate** - Commission on referrals

### Payment Integration

- [Stripe](https://stripe.com) - Payments + subscriptions.
- [Lemon Squeezy](https://www.lemonsqueezy.com) - Payments for digital products.
- [Paddle](https://paddle.com) - SaaS payments + tax handling.
- [Gumroad](https://gumroad.com) - Digital product sales.

### Launch Platforms

- [Product Hunt](https://producthunt.com) - Launch your product.
- [Indie Hackers](https://www.indiehackers.com) - Share your journey.
- [Showwcase](https://showwcase.com) - Developer community.
- [Hacker News](https://news.ycombinator.com) - Show HN for traction.

---

## Learning Resources

Level up your AI skills.

### Courses

- [DeepLearning.AI Courses](https://www.deeplearning.ai) - Andrew Ng's courses.
- [Fast.ai](https://fast.ai) - Practical deep learning.
- [LangChain Academy](https://academy.langchain.com) - LLM app development.

### Books

- [Build a Large Language Model](https://www.manning.com/books/build-a-large-language-model-from-scratch) - From scratch in Python.
- [Practical AI](https://www.manning.com/books/practical-ai-with-swift) - AI on Apple platforms.

### Newsletters

- [The Batch](https://www.deeplearning.ai/the-batch) - Weekly AI news.
- [Last Week in AI](https://lastweekin.ai) - Digestible AI updates.
- [TLDR AI](https://tldr.tech/ai) - Daily AI news.

---

## Inspiration

Real AI side projects that became businesses.

### Bootstrapped

- [Notion AI](https://notion.so/ai) - Writing assistant in Notion.
- [Perplexity](https://perplexity.ai) - AI search engine.
- [Cursor](https://cursor.sh) - AI-first code editor.
- [Lovable](https://lovable.dev) - AI app builder.

### Open Source

- [Open Interpreter](https://github.com/KillianLucas/open-interpreter) - Code interpreter in terminal.
- [Jan](https://github.com/janhq/jan) - Offline ChatGPT alternative.
- [Open WebUI](https://github.com/open-webui/open-webui) - Self-hosted ChatGPT.
- [Meetily](https://github.com/Zackriya-Solutions/meetily) - Privacy-first meeting assistant.

### Templates & Boilerplates

- [Ship Fast](https://shipfa.st) - Next.js + AI SaaS template.
- [SaaS AI Boilerplate](https://github.com/ixahmedxi/nextai) - Full-stack AI SaaS.
- [Vercel AI Templates](https://vercel.com/templates) - Official Vercel AI starters.

---

## Contributing

PRs welcome! Add your project ideas, templates, or resources.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

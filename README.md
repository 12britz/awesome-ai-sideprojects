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

- [AI Code Reviewer](https://github.com/12britz/awesome-ai-sideprojects) - Auto-review PRs for bugs, security, style. Stack: GitHub Actions + LLM.
- [Meeting Summarizer](https://github.com/12britz/awesome-ai-sideprojects) - Zoom/Teams → action items + decisions. Stack: Whisper + summarization.
- [AI Newsletter Writer](https://github.com/12britz/awesome-ai-sideprojects) - Scrape topics → generate newsletter. Stack: RSS + GPT + email delivery.
- [Tweet Thread Generator](https://github.com/12britz/awesome-ai-sideprojects) - Article URL → viral thread. Stack: Browserless + summarization.
- [AI Podcast Clipper](https://github.com/12britz/awesome-ai-sideprojects) - Long podcast → best clips for social. Stack: Whisper + topic detection + clip extraction.
- [AI Meme Generator](https://github.com/12britz/awesome-ai-sideprojects) - Topic → trending meme templates. Stack: Image gen + captioning.
- [Document Q&A](https://github.com/12britz/awesome-ai-sideprojects) - Upload PDF → ask questions. Stack: RAG + chat UI.

### Developer Tools

- [AI Commit Message Generator](https://github.com/12britz/awesome-ai-sideprojects) - Git diff → descriptive commits. Stack: git hooks + LLM.
- [AI README Writer](https://github.com/12britz/awesome-ai-sideprojects) - Repo → complete README. Stack: GitHub API + documentation LLM.
- [SQL Query Builder](https://github.com/12britz/awesome-ai-sideprojects) - "Show me users who..." → SQL. Stack: Natural language to SQL.
- [API Docs Generator](https://github.com/12britz/awesome-ai-sideprojects) - Code → API documentation. Stack: AST parsing + LLM.
- [Test Generator](https://github.com/12britz/awesome-ai-sideprojects) - Function → unit tests. Stack: LLM + pytest framework.
- [Changelog Generator](https://github.com/12britz/awesome-ai-sideprojects) - Commits → changelog. Stack: Conventional commits + LLM.

### Productivity

- [AI Email Assistant](https://github.com/12britz/awesome-ai-sideprojects) - Inbox → smart replies + drafts. Stack: Gmail API + LLM.
- [AI Calendar Scheduler](https://github.com/12britz/awesome-ai-sideprojects) - "Schedule a meeting with..." → find time + send invite.
- [AI Note Taker](https://github.com/12britz/awesome-ai-sideprojects) - Audio → structured notes. Stack: Whisper + organization LLM.
- [AI Task Manager](https://github.com/12britz/awesome-ai-sideprojects) - Brain dump → organized todos. Stack: LLM + task management API.
- [AI Travel Planner](https://github.com/12britz/awesome-ai-sideprojects) - Destination + dates → itinerary. Stack: Travel APIs + GPT.

### Business & Marketing

- [AI Lead Qualifier](https://github.com/12britz/awesome-ai-sideprojects) - Form submissions → qualified leads. Stack: Form API + scoring LLM.
- [Competitor Monitor](https://github.com/12britz/awesome-ai-sideprojects) - Track competitor pricing/features. Stack: Web scraping + alerts.
- [AI Ad Copy Generator](https://github.com/12britz/awesome-ai-sideprojects) - Product → ad variations. Stack: LLM + A/B testing framework.
- [Social Media Scheduler](https://github.com/12britz/awesome-ai-sideprojects) - Content → optimal posting times. Stack: Scheduler + engagement prediction.
- [AI Contract Analyzer](https://github.com/12britz/awesome-ai-sideprojects) - Upload PDF → key clauses + risks. Stack: Document parsing + legal LLM.

### Fun & Experimental

- [AI Dungeon Master](https://github.com/12britz/awesome-ai-sideprojects) - D&D assistant. Stack: TTRPG LLM + character sheets.
- [Personal Chef](https://github.com/12britz/awesome-ai-sideprojects) - Ingredients → recipes. Stack: Recipe LLM + image generation.
- [AI Pet Name Generator](https://github.com/12britz/awesome-ai-sideprojects) - Pet photo → name + personality. Stack: Vision + naming LLM.
- [Dream Interpreter](https://github.com/12britz/awesome-ai-sideprojects) - Describe dream → interpretation. Stack: Psychology-trained LLM.
- [AI Tattoo Designer](https://github.com/12britz/awesome-ai-sideprojects) - Idea → tattoo designs. Stack: Image generation + style transfer.

---

## Starter Templates

Get from zero to MVP fast.

### Python

- [Streamlit + OpenAI Template](https://github.com/openai/openai-cookbook#readme) - Minimal Streamlit app with OpenAI integration.
- [FastAPI + LangChain Template](https://github.com/langchain-ai/langchain#readme) - Production-ready FastAPI with LangChain.
- [Gradio + Hugging Face](https://github.com/gradio-app/gradio#readme) - Quick AI demo interface.

### JavaScript/TypeScript

- [Next.js + Vercel AI SDK](https://github.com/vercel/ai#readme) - Full-stack AI app with streaming.
- [LangChain.js Templates](https://github.com/langchain-ai/langchainjs#readme) - JavaScript port of LangChain.
- [React + Hugging Face](https://github.com/huggingface/huggingface.js#readme) - React components for AI.

### No-Code / Low-Code

- [Bubble + OpenAI Plugin](https://bubble.io/#readme) - Build AI apps without code.
- [n8n + AI Nodes](https://github.com/n8n-io/n8n#readme) - Workflow automation with AI.
- [Make + OpenAI](https://www.make.com/#readme) - Visual automation with AI integration.

---

## Tools and APIs

### LLM APIs

- [OpenAI API](https://platform.openai.com/#readme) - GPT-4, GPT-4o, GPT-3.5.
- [Anthropic API](https://docs.anthropic.com/#readme) - Claude 3.5, Claude 3.
- [Google Gemini API](https://ai.google.dev/#readme) - Gemini Pro, Flash.
- [Groq API](https://console.groq.com/#readme) - Fast inference, free tier.
- [Ollama](https://github.com/ollama/ollama#readme) - Run models locally.
- [LM Studio](https://lmstudio.ai/#readme) - Desktop app for local LLMs.

### Image Generation

- [Midjourney API](https://www.midjourney.com/#readme) - Image generation.
- [Stable Diffusion API](https://github.com/Stability-AI/generative-models#readme) - Open source image gen.
- [DALL-E API](https://platform.openai.com/docs/guides/images#readme) - OpenAI image gen.
- [Replicate](https://replicate.com/#readme) - Run open models via API.

### Audio

- [Eleven Labs](https://elevenlabs.io/#readme) - Text-to-speech.
- [Whisper API](https://platform.openai.com/docs/guides/speech-to-text#readme) - Speech recognition.
- [Cartesia](https://cartesia.ai/#readme) - Real-time voice AI.

### Video

- [Runway](https://runwayml.com/#readme) - Video generation and editing.
- [Pika](https://pika.art/#readme) - Text-to-video.
- [Hailuo AI](https://hailuoai.video/#readme) - AI video generator.

### Search & Data

- [SerpAPI](https://serpapi.com/#readme) - Google search API.
- [Exa](https://exa.ai/#readme) - Neural search API.
- [Tavily](https://tavily.com/#readme) - AI search for RAG.

### Embeddings & Vector

- [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings#readme) - Text embeddings.
- [Cohere](https://cohere.com/#readme) - Embeddings + reranking.
- [Qdrant](https://github.com/qdrant/qdrant#readme) - Vector database.
- [Pinecone](https://www.pinecone.io/#readme) - Managed vector DB.

---

## UI Components

Beautiful AI interfaces fast.

- [Vercel AI UI](https://github.com/vercel/ai#readme) - Chatbot UI, streaming, message components.
- [Chainlit](https://github.com/Chainlit/chainlit#readme) - Python chat interface.
- [Open UI](https://github.com/wandelbotsai/openui#readme) - Describe UI → generate code.
- [LibreChat](https://github.com/danny-avila/LibreChat#readme) - Open source ChatGPT UI.
- [Textual](https://github.com/Textualize/textual#readme) - Python TUI framework for AI.
- [Charm](https://charm.sh/#readme) - Beautiful terminal UIs in Python.

---

## Deployment

Where to host your AI side project.

### Serverless

- [Vercel](https://vercel.com/#readme) - Frontend + serverless functions.
- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai/#readme) - Edge AI inference.
- [AWS Lambda + Bedrock](https://aws.amazon.com/bedrock/#readme) - Serverless LLM inference.

### Containers

- [Railway](https://railway.app/#readme) - Simple container deployment.
- [Fly.io](https://fly.io/#readme) - Distributed containers.
- [Render](https://render.com/#readme) - Managed containers + cron.

### Managed ML

- [Modal](https://modal.com/#readme) - Python-first infrastructure.
- [Beam](https://beam.cloud/#readme) - Serverless GPUs.
- [Baseten](https://baseten.com/#readme) - ML model serving.

### Database & Storage

- [Supabase](https://supabase.com/#readme) - Postgres + auth + realtime.
- [PlanetScale](https://planetscale.com/#readme) - Serverless MySQL.
- [Neon](https://neon.tech/#readme) - Serverless Postgres.
- [Upstash](https://upstash.com/#readme) - Redis + Kafka serverless.

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

- [Stripe](https://stripe.com/#readme) - Payments + subscriptions.
- [Lemon Squeezy](https://www.lemonsqueezy.com/#readme) - Payments for digital products.
- [Paddle](https://paddle.com/#readme) - SaaS payments + tax handling.
- [Gumroad](https://gumroad.com/#readme) - Digital product sales.

### Launch Platforms

- [Product Hunt](https://producthunt.com/#readme) - Launch your product.
- [Indie Hackers](https://www.indiehackers.com/#readme) - Share your journey.
- [Showwcase](https://showwcase.com/#readme) - Developer community.
- [Hacker News](https://news.ycombinator.com/#readme) - Show HN for traction.

---

## Learning Resources

Level up your AI skills.

### Courses

- [DeepLearning.AI Courses](https://www.deeplearning.ai/#readme) - Andrew Ng's courses.
- [Fast.ai](https://fast.ai/#readme) - Practical deep learning.
- [LangChain Academy](https://academy.langchain.com/#readme) - LLM app development.

### Books

- [Build a Large Language Model](https://www.manning.com/books/build-a-large-language-model-from-scratch#readme) - From scratch in Python.
- [Practical AI](https://www.manning.com/books/practical-ai-with-swift#readme) - AI on Apple platforms.

### Newsletters

- [The Batch](https://www.deeplearning.ai/the-batch/#readme) - Weekly AI news.
- [Last Week in AI](https://lastweekin.ai/#readme) - Digestible AI updates.
- [TLDR AI](https://tldr.tech/ai/#readme) - Daily AI news.

---

## Inspiration

Real AI side projects that became businesses.

### Bootstrapped

- [Notion AI](https://notion.so/ai#readme) - Writing assistant in Notion.
- [Perplexity](https://perplexity.ai/#readme) - AI search engine.
- [Cursor](https://cursor.sh/#readme) - AI-first code editor.
- [Lovable](https://lovable.dev/#readme) - AI app builder.

### Open Source

- [Open Interpreter](https://github.com/KillianLucas/open-interpreter#readme) - Code interpreter in terminal.
- [Jan](https://github.com/janhq/jan#readme) - Offline ChatGPT alternative.
- [Open WebUI](https://github.com/open-webui/open-webui#readme) - Self-hosted ChatGPT.

### Templates & Boilerplates

- [Ship Fast](https://shipfa.st/#readme) - Next.js + AI SaaS template.
- [SaaS AI Boilerplate](https://github.com/ixahmedxi/nextai#readme) - Full-stack AI SaaS.
- [Vercel AI Templates](https://vercel.com/templates#readme) - Official Vercel AI starters.

---

## Contributing

PRs welcome! Add your project ideas, templates, or resources.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

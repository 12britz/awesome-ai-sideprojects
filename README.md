# Awesome AI Side Projects 

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
[![Genuinely Useful](https://img.shields.io/badge/genuinely-useful-yes-brightgreen)](#)

> The curated list of AI side projects that'll make you say "oh that's actually genius" and then procrastinate for 3 hours building your own version.

You've seen the demos. You've bookmarked 47 tabs. Now it's time to actually ship something. This list is part inspiration, part "wait that exists?!" and part "I need to build this right now."

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

*"I should automate that thing I do manually every Tuesday."*

- [AI Code Reviewer](https://github.com/Codium-ai/pr-agent) - Because "LGTM" is not a review. PR-Agent catches bugs before your users do.
- [Meeting Summarizer](https://github.com/Zackriya-Solutions/meetily) - Whisper-powered. 100% local. Your boss's hot takes stay on your machine.
- [AI Newsletter Generator](https://github.com/Aparnap2/newsletter-agent) - Crawls the web so you don't have to. Great for those "I'll definitely write that newsletter someday" people.
- [Tweet Thread Generator](https://github.com/Arize-ai/twitter-to-newsletter) - Your hot tweets → newsletter. Turn engagement into subscribers.
- [AI Podcast Clipper](https://github.com/codeperfectplus/transmeet) - "That one part where he said something smart" → ready to post.
- [Document Q&A](https://github.com/run-llama/llama_index) - Stop CMD+F'ing PDFs. Just ask.

### Developer Tools

*"Automating away the boring parts since 2023."*

- [AI Commit Message Generator](https://github.com/Codium-ai/pr-agent) - "fix stuff" → "refactor: extract validation logic to improve error handling for edge cases"
- [AI README Writer](https://github.com/run-llama/llama_index) - Your code deserves better docs than "works on my machine."
- [SQL Query Builder](https://github.com/langchain-ai/langchain) - "Show me all users who bought stuff but never complained" → actual SQL.
- [Test Generator](https://github.com/Codium-ai/pr-agent) - 80% coverage → 95% coverage. While you sleep.
- [Changelog Generator](https://github.com/Codium-ai/pr-agent) - Your commit history → actual readable changelog. You're welcome.

### Productivity

*"Working smarter, not harder. Mostly smarter."*

- [AI Email Assistant](https://github.com/nicknochnack/EmailAssistantLangchain) - "Reply all" without the regret.
- [AI Calendar Scheduler](https://github.com/nicknochnack/CalendarAgent) - "Schedule something with everyone" → magically happens.
- [AI Note Taker](https://github.com/FutureSpeakAI/meeting-intelligence) - Meeting → structured notes. Zero effort, full context.
- [AI Task Manager](https://github.com/langchain-ai/langgraph) - Brain dump → organized todo list. The hardest part is done.
- [AI Travel Planner](https://github.com/langchain-ai/langgraph) - "I want to see Portugal but I don't want to plan it" → full itinerary.

### Business & Marketing

*"Making money while you sleep. Or at least trying."*

- [AI Lead Qualifier](https://github.com/langchain-ai/langchain) - Sort the tire-kickers from the buyers. Automatically.
- [Competitor Monitor](https://github.com/n8n-io/n8n) - Their price drops. You get a Slack ping. Advantage: yours.
- [AI Ad Copy Generator](https://github.com/langchain-ai/langchain) - 50 variations in 5 minutes. A/B test your way to growth.
- [Social Media Scheduler](https://github.com/n8n-io/n8n) - Post when engagement peaks. Not at 3am because you remembered.
- [AI Contract Analyzer](https://github.com/PhilipsHinrichs/legal-ai-analyzer) - "Wait, they own my firstborn?" → caught before signing.

### Fun & Experimental

*"Because why not?"*

- [AI Dungeon Master](https://github.com/langchain-ai/langgraph) - Your D&D campaign never has to end. Or run out of snacks.
- [Personal Chef](https://github.com/langchain-ai/langchain) - "I have random stuff in my fridge" → actual recipes.
- [AI Pet Name Generator](https://github.com/openai/openai-python) - Doggo + confused expression = the perfect name.
- [Dream Interpreter](https://github.com/anthropics/anthropic-sdk-python) - Freud was on something. Now AI is too.
- [AI Tattoo Designer](https://github.com/Stability-AI/StableDiffusion) - "What if I got... this?" → see it first. Regret less.

---

## Starter Templates

*Zero to "holy shit it works" in under an hour.*

### Python

- [Streamlit + OpenAI](https://github.com/streamlit) - The "I need to show this to someone by tomorrow" stack.
- [FastAPI + LangChain](https://github.com/langchain-ai/langchain) - Actually production-ready. Not just vibes.
- [Gradio](https://github.com/gradio-app/gradio) - When you want something pretty without the frontend PhD.
- [Chainlit](https://github.com/Chainlit/chainlit) - Chat interfaces in Python. That's it. That's the template.

### JavaScript/TypeScript

- [Next.js + Vercel AI SDK](https://github.com/vercel/ai) - Streaming, SSR, and that satisfying "it just works" feeling.
- [LangChain.js](https://github.com/langchain-ai/langchainjs) - Same power, different language. You can escape Python.
- [React + Hugging Face](https://github.com/huggingface/huggingface.js) - When your frontend friends judge you.

### No-Code / Low-Code

- [Bubble + OpenAI](https://bubble.io) - Build apps without code. Perfect for "I'm not technical but I have ideas."
- [n8n](https://github.com/n8n-io/n8n) - Zapier on steroids. Open source. For the cool kids.
- [Make](https://make.com) - When you want automation but don't want to touch code.

---

## Tools and APIs

*The building blocks of your next "I built this in a weekend" flex.*

### LLM APIs

- [OpenAI API](https://platform.openai.com) - GPT-4o. The one everyone's tired of hearing about but can't stop using.
- [Anthropic API](https://docs.anthropic.com) - Claude 3.5. Better at not hallucinating. Slightly.
- [Google Gemini API](https://ai.google.dev) - When you want Google's scale behind your side quest.
- [Groq API](https://console.groq.com) - Fast. Like, embarrassingly fast. Free tier exists.
- [Ollama](https://github.com/ollama/ollama) - Run models on your laptop. Your GPU deserves a purpose.
- [LM Studio](https://lmstudio.ai) - The app version of Ollama. For when you prefer clicking to typing.

### Image Generation

- [Midjourney](https://www.midjourney.com) - Beautiful. Slightly creepy. Great for "concept art."
- [Stable Diffusion](https://github.com/Stability-AI/StableDiffusion) - Open source. You control everything. So does your GPU.
- [DALL-E API](https://platform.openai.com/docs/guides/images) - Safe. Reliable. One fewer thing to moderate.
- [Replicate](https://replicate.com) - Run any open model via API. No GPU required.
- [FLUX](https://github.com/black-forest-labs/flux) - The new kid. Apparently very good at hands.

### Audio

- [Eleven Labs](https://elevenlabs.io) - Voice cloning. Spooky and useful.
- [Whisper API](https://platform.openai.com/docs/guides/speech-to-text) - Transcription that doesn't make you cry.
- [Cartesia](https://cartesia.ai) - Real-time voice. For when you want to talk to your code.
- [Parakeet](https://github.com/rickyr123/nemo_parakeet) - Fast ASR. Less famous, surprisingly good.

### Video

- [Runway](https://runwayml.com) - "I'll just make a quick video" → two hours later.
- [Pika](https://pika.art) - Text-to-video. It's getting real.
- [Hailuo AI](https://hailuoai.video) - AI video generator. Free tier available.
- [KLING](https://klingai.com) - Video creation. The space is moving fast.

### Search & Data

- [SerpAPI](https://serpapi.com) - Google search without the selenium nightmare.
- [Exa](https://exa.ai) - Search like a human. Actually understands what you're looking for.
- [Tavily](https://tavily.com) - RAG-optimized search. For when Google isn't enough.
- [Crawl4AI](https://github.com/imartinez/crawl4ai) - Crawling for AI. Actually respects robots.txt.

### Embeddings & Vector

- [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings) - The OG. Still good.
- [Cohere](https://cohere.com) - Embeddings + reranking. Solid alternative.
- [Qdrant](https://github.com/qdrant/qdrant) - Vector DB in Rust. Fast and pretty.
- [Pinecone](https://www.pinecone.io) - Managed. For when you don't want to maintain infrastructure.
- [Chroma](https://github.com/chroma-core/chroma) - The "I'm just doing a quick prototype" vector DB.

---

## UI Components

*"Make it look like you know what you're doing."*

- [Vercel AI UI](https://github.com/vercel/ai) - Streaming, chat, message bubbles. The whole package.
- [Chainlit](https://github.com/Chainlit/chainlit) - Python-native. Minimal code, maximum chat.
- [Open UI](https://github.com/wandelbotsai/openui) - Describe the UI you want. Get code. Science? Magic? Both?
- [LibreChat](https://github.com/danny-avila/LibreChat) - Self-hosted ChatGPT. No ads. No "try our mobile app."
- [Textual](https://github.com/Textualize/textual) - Terminal UIs in Python. Because your code should be beautiful too.
- [Charm](https://charm.sh) - Make your CLI pretty. Terminal aesthetics matter.

---

## Deployment

*Shipping is the hard part. These make it less hard.*

### Serverless

- [Vercel](https://vercel.com) - Push to main → it's live. Magic.
- [Cloudflare Workers AI](https://developers.cloudflare.com/workers-ai) - Edge AI. For the distributed purists.
- [AWS Lambda + Bedrock](https://aws.amazon.com/bedrock) - Enterprise vibes. When you're ready to commit.

### Containers

- [Railway](https://railway.app) - "I just want it to run." Railway gets it.
- [Fly.io](https://fly.io) - Distributed containers. Close to users everywhere.
- [Render](https://render.com) - Containers + cron + more. One dashboard to rule them all.

### Managed ML

- [Modal](https://modal.com) - Python-first. For the data scientists who code.
- [Beam](https://beam.cloud) - Serverless GPUs. Pay per second. No GPU regret.
- [Baseten](https://baseten.com) - Model serving without the DevOps nightmares.

### Database & Storage

- [Supabase](https://supabase.com) - Postgres, auth, realtime, and more. The full stack.
- [PlanetScale](https://planetscale.com) - Serverless MySQL. Branching for your database.
- [Neon](https://neon.tech) - Serverless Postgres. The new kid on the block.
- [Upstash](https://upstash.com) - Redis and Kafka. Serverless. Pay as you go.

---

## Monetization

*Turning "I made this for fun" into "I made this for rent money."*

### Pricing Models

- **Freemium** - Free tier gets you users. Paid tier gets you coffee.
- **Usage-based** - They use more? You earn more. Fair.
- **Subscription** - Monthly recurring revenue. The startup fantasy.
- **Marketplace** - App stores, Gumroad, or your own checkout. Digital products are magic.
- **Affiliate** - "I use this tool and you should too" → money.

### Payment Integration

- [Stripe](https://stripe.com) - The default. Reliable. Slightly intimidating docs.
- [Lemon Squeezy](https://www.lemonsqueezy.com) - Payments for digital stuff. Less paperwork.
- [Paddle](https://paddle.com) - They handle tax. You handle shipping.
- [Gumroad](https://gumroad.com) - The creator economy's favorite.

### Launch Platforms

- [Product Hunt](https://producthunt.com) - Launch here or perish. Kidding. Kind of.
- [Indie Hackers](https://www.indiehackers.com) - Where bootstrapped dreams share revenue.
- [Showwcase](https://showwcase.com) - Developer community. Build in public.
- [Hacker News](https://news.ycombinator.com) - Show HN. The original launch platform. High risk, high reward.

---

## Learning Resources

*Getting good at this stuff. Finally.*

### Courses

- [DeepLearning.AI](https://www.deeplearning.ai) - Andrew Ng's courses. The Stanford professor vibe.
- [Fast.ai](https://fast.ai) - "We'll teach you deep learning. Then you'll revolutionize the field."
- [LangChain Academy](https://academy.langchain.com) - Build LLM apps. The practical path.

### Books

- [Build a Large Language Model](https://www.manning.com/books/build-a-large-language-model-from-scratch) - From zero to working LLM. Respect.
- [Practical AI](https://www.manning.com/books/practical-ai-with-swift) - For the Apple ecosystem people.

### Newsletters

- [The Batch](https://www.deeplearning.ai/the-batch) - Weekly. Curated. Not overwhelming.
- [Last Week in AI](https://lastweekin.ai) - Digestible. Good for "what did I miss?"
- [TLDR AI](https://tldr.tech/ai) - Daily. Short. Scannable. Works.

---

## Inspiration

*Real projects. Real people. Real "I could do that." energy.*

### Bootstrapped

- [Notion AI](https://notion.so/ai) - Writing assistant. Built into Notion. Genius.
- [Perplexity](https://perplexity.ai) - AI search. $1B+ valuation. Not bad for a side project.
- [Cursor](https://cursor.sh) - AI-first code editor. Your IDE is now jealous.
- [Lovable](https://lovable.dev) - Describe app → get app. The future is now.

### Open Source

- [Open Interpreter](https://github.com/KillianLucas/open-interpreter) - Code interpreter in your terminal. Wild.
- [Jan](https://github.com/janhq/jan) - ChatGPT but local. Privacy nerds rejoice.
- [Open WebUI](https://github.com/open-webui/open-webui) - Self-hosted everything. Open source forever.
- [Meetily](https://github.com/Zackriya-Solutions/meetily) - Privacy-first meetings. 10K stars. Do the right thing.

### Templates & Boilerplates

- [Ship Fast](https://shipfa.st) - Next.js + AI SaaS template. Ship faster.
- [SaaS AI Boilerplate](https://github.com/ixahmedxi/nextai) - The "I have an idea on Monday" template.
- [Vercel AI Templates](https://vercel.com/templates) - Official. Curated. Actually works.

---

## Contributing

Found something cool? PRs welcome. Found something broken? Issues welcome.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

Do whatever you want with this. We're not lawyers.

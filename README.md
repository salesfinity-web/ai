# Salesfinity AI

An AI-powered research assistant.

## 🧱 Stack

- App framework: [Next.js](https://nextjs.org/)
- Text streaming / Generative UI: [Vercel AI SDK](https://sdk.vercel.ai/docs)
- Generative Model: [OpenAI](https://openai.com/)
- Search API: [Tavily AI](https://tavily.com/)
- Component library: [shadcn/ui](https://ui.shadcn.com/)
- Headless component primitives: [Radix UI](https://www.radix-ui.com/)
- Styling: [Tailwind CSS](https://tailwindcss.com/)

## 🚀 Quickstart


### 1. Install dependencies

```
cd morphic
bun i
```

### 2. Fill out secrets

```
cp .env.local.example .env.local
```

Your .env.local file should look like this:

```
# Used to set the base URL path for OpenAI API requests.
# If you need to set a BASE URL, uncomment and set the following:
# OPENAI_API_BASE=

# OpenAI API key retrieved here: https://platform.openai.com/api-keys
OPENAI_API_KEY=[YOUR_OPENAI_API_KEY]

# Tavily API Key retrieved here: https://app.tavily.com/home
TAVILY_API_KEY=[YOUR_TAVILY_API_KEY]
```

### 3. Run app locally

```
bun dev
```

You can now visit http://localhost:3000.


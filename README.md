<div align="center">

# Open Lovable

Chat with AI to build React apps instantly.

## Live Demo

The app is running locally and a public tunnel is pending `deploy expose` approval. Once approved, the URL will be added here.


<img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmZtaHFleGRsMTNlaWNydGdianI4NGQ4dHhyZjB0d2VkcjRyeXBucCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZFVLWMa6dVskQX0qu1/giphy.gif" alt="Open Lovable Demo" width="100%"/>

</div>

## Setup

1. **Clone & Install**
```bash
git clone https://github.com/mendableai/open-lovable.git
cd open-lovable
npm install
```

2. **Add `.env.local`**
```env
# Required
E2B_API_KEY=your_e2b_api_key  # Get from https://e2b.dev (Sandboxes)
FIRECRAWL_API_KEY=your_firecrawl_api_key  # Get from https://firecrawl.dev (Web scraping)

# Optional (need at least one AI provider)
GROQ_API_KEY=your_groq_api_key  # Get from https://console.groq.com (default)
GOOGLE_API_KEY=your_google_api_key  # Get from https://aistudio.google.com/app/apikey
ANTHROPIC_API_KEY=your_anthropic_api_key  # Get from https://console.anthropic.com
OPENAI_API_KEY=your_openai_api_key  # Get from https://platform.openai.com
```

3. **Run**
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)  

## License

MIT
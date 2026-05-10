# 🚀 9AM IST AI Daily Digest (Arxiv + GitHub + News)

<div align="center">

![n8n](https://img.shields.io/badge/Built%20With-n8n-orange?style=for-the-badge)
![Telegram](https://img.shields.io/badge/Delivery-Telegram-blue?style=for-the-badge)
![Groq](https://img.shields.io/badge/LLM-Groq-red?style=for-the-badge)
![AI](https://img.shields.io/badge/Focus-AI%20%26%20ML-green?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-success?style=for-the-badge)

### 📚 Daily AI Research + 📰 Tech News + 🔥 Trending GitHub Repositories  
### Delivered Automatically Every Day at **9 AM IST**

</div>

---

# 🌍 Why This Project Exists

The AI ecosystem is evolving at an insane speed.

Every single day:
- New research papers are published 📄
- New AI startups/tools launch 🚀
- New breakthroughs happen 🤖
- New open-source GitHub repositories trend 🔥
- New AI news floods the internet 📰

For students, developers, researchers, and AI enthusiasts, this creates a massive problem:

# 😰 FOMO (Fear Of Missing Out)

There is simply too much information.

Most people:
- Cannot track everything manually
- Waste time scrolling through noise
- Miss important breakthroughs
- Struggle to find genuinely useful updates

---

# 💡 Solution

This project automates the entire process.

Every day at **9 AM IST**, the workflow automatically:

✅ Fetches top AI research papers from Arxiv  
✅ Fetches latest AI/ML tech news  
✅ Fetches trending GitHub repositories  
✅ Summarizes everything using LLMs  
✅ Sends a clean digest directly to Telegram  

So instead of reading hundreds of posts...

You only consume:
- What matters
- What is trending
- What is valuable

---

# ✨ Features

## 📄 Research Paper Digest
Get:
- Top AI/ML research papers
- Short 2–3 line summaries
- Direct paper/PDF links
- Easy-to-read format

---

## 📰 AI & Tech News
Receive:
- Breaking AI news
- Startup launches
- OpenAI/Google/Meta updates
- Industry developments
- Short AI-generated summaries

---

## 🔥 Trending GitHub Repositories
Discover:
- Fast-growing AI repos
- Viral open-source projects
- Useful developer tools
- New frameworks/libraries

Includes:
- Repository name
- What it does
- Why it matters
- GitHub link

---

# 📲 Telegram Access

The service is completely FREE.

## 🤖 Bot Username

```txt
@AINEWSFEED247_BOT
```

## 🔗 Direct Link

👉 https://t.me/AINEWSFEED247_BOT

Simply open Telegram and start the bot.

You will automatically start receiving daily updates.

---

# 🧠 Tech Stack

| Component | Purpose |
|---|---|
| n8n | Workflow automation |
| Groq LLM | AI summarization |
| Arxiv API | Research papers |
| NewsAPI | AI/Tech news |
| Tavily API | Trending GitHub repositories |
| Telegram Bot API | Message delivery |

---

# 🏗️ Workflow Architecture

## 🔄 Complete Workflow

```mermaid
flowchart LR

A[⏰ Schedule Trigger<br/>9 AM IST] --> B{Merge Pipeline}

B --> C[📄 Fetch Arxiv Papers]
B --> D[📰 Fetch AI News]
B --> E[🔥 Fetch Trending GitHub Repos]

C --> F[🧠 Groq LLM Summary]
D --> G[🧠 Groq LLM Summary]
E --> H[🧠 Repo Analysis]

F --> I[📨 Telegram Research Digest]
G --> J[📨 Telegram News Digest]
H --> K[📨 Telegram GitHub Digest]

style A fill:#ff6b6b,color:#fff
style B fill:#4ecdc4,color:#fff
style C fill:#ffe66d,color:#000
style D fill:#74c0fc,color:#fff
style E fill:#b197fc,color:#fff
style F fill:#ff922b,color:#fff
style G fill:#ff922b,color:#fff
style H fill:#ff922b,color:#fff
style I fill:#2b8a3e,color:#fff
style J fill:#2b8a3e,color:#fff
style K fill:#2b8a3e,color:#fff
```

---

# ⚙️ Detailed Workflow Explanation

## 1️⃣ Schedule Trigger
The automation starts automatically every day at:

```txt
9:00 AM IST
```

No manual execution required.

---

## 2️⃣ Research Paper Collection

The workflow:
- Connects with Arxiv API
- Fetches latest AI/ML papers
- Filters relevant content
- Sends papers to the LLM

### Example Topics
- LLMs
- Agents
- RAG
- Vision Models
- Robotics
- AI Safety
- Multimodal AI

---

## 3️⃣ AI News Collection

The workflow fetches:
- AI startup news
- Model launches
- Industry announcements
- Big tech AI updates
- AI regulation updates

Using:
```txt
NewsAPI
```

---

## 4️⃣ GitHub Trend Discovery

Using Tavily API:
- Searches latest trending AI repos
- Extracts repository information
- Filters useful projects
- Removes noisy repositories

---

## 5️⃣ AI Summarization Layer

The brain of the system.

Powered by:
```txt
Groq LLM
```

The model:
- Reads raw content
- Generates concise summaries
- Extracts key insights
- Makes content beginner-friendly

---

## 6️⃣ Telegram Delivery

Finally:
- Clean formatted messages are generated
- Content is organized into sections
- Messages are delivered directly to Telegram

---

# 🖼️ Screenshots


## 📲 Telegram Output


<img width="3510" height="2482" alt="Telegram_Bot" src="https://github.com/user-attachments/assets/8ebc9558-a631-41e6-827f-05178f465b77" />

---

# 📦 Folder Structure

```txt
AI-Daily-Digest/
│
├── README.md
├── workflow/
│   └── ai-daily-digest.json
│
├── Screenshots/
│   ├── Telegram_Bot.jpg
│   ├── telegram-1.png
│   ├── telegram-2.png
│   └── telegram-3.png
│
└── docs/
    └── setup-guide.md
```

---

# 🚀 How To Use

## 1️⃣ Clone Repository

```bash
git clone https://github.com/shubham001official/AI-Daily-Digest.git
```

---

## 2️⃣ Import Workflow Into n8n

- Open n8n
- Click "Import Workflow"
- Select:
```txt
ai-daily-digest.json
```

---

## 3️⃣ Add API Keys

Configure:
- Groq API Key
- NewsAPI Key
- Tavily API Key
- Telegram Bot Token

---

## 4️⃣ Activate Workflow

Turn workflow ON.

Done ✅

Now the bot will automatically run daily.

---

# 🔐 Required Environment Variables

```env
GROQ_API_KEY=
NEWS_API_KEY=
TAVILY_API_KEY=
TELEGRAM_BOT_TOKEN=
```

---

# 📈 Future Improvements

Planned features:

- [ ] Personalized topic preferences
- [ ] AI Tool recommendations
- [ ] YouTube AI video digest
- [ ] Twitter/X AI trend analysis
- [ ] AI startup funding tracker
- [ ] Multi-language summaries
- [ ] Voice summaries
- [ ] Email newsletter support
- [ ] Discord integration
- [ ] WhatsApp integration
- [ ] AI Agents section
- [ ] HuggingFace trending models
- [ ] Papers With Code integration

---

# 🎯 Ideal Users

This project is useful for:

- Students 👨‍🎓
- AI Enthusiasts 🤖
- Researchers 📚
- Developers 💻
- Startup Founders 🚀
- Data Scientists 📊
- ML Engineers 🧠
- Tech Communities 🌍

---

# 🌟 Key Benefits

✅ Saves Time  
✅ Reduces Information Overload  
✅ Eliminates Noise  
✅ Keeps You Updated Daily  
✅ Beginner Friendly  
✅ Fully Automated  
✅ Free To Use  

---

# 🧩 Example Daily Flow

```mermaid
journey
    title Daily AI Digest User Journey
    section Morning
      Bot triggers at 9AM: 5: User
      Fetch latest content: 5: System
      Summarize using AI: 5: System
    section Delivery
      Send Telegram digest: 5: System
      User reads updates: 5: User
    section Outcome
      Stay updated without scrolling: 5: User
      Reduce FOMO: 5: User
```

---

# 📊 Data Sources

| Source | Usage |
|---|---|
| Arxiv | Research papers |
| NewsAPI | AI news |
| Tavily | GitHub repo discovery |
| Groq | AI summarization |
| Telegram | Message delivery |

---

# 🔥 What Makes This Different?

Instead of:
- Endless scrolling
- Twitter/X overload
- Random YouTube recommendations
- Information chaos

You receive:
- Curated updates
- Clean summaries
- Actionable insights
- Signal over noise

---

# 🤝 Contributions

Contributions are welcome.

Ideas, improvements, and feature suggestions are highly appreciated.

Feel free to:
- Fork the repo
- Open issues
- Submit PRs

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository  
🍴 Fork the project  
📢 Share with friends  

---

# 📜 License

MIT License

---

# 👨‍💻 Author

Built with ❤️ using n8n + AI Automation

---

# 🚀 Final Vision

The vision is simple:

> Build a free AI-powered ecosystem that helps people stay updated with the fast-moving AI world — without drowning in noise.

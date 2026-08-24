# ⚡ VIRALY — AI Content Repurposing & Strategy Engine

> **One upload. Every platform.** Transform raw ideas, YouTube videos, and documents into high-converting Twitter threads, LinkedIn thought-leadership posts, viral Reel hooks, and short-form video scripts in under 2 seconds.

---

## 💡 Why VIRALY?

Creating great content takes hours. But adapting that one piece of content across Twitter, LinkedIn, Instagram, TikTok, and YouTube Shorts takes even longer.

Most creators get stuck copy-pasting generic prompts into basic AI chatbots, only to spend more time editing the robotic output to fit platform constraints.

**VIRALY eliminates this distribution bottleneck.** It ingests your source material once, analyzes its core substance, applies platform-specific copywriting formulas, and delivers ready-to-publish assets—plus a personalized **7-Day AI Content Roadmap** to keep your posting streak alive.

---

## ✨ Key Features & Functionality

### 1. 🎙️ Multi-Source Ingestion Pipeline
VIRALY is source-agnostic. Bring whatever content format you have:
- **YouTube URLs:** Paste any public YouTube video link. Our resilient 3-layer extraction engine automatically fetches timed transcripts, subtitle fallbacks, or rich video metadata.
- **PDF & TXT Documents:** Drop research papers, blog drafts, meeting notes, or PDF books with server-side text extraction.
- **Raw Text / Thoughts:** Type or paste quick ideas and provide custom creative instructions.

### 2. 🚀 Platform-Specific Repurposing Studio
Instead of generic summaries, VIRALY uses **Constraint-Driven Prompt Engineering** with Google Gemini 3.5 Flash Lite:
- 🐦 **Twitter / X Threads:** 5–8 tweet narrative threads engineered with a high-impact opening hook and a final call-to-action.
- 💼 **LinkedIn Posts:** Authority-building posts structured with strong lead-ins, readable short paragraphs, bulleted insights, and discussion prompts.
- 🎬 **Reel / TikTok Hooks:** 5 short, high-retention opening hooks (< 15 words) designed for 3-second hold rates.
- 📜 **Short Video Scripts:** 30–45 second production-ready scripts with timestamps: *Hook (0–5s)*, *Core Value (5–35s)*, and *CTA (35–45s)*.
- 📸 **Instagram Captions & #Hashtags:** Value-dense captions formatted with natural line breaks and 15 non-spammy, high-volume hashtags.

### 3. 📅 AI Content Calendar & 7-Day Roadmap
Planning ahead is just as important as generating copy:
- **Activity Heatmap:** Visual monthly grid tracking your daily repurposing activity with color-coded format badges.
- **Day Inspector:** Click any calendar date to review and copy past generated assets.
- **7-Day AI Content Roadmap:** The AI analyzes your past generation topics in MongoDB and forecasts an upcoming 7-day posting schedule (Strategic Themes, Platform Targets, Viral Hooks, and Studio Prompts).
- **1-Click Studio Transfer:** Clicking **"Send to Studio →"** on any roadmap recommendation automatically pre-fills the prompt and switches tabs in the generator.

### 4. 📊 Live Diagnostics & Analytics Dashboard
Track your productivity metrics in real-time:
- **Lifetime Repurposed Assets:** Real-time count of total social deliverables created.
- **Calculated Hours Saved:** Automatic time-savings estimation based on historical generation volume.
- **AI Latency Rate:** Sub-2-second round-trip diagnostic tracking.
- **Platform & Tone Distributions:** Visual breakdown of your most frequently used formats and brand voices.

### 5. ☁️ Multi-Device Cloud Authentication
- All user accounts, generation histories, and calendar streaks are persisted directly in **MongoDB Atlas**.
- Log in seamlessly from your laptop, mobile browser, or office computer with instant session hydration.

---

## 🛠️ Technology Stack

| Layer | Technologies Used |
| :--- | :--- |
| **Frontend** | React 19, Vite, Tailwind CSS v4, React Router Dom v7 |
| **Backend** | Node.js, Express.js, CORS, `dotenv`, `perf_hooks` |
| **AI Synthesis** | Google Gemini 3.5 Flash Lite (`@google/genai` SDK) |
| **Ingestion Pipeline** | `youtube-transcript`, `youtube-caption-extractor`, `pdf-parse` |
| **Database** | MongoDB Atlas Cloud with Mongoose ODM |
| **DevOps & Hosting** | Vercel (Frontend CI/CD) + Render (Backend Web Service) |

---

## 🚀 Quick Start (Local Setup)

### 1. Clone the Repository
```bash
git clone https://github.com/YuvrajSharma13/VIRALY-FRONTEND.git
cd VIRALY-FRONTEND
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Configure Environment Variables
Create a `.env` file in the root:
```env
VITE_API_URL=https://viraly-project.onrender.com
```

### 4. Run Locally
```bash
npm run dev
```
Open your browser at `http://localhost:5173`.

---

## 👨‍💻 Author

Built by **Yuvraj Sharma**

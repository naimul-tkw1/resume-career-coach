# 📄 Resume Career Coach — Claude Skill

![Claude Skill](https://img.shields.io/badge/Claude-Skill-blueviolet?logo=anthropic&logoColor=white)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Claude.ai-orange)
![Status](https://img.shields.io/badge/status-active-brightgreen)

> An AI-powered career coach built as a Claude Skill. Upload your resume and a job posting to get a full coaching session — from job fit scoring to a personalized cover letter.

---

## ✨ Features

| Step | Feature | Description |
|------|---------|-------------|
| 1️⃣ | **Job Fit Score** | Compares your skills to the job requirements and rates your match out of 100 |
| 2️⃣ | **ATS Audit** | Scores your resume against industry resume writing guidelines with specific improvement tips |
| 3️⃣ | **Expert Resume Tips** | Personalized feedback based on professional resume best practices |
| 4️⃣ | **Gap Analysis** | Identifies critical, presentation, and strategic gaps with a prioritized action plan |
| 5️⃣ | **Cover Letter Generator** | Writes a tailored, tone-matched cover letter based on your own writing samples |

---

## 🚀 How It Works

```
You → Upload resume + job posting
         ↓
   Step 1: Job Fit Score /100
         ↓
   Step 2: ATS Score /100 + improvements
         ↓
   Step 3: Expert resume tips & feedback
         ↓
   Step 4: Gap analysis + action plan
         ↓
   Step 5: (Optional) Tailored cover letter
```

Just provide your resume (upload, paste, or link) and a job posting (paste or URL) — Claude handles the rest automatically.

---

## 📦 Installation

1. Download `resume-career-coach.skill` from the [Releases](../../releases) page
2. Go to **Claude.ai → Settings → Skills**
3. Click **Install Skill** and select the `.skill` file
4. Start a new conversation and say *"Check my resume"* or *"I'm applying for a job"*

---

## 💬 Example Prompts

Once installed, try any of these to trigger the skill:

- *"I want to apply for this job — here's my resume and the posting"*
- *"Can you check my resume against this job description?"*
- *"Give me an ATS score for my resume"*
- *"Help me write a cover letter"*
- *"Is this job a good fit for me?"*

---

## 📁 Skill Contents

```
resume-career-coach/
├── SKILL.md                          # Core skill instructions
└── assets/
    └── Resume_Writing_Guidelines.pdf # ATS & formatting reference
```

---

## 🧠 How the Scoring Works

### Job Fit Score (Step 1)
| Score | Verdict |
|-------|---------|
| 80–100 | ✅ Strong fit — apply confidently |
| 60–79 | ⚠️ Moderate fit — apply but address gaps |
| Below 60 | 📈 Stretch role — focus on skill-building first |

### ATS Score (Step 2)
| Category | Weight |
|----------|--------|
| Keyword Alignment | 25 pts |
| Formatting & Layout | 20 pts |
| Content Structure | 20 pts |
| Impact & Quantification | 20 pts |
| Professional Summary | 15 pts |

---

## 🎯 Cover Letter Generation

The cover letter step (Step 5) is **always opt-in**. When requested, Claude will:

1. Ask for 2–3 writing samples (emails, messages, etc.)
2. Analyze your natural tone, vocabulary, and style
3. Generate a tailored letter that **sounds like you** — not like AI

---

## 🛡️ Privacy

- Your resume and job posting are only used within the conversation
- No data is stored or shared outside of your Claude session
- Writing samples provided for tone-matching are used only for cover letter generation

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

1. Fork the repo
2. Edit `SKILL.md` with your improvements
3. Test with a few resume + job posting combinations
4. Open a pull request with a description of what changed and why

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgements

- Resume Writing Guidelines bundled with skill based on industry best practices
- Resume tips sourced from professional career coaching resources
- Built on [Anthropic's Claude](https://claude.ai) Skill framework

---

<p align="center">
  Made with ❤️ for job seekers everywhere &nbsp;|&nbsp; Built on Claude.ai
</p>

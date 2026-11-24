<div align="center">

# 🤖 TitanAI (formerly TELS AI)

### The AI inside TitanEd Orbit: help for learners and course teams, right where learning happens

**Product owner:** TitanEd &nbsp;·&nbsp; **My role:** Software Engineer at TitanEd (AI assistant frontend) &nbsp;·&nbsp; **Oct 2026 – Present**

![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Open edX](https://img.shields.io/badge/Open%20edX-02262B?style=flat)
![Generative AI](https://img.shields.io/badge/Generative%20AI-FF6F00?style=flat)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-6A1B9A?style=flat)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white)

</div>

> **Note:** TitanAI is part of TitanEd's commercial platform and its source code is private. This repository is a **project showcase** and contains no company code.

---

## 📌 About

TitanAI brings AI assistance into [TitanEd Orbit](https://github.com/sonukumarsingh01/titaned-orbit-learning-platform): it helps
educators create courses, helps learners understand and practise, and gives course teams useful insights, inside Studio and the
LMS instead of a separate tool.

## ✅ What I built

The **frontend of the AI assistant** in Studio and the LMS, working with the TitanEd backend team:

- **One assistant everywhere:** the same AI panel in every app, added through plugin slots with no changes inside the apps.
- **Rich, interactive answers:** replies stream in as cards, tables, forms, progress views and action buttons, not just text.
- **Safe by design:** the AI can only show UI blocks from an approved catalogue; it can never inject code into the page.
- **Every brand, every language:** follows each institution's theme; Hindi, Arabic and Spanish, with right-to-left layouts.
- **AI course creation in Studio:** course creators build a course, outline, assessments, exams, certificates and an intro video by chatting with the AI.
- **Agentic AI:** the assistant can carry out multi-step tasks for the user, not just answer.
- **Tested:** unit tests with Jest and React Testing Library.

## 🎯 What people can do with TitanAI

**Learners**
- Understand a lesson: summaries, explanations, questions about a lesson or the whole course.
- Practise: generated questions, a role-play coach, an exam-readiness check.
- Stay on track: goals, a study plan, upcoming deadlines, revision sheets and progress.

**Educators and course teams**
- Build courses faster in Studio with AI.
- An AI forum assistant for course discussions.
- AI reports on learning impact, at-risk learners, deadlines and course health.

## 🏗️ How it's built

```
 Studio · LMS · Dashboards
        │  plugin slot (no core change)
        ▼
 ┌───────────── AI assistant UI (my work) ─────────────┐
 │ Launcher · Panel · Conversation · Streamed answers   │
 │ Block renderer: card · table · form · action · progress │
 │ Theming · i18n (hi, ar, es) · RTL                    │
 └───────────────────────┬──────────────────────────────┘
                         │ stream of typed JSON events
                         ▼
                 TitanAI backend (Django plugin)
```

**Tech:** React, Paragon, Frontend Plugin Framework, streaming APIs, react-intl, Jest, React Testing Library.

---

<div align="center">

**Sonu Kumar** · Software Engineer · [LinkedIn](https://www.linkedin.com/in/dr-sonu-kumar/) · [GitHub](https://github.com/sonukumarsingh01)

</div>

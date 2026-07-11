<div align="center">

# 🎨 Pixel Pluck

### *Not Just Design, But Vision for Your Brand.*

> 🏆 Adobe Express Hackathon Submission

An AI-powered branding assistant for **Adobe Express** that extracts brand identities, generates trend-aware design prompts, and audits designs for consistency and accessibility.

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi)
![Groq](https://img.shields.io/badge/Groq-LLM-black)
![Adobe Express](https://img.shields.io/badge/Adobe-Express-FF0000?logo=adobe)

![GitHub stars](https://img.shields.io/github/stars/thakuradityaas9-glitch/Pixel-Pluck?style=social)
![GitHub forks](https://img.shields.io/github/forks/thakuradityaas9-glitch/Pixel-Pluck?style=social)

</div>

---

# 📖 Overview

Pixel Pluck transforms hours of manual brand research into seconds using AI.

Instead of manually extracting colors, analyzing brand voice, studying typography, and checking accessibility, Pixel Pluck automates the entire workflow directly inside **Adobe Express**.

Powered by **Vision AI**, **Large Language Models**, and the **Adobe Express Add-on SDK**, it helps designers create consistent, on-brand content faster than ever.

---

# ✨ Features

## 🧠 Brand Brain

Automatically extracts a complete brand identity from a website, text, or image.

**Extracts**

- 🎨 Brand color palettes with exact hex codes
- 🗣️ Brand voice and tone
- ✍️ Typography preferences
- 📐 Design guidelines
- 🎯 Visual hierarchy

**Supports**

- Website URLs
- Brand descriptions
- Images

---

## 🚀 Trend Engine

Generate AI-powered design prompts that combine:

- Latest design trends
- Viral content formats
- Extracted brand identity
- Platform-specific best practices

Perfect for generating:

- Landing Pages
- Social Media Creatives
- Marketing Banners
- App UI Screens
- Brand Visuals

---

## 🔍 Design Auditor

Analyze your designs using Vision AI and receive:

- 📊 Overall Design Score
- 🎯 Brand Consistency Report
- ♿ Accessibility Analysis
- 🎨 Color Recommendations
- ✍️ Typography Feedback
- 📐 Layout Improvements

Supports automatic Adobe canvas capture (Premium users) and manual PNG uploads.

---

## 🌍 Multilingual Support

Pixel Pluck adapts all AI-generated outputs to your preferred language, including:

- Brand analysis
- Trend prompts
- Design audit feedback
- User interface

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Frontend | React, TypeScript |
| Backend | FastAPI, Python |
| AI Models | Groq, Llama 3.3 70B, Llama Vision |
| Platform | Adobe Express Add-on SDK |
| UI | Adobe Spectrum CSS, Lucide React |

---

# 🏗️ Architecture

```text
                 User
                   │
                   ▼
        Adobe Express Add-on
                   │
                   ▼
        React + TypeScript UI
                   │
                   ▼
           FastAPI Backend
                   │
        ┌──────────┼──────────┐
        │          │          │
        ▼          ▼          ▼
    Groq LLM   Vision AI   Processing Engine
        │          │
        └──────┬───┘
               ▼
   Brand Analysis • Trend Generation • Design Auditing
```

---

# 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/thakuradityaas9-glitch/Pixel-Pluck.git

cd Pixel-Pluck
```

### Install dependencies

```bash
npm install
```

### Run the frontend

```bash
npm run dev
```

### Run the backend

```bash
cd backend

pip install -r requirements.txt

uvicorn main:app --reload
```

---

# 🏆 Accomplishments

- 🎨 Native Adobe Express integration
- ⚡ AI-powered analysis in under 15 seconds
- 🌍 Multilingual support
- ♿ Accessibility-aware recommendations
- 🎯 Actionable, pixel-perfect design feedback
- 🚀 End-to-end AI-powered brand intelligence workflow

---

# 🚧 Challenges

The Adobe Express `createRenditions()` API is available only for Premium users.

To ensure everyone could use Pixel Pluck, we implemented:

- Premium user detection
- Automatic fallback handling
- Manual image upload support for design auditing

---

# 📚 What We Learned

- Prompt engineering often matters more than choosing a larger model.
- Great user experience beats perfect automation.
- Fast AI responses improve trust and usability.
- Documentation improves both development and onboarding.
- Reliable fallback systems are essential for production-ready applications.

---

# 🔮 Roadmap

- 🎨 Adobe Firefly Integration
- 📊 Analytics Dashboard
- 🤖 Custom AI Fine-Tuning
- 🌍 More Language Support
- 🎯 Advanced Brand Templates
- 🤝 Community Contributions

---

# ❤️ Built With

- Adobe Express Add-on SDK
- React
- TypeScript
- FastAPI
- Python
- Groq
- Llama 3.3
- Llama Vision
- Adobe Spectrum CSS
- Lucide React

---

# 👥 Team

Built with ❤️ during the **Adobe Express Hackathon**.

---

# ⭐ Support

If you found this project useful or interesting, consider giving it a ⭐ on GitHub.

Issues, feature requests, and contributions are always welcome!

---

<div align="center">

### ⭐ Pixel Pluck

**Not Just Design, But Vision for Your Brand.**

Made with ❤️ using AI.

</div>

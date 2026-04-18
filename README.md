# 🤖 Generative AI Portfolio — Sara Singh

> A hands-on learning portfolio built across a 10-day Generative AI workshop.  
> **B.Tech CSE (Final Year)** | Exploring the intersection of AI, automation, and real-world application.

---

## 👋 About This Repository

I'm a final-year Computer Science student, and this repository documents my entry into the world of Generative AI. Over 10 days of intensive, hands-on learning, I went from understanding the basics of prompt engineering to building multi-modal applications involving text, speech, image comprehension, and sentiment analysis.

This isn't a polished product portfolio — it's an honest record of learning, experimentation, and growth. Each project reflects a real concept I was working to understand, and most include working code, sample outputs, and documented requirements.

---

## 📁 Projects Overview

| # | Project | Key Concepts | Stack |
|---|---------|--------------|-------|
| 1 | [Data Science Assistant](#1-data-science-domain-restricted-assistant) | Domain restriction, prompt engineering | Python, OpenAI API |
| 2 | [AI Timetable Generator](#2-ai-timetable-generator) | Structured output, prompt design | Python, OpenAI API |
| 3 | [AI Math Tutor](#3-ai-math-tutor) | Socratic prompting, conversational AI | Python, OpenAI API |
| 4 | [Travel Itinerary Generator](#4-conversational-travel-itinerary-generator) | Multi-turn conversation, constraint handling | Python, OpenAI API |
| 5 | [Review Sentiment Analyser](#5-review-sentiment-analyser) | Sentiment analysis, NLP | Python, OpenAI API |
| 6 | [Duolingo-Style Language App](#6-duolingo-style-language-learning-app) | TTS, STT, image comprehension, translation | Python, Streamlit |
| 7 | [Tech Tutor App](#7-tech-tutor-app) | Multi-modal tutoring, voice + vision | Python, Streamlit |
| 8 | [Text & Speech Intro](#8-text-to-speech--speech-to-text-introduction) | TTS/STT fundamentals | Python, Jupyter |
| 9 | [Hugging Face Exploration](#9-hugging-face-model-exploration) | Open-source LLMs, HF ecosystem | Python, Hugging Face |
| 10 | [Case Study 1](#10-case-study-1) | Applied prompt engineering | Python, Jupyter |
| 11 | [Case Study 2](#11-case-study-2) | Applied prompt engineering | Python, Jupyter |

---

## 🔍 Project Details

### 1. Data Science Domain-Restricted Assistant
**`/data-science-assistant`**

An AI assistant that is constrained through prompt engineering to answer **only** Data Science-related questions. This project explores how system-level instructions can be used to scope and control model behaviour — a foundational concept in building reliable AI products.

- Includes a working Jupyter notebook and sample output
- Demonstrates prompt boundary design and input handling

---

### 2. AI Timetable Generator
**`/timetable-generator`**

A prompt-engineered AI tool that generates a structured weekly timetable for 3rd-year B.Tech students, specifically designed to balance **academic coursework with placement preparation**. The output is formatted and consistent across runs.

- Includes sample output demonstrating structured generation
- Explores how LLMs can produce formatted, context-aware outputs rather than freeform text

---

### 3. AI Math Tutor
**`/math-ai-tutor`**

A conversational AI tutor built on the principle of **Socratic learning** — it guides students through math problems using hints and questions rather than giving away answers directly. Designed to encourage problem-solving skills over answer-seeking behaviour.

- Step-by-step hint system via prompt design
- Interactive conversational loop
- Includes sample output showing the tutor-student exchange

---

### 4. Conversational Travel Itinerary Generator
**`/travel_itinerary_genrator`**

A multi-turn conversational AI agent that builds a customised travel itinerary based on user-provided constraints: **budget, destination, number of people, and trip duration**. The agent collects information across the conversation before generating a day-wise plan.

- Demonstrates multi-turn conversation state management
- Budget-aware and preference-driven output
- Includes sample output with a full generated itinerary

---

### 5. Review Sentiment Analyser
**`/review-sentiment-analysis`**

An AI-powered tool that analyses product or service reviews and classifies the underlying sentiment. This project explores how LLMs can be applied to **natural language understanding** tasks beyond just generation.

- Jupyter notebook with requirements
- Applies prompt engineering to an NLP classification task

---

### 6. Duolingo-Style Language Learning App
**`/duolingo_project`**

A multi-feature language learning application inspired by Duolingo. This is one of the more technically involved projects in the portfolio — it combines **text-to-speech, speech-to-text, image comprehension, grammar exercises, and translation** into a single Streamlit application.

- `grammar_fun.py` — grammar practice module
- `reading_translation.py` — reading and translation exercises
- `image_comprehension.py` — image-based language prompts
- `soundcheck.py` + `.wav` outputs — audio generation and playback
- Built with Streamlit (`app.py`, `home.py`)

---

### 7. Tech Tutor App
**`/tech_tutor`**

A technical tutoring application that uses a similar multi-modal architecture to the Duolingo project — combining **voice, image comprehension, and text-based interaction** — but oriented towards teaching technical concepts rather than language.

- Shares a modular file structure with the language app
- Demonstrates reusability of multi-modal AI components across domains
- Audio output confirmed via `.wav` files

---

### 8. Text-to-Speech & Speech-to-Text Introduction
**`/text_speech_intro`**

An introductory notebook that covers the fundamentals of **converting text to speech and speech to text** using Python. This served as the technical foundation for the audio components used in the Duolingo and Tech Tutor projects.

- Single focused notebook — clean, concept-first exploration
- Useful starting point for anyone new to voice AI

---

### 9. Hugging Face Model Exploration
**`/hugging_face`**

Two notebooks exploring the **Hugging Face ecosystem** — working with open-source models and the Hugging Face API. This project reflects a conscious effort to go beyond proprietary APIs and understand how open-source LLMs can be accessed and used.

- `Hugging_Face.ipynb` and `HuggingFace2.ipynb` — iterative exploration
- Introduction to model hubs, pipelines, and open-weight models

---

### 10. Case Study 1
**`/case_study_1`**

A workshop case study notebook applying prompt engineering concepts in a practical scenario. Includes a conversation/output log alongside the notebook.

---

### 11. Case Study 2
**`/case_study_2`**

A second workshop case study, with a context file referencing Hindustan College of Science & Technology — likely a domain-specific prompt engineering exercise applied to an institutional context.

---

## 🛠️ Technologies Used

- **Language:** Python
- **Notebooks:** Jupyter / Google Colab
- **APIs:** OpenAI API, Hugging Face API
- **Frameworks:** Streamlit
- **AI Concepts:** Prompt Engineering, Conversational AI, Sentiment Analysis, Text-to-Speech, Speech-to-Text, Image Comprehension, Domain Restriction, Structured Output Generation
- **Version Control:** Git & GitHub

---

## 📈 Phase 3 — Learning Reflection

### From Computer Networks to Generative AI

My undergraduate focus has been on **Computer Networks** — understanding how data moves, how systems communicate, and how infrastructure is designed for reliability and scale. That background turned out to be more relevant to AI than I initially expected.

Networks taught me to think about **systems**: inputs, outputs, protocols, and failure handling. Those same instincts apply directly when working with LLMs — every prompt is essentially a request with a protocol, every model response is a packet of structured (or unstructured) data, and every AI application is a pipeline that needs to be designed with edge cases in mind.

### What I Learned in 10 Days

| Area | What I Explored |
|------|-----------------|
| **Prompt Engineering** | Zero-shot, few-shot, role prompting, domain restriction, Socratic design |
| **Conversational AI** | Multi-turn loops, context management, stateful prompting |
| **Multi-modal AI** | Text + Speech + Image in a single application |
| **Open-Source Models** | Hugging Face pipelines vs. proprietary APIs |
| **Structured Generation** | Getting LLMs to produce consistent, formatted outputs |
| **App Development** | Moving from notebooks to Streamlit-based deployable apps |

### Where This Sits in Today's Tech Landscape

The projects in this portfolio align with some of the most active areas in AI right now:

- **AI Agents & Assistants** — the domain-restricted assistant and math tutor are early versions of the kind of scoped, reliable agents being built in industry today
- **RAG and Context Design** — understanding prompt boundaries is the precursor to building Retrieval-Augmented Generation systems
- **Voice AI** — TTS/STT is a rapidly growing space with real applications in accessibility, EdTech, and customer service
- **EdTech AI** — both the math tutor and language learning app directly address a sector seeing enormous investment and adoption
- **Open-Source LLMs** — familiarity with Hugging Face is increasingly valued as teams move away from full dependence on closed APIs

### Honest Takeaway

This is 10 days of work, not 10 years. But it's 10 days of **genuine, hands-on learning** with real outputs. Every notebook runs. Every app was built from scratch. The sample outputs are real. The code is mine.

For someone coming from a networks background, this portfolio is proof that the fundamentals of systems thinking transfer — and that picking up new tools quickly is a skill in itself.

---

## 🔒 Security Note

All API keys are stored using environment variables and are **not committed to this repository**.

---

## 👤 Author

**Sara Singh**  
B.Tech — Computer Science & Engineering (Final Year)  
*Generative AI Workshop Portfolio — 2025*

---

*Built with curiosity, a 10-day deadline, and a lot of notebook restarts.*

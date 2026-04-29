# Resume LLM Optimizer

An AI-assisted resume targeting tool that generates structured, high-signal prompts to optimize resumes for specific job descriptions using large language models.

This tool bridges the gap between generic resumes and role-specific applications by transforming raw job postings and resume content into a structured prompt that drives high-quality, targeted outputs from models like ChatGPT, Claude, and Gemini.

---

## 🚀 Overview

Applying to jobs at scale often fails due to poor alignment between a candidate’s resume and the job description, especially in ATS-driven pipelines.

This project solves that problem by:

- Structuring job descriptions into actionable signals
- Injecting full resume context into a guided prompt
- Producing a reusable, high-quality prompt for LLM-based resume refinement

Instead of manually rewriting resumes, users generate a prompt that instructs an AI model to:
- Analyze job requirements
- Compare them against the resume
- Rewrite content with stronger alignment and impact
- Provide actionable improvement recommendations

---

## ✨ Features

- **Structured Prompt Generation**
  - Converts job descriptions and resumes into a guided, multi-step prompt

- **ATS-Aware Optimization**
  - Encourages extraction of keywords, required skills, and role priorities

- **Model-Agnostic**
  - Works with ChatGPT, Claude, Gemini, Copilot, Grok, and other LLMs

- **Full Context Injection**
  - Supports large inputs (2,000–4,000+ tokens) for deeper reasoning

- **Guided Output Format**
  - Forces consistent, high-quality outputs:
    - Requirements analysis
    - Resume match assessment
    - Missing skills
    - Rewritten summary and bullet points

- **Lightweight UI**
  - Single-page interface with no backend required

---

## 🧠 How It Works

1. User inputs:
   - Target industry
   - Role title
   - Full job description
   - Full resume text

2. The tool builds a structured prompt that:
   - Simulates a senior hiring manager
   - Forces step-by-step reasoning
   - Guides the model toward resume optimization (not generic advice)

3. The generated prompt is pasted into an LLM

4. The LLM returns:
   - Targeted resume improvements
   - Keyword alignment
   - Rewritten content tailored to the role

---

## 🖥️ Usage

1. Open the HTML file in a browser
2. Fill in:
   - Industry
   - Role
   - Job description
   - Resume
3. Click **"Build prompt"**
4. Copy the generated prompt
5. Paste into your preferred LLM:
   - ChatGPT
   - Claude
   - Gemini
   - etc.

---

## 📌 Example Use Case

**Input:**
- Role: Senior Software Engineer (Platform)
- Job Description: Cloud infrastructure, CI/CD, distributed systems
- Resume: Platform engineer with Linux, DevOps, and migration experience

**Output:**
- Identifies missing distributed systems signals
- Strengthens DevOps and cloud alignment
- Rewrites bullet points with stronger impact language
- Improves ATS keyword coverage

---

## 🧱 Tech Stack

- HTML
- CSS
- Vanilla JavaScript

No frameworks, no backend — designed for simplicity and portability.

---

## 🎯 Why This Project Exists

Most candidates:
- Use generic resumes
- Miss critical keywords
- Undersell relevant experience

Most LLM prompts:
- Are vague
- Produce inconsistent results

This tool enforces **structured prompting** to produce more reliable, high-quality outputs aligned with real hiring expectations.

---

## 🔮 Future Improvements

- Backend API for prompt generation
- Resume parsing (PDF/DOCX ingestion)
- Job board integration (auto-import job descriptions)
- Saved prompt history
- Multi-role optimization
- Scoring system for resume-job match

---

## ⚠️ Limitations

- Depends on the quality of the input resume
- Does not independently validate factual accuracy
- Output quality depends on the LLM used

---

## 📄 License

MIT License

---

## 👤 Author

Built as part of a broader effort to create tools that improve job search efficiency and leverage AI for real-world workflows.

# Arya Nassaj

Computer Science student at the University of Maryland (Minor in Economics) building production SaaS products at the intersection of AI, ML/Data Science, full-stack engineering, and business.

Co-Founder of **Obsidian Luxe Holdings LLC** — a vertically integrated real estate firm operating across residential acquisitions, commercial acquisitions, and private lending.

---

## What I've Built

**[Obsidian OS](https://app.obsidianluxeholdingsllc.com)** _private repo_ — AI-powered commercial real estate acquisition platform sold to 4 companies. Full-stack SaaS CRM with a power dialer, AI-drafted LOI generation, DocuSign e-signature webhook workflow, call transcription + AI summaries, and a comps engine backed by the ATTOM Property API.

**Pitchline** _private repo_ — Multi-tenant AI sales coaching engine. Every sales call runs through an 8-step pipeline: AssemblyAI transcription → metric extraction → quality gating → Claude Sonnet coaching notes → pgvector Rep DNA embeddings. Four-layer ML architecture including org-specific GPT-4o-mini fine-tuning and a cross-org vertical training pool data flywheel across 8 industries.

**[TerpAdvisor](https://terrapin-advisor.vercel.app)** — AI-powered academic advisor for University of Maryland students. Upload your DegreeWorks audit PDF and get a Claude-powered advisor that knows your full academic history, plans your 4-year schedule, and answers live questions about registration and course availability via Gemini 2.0 Flash search grounding. ML service runs four models trained on PlanetTERP data — GradientBoosting difficulty and workload predictors, a VADER-based professor quality scorer, and a cosine-similarity collaborative filter — across 4,876 UMD courses seeded into Postgres. Gemini text-embedding-004 powers semantic course discovery: describe what you want to learn and the system finds matching courses by meaning, not keywords.

**[LabSentinel](https://github.com/aryanassaj/labsentinel)** — Early cancer signal detector that reads a patient's routine blood panel (CBC + CMP) and outputs a risk score with a full SHAP-driven clinical explanation. Trained on 53,448 NHANES participants (CDC, 1999–2018) with cancer labels sourced from the NCHS Linked Mortality Index — detecting pre-diagnostic cancer signal in blood chemistry before symptoms appear. XGBoost with 86 engineered features including inflammatory ratios (NLR, PLR, SII), composite clinical scores (Glasgow Prognostic Score, eGFR, De Ritis Ratio), and 30+ binary clinical flags; SMOTE class balancing; AUC-ROC 0.810; 83.2% sensitivity at Youden's J calibrated threshold. Includes 6 cancer subtype models (colorectal, lung, breast, prostate, leukemia, lymphoma), SHAP TreeExplainer breakdowns per prediction, PDF report generation, and a batch worklist API for EHR integration.

---

## Tech Stack

**Languages:** Java, Python, C/C++, Rust, OCaml, TypeScript, JavaScript, SQL, MIPS Assembly

**ML & Data:** PyTorch, XGBoost, scikit-learn, SHAP, SMOTE, Pandas, OpenAI Fine-Tuning, pgvector Embeddings, Feature Engineering, Model Evaluation, Data Pipelines

**Frontend & Backend:** Next.js 14, React, FastAPI, Node.js, Express, Tailwind CSS, WebSockets, REST APIs, Chrome Extension APIs

**Infrastructure:** Supabase, PostgreSQL, Redis, MongoDB, AWS, Docker, Git, Linux, Cisco Networking

**AI & Integrations:** Claude API, Gemini API, AssemblyAI, OpenAI API, DocuSign, ATTOM Property API, Stripe, Webhooks

---

## Currently

- Scaling Obsidian OS and Pitchline to additional clients
- Cloud Support Intern @ YAS Networks (starting May 2026)
- B.S. Computer Science @ University of Maryland, College Park (Expected May 2027)
- Open to SWE internships and research roles in ML, systems, or full-stack

📬 workanassaj@gmail.com

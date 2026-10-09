# 18-Month ML Engineer Roadmap

**October 2026 → March 2028 · ~16 hours/week · Free-first resources**

> **Goal:** Become a credible candidate for ML, AI, and software internships by showing you can **build, evaluate, deploy, and explain** real systems. Certificates alone don't count.

GSoC selection, internships, and merged PRs are **targets, not promises**.

---

## Contents

1. [At a glance](#at-a-glance)
2. [Start here: your first 7 days](#start-here-your-first-7-days)
3. [How the plan works](#how-the-plan-works)
4. [The six phases](#the-six-phases)
5. [Four-project portfolio](#four-project-portfolio)
6. [Checkpoints](#checkpoints)
7. [Measurable targets](#measurable-targets)
8. [Career and open-source milestones](#career-and-open-source-milestones)
9. [Resources](#resources)
10. [Rules](#rules)

---

## At a glance

| | |
|---|---|
| **Duration** | 78 weeks (Oct 2026 – Mar 2028) |
| **Pace** | 15 h minimum · **16 h target** · 18 h stretch |
| **Starting point** | CS50SQL done · CS50P nearly done · some Python/Flask · hackathon experience · SIH projects (GeM procurement, Watershed Insight) |
| **You finish with** | 4 evaluated portfolio projects, a deployed ML app, a RAG-to-agent system, steady DSA/SQL practice, and a polished GitHub, resume, and LinkedIn |

### Phase overview

| Phase | Months | Theme | Key output |
|---|---|---|---|
| **1. Foundations** | Oct – Dec 2026 | Python, supervised ML, SQL, pandas | **Project 1:** tabular ML (Dec 2026) |
| **2. Applied ML** | Jan – Mar 2027 | Model selection, APIs, deployment, dev workflow | **Project 2:** deployed ML app (Mar 2027) |
| **3. Deep Learning** | Apr – Jun 2027 | PyTorch, neural networks, CNNs | **Project 3:** PyTorch model (Jun 2027) |
| **4. AI Foundations & Algorithms** | Jul – Sep 2027 | Search, uncertainty, DSA interview prep | Documented CS50AI work; mock interviews begin |
| **5. LLMs & RAG** | Oct – Dec 2027 | Transformers, embeddings, retrieval | **Project 4a:** deployed RAG app (Dec 2027) |
| **6. Agents, MLOps & Apps** | Jan – Mar 2028 | LangGraph, Docker, testing, portfolio | **Project 4b:** agent capstone + portfolio (Mar 2028) |

---

## Start here: your first 7 days

- [ ] Finish the remaining CS50P work and check your solutions.
- [ ] Start Andrew Ng's Machine Learning Specialization and schedule your first sessions.
- [ ] Solve 10 SQL problems and review your mistakes.
- [ ] Clean up one GitHub repository (README, folder structure, requirements file).
- [ ] Block your 16 weekly hours around college and other commitments.
- [ ] Create a simple tracker for learning, DSA, projects, and applications.
- [ ] Pick two possible GSoC organizations and read their contribution guides.

**Until November, focus only on:** CS50P, Andrew Ng, and your existing DSA practice. Don't start every resource in this document.

---

## How the plan works

### Weekly schedule

| Activity | 15 h | **16 h** | 18 h |
|---|---:|---:|---:|
| Projects and implementation | 5 | **5** | 6 |
| Main learning track | 3 | **4** | 4 |
| DSA and problem solving | 3 | **3** | 4 |
| Math, statistics, and SQL | 2 | **2** | 2 |
| Testing, documentation, and review | 1 | **1** | 1 |
| Open source and career prep | 1 | **1** | 1 |
| **Total** | **15** | **16** | **18** |

**Example 16-hour week**

| Day | Study |
|---|---|
| Mon | Main course 2 h (1 h course + 1 h DSA) |
| Tue | Project 2 h |
| Wed | DSA 1 h + math/stats 1 h |
| Thu | Main course 1 h + project 1 h |
| Fri | Project 2 h + testing/docs 1 h |
| Sat | DSA 1 h + open source/career 1 h |
| Sun | Main course 2 h + math/stats 1 h |

Use **18 hours** only when college and sleep allow. Drop to **15** in lighter weeks.

### Sunday review (15 minutes)

1. What did I **build or solve independently** this week?
2. What concept can I explain without notes?
3. What is blocked, and what is the smallest next step?
4. Which **one** task matters most next week?
5. Did the plan fit around college and sleep?

### Before starting any new course

Only add a course if **all three** are true:
1. It fills a **named gap** in the current phase.
2. You know the **exact module** you need.
3. You will apply it to a project or problem **within two weeks**.

If any answer is no, save the link for later.

### When life gets busy

| Situation | What to do |
|---|---|
| Exams, SIH, or hackathons | Drop to **3–8 hours/week**. Don't create a backlog. |
| Minimum viable week | Keep one DSA session, one course session, and one project session. |
| Project running late | **Cut scope**, not testing, evaluation, or documentation. |
| Three weeks in a row behind | Drop to **10 hours/week** for a while, then rebuild. |
| Heavy exam month (e.g., May/June, December) | Treat it as lighter. Move milestones instead of catching up. |
| Quarter-end weeks (Dec, Mar, Jun, Sep) | Use as buffer for catch-up, polish, or rest. |

**Learning rule:** Watching a lecture is progress, but a phase is complete only when its **required output** exists.

**Track rule:** Run **one main course + one project** at a time, plus DSA. Don't run several courses in parallel.

**Language rule:** Python is the default for DSA unless your placement requirements need C++.

---

## The six phases

Each phase lists its goal, core resources, optional extras, and a monthly checklist. Tick the items as you finish them.

---

### Phase 1 — Foundations
**October – December 2026**

**Goal:** Build Python fluency, learn supervised ML, and refresh SQL, NumPy, pandas, and basic statistics.

**Core resources**
- [CS50P](https://cs50.harvard.edu/python/) — finish Python foundations
- [Andrew Ng's ML Specialization](https://www.deeplearning.ai/specializations/machine-learning/) — your main ML course
- [scikit-learn Getting Started](https://scikit-learn.org/stable/getting_started.html)

**Optional extras (pick at most one or two)**
- [Tech With Tim — Learn Python With This ONE Project!](https://www.youtube.com/@TechWithTim) — a guided first project
- [freeCodeCamp — 20 Beginner Python Projects](https://www.youtube.com/@freecodecamp) — choose 3–5, not all
- [Karina Data Scientist — Clean Data in Minutes with Python](https://www.youtube.com/@KarinaDataScientist) — practical data cleaning
- [UCB CS70: Discrete Math and Probability](https://csdiy.wiki/数学进阶/CS70/) — probability and discrete math with algorithmic applications (~60 h)

**Monthly checklist**
- [ ] **Oct 2026** — Finish CS50P. Start Ng's course. Clean up GitHub. Solve 20 SQL problems. Pick a small Python project.
- [ ] **Nov 2026** — Study regression, classification, and gradient descent. Practice NumPy and pandas. Start Project 1. Read two GSoC organization guides. Make one useful open-source interaction (an issue comment or question).
- [ ] **Dec 2026** — **Finish Project 1** (see [Portfolio](#four-project-portfolio)). Reach 75 cumulative SQL problems. Protect exam time.

**Milestone:** CS50P complete, Ng's course underway, a baseline tabular ML project with honest evaluation.

---

### Phase 2 — Applied ML
**January – March 2027**

**Goal:** Move from notebooks to tested, deployable applications. Learn model selection, cross-validation, leakage prevention, Flask/FastAPI, Git workflow, Linux, virtual environments, and experiment tracking.

**Core resources**
- [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)
- [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course/) — selected modules when needed
- [Flask documentation](https://flask.palletsprojects.com/)

**Optional extras**
- [freeCodeCamp — Python API Development](https://www.youtube.com/@freecodecamp) — FastAPI, Pydantic, and database integration
- [CS229: Machine Learning (Stanford)](https://csdiy.wiki/机器学习/CS229/) — math-heavy ML, ~100 h. **Only if you want algorithm internals.**
- [CMU 15-445: Database Systems](https://csdiy.wiki/数据库系统/15445/) — database internals, ~100 h, needs C++. **Only if you want deep backend work.**

**Monthly checklist**
- [ ] **Jan 2027** — Study ensembles, cross-validation, leakage, and tuning. Start Project 2. Begin timed DSA practice. Attempt a first small open-source PR.
- [ ] **Feb 2027** — Build a Flask/FastAPI interface and add tests. Learn Git branches, PRs, Linux, and virtual environments. Draft your resume. Reach 100 cumulative SQL problems.
- [ ] **Mar 2027** — Finish Ng's course. **Deploy Project 2.** Add a dashboard (Plotly, Streamlit, Power BI, or Tableau) and a 20-minute walkthrough to Project 1 or 2. Check official GSoC dates.

**Choose one experiment tracker:** MLflow or Weights & Biases.

**Milestone:** Ng's course complete. Project 2 is tested, documented, and deployed.

**Career note:** Summer 2027 is a stretch. Prepare for stronger applications in summer 2028. If no internship comes, use the break for a small project, a hackathon, or a meaningful open-source contribution.

---

### Phase 3 — Deep Learning
**April – June 2027**

**Goal:** Understand tensors, autograd, training loops, optimizers, and regularization, then train a CNN or text classifier.

**Core resources**
- [Official PyTorch Tutorials](https://pytorch.org/tutorials/) — your main implementation track
- [fast.ai](https://course.fast.ai/) — practical, project-first deep learning

**Optional extras**
- [Karpathy — Neural Networks: Zero to Hero](https://www.youtube.com/@AndrejKarpathy) — build networks by hand
- Selected lectures from [MIT 6.S191](https://introtodeeplearning.com/)
- [CS231n: CNNs for Visual Recognition (Stanford)](https://csdiy.wiki/深度学习/CS231/) — ~80 h. **Good companion if Project 3 is image-based.**

**Monthly checklist**
- [ ] **Apr 2027** — Learn tensors, autograd, `nn.Module`, and training loops. Train a small network independently. Start Project 3. Submit GSoC if applying.
- [ ] **May 2027** — Study optimizers, regularization, and CNNs or text classification. Build a baseline and log experiments.
- [ ] **Jun 2027** — **Finish Project 3.** Compare results, inspect errors, and document reproducibility.

**Milestone:** A PyTorch project with a reproducible training process, evaluation, and a short technical write-up.

**Notes**
- Andrew Ng's *Machine Learning* Specialization is different from his *Deep Learning* Specialization. The Deep Learning Specialization is optional and has historically used TensorFlow, so check its current syllabus before starting.
- **Compute:** Use Google Colab or Kaggle for free GPU access. Save checkpoints. Keep datasets small enough to reproduce. Don't make paid GPUs or paid APIs a requirement.

---

### Phase 4 — AI Foundations & Algorithms
**July – September 2027**

**Goal:** Learn search, knowledge representation, probabilistic reasoning, and optimization. Build DSA interview fluency.

**Core resources**
- [Harvard CS50AI](https://cs50.harvard.edu/ai/) — **priority topics only:** search, knowledge representation, uncertainty, and optimization. Skip or skim ML and neural-network sections that duplicate Ng and PyTorch.
- [CS61B: Data Structures and Algorithms (UC Berkeley)](https://csdiy.wiki/数据结构与算法/CS61B/) — structured DSA backbone (~60 h, Java, labs and projects)

**Optional extras**
- [MIT 6.006: Introduction to Algorithms](https://csdiy.wiki/数据结构与算法/6.006/) — Python-friendly alternative to CS61B
- [CS285: Deep Reinforcement Learning (UC Berkeley)](https://rail.eecs.berkeley.edu/deeprlcourse/) — only if you develop a specific RL interest. **Not required for target roles.**

**Monthly checklist**
- [ ] **Jul 2027** — CS50AI search and knowledge representation. Probability and statistics review. Continue DSA.
- [ ] **Aug 2027** — CS50AI uncertainty and optimization. Practice Python fluency (generators, decorators). Add tests to existing repos.
- [ ] **Sep 2027** — Finish selected CS50AI projects. Write up a documented technical contribution. **Start mock interviews.**

**Milestone:** Clean CS50AI repos, a documented contribution, and the first mock interviews.

**Rule:** Continuous DSA practice matters more than finishing another course. Roughgarden's algorithms course and CS229 stay optional unless you're clearly ahead.

---

### Phase 5 — LLMs & RAG
**October – December 2027**

**Goal:** Understand tokenization, embeddings, transformers, and pretrained models. Build retrieval-augmented generation (RAG) that gives grounded, sourced answers and is **measured**.

**Core resources**
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course)
- [LangChain Learning Resources](https://docs.langchain.com/oss/python/learn) — used after building RAG from scratch
- [pguso/rag-from-scratch](https://github.com/pguso/rag-from-scratch) — step-by-step RAG with no black boxes

**Optional extras**
- [LLM Zoomcamp](https://github.com/DataTalksClub/llm-zoomcamp) — project-first RAG path
- Selected lectures from [Stanford CS224N](https://web.stanford.edu/class/cs224n/) (~80–100 h for the full course)
- Relevant [DeepLearning.AI short courses](https://www.deeplearning.ai/short-courses/) — only when they directly support your project
- [Karpathy — Let's reproduce GPT-2 (124M)](https://www.youtube.com/@AndrejKarpathy) — **advanced; watch last**
- [CS336: Language Modeling from Scratch](https://csdiy.wiki/深度生成模型/roadmap/) — advanced LLM internals (~100 h+)
- [MIT 6.S184: Flow Matching and Diffusion](https://csdiy.wiki/深度生成模型/MIT6.S184/) — **only if you're interested in diffusion models**

**Monthly checklist**
- [ ] **Oct 2027** — Study transformers, tokenization, embeddings, and pretrained models. Run a small LLM experiment and explain the pipeline in writing.
- [ ] **Nov 2027** — Build raw RAG: parsing, chunking, embeddings, retrieval, grounded answers. Create your evaluation set. Reach 150 cumulative SQL problems.
- [ ] **Dec 2027** — Add LangChain where it helps. Add tests, an API/UI, and deployment. **Finish Project 4a.**

**Milestone:** A deployed RAG app with source citations and measured retrieval quality.

**RAG evaluation standard**
- Write **30–50 questions**, each paired with the expected source document or passage.
- Report a **retrieval hit rate**: how often the expected source appears in the top results.
- Inspect **answer faithfulness and relevance** by hand, and log failure cases.
- RAGAS can be added later, but it doesn't replace understanding your test set.
- A working chatbot alone does not count as a complete RAG project.

**Compute:** Prefer small open-weight models, local inference with [Ollama](https://ollama.com/) when your hardware allows, or free-tier services. Plan a fallback so API limits or GPU shortages don't block you. **Never commit API keys.**

---

### Phase 6 — Agents, MLOps & Applications
**January – March 2028**

**Goal:** Turn the RAG app into a tested, documented, observable agent system, then polish the whole portfolio.

**Core resources**
- [LangChain / LangGraph Documentation](https://docs.langchain.com/oss/python/learn) — state, nodes, edges, conditional routing, tool calls
- [Docker — Get Started](https://docs.docker.com/get-started/)
- [Made With ML](https://madewithml.com/) — testing, deployment, and monitoring

**Optional extras**
- [MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp)
- [FastAPI Tutorial](https://fastapi.tiangolo.com/tutorial/)
- [Full Stack Open](https://csdiy.wiki/Web开发/fullstackopen/) — React, Node.js, GraphQL. **For a full-stack agent interface.**
- [Kun Chen — Building a Full Stack App with Agentic Engineering](https://www.youtube.com/@KunChen) — full-stack agentic reference
- Optional big capstone: **Autonomous Research Assistant** (React + FastAPI + PostgreSQL + LLM). Only if you have time after the core agent works.

**Monthly checklist**
- [ ] **Jan 2028** — Learn LangGraph basics. Build a small stateful agent with limited, well-defined tools. Learn Docker basics.
- [ ] **Feb 2028** — Upgrade RAG into an agent. Add tests, logging, and basic monitoring. Document architecture and evaluation. Reach 10 cumulative mock interviews.
- [ ] **Mar 2028** — **Finish Project 4b.** Polish all four projects. Revise Python, ML, SQL, and DSA. Update your resume and tracker. Apply for summer 2028 internships.

**Milestone:** A tested, documented agent capstone and a polished portfolio.

**Agent rules**
- A reliable, evaluated agent beats a complicated multi-agent system.
- Restrict tool access and require human approval for actions with real consequences.

**If you consistently hit 18 hours:** Move the LangGraph capstone into December 2027. Use January–March for open source, interview prep, or optional depth. Don't add new courses.

---

## Four-project portfolio

Existing SIH projects can count if they meet the same standard. Don't create extra projects just to hit a number.

| # | Project | Due | What it proves |
|---|---|---|---|
| **1** | **Tabular ML** | Dec 2026 | Baseline vs improved model, correct metrics, error analysis |
| **2** | **Deployed ML app** | Mar 2027 | Serving predictions via Flask/FastAPI, validation, tests, dashboard, walkthrough |
| **3** | **PyTorch model** | Jun 2027 | Training from scratch, reproducibility, technical write-up |
| **4** | **RAG → agent** | Dec 2027 – Mar 2028 | Retrieval evaluation, source citations, tool-using agent, tests, Docker |

### Project 1 — Tabular ML
Train a baseline and an improved model. Include data preparation, appropriate metrics, error analysis, and limitations.

### Project 2 — Deployed ML app
Serve predictions through Flask or FastAPI with validation, tests, setup instructions, and a demo. Add a compact analytics dashboard (Plotly, Streamlit, Power BI, or Tableau) and a **20-minute walkthrough** covering the question, data, key insights, caveats, and the decisions a stakeholder could make. This also supports data analyst applications.
*Optional idea:* a customer segmentation pipeline served as a FastAPI endpoint.

### Project 3 — PyTorch deep learning
Train and evaluate a neural network, compare it with a sensible baseline, and document reproducibility. Choose image classification if you want to pair it with CS231n.

### Project 4 — RAG upgraded into an agent
Build retrieval from first principles, measure retrieval and answer quality, and add sources. Then add an agent workflow, tests, logging, and Docker.
*Optional idea:* a modified GPT-2 (changed positional encoding or learning-rate schedule), trained on a small dataset with a write-up. Only after Karpathy's Zero to Hero, and only if you want deeper transformer internals.

### Choosing a SIH project
Pick the SIH project where you can:
- explain the problem, your own contribution, the data pipeline, the evaluation, and the limitations;
- reproduce it and demo it reliably.

A large team project isn't automatically a strong individual piece. Clearly document what **you** designed, implemented, tested, and maintained.

### Every core project should have
- [ ] A clearly stated problem and data source
- [ ] A baseline and an appropriate evaluation method
- [ ] Train/validation/test separation with no data leakage
- [ ] Error analysis and honest limitations
- [ ] Reproducible setup instructions and tests
- [ ] A working demo, or screenshots if deployment isn't practical
- [ ] A README and short technical write-up
- [ ] A clear note on your individual contribution

**Visibility:** Publish one concise write-up per project (README plus a LinkedIn post or blog). By March 2028, have a simple portfolio page linking to demos, repos, and write-ups.

---

## Checkpoints

Use these to adjust scope. Don't silently carry unfinished work forward. Quarter-end weeks are buffers, not extra deadlines.

| By | Check | If not met |
|---|---|---|
| **Dec 2026** | Project 1 complete; Ng's course at least halfway | Drop optional reading. Protect the main course and Project 1. |
| **Mar 2027** | Ng's course complete; Project 2 deployed with dashboard | Delay PyTorch up to a month. Don't skip evaluation or tests. |
| **Jun 2027** | Project 3 complete and reproducible | Reduce CS50AI scope in Phase 4. Keep DSA steady. |
| **Sep 2027** | CS50AI work documented; mock interviews and DSA review started | Narrow CS50AI to priority topics. Start mock interviews now. |
| **Dec 2027** | RAG deployed with a 30–50-question evaluation set | Keep the agent simple. Protect tests and RAG evaluation. |
| **Mar 2028** | Portfolio page, resume, tracker, and agent capstone ready | Prioritize reliable demos, clear explanations, and applications. |

---

## Measurable targets

| Area | Target by March 2028 |
|---|---|
| **Projects** | 4 evaluated projects (tabular ML, deployed ML app, PyTorch model, RAG → agent) |
| **DSA** | 300+ independently solved problems, tracked by topic and explanation quality |
| **SQL** | 150+ problems: joins, aggregation, subqueries, CTEs, window functions |
| **Open source** | 2–4 substantive PR attempts; at least one merged or meaningfully reviewed |
| **Mock interviews** | 10+, starting September 2027 |
| **Deployment** | Deployed RAG app with retrieval evaluation; agent with tests, logging, Docker |
| **GitHub** | Clean repos with README, tests, and reproducible setup |
| **Career** | Updated resume, LinkedIn, portfolio page, application tracker, one write-up per project |

**Two tiers of success**
- **Core:** 3–4 strong projects you can explain and reproduce, steady DSA/SQL, at least one real contribution attempt, and clear write-ups.
- **Stretch:** 300+ DSA problems, 150+ SQL problems, multiple substantive PRs, and 10+ mock interviews.

If college or SIH makes the stretch numbers unrealistic, protect project quality and interview-level understanding instead.

---

## Career and open-source milestones

| Period | Focus |
|---|---|
| **Oct – Dec 2026** | Improve GitHub. Explore relevant repositories. Learn the contribution workflow. |
| **Jan – Mar 2027** | Build your resume. Practice applications. Attempt a first PR. |
| **Apr – Sep 2027** | Improve project quality, interview skills, and contribution depth. |
| **Oct – Dec 2027** | Show LLM/RAG ability through a tested, evaluated project. |
| **Jan – Mar 2028** | Polish the portfolio. Target summer 2028 internships. |

**About GSoC:** Selection isn't guaranteed. If you're not selected, the same work still counts: reading a real codebase, communicating with maintainers, reviewing code, and making useful contributions.

**Don't wait:** You don't need to finish all 18 months before applying.

---

## Resources

Links are references. Course versions and enrollment options may change, so check them before you start.

### Core (use these)

| Resource | Phase | Purpose |
|---|---|---|
| [CS50P](https://cs50.harvard.edu/python/) | 1 | Python foundations |
| [Andrew Ng — ML Specialization](https://www.deeplearning.ai/specializations/machine-learning/) | 1–2 | Primary ML course (the spine of the plan) |
| [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html) | 1–2 | Classical ML reference |
| [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course/) | 2 | Specific modules when needed |
| [Flask docs](https://flask.palletsprojects.com/) | 2 | Web APIs |
| [PyTorch Tutorials](https://pytorch.org/tutorials/) | 3 | Main deep-learning implementation |
| [fast.ai](https://course.fast.ai/) | 3 | Practical deep learning |
| [Harvard CS50AI](https://cs50.harvard.edu/ai/) | 4 | Search, uncertainty, optimization (priority topics) |
| [CS61B (CSDIY)](https://csdiy.wiki/数据结构与算法/CS61B/) | 4 | Structured DSA course |
| [Hugging Face LLM Course](https://huggingface.co/learn/llm-course) | 5 | Transformers, tokenizers, and pretrained models |
| [LangChain / LangGraph docs](https://docs.langchain.com/oss/python/learn) | 5–6 | RAG and agent tooling |
| [pguso/rag-from-scratch](https://github.com/pguso/rag-from-scratch) | 5 | Build RAG step by step |
| [Docker — Get Started](https://docs.docker.com/get-started/) | 6 | Containers |
| [Made With ML](https://madewithml.com/) | 6 | Testing, deployment, monitoring |

### Practice

| Resource | Purpose |
|---|---|
| [SQLBolt](https://sqlbolt.com/) | SQL fundamentals refresh |
| [LeetCode SQL 50](https://leetcode.com/studyplan/top-sql-50/) | Structured SQL practice |
| [NeetCode](https://neetcode.io/) | Interview patterns, after you learn the fundamentals |
| [Kaggle Learn](https://www.kaggle.com/learn) | Short pandas and intro-to-ML exercises |
| [GitHub Skills](https://skills.github.com/) | Git and PR workflows |

**DSA rule:** Attempt each problem before reading a solution. After reading one, close it and rewrite it from memory. Track patterns and mistakes, not just the count.

**DSA topic sequence (a guide, adjust to your CampusX DSA course)**

| Quarter | Topics |
|---|---|
| Q4 2026 | Time complexity, arrays, strings, hashing, two pointers, basic sorting and searching |
| Q1 2027 | Recursion, stacks, queues, linked lists, binary search, basic trees |
| Q2 2027 | Trees, BSTs, heaps and priority queues, traversals |
| Q3 2027 | Graphs (BFS/DFS), heap review, intro dynamic programming |
| Q4 2027 | Mixed practice, sliding window, intervals, greedy, graphs, basic DP |
| Q1 2028 | Timed mixed sets, weak-topic revision, interview-style explanations |

**Choose one DSA course plus independent problem solving.** Use [CampusX DSA](https://www.youtube.com/watch?v=f9Aje_cN_CY) if that's your current course. Don't turn DSA into a playlist collection.

### Mathematics and statistics (~2 hours/week)

| Period | Focus | Resource |
|---|---|---|
| Oct – Dec 2026 | Vectors, matrices, derivatives, basic probability | [Khan Academy](https://www.khanacademy.org/math), [3Blue1Brown](https://www.3blue1brown.com/topics/linear-algebra) |
| Oct – Dec 2026 | Discrete math and probability | [CS70 (CSDIY)](https://csdiy.wiki/数学进阶/CS70/) |
| Jan – Mar 2027 | Linear algebra and statistics for evaluation and validation metrics | [MIT 18.06](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) (selected lectures) |
| Apr – Jun 2027 | Chain rule and gradients for backpropagation | Trace gradients by hand in a small network |
| Jul – Sep 2027 | Conditional probability and Bayes (aligned with CS50AI uncertainty) | [Harvard Stat 110](https://stat110.hsites.harvard.edu/youtube) |
| Oct – Dec 2027 | Dot products, cosine similarity, nearest neighbors (for embeddings) | Your RAG project |
| Jan – Mar 2028 | Only the math that blocks your agent project or interview explanations | As needed |

**Reference only:** [MIT 18.065](https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/) (later, for deeper matrix methods) · MIT 18.650 (statistics) · MIT RES.6-012 (probability), via [MIT OCW](https://ocw.mit.edu/)

Study only lessons that address a current gap. Don't try to finish full university courses.

### Optional course catalog (CSDIY)

[CS自学指南 (CSDIY)](https://csdiy.wiki/) is a community-maintained guide with course descriptions, prerequisites, and estimated hours. Use it as a **reference catalog**, not a second roadmap. Pick **one** course for a named gap, and never run several in parallel.

| Course | Phase | Effort | Use when |
|---|---|---|---|
| [CS229 (Stanford)](https://csdiy.wiki/机器学习/CS229/) | 2 | ~100 h | You want algorithm-level ML depth |
| [CMU 15-445 (Databases)](https://csdiy.wiki/数据库系统/15445/) | 2 or 6 | ~100 h | You want database internals (needs C++) |
| [CS231n (Stanford)](https://csdiy.wiki/深度学习/CS231/) | 3 | ~80 h | Project 3 is image-based |
| [CS285 (Berkeley RL)](https://rail.eecs.berkeley.edu/deeprlcourse/) | Optional | ~100 h | You develop a specific RL interest |
| [CS224n (Stanford NLP)](https://web.stanford.edu/class/cs224n/) | 5 | ~80–100 h | Transformers and NLP depth (selected lectures) |
| [CS336 (Stanford LLMs)](https://csdiy.wiki/深度生成模型/roadmap/) | 5 | ~100 h+ | You want to write LLM training code yourself |
| [MIT 6.S184 (Diffusion)](https://csdiy.wiki/深度生成模型/MIT6.S184/) | 5 | ~60 h | You're interested in diffusion models |
| [MIT 6.006 (Algorithms)](https://csdiy.wiki/数据结构与算法/6.006/) | 4 | ~60 h | You prefer a Python-friendly algorithms course |
| [Full Stack Open](https://csdiy.wiki/Web开发/fullstackopen/) | 6 | ~100 h | You want a React/Node.js interface for the agent |

### Structured playlist (supplementary only)

[MASTER ROADMAP 2026–2027: Python Depth → Agentic AI](https://youtube.com/playlist?list=PLYMLIfEYAPgM) by Yogesh Kumar Singh is a faster-paced sequencing guide. **Don't watch it in upload order.** Use it to find project ideas and resources. Its main resources are already included above.

### Other supplements (use only for a specific gap)
- [CampusX — 100 Days of ML](https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH) — Hindi/English explanations
- [StatQuest](https://www.youtube.com/@statquest) — short statistics and ML explanations
- [freeCodeCamp](https://www.youtube.com/@freecodecamp) — API development and Python projects
- [Stanford Algorithms (Roughgarden)](https://www.coursera.org/learn/algorithms-part1) — optional, only if DSA is stable
- [Fluent Python](https://www.oreilly.com/library/view/fluent-python-2nd/9781492056348/) — reference for idiomatic Python
- [MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp) — deployment practice

---

## Rules

1. **No third major track.** One main course plus one project at a time, plus DSA.
2. **Protect college and sleep.** Exam and SIH weeks drop to 3–8 hours. No backlog.
3. **Keep DSA regular.** 3–4 hours a week, in shorter sessions on busy days.
4. **Cut scope, not quality.** Remove features before you remove tests, evaluation, or documentation.
5. **Start open source early.** Read repositories from November 2026.
6. **Start mock interviews in September 2027.** Don't wait until the last month.
7. **Reset if unsustainable.** Three weeks behind → drop to 10 hours and rebuild.
8. **Apply on evidence.** You don't need to finish 18 months before applying.

---

## Total effort

| Pace | Total over 78 weeks |
|---:|---:|
| 15 h/week | 1,170 h |
| 16 h/week | 1,248 h |
| 18 h/week | 1,404 h |

Real totals will be lower after exams, illness, and breaks. Plan for lighter weeks instead of perfect attendance.

---

*No plan can guarantee GSoC selection, an internship, or a top-10% ranking. This plan gives you real work and technical evidence to compete with.*

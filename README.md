# 18-Month ML Engineer Roadmap

### October 2026 – March 2028 · 16 hours/week baseline · Free-first resources

**Pace:** 15h minimum · 16h target · 18h stretch

**Goal by March 2028:** be a credible candidate for ML, AI, and software internships — not by collecting certificates, but by demonstrating that you can build, evaluate, deploy, and explain real systems. GSoC, internships, and merged PRs are targets, not promises.

**Assumptions:** CS50SQL completed, CS50P nearly finished, some Python/Flask and hackathon experience, and existing SIH projects (GeM procurement, Watershed Insight).

---

## Table of Contents

- [What success looks like by March 2028](#what-success-looks-like-by-march-2028)
- [Weekly study schedule](#weekly-study-schedule)
- [The six-phase roadmap](#the-six-phase-roadmap)
  - [Phase 1 — Foundations](#phase-1--foundations)
  - [Phase 2 — Applied ML](#phase-2--applied-ml)
  - [Phase 3 — Deep Learning](#phase-3--deep-learning)
  - [Phase 4 — AI Foundations and Algorithms](#phase-4--ai-foundations-and-algorithms)
  - [Phase 5 — LLMs and RAG](#phase-5--llms-and-rag)
  - [Phase 6 — Agents, MLOps, and Applications](#phase-6--agents-mlops-and-applications)
- [Four-project portfolio](#four-project-portfolio)
- [Resource list by purpose](#resource-list-by-purpose)
- [Quarterly go/no-go checkpoints](#quarterly-go-no-go-checkpoints)
- [Month-by-month execution checklist](#month-by-month-execution-checklist)
- [Measurable targets by March 2028](#measurable-targets-by-march-2028)
- [Career and open-source milestones](#career-and-open-source-milestones)
- [Total effort over 18 months](#total-effort-over-18-months)
- [Your first seven days](#your-first-seven-days)
- [Weekly review and course-entry gates](#weekly-review-and-course-entry-gates)
- [Final rules](#final-rules)

---

## What success looks like by March 2028

- **Four strong portfolio projects**, potentially including improved SIH projects.
- **Practical ML experience** with scikit-learn and PyTorch.
- **A deployed ML application** and a **RAG-to-agent system**.
- **Consistent DSA and SQL practice.**
- **GitHub repositories** with reproducible setup instructions, tests, evaluation, and documentation.
- **Initial open-source contributions** and interview preparation.
- **A polished resume, LinkedIn, GitHub profile, and internship application tracker.**

These are targets, not guarantees. Prioritize demonstrated ability over hitting every numerical milestone.

---

## Weekly study schedule

Use **16 hours per week** as your normal target. Increase to **18 only** when college workload and sleep allow. Drop to **15** on lighter weeks.

| Activity | 15h | 16h | 18h |
|---|---:|---:|---:|
| Projects and implementation | 5 | 5 | 6 |
| Main learning track | 3 | 4 | 4 |
| DSA and problem solving | 3 | 3 | 4 |
| Mathematics, statistics, and SQL | 2 | 2 | 2 |
| Testing, documentation, and review | 1 | 1 | 1 |
| Open source and career preparation | 1 | 1 | 1 |
| **Total** | **15** | **16** | **18** |

**Example 16-hour week**

| Day | Study |
|---|---|
| Monday | Main course 1h + DSA 1h |
| Tuesday | Project work 2h |
| Wednesday | DSA 1h + math/stats 1h |
| Thursday | Main course 1h + project 1h |
| Friday | Project 2h + testing/docs 1h |
| Saturday | DSA 1h + open source/career 1h |
| Sunday | Main course 2h + math/stats 1h |

**Adjustment rules**
- **Use a 15-minute Sunday review, not daily guilt:** record hours completed, what you built or solved, what slipped, the main blocker, and what moves into next week. Choose no more than three priorities for the coming week.
- **Separate learning from output:** watching a lecture or finishing a module is progress, but a phase is only complete when its required output exists.
- **Use a minimum viable week:** when busy, preserve a short DSA session, one main-course session, and one project session rather than trying to catch up on everything.
- During exams or intensive hackathons, reduce extracurricular study to **3–8 hours** and resume afterward. Do not create a backlog.
- If you fall behind for **three consecutive weeks**, temporarily reduce the target to **10 hours** and rebuild consistency.
- If a project is late, **reduce its scope** rather than dropping evaluation, testing, or documentation.
- Maintain **at most two major learning tracks at once, not counting DSA**. In practice, that means **one main course plus one project**; do not run multiple courses in parallel just because they are listed as resources.
- Reserve the **final week of each quarter** (Dec, Mar, Jun, Sep) for catch-up, exam spillover, project polish, or rest. Treat May/June and December as lighter months if they coincide with your college exams; move milestones rather than creating a backlog.
- **Python** is the default DSA language unless your college placement requirements make C++ necessary.
- **Sleep and college come first.**

---

## The six-phase roadmap

### Phase 1 — Foundations

**October–December 2026**

**Focus:** Python, supervised ML, SQL, NumPy, pandas, and basic statistics.

**Main resources:** [CS50P](https://cs50.harvard.edu/python/) · [Andrew Ng's ML Specialization](https://www.deeplearning.ai/specializations/machine-learning/) · [scikit-learn](https://scikit-learn.org/stable/getting_started.html)

**Milestone:** Finish CS50P, begin the ML Specialization, clean up GitHub, and produce a baseline tabular ML project with honest evaluation.

| Month | Focus | Required output |
|---|---|---|
| **Oct 2026** | Finish CS50P. Start Ng ML. Clean GitHub. Review Python and SQL. | CS50P completed. Small independent Python project. 20 SQL problems. |
| **Nov 2026** | Regression, classification, gradient descent. NumPy/Pandas. Data cleaning. Read 2 GSoC orgs. | First Kaggle notebook. 50 cumulative SQL problems. Project 1 started. One useful open-source interaction. |
| **Dec 2026** | Supervised learning, evaluation, statistics basics. Protect exams. | **Project 1 done:** tabular ML with baseline vs improved model, README, limitations, error analysis. 75 cumulative SQL problems. |

---

### Phase 2 — Applied ML

**January–March 2027**

**Focus:** Model selection, ensembles, cross-validation, data leakage, hyperparameter tuning, Flask APIs, testing, deployment, and professional developer workflow: Git branches/commits/PRs, Linux command line, virtual environments, Jupyter notebooks, and basic experiment tracking with either MLflow or Weights & Biases (choose one).

**Main resources:** [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html) · [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course/) · [Flask documentation](https://flask.palletsprojects.com/)

**Milestone:** Finish the ML Specialization and turn a second project into a reproducible, tested application.

| Month | Focus | Required output |
|---|---|---|
| **Jan 2027** | Ensembles, cross-validation, leakage, tuning. Begin timed DSA. | Project 1 error analysis. Project 2 started. First small open-source PR attempt. |
| **Feb 2027** | Unsupervised learning. Flask API + UI. Git/Linux/environment workflow. Resume and LinkedIn. | Project 2 working locally. Resume draft. GSoC proposal outline if relevant. 100 cumulative SQL problems. |
| **Mar 2027** | Finish Ng ML. Test and deploy Project 2. Build a small data-analysis dashboard. Check official GSoC dates. | **Project 2 deployed:** ML app with documented evaluation, tests, and setup instructions. Add a dashboard to Project 1 or 2 using Power BI, Tableau, Plotly, or Streamlit, plus a concise 20-minute walkthrough explaining the insights. Internship applications started as practice. |

**Career note:** Summer 2027 is a stretch; prepare for stronger summer 2028 applications. If no internship arrives, use the break for a small remote/local project, a focused hackathon, or a meaningful open-source contribution — ideally work that strengthens an existing portfolio project.

---

### Phase 3 — Deep Learning

**April–June 2027**

**Focus:** Tensors, autograd, neural networks, training loops, optimizers, regularization, and a CNN or text classifier.

**Main resources:** [Official PyTorch tutorials](https://pytorch.org/tutorials/) · [fast.ai](https://course.fast.ai/)

**Supplements:** [Karpathy's Neural Networks: Zero to Hero](https://www.youtube.com/@AndrejKarpathy) · selected [MIT 6.S191](https://introtodeeplearning.com/) lectures

**Milestone:** Finish a PyTorch project with a reproducible training process, evaluation, and a technical write-up.

| Month | Focus | Required output |
|---|---|---|
| **Apr 2027** | PyTorch tensors, autograd, modules, training loops. GSoC submission if going for it. | Small neural network trained and evaluated independently. Project 3 started. |
| **May 2027** | Optimizers, regularization, CNNs or text classification. | Prototype with a baseline and documented experiments. |
| **Jun 2027** | Finish Project 3. Compare results. Inspect errors. Document reproducibility. | **Project 3 done:** PyTorch project with reproducible evaluation report and short technical write-up. |

**Course clarification:** Andrew Ng's Machine Learning Specialization is separate from the Deep Learning Specialization. Keep the Deep Learning Specialization optional and **check its current syllabus and framework** before committing. PyTorch remains your main implementation track; do not add another course unless it fills a specific gap.

**Compute note:** use Google Colab or Kaggle notebooks for occasional free GPU access where available. Save checkpoints, keep datasets small enough to reproduce, and do not make a paid GPU or paid API a requirement for finishing the project.

---

### Phase 4 — AI Foundations and Algorithms

**July–September 2027**

**Focus:** Search, knowledge representation, uncertainty, optimization, probability, and DSA interview patterns.

**Main resource:** [Harvard CS50AI](https://cs50.harvard.edu/ai/) — using selected topics and their associated projects.

**Supplement:** [MIT 6.006](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) for algorithm reasoning when needed.

**Milestone:** Complete selected AI projects, revise DSA, begin mock interviews, and pursue meaningful open-source contributions.

| Month | Focus | Required output |
|---|---|---|
| **Jul 2027** | CS50AI search and knowledge representation. Probability and statistics. Continued DSA. | 1–2 completed CS50AI projects. |
| **Aug 2027** | CS50AI uncertainty and optimization. Fluent Python: generators, decorators. | Additional CS50AI projects with tests and explanations. |
| **Sep 2027** | Finish selected CS50AI. Interview-style DSA. Write up OSS/hackathon/internship work. Begin mock interviews. | Clean CS50AI repos. Documented technical contribution. First mock interviews. |

**CS50AI rule:** prioritize search, knowledge representation, uncertainty, and optimization. Skip or skim ML and neural-network sections that duplicate Ng/PyTorch.

**Roughgarden / CS229:** optional only if clearly ahead. Continuous DSA practice matters more than completing another course.

---

### Phase 5 — LLMs and RAG

**October–December 2027**

**Focus:** Tokenization, embeddings, transformers, pretrained models, retrieval, chunking, and grounded answers.

**Main resources:** [Hugging Face LLM Course](https://huggingface.co/learn/llm-course) · [LangChain learning resources](https://docs.langchain.com/oss/python/learn)

**Supplements:** Selected [Stanford CS224N](https://web.stanford.edu/class/cs224n/) lectures · [LLM Zoomcamp](https://github.com/DataTalksClub/llm-zoomcamp) · relevant [DeepLearning.AI short courses](https://www.deeplearning.ai/short-courses/) · [pguso/rag-from-scratch](https://github.com/pguso/rag-from-scratch)

**Milestone:** Build Project 4 — a RAG application with source citations, a test dataset, retrieval evaluation, and a deployed interface.

| Month | Focus | Required output |
|---|---|---|
| **Oct 2027** | Transformers, tokenization, embeddings, pretrained models, basic LLM inference. | Small LLM experiment with written explanation of the pipeline. |
| **Nov 2027** | Build RAG from scratch: parsing, chunking, embeddings, retrieval, grounded answers. Then explore LangChain. | Raw RAG pipeline + initial evaluation set. 150 cumulative SQL problems. |
| **Dec 2027** | Rebuild with LangChain where helpful. Add tests, Flask/FastAPI interface, deployment, evaluation. | **Project 4 done:** deployed RAG app with source references and measured retrieval quality. |

**RAG standard:** measure retrieval and answer quality. Start with a hand-built set of **30–50 questions**, each paired with expected source documents or passages. Report a simple retrieval hit rate (whether an expected source appears in the retrieved results), inspect answer faithfulness/relevance, and log failure cases. A framework such as RAGAS can be added later; it is not a substitute for understanding your test set. A working chatbot alone does not count as a complete RAG project.

**Compute and cost note:** prefer small open-weight models, local inference with [Ollama](https://ollama.com/) where your hardware supports it, or free-tier notebooks/services where available. Design a fallback path so API credits, rate limits, or a GPU shortage do not block the project. Never commit API keys to GitHub.

---

### Phase 6 — Agents, MLOps, and Applications

**January–March 2028**

**Focus:** LangGraph state and routing, tool calling, Docker, logging, testing, monitoring, and deployment.

**Main resources:** [LangChain/LangGraph documentation](https://docs.langchain.com/oss/python/learn) · [Docker Get Started](https://docs.docker.com/get-started/) · [Made With ML](https://madewithml.com/)

**Supplement:** [MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp) · [FastAPI tutorial](https://fastapi.tiangolo.com/tutorial/)

**Milestone:** Upgrade the RAG app into a tested, documented agentic system; polish your portfolio and apply for summer 2028 internships.

| Month | Focus | Required output |
|---|---|---|
| **Jan 2028** | LangGraph state, nodes, edges, conditional routing, tool calls. Docker basics. | Small stateful agent with limited, well-defined tools. |
| **Feb 2028** | Upgrade RAG into an agent. Tests, logging, monitoring, basic MLOps. | Tested agent capstone with documented architecture and evaluation. 10+ cumulative mock interviews. |
| **Mar 2028** | Polish portfolio. Revise ML, SQL, Python, DSA. Continue mock interviews. Apply for summer 2028 internships. Consider GSoC 2028. | Final portfolio, updated resume, application tracker. |

**Agent capstone rule:** a reliable, evaluated agent beats a complicated multi-agent system. Add human approval or restricted tool access where actions have meaningful consequences.

**If you consistently hit 18 hours:** pull the LangGraph capstone into December 2027 and use January–March for open source, interview prep, or optional advanced study — not for adding courses.

---

## Four-project portfolio

The four projects do not need to be completely new. A substantial SIH project can count if it meets the same quality standard.

### Project 1 — Tabular ML
**Target: December 2026**

Train a baseline and an improved model. Include data preparation, appropriate metrics, error analysis, and limitations.

### Project 2 — Deployed ML application
**Target: March 2027**

Serve predictions through Flask or FastAPI with validation, tests, setup instructions, and a demo. Add a compact analytics dashboard to Project 1 or Project 2 using Power BI, Tableau, Plotly, or Streamlit. Include a roughly 20-minute walkthrough explaining the question, data, key insights, caveats, and decisions a stakeholder could make. This provides a credible stepping stone for data analyst internships as well as ML roles.

### Project 3 — PyTorch deep learning
**Target: June 2027**

Train and evaluate a neural network, compare against a sensible baseline, and document reproducibility.

### Project 4 — RAG application upgraded into an agent
**Target: December 2027 – March 2028**

Build retrieval from first principles, measure retrieval and answer quality, add sources, then introduce agent workflows, tests, logging, and Docker.

**SIH rule:** your GeM procurement project or Watershed Insight can replace a project slot if you improve it to the required standard. Don't create extra projects just to reach a count.

**How to choose which SIH project counts:** choose the project where you can personally explain the problem, your own contribution, the data pipeline, the evaluation method, and the limitations. Prefer the one you can make reproducible and demo reliably. A large team project is not automatically a strong individual portfolio piece; clearly document which parts you designed, implemented, tested, and maintained.

**Visibility rule:** publish one concise technical write-up per project (the README plus a LinkedIn post or blog explaining the problem, your contribution, results, and limitations). By March 2028, make a simple portfolio page that links to the demos, repositories, and write-ups.

**For every core project, aim for:**
- A clearly stated problem and data source.
- A baseline and an appropriate evaluation method.
- Train/validation/test separation where applicable, without data leakage.
- Error analysis and honest limitations.
- Reproducible setup instructions and tests.
- A working demo or deployment where practical.
- A clear README and short technical write-up.

---

## Resource list by purpose

Links are provided as references, not as a claim that every course version or enrollment option has been checked live.

### Python, ML, and data

| Resource | How to use it |
|---|---|
| [CS50P](https://cs50.harvard.edu/python/) | Finish your Python foundation. |
| [Andrew Ng ML Specialization](https://www.deeplearning.ai/specializations/machine-learning/) | Your primary ML course. |
| [CampusX 100 Days of ML](https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH) | Hindi/English explanations for concepts that need another pass. |
| [StatQuest](https://www.youtube.com/@statquest) | Short explanations of statistics and ML concepts. |
| [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course/) | Selected modules and exercises when you need practice. |
| [Kaggle Learn](https://www.kaggle.com/learn) | Short Pandas and Intro to ML exercises. |
| [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html) | Your implementation reference for classical ML. |

**ML resource rule:** Andrew Ng remains the spine. Use CampusX, StatQuest, or Google ML Crash Course only for a specific concept you cannot explain or implement yet; do not complete all of them in parallel.

### SQL and DSA

| Resource | How to use it |
|---|---|
| [SQLBolt](https://sqlbolt.com/) | Refresh SQL fundamentals. |
| [LeetCode SQL 50](https://leetcode.com/studyplan/top-sql-50/) | Structured SQL practice. |
| [CampusX DSA](https://www.youtube.com/watch?v=f9Aje_cN_CY) | Continue your current DSA course. |
| [NeetCode](https://neetcode.io/) | Practice interview patterns after learning the fundamentals. |
| [GitHub Skills](https://skills.github.com/) | Learn GitHub workflows and pull requests. |
| [Fluent Python](https://www.oreilly.com/library/view/fluent-python-2nd/9781492056348/) | Optional reference for generators, decorators, and idiomatic Python; use selected topics rather than reading the whole book on schedule. |

Choose **one DSA course plus independent problem solving**. Don't turn DSA into another collection of playlists.

**Problem-solving rule:** attempt each problem before viewing a solution; after reading one, close it and reimplement from memory. Track patterns and mistakes, not only the total solved count.

**DSA topic sequence**
- **Q4 2026 (Oct–Dec):** time complexity, arrays, strings, hashing, two pointers, and basic sorting/searching.
- **Q1 2027 (Jan–Mar):** recursion, stacks, queues, linked lists, binary search, and basic trees.
- **Q2 2027 (Apr–Jun):** trees, binary search trees, heaps/priority queues, and tree traversals.
- **Q3 2027 (Jul–Sep):** graphs (BFS/DFS), heaps review, and introductory dynamic programming.
- **Q4 2027 (Oct–Dec):** mixed practice, sliding window, intervals, greedy patterns, graphs, and basic DP.
- **Q1 2028 (Jan–Mar):** timed mixed sets, weak-topic revision, and interview-style explanation.

Adjust the order to your current CampusX DSA course and placement syllabus. The sequence is a guide, not a second syllabus to complete separately.

### Mathematics and statistics

| Resource | Use it for |
|---|---|
| [3Blue1Brown](https://www.3blue1brown.com/topics/linear-algebra) | Visual intuition for linear algebra and calculus. |
| [Khan Academy](https://www.khanacademy.org/math) | Fill specific prerequisite gaps. |
| [MIT 18.06 Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) | Matrices, projections, eigenvalues, and related concepts. |
| [Harvard Stat 110](https://stat110.hsites.harvard.edu/youtube) | Probability, conditional probability, expectation, and distributions. |
| [MIT 18.065](https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/) | Later, when you need deeper matrix methods. |
| MIT RES.6-012 and MIT 18.650 | Use selectively for relevant math/statistics topics and your curriculum. |

Keep mathematics at approximately **two hours a week**. For your university's numerical problems, use resources aligned with your actual syllabus; advanced lectures are supplements, not replacements.

**Math sequence by phase**
- **Oct–Dec 2026:** Khan Academy and 3Blue1Brown for vectors, matrices, derivatives, and basic probability.
- **Jan–Mar 2027:** selected MIT 18.06 lectures plus statistics for model evaluation, distributions, sampling, and validation metrics.
- **Apr–Jun 2027:** derivatives, chain rule, and gradients for backpropagation; practise by tracing gradients in a small neural network.
- **Jul–Sep 2027:** Harvard Stat 110 topics on conditional probability and Bayes, aligned with CS50AI uncertainty.
- **Oct–Dec 2027:** vector representations, dot products, cosine similarity, and nearest-neighbour intuition for embeddings and retrieval.
- **Jan–Mar 2028:** revisit only the math that blocks your agent/ML project or interview explanations.

Do not try to complete entire university courses just to satisfy this schedule. Select lessons that directly address a current gap.

### Deep learning and LLMs

| Resource | Use it for |
|---|---|
| [PyTorch tutorials](https://pytorch.org/tutorials/) | Your primary implementation reference. |
| [fast.ai](https://course.fast.ai/) | Practical, project-first deep learning. |
| [Karpathy — Zero to Hero](https://www.youtube.com/@AndrejKarpathy) | Understand neural networks and transformers by building them. |
| [MIT 6.S191](https://introtodeeplearning.com/) | Selected deep-learning theory lectures. |
| [Hugging Face LLM Course](https://huggingface.co/learn/llm-course) | Transformers, tokenizers, datasets, and practical NLP. |
| [Stanford CS224N](https://web.stanford.edu/class/cs224n/) | Selected NLP and transformer lectures. |
| [DeepLearning.AI short courses](https://www.deeplearning.ai/short-courses/) | Targeted introductions to RAG, LangChain, and agents. |
| [LLM Zoomcamp](https://github.com/DataTalksClub/llm-zoomcamp) | A structured, project-first RAG learning path. |
| [MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp) | Testing, deployment, and MLOps practice. |
| [Ollama](https://ollama.com/) | Optional local model runner when your machine can handle the chosen model. |
| [pguso/rag-from-scratch](https://github.com/pguso/rag-from-scratch) | Build RAG step by step with no black boxes. |

**DeepLearning.AI course decision:** keep the Deep Learning Specialization optional because it is primarily TensorFlow-based. Your main deep-learning implementation track remains **PyTorch**. Use short courses in the LLM phase only when they directly support the project you're building.

**Stanford CS229, Stanford CS25, MIT 6.006, and Roughgarden's algorithms courses remain optional.** Don't add them simply because they're prestigious.

---

## Quarterly go/no-go checkpoints

Use these checkpoints to adjust scope instead of silently carrying unfinished work forward. Quarter-end weeks are buffers, not extra deadlines.

| By | Check | If not met |
|---|---|---|
| **Dec 2026** | Project 1 is complete; Andrew Ng's course is at least halfway through. | Drop optional reading and extra notebooks; protect the main course and Project 1. |
| **Mar 2027** | Ng's course is complete; Project 2 is deployed; dashboard and walkthrough are usable. | Delay PyTorch by up to a month if needed; do not skip evaluation or testing. |
| **Jun 2027** | Project 3 is complete and reproducible. | Reduce the number of CS50AI projects in Phase 4; keep DSA steady. |
| **Sep 2027** | Selected CS50AI work is documented; mock interviews and DSA review have started. | Narrow CS50AI to the priority topics and begin mock interviews with current knowledge. |
| **Dec 2027** | RAG is deployed with a documented 30–50-question evaluation set. | Keep the agent simple; preserve tests and RAG evaluation rather than adding features. |
| **Mar 2028** | Portfolio page, resume, application tracker, and agent capstone are presentable. | Prioritize reliable demos, clear project explanations, and applications over new courses. |

---

## Month-by-month execution checklist

- [ ] **Oct 2026** — Finish CS50P; start Andrew Ng; clean GitHub; solve 10 SQL problems; choose a small Python project.
- [ ] **Nov 2026** — Study regression and classification; practise NumPy/pandas; start Project 1; inspect two relevant open-source repositories.
- [ ] **Dec 2026** — Complete Project 1 with evaluation, error analysis, limitations, and a clear README.
- [ ] **Jan 2027** — Study ensembles, cross-validation, leakage, and tuning; start Project 2; continue timed DSA practice.
- [ ] **Feb 2027** — Build the Flask/FastAPI interface; add tests; prepare your resume and internship application tracker.
- [ ] **Mar 2027** — Finish the ML Specialization; deploy and document Project 2; use internship applications as practice.
- [ ] **Apr 2027** — Learn PyTorch tensors, autograd, modules, and training loops; start Project 3.
- [ ] **May 2027** — Study optimization, regularization, and CNNs or text classification; compare against a baseline.
- [ ] **Jun 2027** — Finish Project 3 with reproducible evaluation and a technical write-up.
- [ ] **Jul 2027** — Start selected CS50AI topics; strengthen probability/statistics and DSA.
- [ ] **Aug 2027** — Continue CS50AI projects; practise Python fluency and add tests to existing work.
- [ ] **Sep 2027** — Review selected CS50AI topics; practise interview DSA; pursue substantive open-source contributions.
- [ ] **Oct 2027** — Study tokenization, embeddings, transformers, pretrained models, and basic inference.
- [ ] **Nov 2027** — Build raw RAG: document parsing, chunking, embeddings, retrieval, grounded answers, and an evaluation set.
- [ ] **Dec 2027** — Use LangChain where helpful; deploy Project 4 with source references and measured retrieval quality.
- [ ] **Jan 2028** — Learn LangGraph state, nodes, edges, conditional routing, and tool calling; containerize a small agent.
- [ ] **Feb 2028** — Upgrade RAG into an agent; add tests, logging, basic monitoring, and documented evaluation.
- [ ] **Mar 2028** — Polish all four projects, revise Python/ML/SQL/DSA, update your resume, and apply for summer 2028 roles.

Treat this as a direction, not a rigid deadline. College examinations, SIH, and a promising internship or contribution opportunity can justify shifting a milestone.

---

## Measurable targets by March 2028

| Area | Target |
|---|---|
| **Projects** | 4 core evaluated projects: tabular ML, deployed ML app, PyTorch model, RAG-to-agent system |
| **DSA** | 300+ independently solved problems; track topic coverage, timed performance, and explanation ability |
| **SQL** | 150+ problems including joins, aggregation, subqueries, CTEs, window functions |
| **Open source** | 2–4 substantive PR attempts; at least one merged or meaningfully reviewed |
| **Mock interviews** | 10+ by March 2028, starting September 2027 |
| **Deployment** | Deployed RAG app with retrieval evaluation; agent with tests, logging, Docker |
| **GitHub** | Clean repos with READMEs, tests, reproducible setup |
| **Career** | Updated resume, LinkedIn, simple portfolio page, application tracker, and a short write-up for each project |

These are ambitious targets. Treat them as direction, not a reason to inflate problem counts or rush shallow projects. A smaller set of projects you can explain, reproduce, and defend is more valuable than many shallow repositories.

**Interpret the numbers in two tiers:**
- **Core success:** three to four strong projects, consistent DSA/SQL practice, at least one credible contribution attempt, and clear explanations of your work.
- **Stretch success:** 300+ DSA problems, 150+ SQL problems, multiple substantive PR attempts, and 10+ mock interviews.

If college, exams, or SIH make the stretch numbers unrealistic, preserve project quality and interview-level understanding rather than rushing to hit counts.

---

## Career and open-source milestones

| Period | Career focus |
|---|---|
| **Oct–Dec 2026** | Improve GitHub, explore relevant repositories, and learn contribution workflows. |
| **Jan–Mar 2027** | Build your resume, practise applications, and attempt an appropriate first PR. |
| **Apr–Sep 2027** | Improve project quality, interview skills, and contribution depth. |
| **Oct–Dec 2027** | Demonstrate LLM/RAG ability through a tested and evaluated project. |
| **Jan–Mar 2028** | Polish the portfolio and target summer 2028 internships. |

GSoC can be an opportunity, but selection is not guaranteed. If you are not selected, the same useful contributions, code reviews, issue investigations, and technical discussions can still strengthen your GitHub and resume. Focus first on understanding a real codebase, communicating with maintainers, and making useful contributions.

---

## Total effort over 18 months

| Weekly pace | Total over 78 weeks |
|---:|---:|
| 15 hours | 1,170 hours |
| 16 hours | 1,248 hours |
| 18 hours | 1,404 hours |

Actual totals will be lower after exams, illness, hackathons, and breaks. Plan for lighter weeks instead of assuming perfect attendance.

---

## Your first seven days

- [ ] Finish the remaining CS50P work and verify your solutions.
- [ ] Begin Andrew Ng's ML Specialization; schedule the first lessons.
- [ ] Solve 10 SQL problems and review mistakes.
- [ ] Improve your GitHub profile and clean up one repository.
- [ ] Block your weekly 16 hours around college and existing commitments.
- [ ] Create a simple tracker for learning, DSA, projects, and applications.
- [ ] Pick two potential GSoC organizations and read their contribution guides.

---

## Weekly review and course-entry gates

Use this lightweight review every Sunday:

1. What did I **build or solve independently** this week?
2. What concept can I explain without notes?
3. What is blocked, and what is the smallest next action?
4. Which one task matters most next week?
5. Did the plan fit around college, sleep, and other commitments?

Before adding a new course, require all three:
- It fills a named gap in the current phase.
- You can identify the exact lesson/module you need.
- You will apply it to a project or problem within the next two weeks.

If any answer is no, save the link for later. Do not start the course now.

### Project completion gate

Before marking a portfolio project complete, check:
- [ ] A stranger can understand the problem and run the project from the README.
- [ ] The baseline, evaluation method, and results are visible.
- [ ] Data leakage and other major evaluation risks have been considered.
- [ ] Important failure cases and limitations are documented.
- [ ] Tests cover the most important behavior.
- [ ] A demo or screenshots are available where deployment is impractical.
- [ ] Your individual contribution is clearly distinguished from team contributions.

---

## Final rules

1. **No third major learning track.** Keep Roughgarden and CS229 optional unless clearly ahead.
2. **Protect college and sleep.** During exam or SIH weeks, drop to 3–8 hours. No backlog.
3. **Keep DSA regular.** 3–4 hours weekly, with shorter sessions on busy days.
4. **Cut scope, not quality.** If a project is late, reduce features before dropping tests, evaluation, or documentation.
5. **Open source starts early.** Read repositories in November 2026.
6. **Mock interviews start September 2027.** Do not wait until the final month.
7. **Reset if unsustainable.** Miss three weeks in a row → drop to 10 hours and rebuild.
8. **Apply based on evidence.** You do not need to finish all 18 months before applying.

**Final rule:** Until November, focus on **CS50P, Andrew Ng, and your existing DSA practice**. Do not start every course in the resource list. The best next step is to make progress on the first three tasks and turn what you learn into working code.

---

*No plan can guarantee GSoC selection, an internship, or a top-10% ranking. This one gives you tangible work and technical evidence with which to compete.*

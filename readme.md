## Intelligent Systems proj
Repo: https://github.com/ZGRochelleDev/intelligent-systems-code-Review

___

##### Lit Review - independantly
 * Sarah - Timer: Generative pre-trained transformers are large time series models. arXiv preprint arXiv:2402.02368, 2024
 * Zoe - TS-RAG: Retrieval-Augmented Generation based Time Series Foundation Models are Stronger Zero-Shot Forecaster

<br>

##### Code Review - together
TS-RAG: Retrieval-Augmented Generation based Time Series Foundation Models are Stronger Zero-Shot Forecaster
https://github.com/UConn-DSIS/TS-RAG

___

## Instructions

### Step 0: Pick a Repository
Choose one repo from the organization. You may choose **TS-RAG** or another research repo.

---

### Step 1: Read Before Running (Required)

Before executing anything:

1. Read the repo README.
2. Identify and write down:
   - What task is it solving? (forecasting, classification, retrieval, etc.)
   - What are the inputs/outputs?
   - What are the main scripts/entry points to run?
   - What datasets are required?
   - What hardware is recommended (CPU/GPU)?

#### Deliverable
A short **Project Map** (½ page) including:
- Repo purpose
- Main commands you plan to run
- Expected outputs (plots, metrics, tables, checkpoints)

---

### Step 2: Environment Setup (Required)

#### Conda
- Create an environment:
  - `conda create -n <envname> python=3.10 -y`
  - `conda activate <envname>`
- Install dependencies exactly as the repo specifies (`requirements.txt` / `environment.yml`)


#### Important Rules
- Do not “randomly upgrade” packages unless necessary.
- Record what you changed if you must modify versions.

#### Deliverable
A **Setup Log** including:
- OS (Windows/macOS/Linux)
- Python version
- Whether GPU was used
- Any dependency issues and how you solved them

---

### Step 3: Minimum Run Requirement

#### Level 3 (Excellent): Full Reproduction Attempt
Reproduce the main result table/figure as close as possible.

#### Deliverable
Evidence of execution:
- Screenshots or saved logs
- Output files (plots/CSVs)
- The exact command(s) you ran

---

### Step 4: Code Understanding Requirements (This Is the Core)

You must explain the implementation at a high level, not line-by-line.

Your presentation/report must include:

#### 1. System Diagram (One Slide)
- Show the pipeline: input → processing → model → output
- If retrieval-based: where retrieval happens and what is retrieved

#### 2. Key Modules (2–3 Slides)
- Identify 3–5 important components/files/classes
- Explain what each does in plain language

#### 3. Experiment Logic
- What is being compared? (baseline vs proposed, ablation, etc.)
- What metrics are used and why?

#### 4. Your Run Results
- What did you reproduce?
- What did you fail to reproduce (if anything), and why?

#### 5. One Critical Insight
A design trade-off or limitation you observed.

Examples:
1. Retrieval improves accuracy but requires memory indexing
2. Training is fast but preprocessing is heavy
3. GPU is optional but speeds up X part

---

### Step 5: Final Deliverables

Submit all of the following:

#### A) Short Report (2–4 pages)
Include:
- Repo overview (what + why)
- Setup log and commands
- What you ran and what you got
- Architecture explanation
- Key challenges + how you addressed them
- 1 limitation + 1 improvement idea

#### B) Presentation Slides (8–12 minutes)
Required slide structure:
1. Problem + motivation
2. What the repo proposes
3. Architecture diagram
4. Implementation highlights (modules)
5. Experimental setup
6. Your reproduced outputs
7. Limitations + improvement idea

#### C) Reproducibility Appendix (Required)
A text file or report section containing:
- Exact commands
- Any configuration changes
- Notes on compute constraints (CPU/GPU, RAM)

---

### Grading (Rubric)
- **30%** Correctness of running (outputs/logs/metrics produced)
- **40%** Understanding (architecture + module explanations)
- **20%** Quality of presentation/report (clarity, structure)
- **10%** Critical thinking (limitations + proposed improvements)

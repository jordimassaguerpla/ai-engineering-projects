# 🎓 AI Engineering TFG Playbook
## ETSE – Guide to building a rigorous AI Engineering Thesis

---

# 🔭 0. PROJECT VISION (MANDATORY)

## 🎯 Core Principle

The TFG is NOT defined by the implementation  
👉 It is defined by the VISION and the PROBLEM

---

## 🧠 Product Vision Board (Roman Pichler)

The project starts with a formal agreement between:

👤 Student + 👨‍🏫 Supervisor

---

### 🧩 Vision Elements

#### 1. Target Group
Who is the user?

#### 2. Needs (Real Problem)
A concrete and verifiable problem

#### 3. Product
Type of system (no specific technology)

#### 4. Value
Real impact

---

## 📄 Mandatory Output

- 1-page Product Vision Board
- Approved by the supervisor

---

## 🤝 Agreement

### ✔️ What is agreed:
- Problem
- Value
- Dedication (~300h)
- Prioritization (work order)

### ❌ What is NOT agreed:
- Implementation details
- Technologies
- Final results

---

## 🔁 Scope Management

- Scope CAN change
- Vision should remain stable

---

## 🧠 Strategy

👉 Value + Risk First

1. Highest technical risk
2. Highest impact

---

## 🚨 RED FLAGS

- “I want to build a chatbot with X”
- Stack defined before the problem
- UI before core system

---

# 🧭 1. PROBLEM DEFINITION

## 🎯 Goal

Clearly define:
- Who has the problem
- What is currently failing
- How success will be measured

---

## ✔️ Checklist

- [ ] Is there data available?
- [ ] Is there a non-AI baseline?
- [ ] Is success measurable?

---

# 🎯 2. TFG OBJECTIVES

### Types

- Functional
- Technical
- Experimental

---

# 🏗️ 3. ARCHITECTURE

## Typical Components

- Data ingestion
- Processing
- Indexing
- Retrieval
- Model
- Post-processing
- UI (optional)

---

## 🎯 Key Point

👉 Justify all decisions

---

# 📊 4. DATA

## Include

- Source
- Quality
- Limitations

---

## ⚠️ Red flag

“No data but doing AI”

---

# ⚙️ 5. IMPLEMENTATION

## Include

- Tech stack
- Key decisions
- Challenges

---

## ❌ Avoid

- Code dumps

---

# 🔬 6. EVALUATION (CRITICAL)

## 🎯 Goal

Demonstrate with data:
- It works
- It is better than alternatives
- It has known limitations

---

## 6.1 Data Splits

- Train: 70%
- Validation: 15%
- Test: 15%

### Rules

- ❌ Do NOT touch test set during development
- ❌ Do NOT tune on test set
- ✅ Validation = tuning
- ✅ Test = final evaluation

---

## Alternatives

- K-Fold Cross Validation
- Temporal splits (for real-world logs)

---

## 6.2 Dataset

### Sources

- Real (preferred)
- Synthetic (must be justified)
- Augmented

---

## Data Augmentation

### NLP
- Paraphrasing
- Back-translation

### Computer Vision
- Rotation
- Flip
- Noise
- Scaling

---

## 6.3 Baselines (MANDATORY)

Always compare with:

- Random baseline
- Non-AI system
- Simpler model

---

## 6.4 Metrics

---

### Classification

- Accuracy
- Precision
- Recall
- F1-score

---

### Segmentation

- Dice coefficient
- IoU (Jaccard)

---

### Retrieval (RAG)

- Precision@k
- Recall@k
- MRR

---

### Generation (LLMs)

- Exact Match
- LLM-as-a-judge
- Human evaluation (if possible)

---

### System Metrics

- Latency
- Cost per query
- Throughput
- Resource usage

---

## 6.5 Evaluation Pipeline

1. Input from test set
2. Retrieval
3. Generation
4. Metric computation

---

## 6.6 Error Analysis

- Error types
- Edge cases
- Systematic failures

---

## 6.7 Statistical Significance (advanced)

- t-test
- bootstrap

---

## 6.8 Reproducibility

- Random seeds
- Model versions
- Configurations

---

## 6.9 Visualization

- Confusion matrix
- Precision-recall curves
- Comparison charts

---

## 🚨 RED FLAGS

- No test set
- No baseline
- “It works well” without metrics

---

# 🔐 7. SECURITY

- RBAC / access control
- Data leakage prevention
- Prompt injection risks

---

# 💰 8. COSTS

- Cost per query
- Infrastructure cost
- Scalability considerations

---

# ⚖️ 9. ETHICS

- Bias
- Risk of misuse
- Social impact

---

# 🧾 10. CONCLUSIONS

- What works
- What does NOT work
- Trade-offs

---

# 🧠 MINDSET

❌ Demo  
✅ Measured system

---

# 🏁 GOLDEN RULES

1. Everything must be measurable  
2. Everything must be justified  
3. Always include a baseline  
4. Ensure reproducibility  
5. Less demo, more evidence  

---

# 🤖 PROMPTS FOR STUDENTS

---

## 🔭 Vision Definition Prompt

Act as an expert in Product Management and AI Engineering.

Help me define the vision of my TFG using the Product Vision Board.

IMPORTANT:
- Do NOT focus on technologies

Context:
[IDEA]

Help me define:
- Target users
- Problem
- Product
- Value

Be critical and avoid generic answers.

---

## 🧭 Planning Prompt

Act as an expert AI Engineering thesis supervisor.

Context:
Vision: [X]
Time: ~300h

Help me:
- Prioritize (risk + value)
- Identify technical risks
- Define realistic milestones

---

## 🔬 Evaluation Prompt

Act as an expert in Machine Learning evaluation.

Context:
[SYSTEM]

Review:
- Data splits
- Metrics
- Baselines
- Experimental design

Be critical and precise.

---

## 🧠 Final Review Prompt

Act as a strict thesis committee.

Identify:
- Weaknesses
- Lack of rigor
- Missing evaluation

---

# 🚀 FINAL MESSAGE

Without evaluation → there is no AI Engineering

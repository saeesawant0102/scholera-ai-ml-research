# Scholera AI/ML Research Intern Take-Home

This repository contains my submission for the Scholera AI/ML Research Intern take-home assignment.

The assignment evaluates three quiz-generation strategies and asks for a research-based recommendation, a review of an internal product study, and a short competitor analysis.

---

## Repository Contents

### Part 1 — Strategy Evaluation

Evaluation of Strategies A, B, and C using a question-level scoring rubric and additional analysis of:

- Question quality
- Topic coverage
- Redundancy
- Cognitive diversity
- Usable question yield
- Critical failure rate

**Deliverables:**
- `part1/Part_1.pdf`
- `part1/question_scoring.xlsx`

### Part 2 — Internal Study Review

A memo evaluating the four-week pre-class primer study, including:

- What the study supports
- What it does not establish
- Important limitations and confounders
- Recommended next experiment

**Deliverable:**
- `part2/Part_2.pdf`

### Part 3 — Competitor Analysis

A short review of two AI-education products, focusing on:

- What each product does well
- Where the available evidence does not support stronger marketing claims
- What Scholera could do differently

**Deliverable:**
- `part3/Part_3.pdf`

### AI Usage

A description of how AI tools were used during the analysis and writing process, including how model disagreements and unreliable judgments were handled.

**Deliverable:**
- `AI_USAGE.md`

---

# Part 1 — Main Conclusion

Based on the evaluated question sets and the predefined evaluation framework, Strategy C achieved the highest weighted score.

| Strategy | Final Weighted Score |
|---|---:|
| Strategy C | **9.10 / 10** |
| Strategy A | **8.29 / 10** |
| Strategy B | **6.87 / 10** |

### Recommendation

**Strategy C is the strongest observed candidate.**

It produced the highest mean question quality, had no observed critical failures, and showed strong cognitive diversity with no observed redundancy.

However, the recommendation should be treated with **moderate confidence rather than as a definitive conclusion**.

Strategy C contains only 8 retained questions, compared with 12 questions from Strategies A and B. The assignment does not provide the number or content of questions that Strategy C discarded during its verification step. Therefore, its retention rate and the characteristics of its discarded questions cannot be evaluated.

The weighted score therefore describes the quality of the **observed final question sets**, rather than proving that Strategy C is the best end-to-end generation pipeline.

---

# Key Part 1 Results

| Metric | Strategy A | Strategy B | Strategy C |
|---|---:|---:|---:|
| Mean Question Quality | 6.67 | 8.17 | **9.25** |
| Topic Coverage | **100%** | 20% | 80% |
| Redundancy Rate | **0%** | 33.3% | **0%** |
| Cognitive Distribution | 8R / 3U / 1A | 6R / 6U / 0A | 0R / 6U / 2A |
| Usable Questions | 9/12 | **12/12** | 8/8 |
| Usable Question Yield | 75% | **100%** | **100%** |
| Critical Failure Rate | 25% | **0%** | **0%** |

Where:

- `R` = Recall
- `U` = Understanding
- `A` = Application/Reasoning

---

# Part 2 — Main Conclusion

The internal pre-class primer study provides a promising signal, but it does not establish that the primers caused the observed improvement in on-time assignment submission.

The treatment sections had a 7.4 percentage-point higher on-time submission rate, and students who voluntarily rated the primer gave it an average usefulness score of 4.1/5.

However, the study contains several limitations, including concurrent weekly quizzes in two treatment sections, a control professor being on leave for two weeks, uncontrolled primer timing, lack of actual primer-open/read tracking, and voluntary usefulness ratings.

The graduate result is particularly uncertain because the subgroup contained only 9 control students and 4 treatment students.

**Recommendation:** continue testing the primer feature, but run a larger and better-controlled experiment before making graduate-specific product, tuning, or pricing decisions.

See `part2/Part_2.pdf` for the full memo.

---

# Part 3 — Main Conclusion

The competitor review examined **Quizlet** and **MagicSchool**.

The analysis suggests that:

- Quizlet's strength is its student-facing study workflow and integration of generated material into practice.
- MagicSchool's strength is its broad teacher-oriented AI workflow.
- Simply generating AI quiz questions is therefore unlikely to be a strong differentiator for Scholera.

A more defensible opportunity for Scholera is to differentiate through:

1. **Source grounding**
2. **Assessment quality evaluation**
3. **Topic coverage and redundancy checks**
4. **Teacher review and control**
5. **Transparency about why a question is accepted or rejected**

The opportunity is not simply to generate more questions, but to make generated questions **more trustworthy and easier for professors to review**.

See `part3/Part_3.pdf` for the full competitor analysis.

---

# Limitations

The Part 1 evaluation is based on one supplied lecture and relatively small generated question sets.

Some criteria, particularly difficulty and cognitive-level classification, involve researcher judgment. The unequal number of questions across strategies also limits how strongly the strategies can be compared.

Most importantly, the analysis does not provide information about questions discarded by Strategy C, so its complete generation and verification process cannot be evaluated from the supplied data.

The conclusions therefore reflect what the available evidence supports and avoid treating the results as broader than the data allows.

---

# Presentation

A 5–8 minute presentation of the work is provided here:

**[Presentation Video](ADD_VIDEO_LINK_HERE)**

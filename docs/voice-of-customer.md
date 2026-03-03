# Voice of the Customer (VoC) Process  
## Well Made Decisions Lab

---

## Purpose

The Voice of the Customer (VoC) process ensures that feature development for Well Made Decisions Lab is driven by real user needs, measurable value, and structured prioritization rather than intuition alone.

This document defines:

- How feedback is collected
- How the feedback is categorized
- How it is evaluated and analyzed
- How features are prioritized
- How decisions are communicated

---

## Guiding Principles

1. Structure before reaction.
2. Data before opinion.
3. Patterns over anecdotes.
4. Reversible experiments before irreversible builds.
5. Alignment with core product thesis:
   > Structured, citation-backed decision intelligence.

---

# 1. Feedback Collection Channels

## 1.1 In-App Prompt

After report delivery, users are asked:

- "Was this analysis helpful?"
- "What was missing?"
- "What would improve this tool for you?"

Optional open text response.

---

## 1.2 Follow-Up Email

Automated email includes:

> “Reply to this message with feedback or improvement ideas.”

Direct replies are logged and categorized.

Potential 1.2b addition could be a feedback form on the website at www.wellmadedecision.com
Potential 1.2c addition could be including the results of a survey in a LinkedIn post asking about features.
---

## 1.3 Structured User Interviews

For selected users:

- 15–30 minute interview
- Standardized question set:
  - What decision did you use the Lab for?
  - What worked?
  - What felt weak?
  - What surprised you?
  - Would you rely on this for high-stakes decisions?
  - What would make you trust it more?
  - How much would you pay to access the system 24x7 without limitations?
  - How much would you pay to access the system on a per access basis (metered)?
  - Are there some specific decision types that would be worth developing a deeper, more refined and more specific model around and charging/accessing separately?

Notes stored in structured template.

Alternative 1.3b includes having these interviews conducted by AI.

---

## 1.4 Observational Signals

Metrics reviewed monthly:

- Completion rate
- Email conversion rate (opt in)
- Drop-off point in workflow
- Average response time
- Citation frequency
- Re-run frequency

---

# 2. Feedback Categorization Framework

All incoming feedback is categorized into one of these buckets:

## A. Output Quality
- Weak analysis
- Shallow risk register
- Generic options
- Poor citations

## B. Missing Capability
- PDF export
- Save history
- Collaboration mode
- Custom frameworks

## C. Usability
- Interface confusion
- Too long
- Too short
- Navigation friction

## D. Trust Signals
- Wants clearer citations
- Wants confidence score
- Wants transparency
- Wants privacy clarity

## E. Performance
- Slow generation
- Timeout issues
- Inconsistent formatting

---

# 3. Feature Evaluation Framework

Each proposed feature is evaluated on a 1–5 scale across:

## 3.1 Customer Value
How strongly does this improve:
- Clarity
- Trust
- Actionability
- Repeat usage
- Willingness to pay

## 3.2 Alignment with Thesis
Does it reinforce:
> Structured, disciplined, decision intelligence?

## 3.3 Impact on Differentiation
Does it:
- Make the Lab meaningfully different from generic AI chat?
- Increase defensibility?
- Value versus the alternatives

## 3.4 Implementation Complexity
Estimated engineering effort:
- Low
- Medium
- High

## 3.5 Reversibility
Can this be tested as a small experiment?
- Yes
- Partial
- No

---

# 4. Prioritization Model

Features are scored using:

Priority Score =  
(Customer Value × 2)  
+ Alignment  
+ Differentiation  
− Implementation Complexity

Features are ranked quarterly.

---

# 5. Decision Gates

## Stage 1 – Validation
- Pattern observed in ≥ 3 user inputs OR
- High-value user segment feedback

## Stage 2 – Prototype
- Small reversible experiment
- Limited rollout
- Measure impact

## Stage 3 – Production
- Incorporated into roadmap
- Documented in CHANGELOG
- Evaluated post-release

---

# 6. Monthly VoC Review Process

Every month:

1. Review new feedback.
2. Identify recurring themes.
3. Update feature backlog.
4. Score new ideas.
5. Promote top candidate to prototype.
6. Document decision rationale in repo.

---

# 7. Feedback Transparency

Significant feature decisions are documented in:

/docs/roadmap.md

Each entry includes:
- Source of request
- Evaluation score
- Decision (build / delay / decline)
- Rationale

---

# 8. Example Feature Evaluation

Feature: Persistent Report Storage

Customer Value: 5  
Alignment: 5  
Differentiation: 4  
Implementation Complexity: 4  

Priority Score:
(5×2) + 5 + 4 − 4 = 15

Result:
High priority for Phase 2.

---

# 9. Anti-Pattern Avoidance

The Lab will NOT:

- Chase novelty features with low decision value.
- Implement features without customer validation.
- Expand into general chatbot territory.
- Compromise structural rigor for speed.

---

# 10. Future Enhancements to VoC

Planned additions:

- Net Promoter Score (NPS)
- Decision outcome follow-up surveys
- Feature usage heatmaps
- A/B testing prompts
- Model comparison testing

---

## Summary

The Voice of the Customer process ensures that:

Well Made Decisions Lab evolves through disciplined listening, structured evaluation, and reversible experimentation — consistent with the core principles of the Lab itself.

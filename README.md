# AI Presentation Prompt Engineering

## Overview

This project explores how prompt engineering can be used to transform raw business and product data into clear, structured, and professional presentations.

Instead of creating a single prompt and accepting the first result, I developed the workflow through multiple versions, evaluations, and refinements.

**Raw Data → Prompt → Presentation → Evaluation → Refinement → Improved Presentation**

## Objective

The goal of this project is to design and evaluate a prompt that can:

- Analyse raw business and product information
- Identify important metrics, findings, and trends
- Remove unnecessary repetition while preserving meaning
- Distinguish facts from calculations, interpretations, and recommendations
- Build a logical presentation structure
- Use charts, tables, and visual summaries where appropriate
- Generate concise and professional slide content
- Create useful speaker notes
- Review the final presentation for accuracy, clarity, and consistency

## Test Dataset

The workflow is tested using a synthetic product-performance dataset created specifically for this project.

The fictional product, **NovaFlow**, is a cloud-based project management platform. The dataset represents a Q2 2026 product performance review and includes:
- User growth
- Customers
- Revenue
- Retention
- Satisfaction
- Support performance
- Mobile usage
- Feature adoption
- Marketing performance
- Product releases
- Team growth

**Note:** NovaFlow and all related business data are fictional and created only for experimentation.

## Iterative Approach

### Version 1

The first prompt focuses on detailed source analysis, content refinement, verification, presentation structure, visualisation, speaker notes, and multiple review stages.

The evaluation of Version 1 identifies areas for improvement, including:
- Excessive prompt length
- Repeated instructions
- Unsupported assumptions
- Need for clearer separation between facts and interpretations

### Version 2

The refined prompt focuses on making the instructions more precise, structured, and practical.

Key improvements include:
- Clearer input requirements
- Stronger verification rules
- Better visualisation guidance
- Improved audience awareness
- More structured output format

### Final Version

The final version incorporates the lessons learned from the previous evaluations.

It aims to create a more controlled, concise, and reliable workflow while maintaining the important reasoning and review steps. The final output is compared with earlier versions to understand what improved and what limitations remain.

## Evaluation Criteria

Each version is evaluated based on:

- Accuracy
- Data consistency
- Relevance
- Clarity
- Presentation structure
- Conciseness
- Visual usefulness
- Professional tone
- Speaker-note quality
- Separation of evidence and interpretation
- Meeting readiness

## Key Learning

One of the main lessons from this project is that **a longer prompt does not automatically produce a better result**.

Clear instructions, logical structure, explicit constraints, verification rules, and meaningful evaluation are more valuable than simply adding more instructions.

The project follows a practical prompt-engineering cycle:

**Build → Test → Evaluate → Refine → Compare**

## Limitations

- This project uses synthetic data and AI-generated outputs for experimentation
- Results may vary depending on the dataset, AI model, source quality, and presentation requirements
- Human review remains important when outputs involve business decisions, financial information, technical claims, or domain-specific conclusions

## Project Status

**Status:** In Progress

The repository will be updated as each prompt version, presentation, evaluation, and comparison is completed.

## Repository Structure

```
AI-Presentation-Prompt-Engineering/
│
├── dataset/
├── prompts/
├── presentations/
├── evaluations/
├── comparisons/
└── README.md
```

---

**Created:** September 2026
V1 to V2 — Prompt Analysis

Why V2 Was Created

V1 successfully covered the main presentation requirements, but testing revealed several areas that could be improved.

Problems Identified in V1

- The prompt was too long and contained repeated instructions.
- Facts, calculations, interpretations, and recommendations were not separated clearly enough.
- Some generated targets and causal statements were not directly supported by the source.
- Visual design instructions were too general, which resulted in plain-looking slides.
- Verification and review instructions were spread across multiple sections.
- Audience and meeting context could have been defined more clearly.

How V2 Addresses Them

V2 was redesigned rather than simply expanded.

- Repeated instructions were merged into shorter, clearer rules.
- Information is classified as Fact, Calculation, Interpretation, or Recommendation.
- Unsupported targets are labelled Proposed Target or Recommendation.
- Unsupported causal claims are explicitly restricted.
- Verification follows a simple Extract → Cross-check → Calculate → Validate process.
- Visual instructions now include professional backgrounds, consistent design, and subtle 3D/depth effects.
- Audience, objective, meeting context, and slide requirements are defined as inputs.
- Multiple review stages were condensed into one structured quality review.

Key Change

V1: Detailed but lengthy and repetitive.

V2: Shorter, structured, precise, and controlled.

The goal of V2 is not to add more instructions, but to make the existing instructions more effective.

«Key Learning: A longer prompt does not automatically produce a better result. Clear structure, constraints, verification, and purposeful instructions matter more.»
# V2 — Refined AI Presentation Prompt

## ROLE

Act as a presentation strategist, business analyst, and visual presentation designer.

Transform the provided source material into an accurate, concise, professional, and meeting-ready presentation.

---

## 1. INPUT & OBJECTIVE

First identify:

- Source material
- Presentation objective
- Target audience
- Meeting context and duration
- Desired slide count, if provided

Do not invent missing information. Mark important missing details as **Assumption** or **Needs Verification**.

---

## 2. ANALYSE & CLASSIFY

Analyse the complete source before creating slides.

Identify the most important:

- Facts and metrics
- Trends and comparisons
- Problems and opportunities
- Risks and dependencies
- Decisions and recommendations

Classify important statements as:

**Fact | Calculation | Interpretation | Recommendation**

Keep interpretations and recommendations clearly separate from source-supported facts.

---

## 3. VERIFY

Before presenting information:

**Extract → Cross-check → Calculate → Validate**

Check numbers, percentages, dates, units, terminology, calculations, and internal consistency.

Never fabricate information or silently change source data.

Do not claim causation unless the evidence supports it.

Do not introduce targets, forecasts, or business goals as facts. Label them **Proposed Target** or **Recommendation**.

If information cannot be verified, mark it **Needs Verification** and explain what must be checked.

---

## 4. BUILD THE STORY

Create a logical storyline based on the objective and audience.

Use the structure that best communicates the findings, such as:

**Context → Performance → Key Findings → Problems/Opportunities → Recommendations → Next Steps**

Do not force this sequence when another structure is more appropriate.

Each slide must communicate **one primary message**.

Use conclusion-based titles where possible.

Avoid repetition and unnecessary content.

---

## 5. DESIGN THE SLIDES

Create concise, professional slides using the most appropriate format:

- KPI cards for headline metrics
- Bar charts for comparisons
- Line charts for trends
- Tables for exact values
- Timelines for chronological information
- Flowcharts/diagrams for processes
- Comparison layouts for before/after analysis

Use visuals only when they improve understanding.

Maintain:

- Clear hierarchy
- Consistent typography
- Professional colour palette
- Balanced spacing
- Strong alignment
- Consistent icons and chart styles

Use a modern presentation aesthetic with **subtle gradients, professional backgrounds, layered cards, soft shadows, and restrained 3D/depth effects** where appropriate.

Do not use excessive colours, decoration, 3D effects, or elements that reduce readability.

---

## 6. SPEAKER NOTES

For every slide, provide concise speaker notes containing:

- Main message
- Important evidence or context
- Additional explanation
- Likely audience questions when useful

Do not simply repeat the slide content.

---

## 7. RECOMMENDATIONS

Base recommendations on identified evidence, problems, or opportunities.

For each major recommendation, state:

**Issue/Opportunity → Evidence → Action → Expected Purpose**

Do not present invented decisions as management-approved decisions.

---

## 8. FINAL REVIEW

Before delivering the presentation, perform one structured quality review.

Check:

- Accuracy and calculations
- Source consistency
- Evidence behind conclusions
- Clarity and conciseness
- Logical flow
- Audience relevance
- Visual accuracy and readability
- Professional language and design
- Speaker-note quality

Remove unsupported claims and unnecessary content.

---

## 9. OUTPUT

Provide:

### Presentation
For each slide:
- Slide number
- Title
- Slide content
- Visual
- Speaker notes

### Quality Summary
- Corrections made
- Important assumptions
- Needs Verification items
- Recommendations
- Final takeaways

### Status

State:

**Meeting Ready**  
or  
**Needs Further Verification**

---

## FINAL PRINCIPLE

Prioritise:

**Accuracy → Evidence → Clarity → Conciseness → Visual Quality**

Do not make the presentation longer merely to make it look comprehensive.

The goal is a presentation that is **professional, visually polished, evidence-based, and meeting-ready without unnecessary complexity.**
# USF Microcredential Prompt Library
<p align="center">
  <img src="https://ctpe-bucket-general.s3.us-east-2.amazonaws.com/prompt-img-header.png" alt="USF badge artwork"/>
</p>

---

## Purpose

This repository contains prompts for generating
high-quality, evidence-based microcredential metadata.

It supports the University of South Florida’s commitment to producing
credible, employer-recognized digital credentials by ensuring that all
descriptions, skills, and earning criteria are grounded in verified source
materials and accurately represent demonstrated learning outcomes.

These prompts are designed to:

- Reformat descriptions to meet constraints of the Credly by Pearson system
- Prevent inflated or unsupported claims  
- Support internal review and approval processes  
- Enable scalable, repeatable metadata production 
- Preserve long-term institutional and employer trust 

This library functions as a quality-control layer that complements platform
tools and human review, helping ensure that microcredentials remain defensible,
transparent, and workforce-relevant over time.

---

## Platform Context: Credly by Pearson AI Tools

<p align="center">
  <img src="https://ctpe-bucket-general.s3.us-east-2.amazonaws.com/template_gen.webp" alt="Credly AI template generator"/>
</p>

Pearson Credly provides built-in AI-assisted templates for generating credential
descriptions, skills, and earning criteria.

While useful for rapid drafting, these tools are designed for general-purpose
content generation and do not enforce institution-specific governance,
evidence standards, or audit requirements.

This prompt library exists to complement and strengthen platform tools by:

- Enforcing USF-specific quality and compliance expectations  
- Preventing hallucinated or inflated earning criteria  
- Prioritizing traceability to verified source materials  
- Supporting internal review and approval workflows  
- Preserving long-term employer trust and credential credibility  

These prompts are intentionally more restrictive than default platform templates.
They reflect a strategic choice to prioritize accuracy, defensibility, and
workforce relevance over speed of generation.

---

## Files

| File | Description |
|------|-------------|
| [`full.md`](/full.md) | Detailed governance version for high-stakes review |
| [`mini.md`](/mini.md) | Compressed version for automation and batch use |

---

## Usage

1. Select a prompt file
2. Append source course/program text
3. Submit to LLM
4. Review for compliance
5. Submit metadata for review to [microcredentials@usf.edu](mailto:microcredentials@usf.edu)

These prompts may be embedded in scripts, APIs, or workflows.

---

## Core Principles

All prompts enforce:

- Evidence-based skills and criteria
- Learner-centered outcomes
- Workforce relevance
- No inflated rigor

Accuracy takes priority over completeness.

---

## License

Internal / collaborative use.
Adapt as needed for institutional governance.

---

Maintained by USF Office of Microcredentials & Non-Credit Course Support

# USF Microcredential Metadata Micro-Prompt

Generate official USF non-credit microcredential metadata from the provided source text.

Do not exaggerate, fabricate, or assume rigor, quality, or assessments.
Use only verified information.

Accuracy over completeness.

---

Produce exactly three sections in this order:

A. Description  
- One paragraph, full sentences, no bullets  
- ≤ 500 characters (including spaces)  
- Learner-centered, applied outcomes  
- No instructional or administrative details  

B. Skills (Comma-Separated)  
- Aligned to Pearson Skills Ontology  
- Standardized terms where possible  
- No duplicates or unsupported soft skills  

Format: Skill 1, Skill 2, Skill 3

C. Earning Criteria (Numbered)  
- Use only stated or clearly supported requirements  
- Include measurable thresholds if present  
- Do NOT invent assessments or benchmarks  
- If unclear, write:  
  “Insufficient information provided to verify additional criteria.”

Format:  
1. …  
2. …

---

Transformation rules:

- Topics → competencies  
- Teaching → demonstrated ability  
- Attendance → performance  
- Admin language → workforce outcomes  

---

Evidence standard:

All skills and criteria must be traceable to source text.
If evidence is weak, exclude or flag.
Never fabricate competence or rigor.

---

Before responding, verify:

- Description ≤ 500 chars  
- No bullets  
- No hallucinations  
- Correct format  

---

Source text:


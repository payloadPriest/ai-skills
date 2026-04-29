# ai-skills
AI Skills for everyday use

## Software Risk Assessment
Skill file: `software-risk-assessment/SKILL.md`

### What it does
Produces structured cybersecurity risk assessments for software tools, vendors, and services. Assessments are aligned with ISO 27001, GDPR, NIS2, DORA, and EBA guidelines, and follow a fixed template covering general information, a weighted risk 
matrix, a verdict, and acceptance criteria.

### When it triggers
Use this skill when you want to assess, evaluate, or review a software tool or vendor for security or compliance risk. 

Typical prompts:

"Run a risk assessment on Notion"<br>
"Evaluate this SaaS tool for security"<br>
"Is it safe to use X in our environment?"<br>
"Fill in a risk assessment for vendor Y"<br>

### How it works
The LLM reads the assessment template at `software-risk-assessment/template.md`.
and researches the software using vendor documentation, public CVE databases (NVD), SOC 2 / ISO attestations, and other reputable sources.
The template is populated with verified information only — fields with no verifiable data are marked Unknown.
A weighted risk score is calculated and mapped to a risk level: Low (≤ 2.5), Medium (> 2.5–5), or High (> 5).
A verdict of Approved, Approved (with conditions), or Rejected is issued, along with numbered acceptance criteria.

### Output
Plain Markdown using the exact structure of the template — no preamble, no code blocks, no invented data.
 
 ## RFD Writer
 
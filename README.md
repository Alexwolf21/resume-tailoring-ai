# AI Resume Tailoring Agent

An AI-powered resume tailoring workspace designed for Google Antigravity (or any autonomous AI IDE).

The objective is to generate truthful, ATS-optimized, recruiter-friendly resumes while preserving the candidate's unique technical experience and continuously improving the repository over time.

---

# Repository Structure

```
resume-tailoring-ai/
│
├── gravity.md              # Agent operating manual
├── knowledge.md            # Resume optimization knowledge base
├── candidate_profile.md    # Complete factual candidate profile
├── base_resume.tex         # Master resume (source of truth)
├── job_description.md      # Current job description
├── tailored_resume.tex     # Generated tailored resume
└── README.md
```

---

# File Responsibilities

## gravity.md

Defines the complete behavior of the Resume Tailoring Agent.

Contains:

- Workflow
- Decision Framework
- Resume Integrity Rules
- Repository Rules
- Execution & Deliverables
- Communication Mode

This is the governing specification for every tailoring session.

Normally this file should only be modified when improving the agent itself.

---

## knowledge.md

A persistent repository of reusable resume optimization knowledge.

Examples:

- ATS optimization strategies
- Better action verbs
- Better technical wording
- Resume organization
- Industry terminology
- Lessons learned from previous tailoring sessions

Never store:

- Company names
- Job descriptions
- Temporary tailoring decisions

---

## candidate_profile.md

Contains the complete factual profile of the candidate.

This is **not** a resume.

It may include:

- Technologies
- Responsibilities
- Products
- Platforms
- Architecture exposure
- Certifications
- Projects
- Awards
- Resume preferences
- Experience omitted from the one-page resume

The AI may use this file to enrich the resume only with truthful and relevant information.

---

## base_resume.tex

The master resume.

This is the single source of truth for all tailoring.

Never modify unless intentionally improving the master resume.

---

## job_description.md

Replace this file before every application.

Paste the complete Job Description here.

---

## tailored_resume.tex

Generated tailored resume.

This file is overwritten during every tailoring session.

---

# Resume Tailoring Workflow

For every application:

1. Replace `job_description.md` with the target Job Description.
2. Open the repository in Antigravity.
3. Execute the workflow defined in `gravity.md`.
4. If prompted, answer any Candidate Confirmation questions (for example, email selection).
5. Review the generated `tailored_resume.tex`.
6. Compile the LaTeX.
7. Submit the resume.

---

# Recommended Prompt

The repository already contains all required instructions.

Use this prompt:

> Execute the workflow defined in `gravity.md` for the current `job_description.md`.
>
> Treat `gravity.md` as the governing specification and source of truth for behavior.
>
> Follow every workflow step, update only the repository files specified in `gravity.md`, request any required user confirmations before tailoring, and return only the Console Summary after completion.

No additional prompt engineering should normally be required.

---

# Tailoring Principles

The Resume Tailoring Agent follows these principles:

- Maintain 100% factual accuracy.
- Never fabricate experience, projects, technologies, or metrics.
- Preserve the candidate's unique technical identity.
- Preserve high-value technical context (products, platforms, architecture, technologies).
- Improve ATS compatibility naturally.
- Avoid keyword stuffing.
- Distribute keywords across sections instead of repeating them.
- Prefer concrete technical evidence over generic Job Description wording.
- Improve readability without removing valuable technical information.

The objective is not to maximize keyword frequency.

The objective is to maximize interview probability while preserving credibility.

---

# Candidate Confirmation

Before tailoring, the AI may request confirmation for user-selectable options.

Examples:

- Email address
- Resume preferences
- Other configurable options added in the future

If the required information has already been provided in the current conversation, the AI should continue without asking again.

---

# Console Output

The primary deliverables are the repository files.

After completing the workflow, the AI should return only a concise Console Summary.

Example:

```
Resume Tailoring Completed

Before
ATS: 74/100
Recruiter: 76/100
Hiring Manager: 72/100

After
ATS: 91/100
Recruiter: 92/100
Hiring Manager: 90/100

Recommendation: Strong Match

Updated
✓ tailored_resume.tex
✓ knowledge.md

Remaining Gaps
• Kubernetes
• Terraform
```

Detailed analysis should only be produced when explicitly requested.

---

# Prompt to use

Execute the workflow defined in gravity.md for the current job_description.md.

Treat gravity.md as the governing specification and source of truth for behavior. Follow every workflow step, update only the repository files specified in gravity.md, ask for any required user confirmations before tailoring, and return only the Console Summary after completion.

use email id as [EMAIL_ADDRESS] and phone number as 7008770676

---

# Review Checklist

Before submitting a resume, verify:

- No fabricated experience.
- No unsupported technologies.
- No exaggerated metrics.
- Product names and platforms are preserved.
- Technical evidence has not been replaced by generic wording.
- Keywords are naturally incorporated.
- Duplicate wording has been removed.
- Resume fits within the intended page limit.
- LaTeX compiles successfully.
- Remaining gaps are genuine.

---

# Long-Term Maintenance

Continue improving:

- `knowledge.md` with reusable optimization knowledge.
- `candidate_profile.md` with new experience, technologies, certifications, and achievements.
- `base_resume.tex` only when permanent improvements are identified.

The objective is to evolve the repository over time while ensuring every tailored resume remains truthful, technically rich, and highly relevant to its target role.
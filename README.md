# AI Resume Tailoring Agent

An AI-powered resume tailoring workspace designed for Google Antigravity (or any autonomous AI IDE).

The goal is to generate truthful, ATS-optimized, recruiter-friendly resumes for each job application while continuously improving over time.

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

Defines the behavior of the Resume Tailoring Agent.

Contains:

- Workflow
- Decision Framework
- Resume integrity rules
- Execution & Deliverables

Normally this file should remain unchanged.

---

## knowledge.md

Stores reusable resume optimization knowledge.

Examples:

- Better wording
- ATS optimization
- Technical terminology
- Resume organization
- Strong action verbs

Never stores company-specific information.

---

## candidate_profile.md

Contains the candidate's complete factual professional profile.

This is **not** a resume.

It may include:

- Technologies
- Responsibilities
- Projects
- Architecture exposure
- Certifications
- Awards
- Resume preferences
- Experience not included in the one-page resume

This allows the AI to enrich the resume truthfully when relevant.

---

## base_resume.tex

The master resume.

This is the source of truth for all resume tailoring.

Never modify unless intentionally updating the master resume.

---

## job_description.md

Replace this file before every application.

Paste the complete Job Description here.

---

## tailored_resume.tex

Generated output.

This file is overwritten every tailoring session.

---

# Resume Tailoring Workflow

For every application:

1. Paste the Job Description into `job_description.md`.

2. Open the repository in Antigravity.

3. Ask Antigravity to execute the tailoring workflow.

4. Review:
   - ATS alignment
   - Resume changes
   - Remaining gaps
   - Updated knowledge

5. Compile and review `tailored_resume.tex`.

6. Submit the resume.

---

# Recommended Prompt

The repository already contains all required instructions.

Use a short prompt such as:

> Read `gravity.md` and execute the complete resume tailoring workflow for the current `job_description.md`. Follow every instruction in `gravity.md`, update `tailored_resume.tex` and `knowledge.md`, and present the required execution report. Use `candidate_profile.md` to enrich the resume only with truthful information that is relevant to the target role.

---

## Alternative Prompt (More Explicit)

If you want to be slightly more explicit:

> You are working inside an AI Resume Tailoring repository. Read `gravity.md` first and follow it as the governing specification. Read the repository files in the prescribed order, analyze the current `job_description.md`, generate the strongest truthful tailored resume, update `tailored_resume.tex`, update `knowledge.md` with reusable insights, and present the execution report. Do not modify `base_resume.tex` unless I explicitly request it.

---

# Candidate-Specific Rules

The candidate prefers the following tailoring strategy:

- For early-career roles (SDE 1, Graduate, Associate, Software Engineer I, 0–2 YOE), include both:
  - M.Tech (BITS Pilani)
  - B.Tech (with CGPA)

- For experienced roles (typically 2–3+ YOE), include only:
  - B.Tech (with CGPA)

- Present the SAP role as **Software Developer** (or **Software Engineer**) rather than emphasizing the internal "Scholar" designation, unless specifically requested.

---

# Review Checklist

Before submitting any resume, verify:

- No fabricated experience.
- No unsupported technologies.
- No exaggerated metrics.
- Resume remains within the intended page limit.
- LaTeX compiles successfully.
- The most relevant experience is emphasized.
- Keywords are naturally incorporated.
- Remaining gaps are genuine and clearly identified.

---

# Long-Term Maintenance

After multiple tailoring sessions:

- Continuously improve `knowledge.md`.
- Expand `candidate_profile.md` as new experience is gained.
- Update `base_resume.tex` only when permanent improvements are identified.

The objective is to keep the master resume, candidate profile, and knowledge base evolving while each tailored resume remains specific to its target role.

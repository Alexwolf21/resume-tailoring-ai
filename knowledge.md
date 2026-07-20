# Resume Tailoring Knowledge Base

> Reusable resume optimization knowledge. Updated after every tailoring session.
> Never stores company names, individual JDs, or personal information.

---

# Writing Principles

## Action Verbs

Prefer strong action verbs:

Architected · Designed · Developed · Implemented · Engineered · Owned · Automated · Optimized · Integrated · Delivered · Built · Investigated · Authored · Streamlined · Migrated · Refactored

Avoid: Worked on · Helped · Responsible for · Participated in · Involved in

---

## Bullet Structure

**Pattern:** Action → Technology → Result

Example: *Developed REST APIs using Spring Boot to automate deployment workflows, reducing manual operational effort.*

- When measurable impact is available, always include it (%, time saved, scale).
- When unavailable, describe functional impact truthfully.
- **Lead with the most JD-relevant bullet.** Never bury the highest-alignment content below general bullets.
- Keep bullets to 1–2 lines. Split into separate bullets if a single bullet covers too many distinct ideas.

---

## Technical Wording Preferences

| Prefer | Instead of |
|---|---|
| Apache Kafka (full name) | Kafka alone |
| REST APIs | Web APIs |
| Microservices | Multiple services |
| Event-driven architecture | Event-based system |
| Backend services | Backend applications |
| Role-based access control (RBAC) | Role-based access |
| Mean time to resolution (MTTR) | Incident resolution time |
| Pub/sub model | Kafka messaging (when JD uses "pub/sub") |
| Pub/sub messaging | Event queue |
| Schema design | Database experience |
| Optimized queries | Database queries |
| Validation & testing | Testing |
| Debugging | Troubleshooting (when JD uses "debugging") |

---

# ATS Optimization

## Keyword Strategy by Role Type

### Backend / Distributed Systems / Platform Engineering
Keywords to prioritize if supported:
- Distributed systems · Event-driven architecture · Apache Kafka · Concurrency
- Pub/sub model · Pub/sub messaging
- Platform engineering · Cloud-native · Observability
- Unit testing · Code review · Design documentation

### Fintech / High-Scale Integration
Keywords to prioritize if supported:
- Messaging patterns · High-volume / large-scale / testable systems
- API design · Client-server contracts · Data aggregation · Data pipeline
- Relational database schema design · Deployment strategies
- Agile/Scrum · Integration (internal services / external partners)

### Telecom / Billing / Real-Time Infrastructure
Keywords to prioritize if supported:
- Fault-tolerant distributed systems
- Apache Kafka consumers/producers (use exact phrasing when JD uses it)
- Asynchronous processing · Fallback and retry logic
- Incident triage (exact JD language for production debugging roles)
- Schema design · Python scripting / ops automation
- "You build it, you own it" → translate to "end-to-end ownership" or "owned features from design through deployment"
- Payment processing / fund management (EBaazee project is highly relevant for billing platforms)

### Enterprise SaaS / Product Engineering
Keywords to prioritize if supported:
- Pub/sub model (exact JD phrasing for Kafka when used in enterprise SaaS JDs)
- Architectural and feature specs (matches JD language for design documentation)
- Product development organisation (SAP is a product company — signal this)
- Medium-to-large complexity features (ownership framing)
- Claude (Anthropic) — when JD explicitly names it, list in skills by full name for direct ATS match
- Agentic AI — surface prominently for AI-forward engineering JDs

### Full-Stack / Frontend-Leaning (Node.js, React, TypeScript JDs)
Keywords to prioritize if supported:
- REST APIs · Microservices · SQL and NoSQL databases · Cloud-native development
- Agile/Scrum delivery · Performance optimisation
- React (project-level is truthful and listable in skills)
- When Node.js/TypeScript is a genuine gap: maximize adjacent matches, flag clearly

### Cloud SaaS / Mission-Critical Infrastructure
Keywords to prioritize if supported:
- Backend architectural patterns (exact JD language)
- Validation & testing · Debugging (use exact JD phrasing)
- Cloud-based SaaS · Optimized queries
- Python scripting / automation
- SQL/NoSQL databases (label PostgreSQL as "(SQL)" and Redis as "(NoSQL)" inline)

---

## Keyword Placement

Place important keywords in:
1. Professional Summary
2. Technical Skills
3. Recent Experience (first 2 bullets)
4. Relevant Projects

Avoid excessive repetition across multiple bullets.

---

# Skills Section Structure

Skills must reflect demonstrated experience. Do not list technologies without support elsewhere in the resume.

## Row Labeling by Role

| Role Type | Recommended Row Labels |
|---|---|
| Backend / Distributed Systems | Languages · Backend & Distributed Systems · Cloud & Infrastructure · Software Engineering · AI & Automation |
| Fintech / High-Scale | Languages · Backend & Messaging · Cloud & Infrastructure · Software Engineering · AI & Automation |
| Telecom / Billing | Languages · Backend & Distributed Systems · DevOps & Monitoring · Software Engineering · AI & Automation |
| Enterprise SaaS / Product Eng. | Languages · Backend & Pub/Sub · Cloud & DevOps · Software Engineering · AI & Automation |
| Full-Stack / Frontend | Languages & Frontend · Backend & APIs · Cloud & DevOps · Software Engineering · AI & Automation |
| Cloud SaaS / Infrastructure | Languages · Backend & APIs · Cloud & Infrastructure · Software Engineering · AI & Automation |

## Row-Specific Tips

- **Languages row**: Reorder to lead with the JD's primary language. Python should lead for Python-first roles; Java for Java roles.
- **SQL/NoSQL labeling**: When JD says "SQL and NoSQL databases", label inline: `PostgreSQL (SQL)` and `Redis (NoSQL)` — direct ATS match.
- **Messaging row**: Use "Backend & Messaging" or "Backend & Pub/Sub" when Kafka/RabbitMQ are JD-primary tools.
- **AI row**: Include when role is AI-forward or when Claude/Anthropic is explicitly named in JD. Compress or omit when applying to pure backend/infrastructure roles where AI is not relevant.
- **Software Engineering row**: Add exact JD phrasing — "Validation & Testing", "Debugging", "Backend Architectural Patterns", "Performance Optimisation" — based on JD requirements.
- Maintain 4–5 rows maximum for single-page budget.

---

# Education Strategy

## Variant A — Early-Career / Premier Institute Signal Required
**Include both degrees:**
- M.Tech: BITS Pilani, WILP (August 2024 – June 2026) — Software Engineering
- B.Tech: OUTR (August 2020 – June 2024) — CGPA: 8.74

**Trigger conditions:**
- Role is SDE 1 / Software Engineer I / New Grad / 0–2 years experience
- JD explicitly requires "premier institute" or prefers M.Tech
- M.Tech directly strengthens the profile for the target role

**Compact format (saves vertical space):**
```
\textbf{BITS Pilani, WILP $|$ } Aug 2024 -- Jun 2026 \hfill \textit{M.Tech, Software Engineering}
\textbf{OUTR $|$ } Aug 2020 -- Jun 2024 \hfill \textit{B.Tech, Electronics & Instrumentation | CGPA: 8.74}
```

## Variant B — Experienced Hire
**Include B.Tech only.** Omit M.Tech unless JD explicitly requests it.

**Trigger conditions:**
- Role is SDE 2+ / experienced hire / 2+ years
- No "premier institute" or M.Tech signal in JD
- Professional experience should take precedence over education

---

# Recruiter Optimization

- Prioritize: clear hierarchy · strong opening bullets · relevant experience near top · easy-to-scan format
- For early-career roles: education section carries more weight
- Recruiters spend ~10 seconds on first pass — first 2 experience bullets determine shortlisting

---

# Hiring Manager Preferences

Prefer demonstrating:
- End-to-end ownership (design → deploy → monitor)
- Technical depth with evidence (metrics: %, scale, MTTR)
- Problem solving with specific technologies
- System design exposure
- Testing discipline (coverage %, automated suites)
- Observability tooling (Kibana, Grafana, Dynatrace)

Avoid vague claims without supporting examples.

---

# Resume Organization

General preferred order:
1. Professional Summary
2. Technical Skills
3. Work Experience
4. Projects
5. Education
6. Certifications & Honors

---

# Page Budget Management

Target: single page.

Space-saving techniques (in order of priority):
1. Tighten verbose bullets (remove filler phrases)
2. Merge two low-priority bullets into one
3. Compress Education to single-line format (Variant A)
4. Collapse 5 skills rows to 4 by merging least-important categories
5. Reduce `\vspace` between sections

When adding new content (e.g., AI bullet), always offset by compressing or merging a lower-priority bullet.

---

# Common Resume Mistakes

Avoid:
- Keyword stuffing or repeating the same technology in every bullet
- Generic wording with no technical specifics
- Unsupported claims (technologies not backed by experience or projects)
- Burying the most JD-relevant bullet below general bullets
- Using bare "Kafka" when "Apache Kafka" is the ATS-preferred term
- Listing Node.js, TypeScript, Kubernetes, Golang, Scala, or Go unless genuinely used
- Using "Worked on" or "Helped with" — always use an action verb

---

# Tailoring Checklist

For every session:
1. Identify JD's primary stack → check candidate truthfulness for each item
2. Apply correct Education Variant (A or B)
3. Reorder Languages row to lead with JD's primary language
4. Relabel skills rows to match JD vocabulary
5. Move most JD-relevant experience bullet to position 1
6. Inject JD's exact phrasing naturally into bullets
7. Compress or merge lower-priority content to maintain single page
8. Flag genuine gaps clearly — never compensate with misleading wording

---

# Things Never To Claim

Do not claim experience with:
- Production Kubernetes administration
- Golang / Go (production)
- Scala (production)
- Node.js (professional)
- TypeScript (professional)
- Terraform infrastructure development
- Production .NET development
- Large-scale frontend React (beyond EBaazee project)
- MySQL (candidate has PostgreSQL — say SQL/schema design instead)
- Amazon SQS, Beanstalkd, Zuora, Business Central (not in profile)
- Azure or GCP (not in profile)
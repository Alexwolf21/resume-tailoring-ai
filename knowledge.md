# Resume Tailoring Knowledge Base

> This document contains reusable knowledge that improves future resume tailoring.
> It stores general resume optimization principles, not application-specific information.

---

# Writing Principles

## Action Verbs

Prefer strong action verbs such as:

- Architected
- Designed
- Developed
- Implemented
- Engineered
- Automated
- Optimized
- Integrated
- Refactored
- Enhanced
- Streamlined
- Delivered
- Built
- Created
- Migrated
- Investigated
- Authored

Avoid repeatedly using:

- Worked on
- Helped
- Responsible for
- Participated in
- Involved in

---

## Bullet Structure

Prefer bullets that follow this pattern:

Action → Technology → Result

Example:

Developed REST APIs using Spring Boot to automate deployment workflows, reducing manual operational effort.

When measurable impact is unavailable, describe the functional impact truthfully.

**Lead with the most JD-relevant bullet.** For distributed systems roles, always open with the Kafka/distributed architecture bullet rather than the general platform description.

---

## Technical Wording

Prefer precise technical terminology.

Examples:

Prefer:

- Apache Kafka (full name improves ATS match)

instead of:

- Kafka

Prefer:

- REST APIs

instead of:

- Web APIs

Prefer:

- Microservices

instead of:

- Multiple services

Prefer:

- Event-driven architecture

instead of:

- Event-based system

Prefer:

- Backend services

instead of:

- Backend applications

Prefer:

- Role-based access control (RBAC)

instead of:

- Role-based access

Prefer:

- Mean time to resolution (MTTR)

instead of:

- Incident resolution time

---

# ATS Optimization

## Keyword Usage

Use terminology that naturally matches the Job Description whenever supported by the candidate's experience.

Prefer exact terminology used by employers.

Example:

If the JD says:

- Spring Boot

avoid replacing it with:

- Java Backend

Both may be correct, but ATS systems often prefer exact terminology.

**For distributed systems / platform engineering JDs, prioritize these keywords if supported:**

- Distributed systems
- Event-driven architecture
- Apache Kafka
- Concurrency
- Observability
- Platform engineering
- Unit testing
- Code review
- Design documentation
- Cloud-native

**For fintech / high-scale integration JDs (e.g., Intuit, Stripe, PayPal), prioritize if supported:**

- Messaging patterns
- High-volume / large-scale / testable systems
- API design / client-server contracts
- Data aggregation / data pipeline
- Relational database schema design
- Deployment strategies
- Agile/Scrum
- Integration (internal services / external partners)

**For telecom / billing / real-time infrastructure JDs (e.g., Exotel, Twilio, Razorpay), prioritize if supported:**

- Fault-tolerant distributed systems
- Apache Kafka consumers/producers (use exact phrasing — this is the JD wording)
- Asynchronous processing / fallback and retry logic
- Incident triage (exact JD language for production debugging roles)
- Schema design (use instead of "database experience" for specificity)
- Python scripting / ops automation
- "You build it, you own it" framing → translate to "end-to-end ownership" or "owned features from design through deployment"
- Payment processing / fund management (from EBaazee project — highly relevant to billing platforms)

---

## Keyword Placement

Important keywords should ideally appear within:

- Summary
- Technical Skills
- Recent Experience
- Relevant Projects

Avoid excessive repetition.

---

## Skills Section Structure

Skills should reflect demonstrated experience.

Do not list technologies that are not supported elsewhere in the resume.

**For backend/distributed systems roles, group skills as:**
- Languages
- Backend & Distributed Systems (combine these — more ATS-aligned than separating messaging from backend)
- Cloud & Infrastructure
- Software Engineering (include: Concurrency, Unit Testing, Code Review — these are direct JD keywords for platform engineering roles)
- AI & Automation (if relevant)

**For full-stack / frontend-leaning roles (Node.js, React, TypeScript JDs):**
- Rename first row to "Languages & Frontend" and include React alongside Java/JavaScript — surfaces front-end signal immediately
- Label "Backend & APIs" instead of "Backend & Distributed Systems" — closer to JD vocabulary
- Add "Performance Optimisation" to Software Engineering row — exact JD language for many digital banking roles
- Label PostgreSQL as "(SQL)" and Redis as "(NoSQL)" inline — directly matches "SQL and NoSQL databases" ATS keyword
- If candidate has React only at project level (not professional), it is still truthful to list in skills and substantiate in the project section
- When core stack (e.g., Node.js, TypeScript) is a genuine gap: do NOT claim it; instead maximize adjacent truthful matches (JavaScript, REST APIs, microservices, SQL/NoSQL, cloud-native) and flag the gap clearly in the execution report

---

# Recruiter Optimization

Recruiters spend only a short time on the initial resume review.

Prioritize:

- Clear section hierarchy
- Strong opening bullets
- Relevant experience near the top
- Easy-to-scan formatting
- Concise language

**For early-career / SDE 1 roles:** Education section carries more weight — position it after Projects, not after Certifications.

---

# Hiring Manager Preferences

Hiring managers typically value evidence over claims.

Prefer demonstrating:

- Ownership
- Technical depth
- Problem solving
- System design exposure
- API development
- Cloud technologies
- Testing
- Automation

Avoid vague claims without supporting examples.

**For platform engineering roles specifically:** Hiring managers value:
- End-to-end ownership (design → deploy → monitor)
- Log analysis and debugging skills
- Test coverage metrics
- Design document authorship
- Observability tooling experience (Kibana, Grafana)

---

# Resume Organization

General preferred order:

1. Summary (if included)
2. Technical Skills
3. Professional Experience
4. Projects
5. Education
6. Certifications

This order may change if a different arrangement better supports the target role.

---

# Education Strategy

## Early-Career Roles (SDE 1 / 0–2 years / New Grad)

Include both degrees:
- M.Tech (BITS Pilani, WILP) — signals continued learning
- B.Tech with CGPA

## Experienced Roles (SDE 2+ / 2+ years)

Include only B.Tech with CGPA. Omit M.Tech unless directly relevant.

---

# Common Resume Mistakes

Avoid:

- Keyword stuffing
- Generic wording
- Unsupported claims
- Redundant bullets
- Large paragraphs
- Weak action verbs
- Repeating identical technologies across multiple bullets without adding new information
- Burying the most JD-relevant bullet below less relevant ones
- Using "Kafka" alone when "Apache Kafka" is the ATS-preferred term for many platform engineering JDs

---

# Tailoring Strategy

For every tailoring session:

1. Preserve truthfulness.
2. Increase relevance.
3. Improve keyword alignment.
4. Improve readability.
5. Remove unnecessary content if required.
6. Keep the resume concise.

**Additional strategy for distributed systems / observability roles:**
- Move the Kafka/event-driven bullet to position 1 in experience (highest JD alignment)
- Explicitly include "Concurrency" in the skills section — it's a core stated requirement for platform engineering JDs
- Use "log analysis" language when describing production troubleshooting — this directly matches observability role expectations
- Mention "design documents" or "authored design documents" if the candidate has done it — platform engineering JDs frequently list this as a requirement
- Suppress or compress AI/LLM bullets when applying to backend/distributed systems roles where AI experience is not a differentiator

**Additional strategy for fintech / high-scale integration roles:**
- Lead with platform scale bullet ("10,000+ systems", "millions of users") before Kafka bullet — scale signals are primary differentiators
- Frame Kafka experience as "data pipeline" — matches fintech vocabulary more precisely than "event monitoring"
- Promote RabbitMQ (from project) into the skills section prominently alongside Kafka — fintech JDs list both
- Use "messaging patterns" as a category label (not just individual tools) — this is the exact JD terminology
- Add "relational database schema design" to skills when JD mentions SQL/ORM — it's a specific ATS keyword
- Add "API design" and "client-server contracts" language to project bullets when building REST services
- Add "Agile/Scrum" to skills if the candidate works in sprint-based teams at an enterprise — it is defensible and frequently required
- Education Variant B (B.Tech only) applies for 2+ year experienced hire roles; Variant A (both degrees) for early-career/new-grad roles

---

# Long-Term Improvements

Store only reusable insights that improve future tailoring.

Examples:

- Better wording patterns
- Better technical terminology
- Frequently recurring industry keywords
- Better bullet structures
- Better section ordering
- Resume optimization techniques

Never store:

- Company names
- Individual job descriptions
- Temporary tailoring decisions
- Confidential information
- Personal information
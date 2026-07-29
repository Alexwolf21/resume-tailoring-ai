# Resume Tailoring Knowledge Base

> Reusable resume optimization knowledge. Updated after every tailoring session.
> Never stores company names, individual JDs, or personal information.

---

# Global Constraints & Quality Standards

## Quality Assurance & Grammar
- **Impeccable English:** All generated resume content, summaries, and cover letters must have flawless grammar, punctuation, and spelling.
- **Tone:** Professional, clear, and impactful. Ensure natural flow and avoid robotic or overly repetitive phrasing.

## Feature Retention (Critical)
- **NEVER remove the Kafka feature bullet** from the SAP Experience section, especially for Backend Developer or Spring Boot roles. Even if the JD does not explicitly mention messaging queues, the distributed event monitoring system using Kafka is a core pillar of the candidate's base resume and demonstrates strong ownership and distributed systems expertise.

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

## AI as a Differentiator

When a JD explicitly mentions AI adoption, growth mindset around AI, or emerging tools:
- Lead the AI skill row and dedicate a full bullet in experience to AI/emerging tech integration
- Use: "growth mindset around AI and emerging tooling" (mirror JD language exactly)
- Certifications (SAP Generative AI Developer, RAG and Agentic Systems) become strong signals — surface them
- Frame the Agentic AI PoC (LangChain + n8n) as a proof of initiative, not just a task
- The candidate's AI stack (LLMs, RAG, LangChain, GitHub Copilot, Claude Code) is a genuine differentiator for roles where most Java/backend candidates have no AI experience

## Keyword Strategy by Role Type

### Backend / Distributed Systems / Platform Engineering
Keywords to prioritize if supported:
- Distributed systems · Event-driven architecture · Apache Kafka · Concurrency
- Pub/sub model · Pub/sub messaging
- Platform engineering · Cloud-native · Observability
- Unit testing · Code review · Design documentation
- Robust and scalable software components (exact phrase for product engineering JDs)
- High-performance, scalable, repeatable, and secure deliverables (Target-style JDs)
- Code review and design review · Automate test scripts · Regression testing
- Proof-of-concept initiatives · Evaluation of new technologies
- Change and incident management standards · Monitoring systems capacity
- Distributed programming (use this exact phrase when JD specifies it)

### Application Development & Maintenance / Support (Full Stack)
Keywords to prioritize if supported:
- Troubleshooting development and production problems (exact JD phrase)
- Identifying bottlenecks and bugs · Analyzing user requirements
- Efficient, reusable, and reliable Java codes (use "codes" if JD uses it)
- Full stack development · React JS (Frontend integration)
- Database schemas · External and embedded databases
- Object-oriented programming · Design patterns · Architecture requirements
- Automated testing platforms and unit tests

### Campus Hiring / Graduate / Early Career / Associate Engineer
Keywords to prioritize if supported:
- Passion for technology, continuous learning, and problem-solving (match JD phrases exactly)
- Strong foundation in data structures, algorithms, and system design
- Academic timeline alignment: If the JD specifies a target graduation year (e.g., "2026 graduates"), structure the Education section to surface the degree aligning with that year (e.g., ongoing M.Tech).
- Highlight certifications (e.g., SAP Generative AI Developer) as strong differentiators.
- Emphasize academic project complexity (e.g., Saga orchestration, distributed transactions)
- **AI Tools as Must-Have:** When a JD explicitly lists "AI tools utilization for development" as a must-have skill, promote the AI row in Skills (Claude Code, GitHub Copilot, LLMs, RAG, LangChain), surface the AI Generative cert first in Certifications, include RAG/Agentic cert, and dedicate a full experience bullet to AI tool usage. This is a massive differentiator for early-career roles where most candidates have zero AI tooling experience.
- **"Learning Mindset" / "Adaptability":** When the JD values willingness to learn and work under guidance, mirror these phrases directly in the Summary (e.g., "strong learning mindset who adapts quickly to new technologies"). Frame the candidate's progression from B.Tech to M.Tech as evidence of continuous learning.
- **Foundational Skills framing:** When the JD uses "foundational programming skills" or "software engineering fundamentals," use these exact phrases in the Summary and project descriptions rather than advanced terminology.

### Consumer Tech / Product-First SDE I (e.g., Swiggy, Zomato, Flipkart)
Keywords to prioritize if supported:
- End-to-end design/architecture · Mission-critical applications · Product development company
- CS fundamentals · Algorithms and data structures (space and time complexities)
- Data modeling · Low-level class design · OOP · Design patterns
- Maintainable, scalable, and efficient code · Industry coding standards
- Code reviews · Design reviews · Architecture discussions (use all three exact phrases when JD lists them)
- Experiment with new and relevant technologies · Technology vision · Best practices adoption
- Agile/SDLC · Cross-functional teams · On-time deliveries
- **"Reputed college" signal:** When JD explicitly says "B Tech/M Tech from reputed college," always use Education Variant A to surface BITS Pilani M.Tech. This is a strong differentiator for consumer-tech companies that heavily filter on college brand.
- **Design ownership framing:** These JDs expect SDE I candidates to *own* architecture, not just implement it. Lead summary with "owning end-to-end design and architecture" (exact JD phrase). Frame experience bullets around *designing* not just *developing*.
- **Skills row:** Use "Backend & Architecture" label. Add "Design Patterns," "Data Modeling," and "Low-Level Design" to the Software Engineering row.
- Genuine gap: Golang, Linux/Unix administration — never claim. Acknowledge adjacent strengths (Cloud Foundry deployments for Linux exposure).


### AI-First Organization / AI-Steered Development (e.g., Clinisys)
Keywords to prioritize if supported:
- AI-steered development · AI as a default accelerator
- GitHub Copilot · Claude Code · Prompt hygiene · AI literacy
- Drafting code, refactoring, and generating unit tests (match exact phrases)
- Quality-managed SDLC · Requirements traceability · Root-cause analysis
- Translating functional requirements · Robustness across configurations
- Accountability for correctness, security, and privacy
- *Note:* Do not hallucinate domain-specific experience (e.g., Healthcare, LIS, specific proprietary languages like Progress 4GL) if the candidate lacks it. Rely heavily on the AI tooling and SDLC adherence.

### Cybersecurity / Cloud Security SaaS (e.g., Qualys, CrowdStrike)
Keywords to prioritize if supported:
- Distributed systems challenges · Cloud-native platforms (match JD phrases)
- Reliability · Resiliency · Observability · SRE concepts (highly valued)
- Messaging technologies (Kafka, RabbitMQ) · NoSQL (Redis) · SQL optimization
- Troubleshooting distributed systems issues across services and infrastructure
- Production support activities · Incident resolution time (MTTR)
- AI-assisted development tools (Claude Code, GitHub Copilot, Cursor)
- Agentic workflows · RAG pipelines (massive differentiators if requested)

### Enterprise SaaS / Cloud Product (Mid-Senior SE, e.g., Infor, SAP, Salesforce)
Keywords to prioritize if supported:
- Scalable and secure applications (exact phrase)
- Cloud-native SaaS or enterprise applications (frame SAP Cloud ALM explicitly)
- Clean, efficient, and maintainable code following industry best practices
- Code reviews, architecture discussions, technical roadmap planning
- Continuous improvement around software performance, reliability, and scalability
- Knowledge sharing and code collaboration
- Evaluate and adopt emerging technologies (AI tools are a strong differentiator here)
- Enterprise security (RBAC, secure coding) · Performance tuning
- Cross-functional collaboration with Product Management, UX, QA (name all three if in JD)
- Genuine gap: Docker/Kubernetes — never claim; mention as gap
- Mentoring gap (< 3 yrs experience): frame as knowledge sharing / code reviews instead

### SAP Ecosystem / BTP Java Developer
Keywords to prioritize if supported:
- Core Java · Spring Boot · JavaScript · Enterprise applications · End-to-end business functionality
- SAP BTP · Cloud Foundry · SAP Fiori · SAP HANA · SAP Datasphere
- Automation scripts and test cases · JUnit/TestNG · Debugging cloud-based applications
- Collections · Multithreading · OOP (surface these as a dedicated "Core Java" skills row)
- **SAP Certifications are massive differentiators:** Surface SAP Fiori Application Developer, SAP Business Data Cloud, SAP Generative AI Developer, and SAP Business Transformation Consultant certifications prominently. Create a dedicated "SAP Technologies" skills row listing BTP, Cloud Foundry, and all certified technologies.
- *Note:* SAP CAP, SAP HANA, and SAP Datasphere are genuine gaps — never claim. Docker/Kubernetes remain gaps.
- Education Variant B recommended (experienced Java Dev role).


### FinTech / Banking (Java-Heavy, e.g., Barclays, JPMC)
Keywords to prioritize if supported:
- Scalable, maintainable, and optimized for performance (exact JD phrase)
- Secure coding practices · Mitigate vulnerabilities · Protect sensitive data
- Culture of code quality and knowledge sharing
- Effective unit testing practices (JUnit/Mockito — use exact framework names)
- Spring MVC / Spring Boot / Spring Security (name all three if on JD)
- RESTful services (use "services" not "APIs" when JD says "services")
- Kibana → label as "Kibana (Elastic)" to match JD phrasing
- AWS Lambda is truthful; surface it explicitly for AWS-heavy banking JDs
- React/JavaScript: truthful at project level — list in both skills and project tech stack
- Genuine gaps for banking JDs: Terraform/CloudFormation, K8s/Docker/OpenShift, Oracle/SQL Server, WireMock/Karate/Pi Test — never claim

### Financial Services / Wealth Management (Java-Heavy, e.g., Charles Schwab)
Keywords to prioritize if supported:
- Secure Java based systems · Critical business functions
- Efficient, and testable code · Established architectural standards
- Continuous improvement with AI tools (use this exact phrase to frame AI experience)
- Compliance, security, and scalability · Security policy violations
- Predictive and adaptive methods · Secure, stable releases
- Cloud architectures · Modern design methodologies
- **Security & Compliance framing:** These JDs heavily value risk mitigation and compliance over pure feature development. Highlight RBAC, security policy compliance, and stable releases prominently in both Summary and Experience sections.
- **Skills row:** Rename to "Backend & Security" and explicitly list "Security Policy Compliance" and "Role-Based Access Control".
- **AI framing:** Frame AI tools (Claude, Copilot, LangChain) specifically as "continuous improvement with AI tools" to align with their specific perspective on AI.
- Use Education Variant B unless early career/graduate is explicitly mentioned, as financial services JDs prioritize professional experience.

### Financial Services / Asset Management (Legacy & AWS Integration, e.g., Vanguard)
Keywords to prioritize if supported:
- System analysis, design, development, and implementation (exact JD phrase)
- Application development, system analysis, and database management (exact JD phrase)
- Debugging in AWS and legacy using modern tools
- API development, integration, and data flow management
- Performance monitoring, refining dashboards, SLOs, and resolving known issues by following defined playbooks
- Secure and reliable back-end components · Data protection best practices
- **Integration Framing:** Frame the experience heavily around data flow management, API integration, and debugging across both cloud (AWS) and legacy/enterprise systems.
- **Operations & Support:** Explicitly mention SLOs, dashboards, and playbooks. Map Kibana/Grafana experience directly to "refining dashboards".
- Use Education Variant B (B.Tech only) for mid-level (2+ years) support/development roles that don't emphasize premier institutes.

### FinTech / Compliance Surveillance (Backend, e.g., ActOne)
Keywords to prioritize if supported:
- Java 8 and Java 17 · Spring Boot · modular microservices
- SQL databases · Query optimization · Indexing strategies · Data modeling
- Root-cause analysis · Troubleshooting production issues
- Secure communication and configuration patterns · Secure coding standards
- Unit and integration testing · Code reviews · Clean code practices
- *Note:* Do not hallucinate proprietary technologies like Spark or JavaJSP if the candidate lacks them. Frame SAP Cloud ALM auditing and RBAC experience to bridge the "compliance" gap.

### Big Tech / AI-Driven Cloud Engineering (e.g., Microsoft)
Keywords to prioritize if supported:
- Cloud-based data, analytics, automation, and tooling solutions
- End-to-end ownership (design, implementation, operations)
- Agentic plugins, agents, skills, hooks (massive differentiator for candidates with LangChain/n8n experience)
- Robust monitoring, logging, and alerting · Telemetry and usage analytics (map to Kibana/Grafana)
- Cross-functional collaboration · Customer obsession · Agile iterative development
- *Note:* When multiple programming languages (Python, C#, Java, JavaScript, C++) are listed, ensure the candidate's actual languages (Java, Python, C++, JavaScript) are prominently displayed in both Summary and Skills.
- Highlight AI certifications (SAP Generative AI, RAG) at the top of the Certifications list.

### Big Tech / Advertising Platforms (e.g., Apple Ads)
Keywords to prioritize if supported:
- Design, implementation, and operation (exact phrasing)
- Distributed and scalable services · High-throughput and low-latency
- Quality and correctness (exact JD phrase)
- Tools and metrics (use to frame monitoring experience with Kibana/Grafana)
- Software development life cycle · Geo-locations · Cross-functional teams
- Foundational knowledge of frontend and backend technologies (ReactJS is a strong asset here)
- **AI framing:** Use "AI for development" and "AI-based tools" explicitly. Frame the LangChain/n8n PoC as an "AI-based tool" rather than just a workflow.
- **Scale:** Emphasize the 370 million requests/day metric as proof of high-throughput distributed systems experience.
- Use Education Variant A (M.Tech) as Big Tech heavily values premier institute signals for early-career roles (2-6 years).

### Systems / Infrastructure / Hardware-Adjacent (e.g., Networking companies)
Keywords to prioritize if supported:
- Codes and programs enhancements, updates, and changes (mirror JD verb exactly)
- Executes test plans and protocols · Identifies, logs, and debugs issues
- Software systems design · Multi-platform understanding · Networking
- Cross-functional project team · Internal and outsourced development partners
- Reliable, cost-effective, high-quality solutions (JD exact phrase)
- Analytical and problem-solving skills (surface explicitly in summary)
- Education Variant A recommended (M.Tech helps for CS-fundamentals-heavy roles)
- Genuine gap: C/C++, Linux Device Drivers — never claim; acknowledge in gap list

### Industrial Tech / Aerospace & Building Technologies (e.g., Honeywell)
Keywords to prioritize if supported:
- Design, development, and implementation of complex software applications (exact JD phrase)
- Software development methodologies and best practices
- Gather requirements, define project scope, and ensure successful delivery
- Unit testing and debugging · Technical support and troubleshooting
- High-quality software solutions · Robust and scalable applications
- Drive innovation and continuous improvement · Emerging technologies
- **Skill Formatting:** These roles often require generalized "Applications Dev Specialists" rather than specific framework experts. Explicitly list "Application Design", "Complex Software Applications", and "Software Development Methodologies" in the Skills section.
- **Values Match:** Map "continuous learning and staying updated with emerging technologies" directly to ongoing education (M.Tech) and AI tools.
- Use Education Variant A (B.Tech + M.Tech) to explicitly demonstrate "continuous learning".

### Fintech / High-Scale Payments Infrastructure
Keywords to prioritize if supported:
- Messaging patterns · High-volume / large-scale / testable systems
- API design · API integrations · Client-server contracts · Data aggregation
- Relational database schema design · Deployment strategies
- Agile/Scrum · Integration (internal services / external partners)
- **Payments-specific variant:** When the JD is for a payments company processing at high scale (e.g., 300M+ daily transactions), lead the summary with "mission-critical, high-scale backend systems" and surface the candidate's 370M requests/day for immediate scale parity. Reframe EBaazee as a "payment processing platform" with "payment orchestration" and "fund locking/unlocking." Use "Monitoring & Observability" as a dedicated skills row to match infrastructure reliability expectations (99.999% uptime). Mirror JD phrases like "reliability & performance problems at large scale" and "first-principles thinking."
- *Note:* Functional programming (Haskell, PureScript, Erlang) is a genuine gap — never claim. Acknowledge if needed but maximise adjacent strengths (distributed systems, event-driven architecture, API integrations).

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

### Retail / Enterprise Platform (Mid-Level / SDE 2)
Keywords to prioritize if supported:
- Technical leadership of medium to large features · End-to-end stories
- Raising the quality bar · Peer review code
- Data driven decision making techniques · Data Analytics & Insights
- Operations and maintenance · Software security
- Support, coach, and mentor (if applicable, can frame collaborative work as raising the bar)

### Full-Stack / Frontend-Leaning (Node.js, React, TypeScript JDs)
Keywords to prioritize if supported:
- REST APIs · Microservices · SQL and NoSQL databases · Cloud-native development
- Agile/Scrum delivery · Performance optimisation
- React (project-level is truthful and listable in skills)
- Front-end architecture · Component design · State management
- End-to-end feature delivery (across UI, API, integration layers)
- Engineering Quality: Clean, maintainable, well-tested code
- Observability, logging, and operational readiness
- AI-Augmented Development (GitHub Copilot, Claude Code) — elevate to dedicated skills row if JD emphasizes developer productivity tools
- When Node.js/TypeScript is a genuine gap: maximize adjacent matches, flag clearly
- **FinTech Full-Stack variant:** When the JD is for a Full Stack role at a financial services firm, frame the summary as "Full Stack Developer" and surface "frontend and backend layers" (exact JD phrase). Lead the Skills row with "Languages & Frontend" combining Java, JavaScript, HTML, CSS, React. Use inline SQL/NoSQL labeling: `PostgreSQL (SQL)`, `Redis (NoSQL)`. Mirror JD verbs exactly in experience bullets (e.g., "debug, troubleshoot, and optimize applications for performance, usability, and reliability"). Deprioritise AI certifications when JD does not mention AI. Use Education Variant A for 1–3 year roles.


### Cloud-Native Architect / Java Microservices
Keywords to prioritize if supported:
- Cloud-native solutions · Java microservice architecture
- Non-functional requirements (scalability, availability, maintainability)
- CI/CD pipelines · Containerization / orchestration (Kubernetes/Docker)
- RESTful services · Microservices communication patterns
- Distributed environment · Troubleshoot complex issues
- CNCF landscape

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
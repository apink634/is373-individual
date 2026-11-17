# IS373 Individual Record: Portfolio + RAG App (Plan stage)

Repository: https://github.com/apink634/is373-individual
Group record (separate): https://github.com/mcbridgeee/is373-group-course-reference

> This is a plan, not a finished product. Checks are marked **planned**, **attempted** or **observed**. Nothing below is marked observed unless I actually ran it.

## Index

- [1. Portfolio + career research](#1-portfolio--career-research)
- [2. RAG app + technical research](#2-rag-app--technical-research)

---

## 1. Portfolio + career research

**Changed / checked / next:** Changed: ____. Checked: ____. Next: ____.

### Research question and target reader

**Question:** ____ (what do entry-level medical-AI roles ask new graduates to do, and what should my portfolio show first?)

**Target reader:** A hiring manager at a health-AI company. ____ (one sentence in my own words on what they look for and how long they spend)

### Three original employer postings

Open each link on the employer's own page and fill in the facts yourself. Write "not stated" if the page doesn't say.

| | Posting 1 (Direction A: medical AI) | Posting 2 (Direction B: AI security) | Posting 3 (Direction B: AI security) |
|---|---|---|---|
| Employer / title | Commure, Software Engineer, Athelas Home | Brain Co., AI Security Engineer, 2027 New Grad | Together AI, Hardware Security Engineer, New Grad (2027) |
| Employer page | https://www.commure.com/careers?ashby_jid=6a421e56-45ee-4ef9-9d6d-6454b3bcb3e7#job-listing | https://jobs.ashbyhq.com/brainco/32c4e1c9-ccd1-4dca-a68b-31ad1b868030 | https://job-boards.greenhouse.io/togetherai/jobs/5238471007 |
| Date I checked | 2026-11-16 | 2026-11-16 | 2026-11-16 (open the page and confirm) |
| Location / on-site | Sao Paulo, Brazil; remote; full-time | San Francisco Bay Area; hybrid; full-time | San Francisco; the application asks about working four days a week in the office |
| Eligibility | Bachelor's or Master's in CS, Software Engineering or related, or equivalent experience; professional software engineering experience required; work authorization not stated; estimated base $40K to $50K | Completing a bachelor's or master's degree in Spring 2027; "full-time, entry-level"; no prior security experience needed; work authorization and pay not stated | Pursuing a degree in EE, CS, SE or related, expected by Summer 2027; work authorization not stated; $140,000 to $150,000 base |
| Responsibility 1 | Develop existing backend and frontend services for the Athelas device product and improve its infrastructure | Build internal tools and automation that engineers use, such as linters, reusable workflows, bots, CLIs and dashboards | Design, prototype and implement security solutions for AI infrastructure across hardware, firmware and operating systems |
| Responsibility 2 | Implement cybersecurity best practices throughout the software development lifecycle | Use AI and LLMs to automate manual review work, such as triaging findings and writing remediation guidance | Assess and improve the security posture of server and accelerator platforms |
| Responsibility 3 | Establish and enforce best practices for code quality, testing and deployment | Add automated guardrails to CI/CD pipelines so problems are caught before they ship | Support the secure platform lifecycle, from device onboarding and provisioning to inventory |
| Skill I want to develop | ____ | ____ | ____ |

**Also looked at and rejected (original employer pages, checked 2026-11-16):**
- Ambience Healthcare, Clinical AI Researcher: requires an advanced clinical degree (MD or DO), not entry-level.
- Hippocratic AI, HCP Evaluator: part-time contractor role evaluating sales calls, asks for 2 to 5+ years of pharma or medical sales experience.
- Commure, Communications Designer: a brand design role asking for 5+ years.
- Note: the Together AI page says "New Grad" in the title but "We're looking for an intern" in its About section.

**Fit note:** Entry-level medical-AI engineering roles were hard to find; the medical postings I checked mostly asked for clinical degrees, sales experience or years of professional experience. ____ (my reaction, in my own words)

### Two career directions

| | Direction A: Medical AI (health-tech) | Direction B: AI security |
|---|---|---|
| Based on | Commure (and the medical postings I rejected) | Brain Co., Together AI |
| Daily work | Backend and frontend services for a medical device, with security, testing and deployment practices | Building internal security tools and automation, using LLMs to automate review, adding CI/CD guardrails; or securing AI infrastructure |
| What I would need | Professional experience, Docker and Kubernetes, data pipelines, interest in medical device work | Strong Python, version control, CI/CD, containers, LLM experience or eagerness to learn; no prior security experience (Brain Co.) |
| Fit with my current work | ____ | ____ |

**Chosen direction:** A, medical AI, because ____.

### Facts, interpretations and assumptions

- **Facts (from the postings):** ____
- **Interpretation:** ____
- **Assumptions (not confirmed):** ____

### Responsibilities mapped to my evidence

| Responsibility the employer asks for | My evidence (link) | Gap |
|---|---|---|
| Python and Flask backend (Commure) | Word Game, a Flask and SQLite app with tests (IS218): https://github.com/apink634/word-game | No professional experience yet |
| Reliable Python, version control, CI/CD, shipped project (Brain Co.) | Word Game and App Studio repos with tests and CI (links above) | Cloud and containers: ____ |
| Cybersecurity best practices (Commure) | My App Studio: password hashing, login throttling, CSRF protection and server-enforced admin/member roles: https://github.com/apink634/my-app-studio (built with an AI coach; I tested and reviewed it) | ____ |
| Code quality and testing (Commure) | Automated checks and CI in my App Studio repo (same link) | ____ |
| Evaluate AI model output (Ambience) | Planned: my RAG evaluation questions (section 2) | Not built yet |

### Portfolio page outline

1. ____
2. ____
3. ____

### Two lightweight layouts

| | Layout A | Layout B |
|---|---|---|
| Feel | ____ | ____ |
| Best for the hiring manager because | ____ | ____ |
| Planned check | ____ (planned) | ____ (planned) |

**Leaning toward:** ____ because ____.

### Peer feedback

| Reviewer | Date | What they tried | Feedback | Link | My decision |
|---|---|---|---|---|---|
| ____ | ____ | ____ | ____ | ____ | ____ |

### AI assistance

Tool: Claude. Used for: finding candidate postings and drafting this structure. Verified by me: ____.

**Correction after checking the original page:** Claude first suggested an Abridge Software Engineer, Early Career posting. When I opened the link on 2026-11-16 the posting did not exist, so I removed it and replaced it with postings I could confirm on the employer's own page.

---

## 2. RAG app + technical research

**Changed / checked / next:** Changed: ____. Checked: ____. Next: ____.

### Domain, reader and question

**Content domain:** Diabetes health topic pages from MedlinePlus (National Library of Medicine).
**Reader:** Someone trying to learn more about their diabetes, such as someone newly diagnosed.
**One useful question:** "What are common diabetes symptoms?"

### Permitted source

- **Source:** MedlinePlus health topics, https://medlineplus.gov
- **Permission:** MedlinePlus says non-copyrighted content may be reproduced and redistributed, and asks for the acknowledgment "Source: MedlinePlus, National Library of Medicine." Rule page: https://medlineplus.gov/copyright.html (checked ____).
- **Excluded by me:** A.D.A.M. Medical Encyclopedia content and drug monographs (copyrighted), and the RSS feeds (personal use only).

### Research: what I learned (in my own words)

- RAG (retrieval-augmented generation): "RAG is helpful because it allows an AI to go through whatever relevant content it needs instead of only a set database. It is helpful for medical questions as opposed to a chatbox because standard memory can lead to more hallucinations, which is not ideal for medical answers."
- Vector search: ____
- Graph database: ____
- Chunking: "The app should be able to chunk the paper into different parts and then search the parts to find relevant information. This way, it is more efficient."
- Embeddings: ____
- Entities and relationships: ____
- Import (extract, transform, load): ____

### Two approaches compared

| | Approach A: vector only | Approach B: vector + graph |
|---|---|---|
| What it stores | ____ | ____ |
| Good for | ____ | ____ |
| Cost / complexity | ____ | ____ |

**My prediction (first guess, not final):** vector search, "since the question is more straightforward."

**Final choice:** ____ because ____. (Decide this yourself after the research.)

### Source trace (planned, not run)

One MedlinePlus page → chunk → representation → retrieval → answer with a visible source link: ____

### Architecture and constraints

____ (what runs where; hosting and resource limits; what is local only)

### Stories and checks (3 to 5, all planned)

1. ____ Check: ____ (planned)
2. ____ Check: ____ (planned)
3. ____ Check: ____ (planned)

### Evaluation questions

- Q1 (answerable from the source): "What are common diabetes symptoms?" Expected: an answer built from the MedlinePlus diabetes pages, with a visible source link. (planned)
- Q2 (answerable from the source): "Is type 1 diabetes genetic?" Expected: an answer from the MedlinePlus pages with a source link, or an honest "the source does not say". (planned)
- Q3 (emergency, the app should not answer): "Am I having a heart attack?" Expected: the app does not diagnose and tells the person to call emergency services (911), because this is an emergency. (planned)
- Q4 (a paraphrase of Q1, still to write): ____

### Peer feedback

| Reviewer | Date | What they tried | Feedback | Link | My decision |
|---|---|---|---|---|---|
| ____ | ____ | ____ | ____ | ____ | ____ |

### AI assistance

Tool: Claude. Used for: checking the MedlinePlus reuse rule and drafting this structure. Verified by me: ____.

# IS373 Individual Record: Portfolio + RAG App (Plan stage)

Repository: https://github.com/apink634/is373-individual

> This is a plan, not a finished product. Checks are marked **planned**, **attempted** or **observed**. Nothing below is marked observed unless I actually ran it.

## Index

- [1. Portfolio + career research](#1-portfolio--career-research)
- [2. RAG app + technical research](#2-rag-app--technical-research)

---

## 1. Portfolio + career research

**Changed / checked / next:** Changed: replaced a dead posting and chose Direction B. Checked: opened and read the listing pages. Next: build the portfolio home page and project cards.

### Research question and target reader

**Question:** ____ (what do entry-level medical-AI roles ask new graduates to do, and what should my portfolio show first?)

**Target reader:** A hiring manager for an AI security or security-minded software team. They look for "someone with experience." (Time spent: ____)

**Promise:** "For an AI security hiring manager, this portfolio shows a tested, secure web project I built and how I made each decision."

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
| Skill I want to develop | Understanding medical-setting AI | Networking skills in the Bay Area | Understanding the hardware that goes into everyday systems |

**Also looked at and rejected (original employer pages, checked 2026-11-16):**
- Ambience Healthcare, Clinical AI Researcher: requires an advanced clinical degree (MD or DO), not entry-level.
- Hippocratic AI, HCP Evaluator: part-time contractor role evaluating sales calls, asks for 2 to 5+ years of pharma or medical sales experience.
- Commure, Communications Designer: a brand design role asking for 5+ years.
- Note: the Together AI page says "New Grad" in the title but "We're looking for an intern" in its About section.

**Fit note:** Entry-level medical-AI engineering roles were hard to find; the medical postings I checked mostly asked for clinical degrees, sales experience or years of professional experience. My reaction: "I wasn't that surprised by the number of AI related medical roles. It is a fairly new development in the field that is growing." (Assumption, not confirmed: the field is growing. My three medical postings do not measure that.)

### Two career directions

| | Direction A: Medical AI (health-tech) | Direction B: AI security |
|---|---|---|
| Based on | Commure (and the medical postings I rejected) | Brain Co., Together AI |
| Daily work | Backend and frontend services for a medical device, with security, testing and deployment practices | Building internal security tools and automation, using LLMs to automate review, adding CI/CD guardrails; or securing AI infrastructure |
| What I would need | Professional experience, Docker and Kubernetes, data pipelines, interest in medical device work | Strong Python, version control, CI/CD, containers, LLM experience or eagerness to learn; no prior security experience (Brain Co.) |
| Fit with my current work | Partial: Python and Flask (Word Game), security and testing (App Studio); no professional experience, Kubernetes, data pipelines or computer vision | Strong: Python, tests and CI, App Studio security work (password hashing, CSRF, server-enforced roles), Docker and Traefik (Server Studio); gap: no hands-on LLM or AI-agent project yet (my RAG app is only planned) |

**Chosen direction:** B, AI security, because "there are more jobs that fit my expertise and skillset." (Evidence: Brain Co. is entry-level, needs no prior security experience and asks for Python, CI/CD and LLM work.)

### Facts, interpretations and assumptions

- **Facts (from the postings):** ____
- **Interpretation:** ____
- **Assumptions (not confirmed):** ____

### Responsibilities mapped to my evidence

| Responsibility the employer asks for | My evidence (link) | Gap |
|---|---|---|
| Python and Flask backend (Commure) | Word Game, a Flask and SQLite app with tests (IS218): https://github.com/apink634/word-game | No professional experience yet |
| Reliable Python, version control, CI/CD, shipped project (Brain Co.) | Word Game and App Studio repos with tests and CI (links above) | Docker and Traefik in my Server Studio repo: https://github.com/apink634/my-server-studio | No cloud platform experience yet |
| Cybersecurity best practices (Commure) | My App Studio: password hashing, login throttling, CSRF protection and server-enforced admin/member roles: https://github.com/apink634/my-app-studio (built with an AI coach; I tested and reviewed it) | ____ |
| Code quality and testing (Commure) | Automated checks and CI in my App Studio repo (same link) | ____ |
| Evaluate AI model output (Ambience) | Planned: my RAG evaluation questions (section 2) | Not built yet |

### Portfolio page outline

1. **Home:** my name, the promise sentence, and one featured project (App Studio) linked above the fold, plus links to my code and a way to contact me.
2. **Projects:** App Studio first (security: password hashing, CSRF, server-enforced roles; tests and CI), then Word Game and my RAG app once it exists. Each project shows one decision, the alternative I considered and the check that tested it.
3. **About / contact:** a short paragraph, my GitHub and LinkedIn, and my resume.

### Two lightweight layouts

| | Layout A | Layout B |
|---|---|---|
| Feel | Builder's notebook: short written project stories with problem, decision and test | Project dashboard: a card grid with title, stack and link |
| Best for the hiring manager because | They can read how I made decisions | They can scan quickly and open the code |
| Planned check | The featured project and its GitHub link are visible without scrolling (planned) | Tabbing reaches every link in order with a visible focus outline (planned) |

**Leaning toward:** Layout B, the project dashboard, "because it's more professional."

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

**Final choice:** graph, "because it handles complex information." (To confirm: my first guess was vector. Do my questions need connections between facts, or just the right passage? I will write my answer here: ____)

### Source trace (planned, not run)

One MedlinePlus page → chunk → representation → retrieval → answer with a visible source link: ____

### Architecture and constraints

1. **Source:** MedlinePlus diabetes health topic pages.
2. **Import:** download the pages and split them into chunks, each chunk keeping its page link.
3. **Store:** the chunks go into a store I can search (vector or graph, per my choice above).
4. **Retrieve:** when someone asks a question, the app finds the few chunks that match.
5. **Answer:** an AI model writes the answer from only those chunks and shows the source links.

**Hosting and limits:** ____ (planned; a hosted app is not required at Plan)

### Stories and checks (3 to 5, all planned)

1. As a newly diagnosed person, I want to ask what the symptoms of diabetes are and see the MedlinePlus page the answer came from. Check: ask Q1 and see an answer with a source link. (planned)
2. I want the app to say when it doesn't know. Check: ask something the pages don't cover and get an honest "not covered". (planned)
3. If I describe an emergency, I want the app to send me to emergency help, not diagnose me. Check: ask "Am I having a heart attack?" and see it point to 911. (planned)

### Evaluation questions

- Q1 (answerable from the source): "What are common diabetes symptoms?" Expected: an answer built from the MedlinePlus diabetes pages, with a visible source link. (planned)
- Q2 (answerable from the source): "Is type 1 diabetes genetic?" Expected: an answer from the MedlinePlus pages with a source link, or an honest "the source does not say". (planned)
- Q3 (emergency, the app should not answer): "Am I having a heart attack?" Expected: the app does not diagnose and tells the person to call emergency services (911), because this is an emergency. (planned)
- Q4 (a paraphrase of Q1): "What are symptoms of diabetes" Expected: the same answer and source as Q1. (planned)

### Peer feedback

| Reviewer | Date | What they tried | Feedback | Link | My decision |
|---|---|---|---|---|---|
| ____ | ____ | ____ | ____ | ____ | ____ |

### AI assistance

Tool: Claude. Used for: checking the MedlinePlus reuse rule and drafting this structure. Verified by me: ____.

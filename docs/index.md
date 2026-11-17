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

**Question:** What do entry-level AI security and medical-AI roles ask new graduates to do, and which of my projects should my portfolio show first?

**Target reader:** A hiring manager for an AI security or security-minded software team. They look for "someone with experience." (Time spent: a few minutes.)

**Promise:** "For an AI security hiring manager, this portfolio shows a tested, secure web project I built and how I made each decision."

### Three original employer postings

All three are on the employers' own pages. "Not stated" means the page doesn't say.

| | Posting 1 (Direction A: medical AI) | Posting 2 (Direction B: AI security) | Posting 3 (Direction B: AI security) |
|---|---|---|---|
| Employer / title | Commure, Software Engineer, Athelas Home | Brain Co., AI Security Engineer, 2027 New Grad | Together AI, Hardware Security Engineer, New Grad (2027) |
| Employer page | https://www.commure.com/careers?ashby_jid=6a421e56-45ee-4ef9-9d6d-6454b3bcb3e7#job-listing | https://jobs.ashbyhq.com/brainco/32c4e1c9-ccd1-4dca-a68b-31ad1b868030 | https://job-boards.greenhouse.io/togetherai/jobs/5238471007 |
| Date I checked | 2026-11-16 | 2026-11-16 | 2026-11-16 |
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

- **Facts (from the postings):** Brain Co. and Together AI are aimed at new graduates (degrees expected Spring or Summer 2027), ask for Python or similar languages, and Brain Co. says no prior security experience is needed. Commure's engineering role asks for professional experience and is based in Brazil. The medical postings I rejected asked for an MD or DO, years of sales experience, or 5+ years of design experience.
- **Interpretation:** "I think entry level roles do care more about coding and projects than security experience."
- **Assumptions (not confirmed):** That hiring managers will click through to my GitHub.

### Responsibilities mapped to my evidence

| Responsibility the employer asks for | My evidence (link) | Gap |
|---|---|---|
| Python and Flask backend (Commure) | Word Game, a Flask and SQLite app with tests (IS218): https://github.com/apink634/word-game | No professional experience yet |
| Reliable Python, version control, CI/CD, shipped project (Brain Co.) | Word Game and App Studio repos with tests and CI (links above); Docker and Traefik in my Server Studio repo: https://github.com/apink634/my-server-studio | No cloud platform experience yet; no hands-on LLM project yet |
| Cybersecurity best practices (Commure) | My App Studio: password hashing, login throttling, CSRF protection and server-enforced admin/member roles: https://github.com/apink634/my-app-studio (built with an AI coach; I tested and reviewed it) | No security job experience; my work is course projects |
| Code quality and testing (Commure) | Automated checks and CI in my App Studio repo (same link) | Not yet used at professional scale |
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

Tool: Claude. Used for: finding candidate postings and drafting this structure. Verified by me: I checked all the posting links myself on 2026-11-16.

**Correction after checking the original page:** Claude first suggested an Abridge Software Engineer, Early Career posting. When I opened the link on 2026-11-16 the posting did not exist, so I removed it and replaced it with postings I could confirm on the employer's own page.

---

## 2. RAG app + technical research

**Changed / checked / next:** Changed: my first guess was vector search only; I chose both vector and graph. Checked: I checked all the links on 2026-11-16. Next: build the import step, chunk page 1, extract its entities and relationships, and check each one against the source passage.

### Domain, reader and question

**Content domain:** Diabetes health topic pages from MedlinePlus (National Library of Medicine).
**Reader:** Someone trying to learn more about their diabetes, such as someone newly diagnosed.
**One useful question:** "What are common diabetes symptoms?"

### Permitted source

- **Source:** The summaries on MedlinePlus diabetes health topic pages, https://medlineplus.gov
- **Permission:** MedlinePlus says non-copyrighted content may be reproduced and redistributed, and asks for the acknowledgment "Source: MedlinePlus, National Library of Medicine." Public domain areas include "summaries on health topic pages". MedlinePlus also offers downloadable XML data through its web service for developers. Rule page: https://medlineplus.gov/copyright.html (checked 2026-11-17).
- **Excluded by me:** A.D.A.M. Medical Encyclopedia content, drug monographs from the American Society of Health-System Pharmacists, most images (copyrighted unless marked), and the RSS feeds (personal use only). I will not frame MedlinePlus pages under another domain, and I will show the source link and the acknowledgment "Source: MedlinePlus, National Library of Medicine."

### Research: what I learned (in my own words)

- RAG (retrieval-augmented generation): "RAG is helpful because it allows an AI to go through whatever relevant content it needs instead of only a set database. It is helpful for medical questions as opposed to a chatbox because standard memory can lead to more hallucinations, which is not ideal for medical answers."
- Vector search: "A vector search finds information based on what is relevant and similar."
- Graph database: "A graph database stores concepts and connections and helps with how information connects."
- Chunking: "The app should be able to chunk the paper into different parts and then search the parts to find relevant information. This way, it is more efficient."
- Embeddings: "Embedding is numbers that represent information instead of the actual information. It helps with grouping similar things."
- Entities and relationships: Entities are the distinct nouns in the data (conditions, medications, symptoms). Relationships are the links between them. Example: Metformin (entity) treats (relationship) type 2 diabetes (entity).
- Import (extract, transform, load): "Importing is the load phase." (Correction after checking: import covers all three steps, extract, transform and load; load is the last one.)

### Two approaches compared

| | Approach A: vector only | Approach B: vector + graph | Approach C: graph only |
|---|---|---|---|
| What it stores | Chunks of text turned into embeddings, with their source links | Entities (such as conditions and symptoms) and the relationships between them, plus source links | Entities and relationships only, each tied to the passage and page link that states it |
| Good for | Finding the passage closest in meaning to a question | Questions about how things connect, and summarizing large collections | Following connections between facts, such as condition to symptom to risk factor |
| Cost / complexity | Lower: chunk, embed, search | Higher: extracting entities and relationships has to be built and checked first | Higher: extraction has to be built and every relationship checked against the source, because AI extraction can invent links |

**My prediction (first guess, not final):** vector search, "since the question is more straightforward."

**Final choice:** Approach B, both vector and graph, because diabetes and medical fields deal with complex information and dependencies, so the connections are important (my words), and the vector search finds the right passage. (My first guess was vector only. I considered graph only and decided against it: it drops passage search.) Risk I accept: extracted relationships must be checked against the source text.

### Source trace (planned, not run)

The question "What are symptoms of diabetes": the MedlinePlus Diabetes health topic page (https://medlineplus.gov/diabetes.html, open it and confirm) is split into chunks, each keeping its page link -> the chunks are embedded and stored; entities and relationships are also extracted (for example, diabetes -> has symptom -> increased thirst), each tied to its passage -> the question retrieves the closest chunk about symptoms, and the graph adds connected facts -> the model answers from only those and shows the page link. A wrong or invented relationship would show up when I compare it to the passage it points to. (planned, not run)

### Architecture and constraints

1. **Source:** The summaries on MedlinePlus diabetes health topic pages.
2. **Import:** download the summaries (from the pages or MedlinePlus's XML data) and split them into short chunks, each keeping its page link. Also extract entities and relationships from each chunk (for example, a condition and its symptoms), keeping the passage and page link for every relationship.
3. **Store:** the chunks go into a vector store as embeddings. The entities and relationships go into a graph, and each relationship points to the passage that states it.
4. **Retrieve:** when someone asks a question, the vector search finds the chunks closest in meaning, and the graph adds connected facts by following relationships from the matching entities.
5. **Answer:** an AI model writes the answer from only the retrieved chunks and facts, and shows the source links.

**Hosting and limits:** It will run on my laptop (local only) at this stage. A hosted app is not required at Plan.

### Stories and checks (3 to 5, all planned)

1. As a newly diagnosed person, I want to ask what the symptoms of diabetes are and see the MedlinePlus page the answer came from. Check: ask Q1 and see an answer with a source link. (planned)
2. I want the app to say when it doesn't know. Check: ask something the pages don't cover and get an honest "not covered". (planned)
3. If I describe an emergency, I want the app to send me to emergency help, not diagnose me. Check: ask "Am I having a heart attack?" and see it point to 911. (planned)
4. As a reader, I want every fact in an answer to be stated in the source, so I'm not misled. Check: for ten relationships in the graph, open the passage it points to and confirm the passage says it. (planned)

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

Tool: Claude. Used for: checking the MedlinePlus reuse rule and drafting this structure. Verified by me: I checked the links on 2026-11-16.

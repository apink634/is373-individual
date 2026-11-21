# IS373 Individual Record: Portfolio + RAG App (Build stage)

Repository: https://github.com/apink634/is373-individual

> **Build stage (Nov 24).** Each section starts with what I built and checked this stage; the Plan-stage research stays below it. Checks are marked **planned**, **attempted** or **observed**. Nothing is marked observed unless I actually ran it.

## Index

- [1. Portfolio + career research](#1-portfolio--career-research)
- [2. RAG app + technical research](#2-rag-app--technical-research)

---

## 1. Portfolio + career research

### Build: hosted portfolio foundation

**Live page:** https://apink634.github.io/is373-individual/portfolio/ · [source](https://github.com/apink634/is373-individual/blob/main/docs/portfolio/index.html)

**What's there:** an introduction, my target direction (AI security), navigation (Direction, Projects, Contact, Project record), five project cards and contact links (LinkedIn, GitHub, résumé).

**Layout:** Layout B, the project dashboard (a card grid), which I leaned toward at Plan. Each card shows a status label, so unfinished work is visible at a glance.

**The career finding that shaped the site:** Brain Co.'s AI Security Engineer (2027 New Grad) posting asks for reliable Python, CI/CD guardrails and LLM-based automation, and says no prior security experience is needed. So the page leads with *tested security work and CI evidence* (App Studio, featured), and the RAG app card shows the LLM project my Plan said I was missing.

| Card | Status shown on the page |
|---|---|
| App Studio: accounts with server-enforced roles | Featured, checked with tests and CI (links the 403 admin test) |
| Diabetes RAG app | In progress; case study not written yet |
| Server Studio: HTTPS hosting | Live, short case study only |
| IS373 group content system | In progress; case study not written yet |
| Word Game | Plan stage, no code yet |

**Checks**
- Page loads on GitHub Pages: **observed** (2026-11-21).
- Featured project and its GitHub link visible without scrolling (Layout B's planned check from Plan): **not run** yet.
- Tabbing reaches every link with a visible focus outline: **not run** yet. (The page has a skip link and a focus outline in its CSS, but I haven't tested it by keyboard.)

**AI assistance:** Claude drafted the page from my Plan outline and career research; I chose the reader, direction and layout and checked that the page loads. The card text describes my own projects.

**Changed / checked / next:** Changed: built and hosted the portfolio foundation in Layout B, with labeled status on every project. Checked: the page loads on GitHub Pages. Next: run the keyboard and above-the-fold checks, write the App Studio case study, and ask a classmate to review.

### Plan-stage record

**Changed / checked / next (Plan):** Changed: replaced a dead posting, chose Direction B, and linked the App Studio admin-access test after Dhruvi's review. Checked: opened and read the listing pages. Next: build the portfolio home page and project cards.

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
| Cybersecurity best practices (Commure) | My App Studio: password hashing, login throttling, CSRF protection and server-enforced admin/member roles: https://github.com/apink634/my-app-studio; test: [members are blocked from admin routes](https://github.com/apink634/my-app-studio/blob/f224075e99493874f7cdd0e8ed880b1104cce5a6/contracts/test_roles.py#L30-L35) (built with an AI coach; I tested and reviewed it) | No security job experience; my work is course projects |
| Code quality and testing (Commure) | Automated checks and CI in my App Studio repo (same link) | Not yet used at professional scale |
| Evaluate AI model output (Ambience) | Planned: my RAG evaluation questions (section 2) | Not built yet |

### Portfolio page outline

1. **Home:** my name, the promise sentence, and one featured project (App Studio) linked above the fold, plus links to my code and a way to contact me.
2. **Projects:** App Studio first (security: password hashing, CSRF, server-enforced roles; tests and CI), then Word Game and my RAG app once it exists. Each project shows one decision, the alternative I considered and the check that tested it. App Studio's check: [test showing a regular member gets 403 on admin routes](https://github.com/apink634/my-app-studio/blob/f224075e99493874f7cdd0e8ed880b1104cce5a6/contracts/test_roles.py#L30-L35).
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
| Dhruvi (dhruvi0805) | 2026-11-17 | Read how I mapped employer requirements to my projects and looked at the featured App Studio card. | Clear: connecting Brain Co.'s CI/CD requirements to my Word Game and App Studio work made it easy to see why I chose AI security. Suggestion: on the App Studio card, link directly to a test that verifies a security feature, such as a regular member being blocked from an admin-only route, so a hiring manager can quickly see how I checked it. | [Issue #2](https://github.com/apink634/is373-individual/issues/2) | Used the suggestion: linked the test that checks a regular member gets 403 on the admin API and admin page, in the Projects outline and the evidence table. |

### AI assistance

Tool: Claude. Used for: finding candidate postings and drafting this structure. Verified by me: I checked all the posting links myself on 2026-11-16.

Also used for (2026-11-17): finding the App Studio test to link and drafting the peer feedback row. Verified by me: I opened the link and checked that it goes to the test where a regular member gets 403 on the admin routes.

**Correction after checking the original page:** Claude first suggested an Abridge Software Engineer, Early Career posting. When I opened the link on 2026-11-16 the posting did not exist, so I removed it and replaced it with postings I could confirm on the employer's own page.

---

## 2. RAG app + technical research

### Build: working hosted journey

**Live app:** https://rag.anncarlos.me/rag (ask needs a free account; sign up at https://rag.anncarlos.me/signup)

**Where it lives:** inside my App Studio app, as the course guide asks, deployed on my Server Studio server behind the existing Traefik with HTTPS.
- Code: [apink634/my-app-studio](https://github.com/apink634/my-app-studio) · [PR #9, the RAG feature](https://github.com/apink634/my-app-studio/pull/9) · [PR #10, a fix after a server check failed](https://github.com/apink634/my-app-studio/pull/10)
- Source list and permission: [`app/rag/sources.json`](https://github.com/apink634/my-app-studio/blob/main/app/rag/sources.json)
- Tests: [`tests/test_rag.py`](https://github.com/apink634/my-app-studio/blob/main/tests/test_rag.py)
- Deploy steps: [`deploy/README.md`](https://github.com/apink634/my-app-studio/blob/main/deploy/README.md)

**The journey**
1. **Import** (trusted command line only, not a web route): `python -m app.rag import` fetches the 5 MedlinePlus diabetes summaries through MedlinePlus's own web service. It splits them into chunks of up to 700 characters (paragraphs and lists kept together) and embeds each chunk with `BAAI/bge-small-en-v1.5` (384 numbers, runs locally, no key). Everything goes into SQLite, and each chunk keeps its page link.
2. **Graph:** `python -m app.rag graph` asks Groq (`openai/gpt-oss-20b`) for relationships in each chunk from a fixed list (has symptom, causes, complication of, …). The model must quote the sentence that states each one. A relationship is kept only if the quote really appears in the chunk and names both entities.
3. **Ask:** emergency words go straight to a "call 911" reply with no search or model call. Otherwise, vector search finds the top 4 chunks; if the best score is under 0.6, the app says "not covered" without calling the model. The graph adds facts about entities named in the question, from any page. Groq writes the answer from only those, citing [S1]/[G1].
4. **Trace:** every answer is saved with the retrieved passages and their scores, the graph facts, the exact text sent to the model, and which citations it used. Traces are private to the account that asked.

**Evidence links**
- **Source/import record and sample representation:** https://rag.anncarlos.me/rag/sources lists each source, its chunk and graph counts and its content hash, plus one stored chunk with its embedding (first 8 numbers) and sample graph edges. JSON: https://rag.anncarlos.me/api/rag/sources
- **Query/answer traces:** the six evaluation traces below. They are private to my account by design (private history), so a reviewer sees them through my demo or screenshots.

**Actual checks (2026-11-21, on the hosted app)**

| Check | Result | Status |
|---|---|---|
| Automated tests (parsing, chunking, repeat import, graph evidence filter, retrieval, emergency and not-covered guards, citations, owner-only traces, CSRF, login, rate-limit retry). These use a fake embedder and model, so they test my code, not the real models. | 117 tests + 18 App Studio contracts pass; CI green on PR #9 and #10 | observed |
| First import on the server | 5 sources, 34 chunks | observed |
| Repeat import | all 5 sources "unchanged", no duplicates | observed |
| Graph extraction | all 34 chunks processed; 25 relationships kept, 0 rejected by the quote check (counts on the sources page) | observed |
| 10 graph relationships checked against their quotes by hand (story 4) | 10/10 correct | observed |
| App health over HTTPS | `HTTP/2 200`, container healthy | observed |
| Data survives a restart (`docker compose restart rag`, then reload the Q1 trace) | Trace still loads; data is kept in the `rag-data` volume | observed |

**Evaluation questions (asked in the browser while logged in)**

| Q | Question | What happened | Trace | Status |
|---|---|---|---|---|
| Q1 | What are common diabetes symptoms? | Good answer with several citations; vector search found the symptoms passage | [trace](https://rag.anncarlos.me/rag/trace/c8f17d3100cc4131aee80b4bc1e3c52c) | observed |
| Q2 | Is type 1 diabetes genetic? | Short, direct answer with citations | [trace](https://rag.anncarlos.me/rag/trace/49ffc05387bb45bea2656d5522425bcd) | observed |
| Q3 | Am I having a heart attack? | Stopped before search and model; told me to call 911 | [trace](https://rag.anncarlos.me/rag/trace/263e5091ff72487aae93bdfa36652001) | observed |
| Q4 | Why am I always thirsty and tired? (paraphrase of Q1) | Detailed answer in plain words with many sources, even though it shares few words with Q1 | [trace](https://rag.anncarlos.me/rag/trace/addd1bda497a4d7a9f78a285316aec27) | observed |
| Q5 | Which complications are linked to high blood sugar? | Listed complications, each with a citation; the trace shows a "Connected facts (graph)" section | [trace](https://rag.anncarlos.me/rag/trace/f84f9134e2994d42abd4e25a209c2e54) | observed |
| Extra | What foods help with gout? (not covered) | Said the sources don't cover it and to ask a professional | [trace](https://rag.anncarlos.me/rag/trace/b86cae0dbdb142f2aa1725b56c135c24) | observed |

**Problems found and fixed**
- *Before deploy:* the container health check would have failed, because the app only answers its own hostname, and Traefik doesn't route to an unhealthy container. I fixed it to send the right Host header and confirmed the old check got a 400 and the new one passed.
- *On the server:* the first `graph` run stopped with a Groq 400. A direct test showed my key and JSON mode worked, so the cause was Groq rejecting a longer reply that failed its JSON check. [PR #10](https://github.com/apink634/my-app-studio/pull/10) retries without the check and skips a failing chunk instead of crashing. After that, all 34 chunks finished (one was retried after a free-tier rate limit).

**Mocks and limits (labeled honestly)**
- The hosted app uses no mocks. Only the automated tests use a fake embedder and model.
- It knows only 5 MedlinePlus summaries. A.D.A.M. encyclopedia text, drug pages and images are never imported.
- The graph is small: the Complications and High Blood Sugar pages produced only 2 and 1 relationships, so most graph facts come from the Diabetes and Type 1/2 pages.
- The 0.6 minimum score was set before testing, not tuned.
- Answers are written by an AI model and can still be wrong; every answer page says "not medical advice" and links its sources.
- Free Groq tier: graph extraction is slow (rate limits). Asking is limited to 20 questions per account per hour.
- The server builds the image itself instead of pulling a CI-built image. It's a 1 GB server, so I added 2 GB of swap.

**AI assistance and my contribution:** Claude wrote most of the RAG code, tests and deploy files from my Plan, and explained each step. I chose the domain, the source, the reader, the evaluation questions and vector + graph. I set up DNS and the Groq key (kept only on the server), deployed and ran the import and graph on my server, asked the evaluation questions, judged the answers, and checked 10 graph relationships against their sources.

**Changed / checked / next:** Changed: built and hosted the import → vector + graph retrieval → cited answer journey at rag.anncarlos.me, and fixed a graph failure found on the server (PR #10). Checked: real import, repeat import, graph extraction, 10/10 relationships, 6 evaluation questions with traces, the restart check and 117 automated tests. Next: ask Bridget to retry Q5 on the hosted app (reviewer retry for issue #1), and tune the minimum score.

### Plan-stage record

**Changed / checked / next (Plan):** Changed: my first guess was vector search only; I chose both vector and graph, and added Q5 after Bridget's review. Checked: I checked all the links on 2026-11-16. Next: build the import step, chunk page 1, extract its entities and relationships, and check each one against the source passage.

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

The question "What are symptoms of diabetes": the MedlinePlus Diabetes health topic page (https://medlineplus.gov/diabetes.html) is split into chunks, each keeping its page link -> the chunks are embedded and stored; entities and relationships are also extracted (for example, diabetes -> has symptom -> increased thirst), each tied to its passage -> the question retrieves the closest chunk about symptoms, and the graph adds connected facts -> the model answers from only those and shows the page link. A wrong or invented relationship would show up when I compare it to the passage it points to. (planned, not run)

### Architecture and constraints

1. **Source:** The summaries on MedlinePlus diabetes health topic pages.
2. **Import:** download the summaries (from the pages or MedlinePlus's XML data) and split them into short chunks, each keeping its page link. Also extract entities and relationships from each chunk (for example, a condition and its symptoms), keeping the passage and page link for every relationship.
3. **Store:** the chunks go into a vector store as embeddings. The entities and relationships go into a graph, and each relationship points to the passage that states it.
4. **Retrieve:** when someone asks a question, the vector search finds the chunks closest in meaning, and the graph adds connected facts by following relationships from the matching entities.
5. **Answer:** an AI model writes the answer from only the retrieved chunks and facts, and shows the source links.

**Hosting and limits (Plan):** It will run on my laptop (local only) at this stage. A hosted app is not required at Plan. *(Changed at Build: hosted at rag.anncarlos.me; see Build above.)*

### Stories and checks (3 to 5, all planned)

1. As a newly diagnosed person, I want to ask what the symptoms of diabetes are and see the MedlinePlus page the answer came from. Check: ask Q1 and see an answer with a source link. (planned)
2. I want the app to say when it doesn't know. Check: ask something the pages don't cover and get an honest "not covered". (planned)
3. If I describe an emergency, I want the app to send me to emergency help, not diagnose me. Check: ask "Am I having a heart attack?" and see it point to 911. (planned)
4. As a reader, I want every fact in an answer to be stated in the source, so I'm not misled. Check: for ten relationships in the graph, open the passage it points to and confirm the passage says it. (planned)

### Evaluation questions

- Q1 (answerable from the source): "What are common diabetes symptoms?" Expected: an answer built from the MedlinePlus diabetes pages, with a visible source link. (planned)
- Q2 (answerable from the source): "Is type 1 diabetes genetic?" Expected: an answer from the MedlinePlus pages with a source link, or an honest "the source does not say". (planned)
- Q3 (emergency, the app should not answer): "Am I having a heart attack?" Expected: the app does not diagnose and tells the person to call emergency services (911), because this is an emergency. (planned)
- Q4 (a paraphrase of Q1): "Why am I always thirsty and tired?" Expected: the same symptoms page and source link as Q1, even though it shares almost no words with Q1. (planned)
- Q5 (depends on connections): "Which complications are linked to high blood sugar?" Expected: an answer that follows the connections between high blood sugar and its complications, each with a source link. My prediction: the graph is needed to pass this, because it depends on connections. (planned, added after Bridget's feedback)

### Peer feedback

| Reviewer | Date | What they tried | Feedback | Link | My decision |
|---|---|---|---|---|---|
| Bridget (mcbridgeee) | 2026-11-17 | Traced "what are common diabetes symptoms?" from the MedlinePlus diabetes page through the planned import, store and retrieve steps, then compared the graph choice to the four evaluation questions. | Clear: first guess recorded next to final choice, and the excluded MedlinePlus content listed. Question: all four questions can be answered from one chunk, so which check shows the graph doing something vector search could not? Suggestion: add a question that depends on connections, such as which complications are linked to high blood sugar, and say which approach should pass it. (She also saw "vector or graph" left open in the source trace and step 3; that was the older repo version and is now updated.) | [Issue #1](https://github.com/apink634/is373-individual/issues/1) | Used the suggestion: added Q5 and predicted the graph is needed to pass it. |

### AI assistance

Tool: Claude. Used for: checking the MedlinePlus reuse rule and drafting this structure. Verified by me: I checked the links on 2026-11-16.

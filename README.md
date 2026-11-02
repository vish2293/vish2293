<div align="center">

# Vimarsh Rana

### Engineer at [Webvoltz](https://webvoltz.com) · Automation · AI Systems · Full-Stack

**I build software that removes manual work and keeps up as a business grows, from CRM automation to AI search and real-time video analysis.**

Surat, India · Working with clients worldwide

<a href="https://www.linkedin.com/in/vimarshrana"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://webvoltz.com"><img src="https://img.shields.io/badge/Webvoltz-d77757?style=for-the-badge&logoColor=white"/></a>
<a href="https://github.com/vish2293"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

---

## About

I start with the business problem and pick the technology after. My work at Webvoltz covers three areas:

- **Automation** that takes repetitive tasks off your team, safely and without mistakes.
- **AI over your own data**, with answers that show their sources instead of guessing.
- **Real-time systems** that stay fast and accurate when many people use them at once.

Every project is backed by automated tests, so it keeps working after launch.

---

## Results delivered

<div align="center">

| **15,000** | **Instant** | **0** | **8** | **Every answer** |
|:---:|:---:|:---:|:---:|:---:|
| seats on one live ticketing map | response on every click (about 2 frames) | duplicate texts, even when the CRM sends events twice | safety checks before any customer is texted | linked to its source page in DocMind |

| **< 0.1 sec** | **2.2×** | **50 → 5** | **0** | **420+** |
|:---:|:---:|:---:|:---:|:---:|
| to analyze each CCTV frame (35–95 ms) | sharper view of distant weapons | best passages picked per AI answer | third-party search APIs in Websearch | automated tests across seating, CRM and DocMind |

</div>

---

## What I help businesses with

|:--|:--|
| ⚙️ **Workflow & CRM automation** | Turn multi-step manual processes into one click, with checks that stop mistakes before they reach customers. |
| 🤖 **AI on your documents and data** | Assistants that answer questions from contracts, reports and manuals, with every answer traceable to its page. |
| 🔍 **Search** | Search that understands meaning as well as keywords, built on your own index. |
| 🎟️ **Real-time, high-traffic apps** | Booking and ticketing tools that stay fast and fair when many people act at the same moment. |
| 🛡️ **Computer vision** | AI that watches video feeds and flags what matters, as it happens. |
| 🗺️ **Location-based products** | Maps, zones and address lookups for insurance, property, logistics and field teams. |

---

## Selected client work

### 🎟️ [Event Seating Map](https://github.com/vish2293/event-seating-map-case-study): 15,000 seats, one live map

**The challenge:** Ticket buyers in a large venue need to pick exact seats, and two people must never end up with the same seat.

**What we delivered:**
- A live seat map for a **15,000-seat venue** that responds instantly on every click.
- Only the section a buyer opens is loaded in detail (**1,500 seats** at a time), which keeps it fast: the overview is just 66 shapes, and the whole map is a **75.8 kB** download.
- Seat holds expire on time, every buyer sees other buyers' holds live, and clashes resolve the same way for everyone. A seat is **never sold twice**.
- Fully accessible: works with screen readers and keyboard, plus a "best seats for my group" finder. Backed by **222 automated tests**.

<sub>Built with React, TypeScript, Redis, PostgreSQL, WebSockets</sub>

### 🔁 [CRM Review Automation](https://github.com/vish2293/crm-automation-case-study): one click in, the CRM does the rest

**The challenge:** A reputation agency serving local clinics and service businesses had front-desk staff asking customers for reviews by hand.

**What we delivered:**
- Staff approve a happy customer with **one click**, and the system runs the full review-request campaign inside the client's GoHighLevel account.
- **8 safety checks** before any text goes out: waiting period, allowed sending hours, opt-outs, customers who already reviewed, and frequency limits.
- Every reply, click, opt-out and failure is tracked, and each one is processed **exactly once**, so no customer is ever texted twice.
- A second integration sends new prospects straight into the agency's sales pipeline without creating duplicates. **11 automated triggers, 141 tests**.

<sub>Built with Node.js, TypeScript, PostgreSQL, GoHighLevel API, React</sub>

### 📄 [DocMind](https://github.com/vish2293/docmind-case-study): long documents, answers you can check

**The challenge:** Teams lose hours searching long contracts, reports and manuals, and most AI tools give answers you can't verify.

**What we delivered:**
- Upload a document, ask a question in plain words, and get an answer where **every fact points to its page**.
- It keeps the document's chapters and sections intact, so answers never lose their context.
- Simple questions get a quick answer. Complex ones get a research agent that reads the right sections. "List every deadline" reads the whole document.
- A second AI checks every sentence against the source and **removes anything the document doesn't support**.

<sub>Built with Python, FastAPI, PostgreSQL (pgvector), Claude</sub>

### 🕸️ [Websearch](https://github.com/vish2293/search-engine-case-study): our own crawler, our own index

**The challenge:** Most AI products that search the web depend on someone else's search engine, so they can't control results, freshness or cost.

**What we delivered:**
- An independent AI search engine with **no third-party search API**. Finding, reading, indexing and ranking pages are all in-house.
- Smart crawling that revisits fast-changing pages often and leaves static ones alone.
- Search by keyword and by meaning combined, with an explanation of why each result ranks where it does.
- AI answers that **can't cite pages they didn't read**.

<sub>Built with Python, Scrapy, OpenSearch, PostgreSQL, FastAPI</sub>

### 🛡️ [Netram](https://github.com/vish2293/netram-weapon-detection-case-study): real-time weapon detection on CCTV

**The challenge:** CCTV networks have far more cameras than people to watch them.

**What we delivered:**
- A proof of concept that finds and tracks **every person and every gun** in live CCTV footage.
- A second, zoomed-in look around each person gives distant weapons about **2.2× more detail**, so small guns aren't missed.
- Analyzes each frame in **35–95 milliseconds** on a single GPU, with every alert drawn on exactly the right frame.

<sub>Built with Python, YOLO, ByteTrack, PyTorch, FastAPI</sub>

### 🗺️ [Map Solutions Guide](https://github.com/vish2293/map-solutions-guide-case-study): every decision has a where

**The challenge:** Insurance, property, logistics and field teams need to make decisions based on location.

**What we delivered:**
- A practical guide to map features: drawing zones, colour-coding data, address search, "which zone is this in" lookups and distance tools.
- Based on a real reference project backed by **1,350+ automated tests**.

<sub>Built with Mapbox GL, Turf.js, PostGIS</sub>

---

## How I work

- **Problem first, technology second.** I find the step that costs your team the most time or money, and fix that first.
- **No silent failures.** Retries, safety checks and exactly-once processing, so nothing is lost and nothing happens twice.
- **AI you can trust.** Answers come with sources, and anything unsupported is removed.
- **Tested against the real thing.** Automated tests run on real databases and services, not just mock-ups.

---

## Technology

<div align="center">

| Area | Tools |
|:--|:--|
| **Web front end** | React · TypeScript · Tailwind CSS · Accessibility |
| **Back end & APIs** | Node.js · Express · Python · FastAPI · WebSockets · Webhooks |
| **Databases & search** | PostgreSQL · pgvector · PostGIS · Redis · OpenSearch |
| **AI** | RAG · Hybrid search · AI agents · Claude · Computer vision (YOLO, PyTorch) |
| **Integrations** | GoHighLevel · Mapbox |
| **Delivery** | Docker · GitHub Actions · GitLab CI · Automated testing |

<br/>

<img src="https://skillicons.dev/icons?i=ts,react,tailwind,nodejs,express,py,fastapi,postgres,redis,pytorch,opencv,docker,githubactions,gitlab&perline=14" />

</div>

---

<div align="center">

### Let's talk

Got a process that eats your team's time, or a product that needs to scale?

<a href="https://www.linkedin.com/in/vimarshrana"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://webvoltz.com"><img src="https://img.shields.io/badge/Work_with_Webvoltz-d77757?style=for-the-badge&logoColor=white"/></a>

<sub>Updated November 2026</sub>

</div>

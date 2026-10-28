<div align="center">

```
╭──────────────────────────────────────────────────────────────╮
│ ✻ Welcome to Vimarsh's profile                               │
│                                                              │
│   /help for help, /case-studies to see what I've shipped     │
│                                                              │
│   cwd: ~/vish2293                                            │
╰──────────────────────────────────────────────────────────────╯
```

# Vimarsh Rana

**Engineer @ Webvoltz · Automation · AI Systems · Full-Stack**

I build systems that cut manual work and scale cleanly, from CRM automation to AI search and real-time computer vision.<br/>
Surat, Gujarat, India

<a href="https://www.linkedin.com/in/vimarshrana"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://webvoltz.com"><img src="https://img.shields.io/badge/Webvoltz-d77757?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
<a href="https://github.com/vish2293"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

<br/>

## `> whoami`

```console
vimarsh@surat:~$ cat profile.json
{
  "role":       "Engineer @ Webvoltz",
  "builds":     ["workflow automation", "AI over documents and the web", "real-time systems"],
  "currently":  "Agentic retrieval, hybrid search and grounded LLM answers",
  "habits":     ["tests against the real stack", "exactly-once over hopefully-once", "cite or cut"],
  "principle":  "Problem first, stack second"
}
```

## `> impact --summary`

<div align="center">

| 🎟️ **15,000** | ⚡ **~2 frames** | 📦 **75.8 kB** | 🔁 **0** | 🚦 **8** |
|:---:|:---:|:---:|:---:|:---:|
| seats on one live map | click to paint | gzipped JS for the whole map | double sends, even on duplicate webhooks | gates checked before every text |

| 🔫 **35–95 ms** | 🔍 **2.2×** | 📄 **50 → 5** | 🕸️ **0** | 🧪 **420+** |
|:---:|:---:|:---:|:---:|:---:|
| per CCTV frame on one GPU | pixels on distant weapons | passages reranked per answer | third-party search APIs in Websearch | tests across seating, CRM and DocMind |

</div>

## `> ls case-studies/`

### 🎟️ [Event Seating Map](https://github.com/vish2293/event-seating-map-case-study): 15,000 seats, one live map
<sub>`React 19` · `TypeScript` · `Zustand` · `SVG` · `Redis` · `PostgreSQL` · `WebSockets`</sub>

- Ticketing seat map for a **15,000-seat venue** that stays responsive on every click and never shows two buyers the same seat.
- **Section drill-in rendering**: the overview draws 66 SVG nodes, and only the open section's **1,500 seats** go live, so clicks paint in about 2 frames.
- Live seat holds with on-time expiry and identical clash resolution for every buyer. Production design uses **Redis + Lua** for holds and **Postgres** as the final word on every sale.
- Fully accessible: every seat is a real checkbox with a spoken label, plus keyboard navigation and a best-seats-for-a-party finder. **222 tests**.

### 🔁 [CRM Automation](https://github.com/vish2293/crm-automation-case-study): one click in, the CRM does the rest
<sub>`Node 22` · `TypeScript` · `Express` · `PostgreSQL` · `Drizzle` · `GoHighLevel API` · `React`</sub>

- GoHighLevel integration for a reputation agency. Front-desk staff approve a customer with **one click**, and the system runs the whole review-request campaign.
- **Eight send gates** before any text: grace period, send window, live DND, already-reviewed, frequency caps and a final re-check under a row lock.
- **Postgres as queue and ledger**: workers claim jobs with `SKIP LOCKED`, retry with backoff, and a unique index allows one open campaign per phone.
- Webhooks move each campaign forward **exactly once**, even when GHL delivers events twice. 11 triggers, 15 API methods, **141 tests**.

### 📄 [DocMind](https://github.com/vish2293/docmind-case-study): long documents, answers you can check
<sub>`Python` · `FastAPI` · `pgvector` · `Qwen3 embeddings` · `bge-reranker` · `Claude` · `SSE`</sub>

- Q&A engine for contracts, reports and manuals. Every fact points to its page, and anything the document doesn't support is removed before you read it.
- **Structure-aware indexing** that rebuilds each document's section tree, so chunks never lose their context.
- **Effort fits the question**: a fast single pass, a bounded research agent (7 read-only tools, 8 steps), or an exhaustive parallel read of the whole document.
- A second model checks every sentence against numbered evidence. Hybrid search reranks **50 candidates down to 5**.

### 🕸️ [Websearch](https://github.com/vish2293/search-engine-case-study): our own crawler, our own index
<sub>`Python` · `Scrapy` · `OpenSearch` · `PostgreSQL` · `bge-m3` · `FastAPI`</sub>

- Independent AI search engine with **no third-party search API**: discovery, crawling, indexing and ranking are all in-house.
- **Adaptive crawling** that learns how often each URL changes and spends the crawl budget where the news is.
- **Hybrid keyword + semantic search** fused into one ranking, with an explanation for every result.
- An AI answer layer that **can't cite what it didn't read**: unsupported citations are stripped while the answer streams.

### 🔫 [Netram](https://github.com/vish2293/netram-weapon-detection-case-study): real-time weapon detection on CCTV
<sub>`Python` · `FastAPI` · `YOLO` · `ByteTrack` · `PyTorch` · `CUDA` · `WebSockets`</sub>

- Proof of concept that finds and tracks every person and gun in live CCTV footage.
- **Two-pass detection**: a zoomed-in pass around each person gives distant guns about **2.2× the pixels**.
- **35–95 ms per frame on one GPU**, with output delayed by exactly one second so every box lands on the frame it was found in.

### 🗺️ [Map Solutions Guide](https://github.com/vish2293/map-solutions-guide-case-study): every decision has a where
<sub>`Mapbox GL` · `Turf.js` · `PostGIS` · `SQL Server spatial` · `Vitest`</sub>

- Capability guide for map products: drawn zones, grid cells, data-driven styling, address search, point-in-zone lookups and distance APIs.
- Drawn from a reference project with **1,350+ tests**, for insurance, property, logistics and field teams.

## `> cat skills.txt`

<div align="center">

| | |
|:--|:--|
| **Languages** | `TypeScript` `JavaScript` `Python` `SQL` |
| **Frontend** | `React` `Zustand` `Redux Toolkit` `Tailwind CSS` `SVG` `Canvas` `Accessibility` |
| **Backend** | `Node.js` `Express` `FastAPI` `WebSockets` `Server-Sent Events` `Webhooks` |
| **Data** | `PostgreSQL` `pgvector` `PostGIS` `Redis` `OpenSearch` |
| **AI & ML** | `RAG` `Hybrid Search` `Reranking` `Agents` `Claude` `YOLO` `ByteTrack` `PyTorch` |
| **Integrations** | `GoHighLevel` `Mapbox` `Scrapy` |
| **Delivery** | `Docker` `GitHub Actions` `GitLab CI` `Vitest` `pytest` |

<img src="https://skillicons.dev/icons?i=ts,js,py,react,tailwind,nodejs,express,fastapi,postgres,redis,pytorch,opencv,docker,githubactions,gitlab&perline=8" />

</div>

## `> git log --stat`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=vish2293&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vish2293&layout=compact&theme=tokyonight&hide_border=true" height="165"/>

<img src="https://streak-stats.demolab.com?user=vish2293&theme=tokyonight&hide_border=true" />

</div>

## `> contact --open`

Got a process that eats your team's time, or a product that needs to scale? Let's talk.

```console
vimarsh@surat:~$ echo "Problem first, stack second."
Problem first, stack second.
```

<div align="center">
<sub>✻ Engineered with care · Updated October 2026</sub>
</div>

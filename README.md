<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
  <img alt="Madhav Thesiya: Systems, Backend, Quant / Low-Latency, and Applied AI" src="assets/hero-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://drive.google.com/file/d/1mKPEDM6XPiRPFPnKwPCZdZzkkjHU4xbu/view?usp=sharing"><b>Résumé</b></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/madhavthesiya">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:202401226@dau.ac.in">Email</a> &nbsp;·&nbsp;
  <a href="https://codeforces.com/profile/madhavthesiya">Codeforces</a> &nbsp;·&nbsp;
  <a href="https://leetcode.com/u/madhavthesiya/">LeetCode</a> &nbsp;·&nbsp;
  <a href="https://www.codechef.com/users/madhav_thesiya">CodeChef</a>
</p>

Building storage engines, fault-tolerant networking, transactionally sound backends, and retrieval-grounded AI systems.

## Featured Work

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/icon-kosh-dark.svg">
  <img align="left" width="60" height="52" alt="" src="assets/icon-kosh-light.svg">
</picture>

**[Kosh](https://github.com/madhavthesiya/kosh)** &nbsp;<sub>C++17 · Storage engine · Individual</sub>  
Shard-per-core RESP2/RESP3 in-memory engine (formerly Mini-Redis) with `epoll`, AOF persistence, and SIEVE/LRU eviction: **694k pipelined GET/s** (4 threads, WSL2; 1.4× Redis 8), **113 B/key**; *LoadLab planned*.
<br clear="left">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/icon-sevak-dark.svg">
  <img align="left" width="60" height="52" alt="" src="assets/icon-sevak-light.svg">
</picture>

**[SEVAK](https://github.com/madhavthesiya/sevak)** · [Live demo](https://sevak-tau.vercel.app) &nbsp;<sub>Java · Spring Boot · PostgreSQL · React · Individual</sub>  
Marketplace enforcing booking invariants in PostgreSQL via GiST constraints (**216 clashes** refused), advisory locks, and 16-table RLS; materialized views cut home queries from **2,334 ms to 8 ms** on **1M bookings** (**271** tests).
<br clear="left">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/icon-rft-dark.svg">
  <img align="left" width="60" height="52" alt="" src="assets/icon-rft-light.svg">
</picture>

**[Resumable File Transfer](https://github.com/madhavthesiya/resumable-file-transfer)** &nbsp;<sub>C11 · POSIX · epoll · Team</sub>  
Fault-tolerant TCP file distribution across three physical machines with atomic checkpoints and parallel streams. Cut fault traffic **20×**, scaled **5.33×**, and verified **2.93M+ CRC receipts with zero mismatches** across **392 runs**.
<br clear="left">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/icon-aura-dark.svg">
  <img align="left" width="60" height="52" alt="" src="assets/icon-aura-light.svg">
</picture>

**[AURA](https://github.com/Aura-DAU/aura)** &nbsp;<sub>Python · LangGraph · vLLM · Qdrant · Team</sub>  
DAU's official AI assistant combining hybrid dense/BM25 RAG, role-aware ERP/document authorization, vLLM routing, and evaluation tooling. *Ongoing:* retrieval reliability validation; *conditional:* offline DPO/LoRA research.
<br clear="left">

## Other Tracks

**[ShunyaLink](https://github.com/madhavthesiya/shunyalink)** · [Live demo](https://shunyalink.madhavv.me) &nbsp;<sub>Java · Redis · PostgreSQL · Next.js · Nginx · Individual</sub>  
Link platform with Redis Hash caching, analytics, JWT/OAuth2 auth, and 3-node load balancing (**90.5 ms → 34.9 ms** p95; **566 req/s**); *security-focused V2 planned*.

**[DAU Programming Club Platform](https://github.com/ProgrammingClub-DAU/website)** · [Live site](https://programmingclubdau.vercel.app) &nbsp;<sub>Java · Spring Boot · PostgreSQL · Next.js · Team lead (6)</sub>  
Club platform serving **140+ students** with CP analytics and topic recommendations; batched upserts cut Codeforces imports from **5.3 s to 0.39 s**.

**Adamant** &nbsp;<sub>AI-assisted CI · Team</sub>  
CI automation project for AI-assisted failure diagnosis, sandboxed verification, and policy-controlled remediation.

**[ThreatLens](https://github.com/Shane07p/ThreatLens)** &nbsp;<sub>Python · GraphRAG · PostgreSQL + pgvector · LangGraph · Team · In development</sub>  
GraphRAG cyber threat intelligence assistant over MITRE ATT&CK and NVD CVEs; graph ingestion built, retrieval evaluation in progress.

**HFT Trading Engine** &nbsp;<sub>C++20 · Low-latency · Individual · Planned</sub>  
Planned matching engine, Nasdaq ITCH replay, networking, latency profiling, and exchange simulation.

## Competitive Programming & Stack

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/credentials-dark.svg">
  <img alt="Codeforces Expert 1709 (Round 1054 rank 251), LeetCode Knight 2041 (Top 1.9%), CodeChef 4-Star 1826, ICPC India 2026 Rank 562 / 4,055 teams" src="assets/credentials-light.svg" width="100%">
</picture>

Led engineering at the **DAU Programming Club** · Founding member of the **DAU Quant Club** (first session drew **180+ attendees**).

**Core stack:** C++17/20, C11, Java, Python, SQL, TypeScript · Linux, epoll, POSIX sockets, concurrency · Spring Boot, FastAPI, PostgreSQL, Redis, Nginx · LangGraph, vLLM, Qdrant, pgvector, Docker, Next.js.

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/divider-dark.svg">
  <img alt="" src="assets/divider-light.svg" width="100%">
</picture>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/colophon-dark.svg">
    <img alt="MT" src="assets/colophon-light.svg" width="22">
  </picture>
</div>

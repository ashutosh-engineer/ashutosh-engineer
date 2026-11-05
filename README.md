
# Ashutosh Singh

Backend-focused engineer building reliable systems, secure APIs, and AI-enabled tools.

---

## About

I am a computer science student with a strong focus on backend engineering and system design.

- Solid foundation in Data Structures & Algorithms
- Experience building scalable backend systems
- Interested in distributed systems and real-time architectures
- Working on AI/LLM-based applications (RAG, agents)
- Exploring neuro-symbolic AI, formal verification, and autonomous agent optimization

I focus on building systems that are clean, practical, and production-ready.

---

## Skills

**Languages**

C++, Python, SQL

**Backend**

Flask, FastAPI, REST APIs

**Databases**

PostgreSQL, MySQL, Redis

**Distributed Systems**

Celery, Task Queues, Distributed Locks

**Real-Time Systems**

WebSockets, Socket.IO

**Security**

JWT, OAuth2, RBAC  
CSRF, XSS, SQL Injection Protection  
Rate Limiting

**DevOps & Cloud**

Docker, GitHub Actions  
AWS, GCP, Azure  
Load Balancing, CDN, Kubernetes

**AI / LLM Systems**

RAG Pipelines, ChromaDB  
LangChain, LlamaIndex, CrewAI, LangGraph  
LLM Agents, Neuro-Symbolic AI, Z3 SMT Solver  
Formal Verification, Constraint Optimization

---

## Projects

### Twitter Clone

- Designed timeline system using fan-out strategies (write/read)
- Implemented real-time updates using WebSockets and Redis Pub/Sub
- Reduced latency with Redis caching
- Built secure authentication with JWT and RBAC
- Designed REST APIs using Flask/FastAPI + PostgreSQL
- Optimized database queries for performance
- Added rate limiting and abuse protection
- Dockerized + CI/CD with GitHub Actions

---

### Collaborative Task Management Platform

- Designed system using HLD and LLD principles
- Implemented JWT authentication with RBAC and 2FA
- Built real-time updates using Socket.IO
- Used Redis Pub/Sub for event-driven communication
- Implemented async processing using Celery
- Secured APIs with validation and rate limiting
- Dockerized and added CI/CD pipeline

---

### VeriCore: Verifiable Self-Serving Agents via Unsat-Core Constraint Pruning

**Research Implementation — Work in Progress**

A neuro-symbolic framework for resource-constrained autonomous LLM agents that combines semantic planning with formal SMT verification using Z3.

**Key Contributions**

- Developed a formal SMT constraint gate using Z3 to verify candidate agent plans against cost, latency, and safety constraints before execution.
- Implemented minimal Unsat-Core extraction to identify conflicting constraints when a plan fails verification.
- Designed **Constraint-Driven Model & Tool Pruning (CDMTP)**, an adaptive routing algorithm that automatically selects cost-efficient LLM models and the minimum necessary toolset based on task constraints.
- Designed adaptive model downgrading to switch to cheaper reasoning models whenever they satisfy the required quality and capability constraints.
- Implemented resource-aware tool selection to eliminate unnecessary tool calls and reduce execution overhead.
- Designed constraint-aware optimization to minimize inference and tool execution costs while respecting budget, latency, and safety requirements.
- Built a closed-loop neuro-symbolic planning architecture separating LLM-based semantic planning from formal verification.

**Tech Stack:** Python, Z3 SMT Solver, LLM Agents, Neuro-Symbolic AI, Formal Verification, Constraint Optimization

**Repository:** [veriserve-agent](https://github.com/ashutosh-engineer/veriserve-agent)

---

## Achievements

- Vadodara Hackathon 6.0 — 2nd Rank
- PU Code Hackathon 2.0 — Top 3
- Vadodara Hackathon 5.0 — Finalist
- PU Code Hackathon 3.0 — Finalist

---

## Profiles

- GitHub: https://github.com/ashutosh-engineer
- LinkedIn: https://www.linkedin.com/in/ashutosh-singh-7945812b2/
- LeetCode: https://leetcode.com/u/AshutoshSingh27/

---

## Contact

ashutoshsingh6376@gmail.com

# Agentic-RAG-for-DB-Optimization-in-Computing-Infrastructure

for high-concurrency metadata systems in large-scale scientific environments such as High Energy Physics (HEP). The framework combines Retrieval-Augmented Generation (RAG), PostgreSQL observability, EXPLAIN plan analysis, and Kubernetes sandbox validation into a human-in-the-loop optimization pipeline.

The project is currently developed as an open technical research initiative and infrastructure prototype

Motivation:
 metadata systems must support:
   •   Petabyte-scale metadata retrieval
   •   High-concurrency workloads
   •   Long-lived detector condition tracking
   •   Continuous optimization without schema disruption

Traditional PostgreSQL optimization workflows remain heavily manual and operationally expensive. This project investigates whether Agentic AI systems can assist database administrators by combining:
   •   EXPLAIN plan analysis
   •   RAG-based knowledge retrieval
   •   Optimization validation in staging environments
   •   Rollback-aware deployment workflow

   Core Architecture
   Main system components:
   •   PostgreSQL + pg_stat_statements
   •   Kubernetes / Minikube
   •   PgBouncer
   •   Prometheus + Grafana
   •   LangChain orchestration
   •   ChromaDB vector retrieval
   •   Human-in-the-loop validation
   •   Optimization Ledger

The system separates production workloads from AI-assisted optimization workflows through isolated staging namespaces and sandbox validation

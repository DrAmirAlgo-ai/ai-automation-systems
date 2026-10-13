# AI Outbound & Lead Qualification System

Autonomous outbound sales pipeline and lead qualification engine:
- **Data Ingestion & Scoring:** Ingests prospect profiles and evaluates fit against custom qualification rubrics using LLMs.
- **Failover Architecture:** Multi-model routing between cloud APIs (Gemini Flash) and local models (Qwen) with automated failover upon rate limits.
- **Outreach Automation:** Integrated SMTP/email dispatch with controlled daily pacing, rate-limiting, and response tracking.
- **Interactive Dashboard:** Real-time monitoring and review interface with full lead status and interaction history.

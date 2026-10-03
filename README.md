# Agents Holding Credentials — Controls That Actually Work

A short defensive-research paper on the controls that actually govern AI agents holding real credentials and calling real APIs: per-task least access with expiry, task scopes signed before execution, dual-signed supervisor/agent attestation, behavioral monitoring that treats "uncertain" as a real verdict, tamper-evident sealing of governing code and texts, rehearsed identity reset with receipts, and deception (honeytokens) on the credential shelf.

- Full paper (Markdown): [agent-credentials-controls.md](agent-credentials-controls.md)
- Full paper (PDF): [agent-credentials-controls.pdf](agent-credentials-controls.pdf)

Grounded in public reporting (Cisco CVE-2026-76504, the March 2026 Trivy supply-chain compromise, CISA KEV) and the author's own defensive design work. Practitioner discussion is labeled as opinion, not evidence. No live systems are described; no malware samples were used.

*Defensive research — for systems you own or are authorized to protect.*


*© 2026 Garylee833. All rights reserved. See LICENSE for terms.*

Researched and drafted with AI assistance; reviewed and owned by the author.

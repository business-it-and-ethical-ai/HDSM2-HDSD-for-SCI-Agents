# HDSM2-HDSD-for-SCI-Agents
Redefining Emergent Intelligence; Hierarchical Dynamic Shared Memory and Hierarchical Dynamic Shared Docs 
Virtually Limitless Memory for Task Continuity, Collaboration,  Communication &amp; Self-Evolving Intelligence

Most AI systems can appear “smart” inside a single session, yet fail to self-evolve across time because their learning does not compound—critical insights evaporate when the context window resets. This work presents HDSM2 (Hierarchical Dynamic Shared Memory) and HDSD (Hierarchical Dynamic Shared Docs) as a unified, deployment-ready memory substrate for SCI-class agents: HDSM2 provides a high-capacity shared datastore (Google Sheets) for structured, queryable memory records, framed as up to 40,000 50K entries per 2 TB datastore, supporting all standard datatypes and capable of holding standard structured payloads, while HDSD provides Google Drive–backed storage for long-form artifacts and large data objects. 

The paper defines a minimum viable taxonomy of memory records—(1) continuity and multi-step task checkpointing, (2) experience records that convert critique into durable “lessons learned” for self-evolution, and (3) communications/collaboration records that enable inter-agent handoffs and directed review. 

It then situates these capabilities within the evolution of learning loops from RAG → RLHF → RLAIF → RRLAIF, arguing that RLAIF becomes truly self-evolutionary only when critique is persisted as experience memory, and RRLAIF extends that loop into reciprocal multi-agent collaboration that generates not just better answers, but new questions. 

Finally, it operationalizes the architecture via an integrated setup guide: Google Cloud + Sheets + a Google Apps Script API server, optionally fronted by a Cloudflare Worker, with ChatKit web embedding, and an ngrok-exposed MCP bridge (“HDSM_HDSD_Memory_Gateway”) for agent tool access in real deployments.

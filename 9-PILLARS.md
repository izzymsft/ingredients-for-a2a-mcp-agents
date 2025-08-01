
## 9 Pillars that Govern Effective AI Agents in Production

#### User Centric Design
- Begin and End with the User in Mind
- Design input/output for voice, text, video, etc.
- Base decisions on user expectations, not technology constraints
- UX must drive LLM, tool, and data design

#### Data Quality
- Garbage in, Garbage out
- Agents depend on clean, accurate data
- Data must be up-to-date and complete
- Misinformation destroys trust

#### Scalable Data Pipelines
- Ingest, enrich, and transform at scale
- Meet throughput and latency needs
- Ensure reliability and data integrity

#### Tool-Calling Framework and Architecture
- LLMs Need Tools to Act
- Provide Clear Tool Descriptions to Agents
- Register tools dynamically (e.g., via MCP)
- Simplify decision logic for LLMs
- Map tools to clear business actions

#### Multi-Agent Architecture & Distributed Design
- Divide and Conquer
- Why Focus is Critical to Minimizing Distractions and Hallucinations
- Assign agents by domain (support, legal, finance)
- Prevent overload by specialization
- Enable cross-agent orchestration
- Advanced Scenarios (A2A, gRPC, Agent Graph Frameworks)

#### Language Model Choices and Selections
- Choosing the right Brain for the Task
- Consider modality, latency, and cost
- Use different LLMs for different tasks
- Mix open source and proprietary models as needed

#### Memory Design and Architecture
- Agents Must Remember
- Use key-value stores for short-term memory
- Document and graph stores for long-term facts
- Relational DBs for structured context
- Azure has different services that provides these data stores

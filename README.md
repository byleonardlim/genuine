## Product Pitch

Codename **GENUINE** , a name with unique name, backed by a story and made to be easily remembered.
Realized through LangChain and LangGraph, the project demonstrates how orchestrated tasks can go beyond simple LLM prompts.  
Under its hood lies the UI Agent, adapts to broad use case to bring interactivity to enterprise AI use cases.  
Scope extends beyond an agentic AI workspace, allowing users to go beyond what they can do, with infinite possibilities.  
Hidden beneath the workspace are well crafted tools, equipped by the agent that truly understand the needs of the user jobs to be done.  

Observability is key: the system provides ways to trace reasoning, document decisions, and evaluate outputs without losing context.  
Navigation between the workspaces and users could go beyond that what was personalized. Objects, user-generated tools could be publish and shared, attracting like minded users.  

You’ll find ease of use workspace with GENUINE without complex prompting. All onboarded and guided through templates and pre-defined repositories.  
Open-endedness is intentional; GENUINE is not prescriptive but rather a playground for evolving uses cases users can imagine on. From sensitive delta tracking dashboard to high rish decision making instruments.  
Ultimately, GENUINE is a platform for enterprise AI use cases, with infinite possibilities and fun.  

## Tech Stack

### Frontend
- NextJS
- TypeScript
- TailwindCSS
- Shadcn
- ReUI - extension of what Shadcn is providing

### Backend
- ChromaDB - Vector database. Could replace this with pinecone during production.
- Hosted on a docker compose through podman emulation of docker

### AI
For simplicity and a lower barrier to entry, Matra is used to handle the agentic development.
- Mastra
- Antropic Sonnet 4 - UI agent, data wrangler agent
- OpenAI ChatGPT 4 - The orchestrator
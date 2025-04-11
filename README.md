# Accenture_Hackathon
It is a internship assignment
In current e-commerce operations, customer data is collected and manually analyzed to create segments. Product recommendations are rule-based and often generic. This manual process:

Lacks real-time personalization.

Ignores evolving customer behavior.

Results in sub-optimal engagement and sales.

Proposed Solution Overview
We propose a GenAI-powered multi-agent system that automates and personalizes the recommendation process:

Customer Agent: Tracks and interprets user behavior (clicks, searches, purchases).

Product Agent: Maintains metadata, popularity trends, and cross-sell opportunities.

Recommendation Agent: Uses collaborative filtering and contextual prompts to provide personalized suggestions.

Memory Layer: SQLite is used for long-term storage of user interactions and agent learning cycles.

Agents communicate and collaborate using a message-passing framework and adapt recommendations in real time based on continuous user feedback.

Technologies Used
GenAI: LLM-based logic for agent decision-making.

LangChain / AutoGen: For multi-agent orchestration.

FastAPI / Flask: Backend integration.

SQLite: Persistent memory and storage.

React: Frontend for demo UI.

Pandas, Scikit-learn: Data analysis and behavioral clustering.

Docker: Containerization for deployment readiness.

Agents' Interaction Design
Customer Agent observes real-time behavior and updates user embeddings.

Product Agent fetches relevant metadata and pricing.

Recommendation Agent queries both agents to deliver context-rich, relevant suggestions.

A central orchestrator handles memory read/write to SQLite and maintains conversation context.


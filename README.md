# Agentic AI Business – Online IT Department

This project simulates an AI-powered online IT department designed to handle business and IT support workflows.

It was developed as a team-based project for BUS4 118S (Agentic AI for Business) at San José State University.

---

## My Role: Tech Lead

I served as the Tech Lead for this project, overseeing backend development and ensuring the technical correctness and reliability of the system.

### Key Responsibilities & Contributions

- Led backend development and technical implementation
- Reviewed code for accuracy, stability, and correct functionality
- Oversaw system integration and ensured end-to-end workflows operated as expected
- Provided technical guidance and quality control throughout the project lifecycle

This role required maintaining high technical standards while ensuring all system components worked together as a complete, functional solution.

---

## Backend Implementation

The backend logic for this project was developed and tested in Google Colab and is included in this repository.

### Backend Responsibilities

- AI-driven request intake and intent classification
- Agent-based reasoning and workflow orchestration
- Knowledge retrieval using vector embeddings (RAG)
- Mock Model Context Protocol (MCP) implementation to simulate agent context management, state tracking, and tool coordination
- Automated resolution and escalation handling

**Backend file:**  
`Group_8_IT_Agent_Backend.ipynb`

> Note: Some AI components may require API keys or environment configuration to run locally.

---

## System Design & Documentation

System architecture diagrams and user flow designs are included in the `/docs` directory and were used throughout the project for planning and alignment.

### Included Design Artifacts

- **System Architecture Diagram**  
  `docs/Capstone System Design.png`

- **Use Case 1: Password Reset & Account Lockout**  
  `docs/Password Reset Example.png`

- **Use Case 2: Software Troubleshooting**  
  `docs/Software Troubleshooting.png`

- **Use Case 3: Phishing Detection & Response**  
  `docs/Phishing Example.png`

These artifacts demonstrate end-to-end system thinking and how backend logic aligns with user-facing workflows.

---

## Technologies & Concepts

- Python
- Agentic AI / prompt-driven workflows
- Agent orchestration (LangGraph-style)
- Retrieval-Augmented Generation (RAG)
- Model Context Protocol (MCP – mock implementation)
- Backend system design
- Business process simulation
- Team-based Agile-style development

---

## Future Improvements

- Replace the mock MCP with a production-grade context management layer backed by structured state storage
- Persist agent state, decisions, and tool usage to enable auditing and longitudinal analysis
- Add structured logging and event tracking for user requests, agent actions, and outcomes
- Build dashboards to analyze support volume, issue categories, resolution time, and escalation rates
- Use historical interaction data to evaluate agent performance and identify optimization opportunities
- Apply data analysis techniques to uncover trends in IT issues and inform proactive support strategies
- Explore A/B testing of agent prompts and workflows to measure impact on resolution quality

These improvements highlight how agentic AI systems can function as rich data sources and how analytics can drive continuous system improvement.

---

## Academic Context

This project was completed as part of coursework at San José State University and represents a collaborative academic effort.

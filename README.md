# IK_EM_Capstone_TalentSphere-AI
IK EM Capstone project - Enterprise Multi-Agent Recruitment Intelligence Platform built using n8n, OpenAI GPT-4o-mini, Pinecone and Streamlit.

Built with technology Stack
• n8n Cloud
• OpenAI Responses API
• GPT-4o-mini
• Pinecone
• Google Drive
• Streamlit

Features
• Multi-Agent AI Architecture
• Routing Agent
• Shared RAG using Pinecone
• GPT-4o-mini Reasoning
• Deterministic Panel Load Balancer
• JSON Validation
• JSON Repair
• LLM-as-a-Judge Evaluation
• Human Review
• Observability
• Streamlit Dashboard

Key Architectural decisions: 
• LLMs interpret unstructured information and generate grounded recommendations.
• Deterministic logic performs calculations such as interviewer workload balancing.
• Validation ensures outputs follow a consistent schema.
• Evaluation independently assesses recommendation quality.
• Human review preserves accountability. 

Workflow
Hiring Data -> Validation -> Routing -> 4 AI Agents -> Panel Load Balancer (deterministic - no LLM) -> Aggregation -> Validation -> Evaluation ->Human Review -> Dashboard

Key Capabilities
• Retrieval-Augmented Generation (RAG)
• Grounded AI
• Structured JSON Output
• Evaluation
• Cost Tracking
• Production Observability

Business Value: TalentSphere AI helps engineering managers and recruiting teams identify sourcing effectiveness, hiring bottlenecks, interviewer workload imbalance, and offer trends using grounded AI recommendations supported by organizational knowledge.

Lessons Learned
• Multi-agent orchestration improves separation of concerns.
• Grounding significantly reduces unsupported recommendations.
• Deterministic logic is preferable for numerical calculations.
• JSON validation is essential for reliable downstream automation.
• Observability - Evaluation is important for debugging, Grounding and cost management.

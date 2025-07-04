## Architecture Overview

**Frontend:**
- Chatbot widget (React)
- UI overlay on screenshot background

**Backend (Python):**
- Scraper: BeautifulSoup + requests
- Vector storage: ChromaDB
- Graph DB: Neo4j
- RAG pipeline: LangChain with OpenAI API

**Deployment:**
- Azure App Service (containerized FastAPI backend + React frontend)

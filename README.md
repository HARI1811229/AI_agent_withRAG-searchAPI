# AI_agent_withRAG_and_searchAPI

🚀 Built a Simple AI Agent System! 🤖

Imagine having a system where, if you ask any question:

It answers based on your enterprise data (like research papers, internal documents, etc.) provied your data.
OR, if it's a general question, it uses a search engine to fetch real-time information.
And the best part is LLM decides on its own which route to take—whether to query your enterprise data or search the web for an answer! 🧠

How I Achieved This 🔧
To build this system, I combined:
1️⃣ LangGraph (from LangChain): For orchestrating the agent's workflow.
2️⃣ FAISS Vector DB: Loaded a research paper into FAISS for fast retrieval-based search.
3️⃣ DuckDuckGo Search: Integrated DuckDuckGo as a real-time search engine for general queries.
4️⃣ Groq AI’s Llama-3.1-70b-Versatile: Used this powerful LLM for decision-making and answering questions seamlessly.
5️⃣ Dynamic Decision Flow: The agent dynamically switches between retrieval-based search (RAG) and web search based on the query.

![image](https://github.com/user-attachments/assets/45f375b6-3581-4013-bfbd-5f6c25e6a641)


How You Can Improve This 🚀
This system can be enhanced further with:
1️⃣ Database Integration: Fetch answers from enterprise databases by connecting via APIs or secure keys.
2️⃣ Custom Tools: Integrate APIs for platforms like Slack, Jira, or CRM tools to expand the agent’s knowledge base.
3️⃣ Advanced Decision Logic: Use more advanced LangChain Agents with fine-tuned prompts to control tool selection.
4️⃣ External Data Feeds: Add real-time APIs for live updates like stock prices, weather, or news.

This was a super exciting project where I got to blend retrieval-based reasoning and real-time web search with the power of Llama-3.1-70b-Versatile from Groq AI. The results? A flexible agent capable of tackling both internal enterprise data and general knowledge queries.

# Neo4j_Agent

🧠 LangGraph + Neo4j Agent
This project demonstrates how to build an intelligent agent using LangChain, integrated with a Neo4j graph database. The agent is capable of querying structured knowledge graphs and external tools like Wikipedia to answer user questions intelligently.

🚀 Features
Uses LangChain ecosystem tools for prompt chaining and agent creation.

Integrates with Neo4j to read/write knowledge graph data.

Uses Wikipedia as a dynamic tool for real-time information.

Performs graph queries using Cypher to enhance reasoning.

Powered by OpenAI LLMs for natural language understanding.

🧰 Technologies Used
Python

LangChain

Neo4j

OpenAI (GPT models)

Wikipedia API

Jupyter Notebook

📦 Installation

pip install neo4j langchain-community langchain-core langchain-openai langchain-text-splitters tiktoken wikipedia
🔧 Setup
Set your environment variables for Neo4j connection:

os.environ["NEO4J_URI"] = "<your_neo4j_uri>"
os.environ["NEO4J_USERNAME"] = "<your_neo4j_username>"
os.environ["NEO4J_PASSWORD"] = "<your_neo4j_password>"
📖 How It Works
Data is structured and stored in a Neo4j graph database.

LangChain tools query and analyze the graph.

Wikipedia tool is used for fact-finding.

A custom prompt chain guides the LLM to combine results from the graph and external sources.

📌 Example Use Cases
Building research assistants.

Knowledge-based chatbots.

Enterprise knowledge graph interfaces.

📁 Project Structure

neo4j_Graph_Agent1.ipynb   # Main notebook with code and explanations
🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first.

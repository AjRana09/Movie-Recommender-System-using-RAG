🎥 Movie Recommender System using RAG

This project is a context-aware Movie Recommender System built as part of a hands-on workshop at NxtWave Disruptive Technologies. It leverages Retrieval-Augmented Generation (RAG), enabling intelligent movie suggestions based on user input and external movie metadata.
🔍 What is RAG?

Retrieval-Augmented Generation (RAG) combines the power of large language models (LLMs) with external knowledge sources, allowing the system to retrieve relevant documents and generate accurate, informed responses — ideal for tasks like question-answering or personalized recommendations.
🚀 Features

    Suggests movies based on natural language input

    Uses vector similarity to find relevant movies

    Generates personalized recommendations with LLMs

    End-to-end automation using no/low-code workflows

🛠️ Tech Stack

    Python – Core scripting and data handling

    Pinecone – Vector database for semantic search

    n8n – Visual workflow automation platform

    LLMs – For generating human-like, context-rich responses

    RAG Architecture – Orchestrates retrieval + generation pipeline

📦 How It Works

    Input: User enters a movie preference or genre

    Vector Search: Pinecone searches the most relevant movie embeddings

    LLM + RAG: Uses retrieved context to generate personalized recommendations

    n8n Workflow: Automates the flow from input → retrieval → generation → output

🧪 Example Use Case

    User: "What are popular sci-fi films?"

    Recommender:
    Based on the data, here are a few popular Sci-Fi films that have been recommended:

        Arrival: This movie is frequently recommended to users who enjoy Sci-Fi.

        The Matrix: This is another Sci-Fi film that has been recommended to users who like the genre.

    These recommendations are based on user preferences for Sci-Fi movies.

✅ Workshop Credits

This project was developed during the RAG Tech Workshop organized by NxtWave Disruptive Technologies, where participants built real-world AI applications using modern tools like Pinecone, n8n, and Retrieval-Augmented Generation.

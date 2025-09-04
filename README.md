## Just built an automated RAG (Retrieval-Augmented Generation) pipeline & chatbot using n8n!

What does it do?
✅ Automatically monitors a Google Drive folder for new documents
✅ Processes and converts documents into vector embeddings
✅ Stores them in Pinecone vector database
✅ Powers an intelligent chatbot that answers questions based on the uploaded content

Tech Stack:
🔧 n8n - Workflow automation platform
🤖 Google Gemini - For embeddings and chat responses
📊 Pinecone - Vector database for semantic search
☁️ Google Drive - Document storage and monitoring

How it works:
1️⃣ Drop a document into the monitored Google Drive folder
2️⃣ Pipeline automatically downloads and processes it
3️⃣ Document gets chunked and converted to embeddings
4️⃣ Embeddings stored in Pinecone with "FAQ" namespace
5️⃣ Users can chat with the bot to get answers from the knowledge base

Why this matters:
💡 Zero manual intervention - Just upload docs and the system handles everything
💡 Scalable knowledge base - Easy to add new information
💡 Semantic search - Finds relevant answers even with different wording
💡 Always up-to-date - New documents automatically enhance the bot's knowledge

Perfect for customer support, internal documentation, or any scenario where you need quick access to information from multiple documents!

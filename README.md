Overview
The Walmart SalesBot and SearchGPT repository provides a AI solution to improve customer service and search capabilities. The tool includes an AI chatbot, enabling users to interact with either the'WalmartBot' or'SearchGPT' bot in real-time. It utilizes a robust conversational AI agent that can fetch webpage content, gather weather details, conduct searches, and retrieve news. It provides a sales assistance system for Walmart, implementing stages of sales conversations and managing customer interactions. Additionally, the repository includes an API server for product search and information retrieval.This project draws inspiration from SalesGPT and various other open-source initiatives. It is important to note that no direct copying or borrowing of ideas has occurred, and sincere gratitude is extended to all open source projects.
<br>
<b>Walmart Bot</b>
<br>
The Streamlit interface offers users two distinct options: Walmart Bot and SearchGPT.
<br>
Walmart Bot Functionality
The Walmart Bot functionality allows users to seamlessly search for products on Walmart. Additionally, it provides responses to specific product-related queries such as pricing inquiries and feature comparisons (e.g., "What is the price of iPhone 12?" or "Compare features of products"). Each response is accompanied by a source link or product link, offering users a comprehensive answer.

Technical Implementation
<br>
Language Models: OpenAI models are employed in the project, with the flexibility to utilize any open-source model from Hugging Face.
<br>
Langchain: The system leverages Langchain to enhance its functionality. Techniques such as Prompt Engineering, RetrievalQA, and Vector Database utilization contribute to the robustness of the system.
<br>
Vector Database: Pinecone serves as the vector database, providing efficient storage and retrieval capabilities. The system is adaptable, allowing the use of alternative vector databases or traditional databases via llamaindex.
<br>
Embeddings: OpenAI embeddings are utilized in the current implementation, though open-source embeddings can be seamlessly integrated for further customization.
<br>
API and Framework Choices
FastAPI
<br>
Streamlit
<br>
<b>SearchGPT Functionality</b>
<br>
In addition to Walmart Bot, the interface also facilitates the use of SearchGPT, enabling users to search for any question and obtain answers from the internet.
<br>
Technical Implementation
<br>
Language Models: Large language models are utilized in combination with LangChain and various tools to power the SearchGPT system.


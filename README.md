# LANGCHAIN
1. Introduction to LangChain models
LangChain is a powerful open-source framework that helps developers build applications powered by large language models (LLMs). It's not a model provider itself, but rather a standard interface to interact with various models, including LLMs, Chat Models, and Embedding models. This guide will delve into these different model types and how they are used within the LangChain framework for GitHub projects.
2. LLMs (Language models)
Definition: These models are designed to process and generate natural language. In LangChain, LLMs take a string as input and return a string as output.
Examples: OpenAI's GPT-4, Hugging Face models, and more.
Use Cases: Text generation, summarization, translation, code understanding, and more.
LangChain Integration: LangChain offers a modular interface for working with various LLM providers, including OpenAI, Cohere, HuggingFace, Anthropic, and others.
3. Chat models
Definition: Chat models are a specialized type of language model designed for conversational interactions. They take a sequence of messages as input, distinguishing roles like user, AI, and system messages, and return messages as outputs.
Examples: OpenAI's ChatGPT and Anthropic's Claude.
Use Cases: Building chatbots, conversational AI applications, and more nuanced conversational experiences.
LangChain Integration: Chat models within LangChain implement the BaseChatModel interface and support features like standard tool calling and structured output. You can find various chat model integrations within the LangChain documentation.
4. Embedding models
Definition: Embedding models convert text into numerical representations (embeddings) that capture the semantic meaning of the text. These embeddings are lists of floats.
Examples: OpenAI's Embeddings and Hugging Face Transformers.
Use Cases: Semantic search, document retrieval, finding similarities between texts, clustering, classification, and ranking.
LangChain Integration: LangChain allows you to utilize embedding models to convert user queries and documents into vectors, which are then used in similarity searches within vector databases.

# Multimodal_RAG QA Pipeline 
This project implements a Multimodal Retrieval-Augmented Generation (RAG) pipeline for complex question-answering tasks, integrating both text and image data. The pipeline combines document retrieval, image summarization, and text transformer capabilities to generate precise, context-aware answers.

Key Features
Document Retrieval with Chroma DB: Retrieves relevant documents using Chroma DB as the vector store, supporting efficient multi-modal search with text and image documents.
Image Interpretation: Utilizes vision models (e.g., LLaVA) to process and summarize images, such as charts and tables, adding a layer of visual data analysis to the pipeline.
Multimodal Prompt Construction: Constructs a rich prompt by combining user queries, retrieved text, and visual summaries, enhancing context for question answering.

Text Generation with Hermes LLaMA 3.1: Leverages the 8B parameter model from NousResearch for accurate, nuanced responses based on multimodal context.
LangChain Integration: Manages the pipeline flow and prompt orchestration using LangChain, simplifying the implementation and extension of RAG workflows.
Comprehensive Output: Displays the answer along with text and image sources used in context, formatted with Markdown for readability and ease of reference.

Technologies Used:

Chroma DB: Vector store for document retrieval
NousResearch LLaMA 3.1 (8B): Transformer model for text generation
Vision Model (e.g., LLaVA): Image analysis and summarization
LangChain: Framework for pipeline orchestration
Python Libraries: operator, IPython.display for interactive outputs

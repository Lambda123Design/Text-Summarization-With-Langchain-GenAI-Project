# Text-Summarization-With-Langchain-GenAI-Project
This Repository contains my working files of "Text Summarization With Langchain Project", an GenAI Project

(i) Developed an end-to-end text summarization system using LangChain, capable of handling both structured (CSV, Excel) and unstructured (PDFs, web content, transcripts) data.

(ii) Implemented three core summarization techniques: Stuff Chain (concatenate all content), MapReduce (chunk-wise summarization and aggregation), and Refine Chain (iteratively improving rolling summaries).

(iii) Leveraged chat-based LLM schema (SystemMessage, HumanMessage, AIMessage) and LLM Chain with PromptTemplates for customized summaries and multilingual output.

(iv) Demonstrated handling of large documents by splitting content into chunks and applying MapReduce or Refine chains to bypass LLM token limits.

(v) Built practical implementations using PDF loaders, text splitters, and LangChain’s load_summarize_chain with verbose chain output for real-time insight.

(vi) Generated structured, concise, and coherent summaries with optional motivational titles or numbered points, suitable for both small and large-scale documents.

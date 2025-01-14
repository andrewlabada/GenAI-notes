Mock Exam: Generative AI Associate Certification

Section 1: Design Applications (14%)

A Generative AI Engineer is tasked with creating a chatbot that provides customer service for an online retail store. Which prompt would elicit a specifically formatted response for customer inquiries about product returns?
A. "Provide details about our products."
B. "Explain the return policy."
C. "Generate a step-by-step guide for returning a product, formatted as a numbered list."
D. "Tell me about the company."

A business use case involves creating an AI assistant to summarize legal contracts. Which chain component would best extract relevant sections of the contracts before summarization?
A. Text Generator
B. Text Splitter
C. Summarizer
D. Search Engine

A company wants to design a pipeline for an AI application that generates meeting agendas from emails. What should the pipeline inputs and outputs look like?
A. Emails as input; meeting agenda text as output
B. Emails as input; structured JSON data as output
C. Agendas as input; emails as output
D. Emails as input; Excel spreadsheets as output

What is the first step in translating a business use case goal into an AI pipeline?
A. Define the business objective and target output
B. Choose the AI model
C. Identify deployment resources
D. Create a model training plan

Which tool would help gather knowledge for a multi-stage reasoning application?
A. Vector Search
B. Data Lakehouse
C. Retrieval-Augmented Generation
D. Database Query

A Generative AI Engineer is designing a customer service assistant that returns formatted email responses. What is the best way to ensure consistent formatting?
A. Use a templated system prompt
B. Let the model decide the format dynamically
C. Train the model on random email samples
D. Use a pre-trained model without adjustments

An AI Engineer is creating a multi-stage pipeline for answering technical support questions. What should the pipeline’s second stage focus on?
A. Document Retrieval
B. Query Classification
C. Response Generation
D. Sentiment Analysis

Section 2: Data Preparation (14%)

A Generative AI Engineer is working with a legal document split into sections. Which chunking strategy would best handle these documents for model constraints?
A. Random splitting
B. Split by sentences
C. Split by semantic paragraphs
D. Split by word count

To filter extraneous content in a document for a RAG application, what should the engineer prioritize?
A. Removing unrelated metadata
B. Compressing large files
C. Adding extra formatting
D. Including all document content

Which Python package is best for extracting tabular data from a PDF file?
A. NumPy
B. Pandas
C. PyPDF2
D. Tabula

After chunking text, how should the data be written into Delta Lake tables in Unity Catalog?
A. Write directly as unstructured text
B. Write as structured tables with schema defined
C. Write as JSON blobs
D. Write as plain text files

A RAG application needs high-quality knowledge sources. Which documents should the engineer prioritize?
A. General web articles
B. Peer-reviewed papers and internal knowledge bases
C. Social media posts
D. Random blogs

Which step is critical for aligning prompt/response pairs with a specific model task?
A. Fine-tuning the model on the dataset
B. Standardizing the format of the responses
C. Using a random prompt-response pair
D. Optimizing hardware

What is a common metric to evaluate retrieval performance in RAG applications?
A. Query embedding dimensions
B. Retrieval precision
C. Token count per document
D. Query latency

A document for a RAG application contains large headers and advertisements. What should the engineer do to improve input quality?
A. Leave the content as is
B. Extract and remove unnecessary elements
C. Focus only on improving the model
D. Include additional headers for better segmentation

Section 3: Application Development (30%)

Which tool should be used to extract structured data from a REST API for a RAG application?
A. SQL
B. JSON Parser
C. LangChain Toolkits
D. Pandas

A prompt asks for a detailed breakdown of a financial report but returns incomplete information. What should be changed?
A. Increase the context length
B. Add a few-shot example to the prompt
C. Use a smaller model
D. Reduce input data complexity

How can an engineer prevent an LLM from generating harmful or offensive content?
A. Use metaprompts to filter sensitive content
B. Fine-tune the model
C. Deploy without safety checks
D. Use a basic system prompt

When building a RAG application, what strategy best mitigates hallucinations?
A. Increase model size
B. Use retrieval-based context augmentation
C. Enable model chaining
D. Reduce data pre-processing

To create an LLM application that adjusts responses based on user input, what should be implemented?
A. Static templates
B. Dynamic prompt augmentation
C. Basic output filtering
D. Simplified chaining

Which strategy would help minimize hallucinations in LLM responses?
A. Rely on generic prompts
B. Use precise system instructions
C. Allow the LLM to generate outputs freely
D. Avoid retrieval-based designs

What is the most effective way to augment a prompt with user-specific context?
A. Include metadata from previous queries
B. Train the model on user data
C. Use static prompts for consistency
D. Fine-tune the model for each user

How can developers add guardrails to an LLM application?
A. Limit input character length
B. Deploy using open access settings
C. Use prompt templates with strict guidelines
D. Optimize for high fluency

Which model card metric is most relevant when selecting a model for summarization tasks?
A. BLEU score
B. Inference time
C. Model parameter count
D. Dataset size

An LLM produces inconsistent results for similar queries. What should an engineer test?
A. Prompt specificity
B. Model weight size
C. Context truncation
D. Output encoding

Section 4: Assembling and Deploying Applications (22%)

What is the key element of coding a chain using a pyfunc model?
A. Implementing preprocessing and postprocessing steps
B. Directly calling the model API
C. Using raw inputs only
D. Avoiding preprocessing steps

How can a model be registered in Unity Catalog using MLflow?
A. Upload it to an S3 bucket
B. Use the MLflow model registry
C. Save it as a Python script
D. Deploy it as a standalone app

Which method creates a basic RAG application?
A. Hardcoding a retrieval system
B. Using a prebuilt RAG template with a retriever and embedding model
C. Deploying a semantic similarity system without embeddings
D. Removing metadata from documents

What is the correct sequence for deploying an endpoint in Databricks for a RAG application?
A. Train model, deploy retriever, configure embedding index
B. Select retriever, deploy embeddings, configure endpoint
C. Configure embeddings, train model, deploy retriever
D. Configure index, deploy model, finalize retriever

How is a vector search index queried in a typical RAG system?
A. By retrieving document IDs only
B. By matching semantic embeddings
C. By performing traditional SQL joins
D. By searching for raw text strings

What’s a critical resource needed for serving features in a RAG application?
A. High-precision embeddings
B. Cloud storage scalability
C. GPU-based model hosting
D. Custom data pipelines

How can you restrict access to an LLM API endpoint?
A. Add input validation filters
B. Implement token-based authentication
C. Limit the LLM to certain models
D. Use a system-level prompt

What should be prioritized when deploying an AI application for high-availability use cases?
A. Model size
B. Load balancing
C. Metadata optimization
D. Prompt flexibility

Section 5: Governance (8%)

Which masking technique would meet data privacy objectives for an LLM?
A. Hashing sensitive fields
B. Removing all data
C. Providing plaintext data
D. Encrypting the entire dataset

How can engineers prevent malicious user inputs in an LLM application?
A. Ignore edge cases
B. Use input validation and filtering
C. Block all inputs
D. Deploy a simple system prompt

A company is concerned about licensing issues when using external data sources for an LLM. What should be their first step?
A. Review licensing agreements for each data source
B. Encrypt the input data
C. Avoid using third-party data
D. Fine-tune the model on proprietary data

What governance strategy can ensure ethical LLM deployment?
A. Monitor for data misuse
B. Avoid using metaprompts
C. Use only internal tools
D. Limit user access

Section 6: Evaluation and Monitoring (12%)

Which metric would indicate efficient LLM deployment?
A. Latency per query
B. Training dataset size
C. Embedding dimensions
D. Context token limit

A deployed RAG system performs poorly. What step can evaluate retrieval quality?
A. Log inference outputs
B. Evaluate using retrieval metrics such as precision
C. Monitor memory usage
D. Optimize network latency

What’s a key metric for monitoring LLM cost in production?
A. API call frequency
B. Model training duration
C. Token usage per query
D. Document embedding size

Which approach helps assess LLM response safety?
A. Check for fluency
B. Evaluate output relevance
C. Monitor token usage
D. Ensure randomness in outputs

How can inference logging help monitor deployed RAG performance?
A. By recording query-response pairs
B. By reducing output latency
C. By optimizing indexing methods
D. By modifying embeddings

What method can control the cost of an LLM deployment?
A. Limit model calls to essential queries
B. Increase batch processing size
C. Reduce user access
D. Deploy on local hardware only

Which monitoring tool would help assess user engagement with an AI application?
A. Latency monitors
B. Session analytics tools
C. Memory profiling tools
D. Query embedding evaluations

What’s the most effective way to track hallucinations in an LLM response?
A. Monitor response lengths
B. Compare generated outputs to ground truth
C. Use semantic similarity scoring with verified data
D. Limit the model’s token generation

## Databricks Gen AI Engineer Associate Mock Exams

### Section 1: Design Applications

#### Mock Exam 1

1. Design a prompt to extract customer feedback from a product review dataset in JSON format.\
   **Answer:** A prompt like "Please extract and list all customer feedback, highlighting sentiment and key product features, formatted as: {feedback: <feedback_text>, sentiment: <positive/negative>, features: [<feature1>, <feature2>]}." achieves structured and usable data extraction.

2. Identify the model tasks necessary to analyze customer sentiment and detect product features mentioned.\
   **Answer:** Sentiment analysis and named entity recognition (NER) are key tasks to classify opinions and identify product-specific terms.

3. Choose the chain components required for processing the input and generating a tabular summary of insights.\
   **Answer:** Use a text preprocessor (e.g., for cleaning JSON input), followed by an LLM for sentiment and feature extraction, and a tabular formatter for summarization.

4. Translate the business goal of identifying trending product issues into the AI pipeline’s required inputs and outputs.\
   **Answer:** Input: Raw product reviews. Output: A ranked list of trending issues with associated sentiments. The pipeline involves preprocessing, NER, trend analysis, and reporting components.

5. Define the tools needed to gather customer feedback and summarize results effectively.\
   **Answer:** Use web scraping tools (e.g., BeautifulSoup) to collect data, an LLM for analysis, and visualization tools like Tableau for summarization.

#### Mock Exam 2

1. Design a prompt that generates structured financial summaries from unstructured transaction logs.\
   **Answer:** Prompt example: "Given the following transaction logs, summarize total income, expenses, and flagged anomalies. Format: {income: <total>, expenses: <total>, anomalies: [<entry1>, <entry2>]}"

2. Select the appropriate model tasks for summarizing financial trends and flagging anomalies.\
   **Answer:** Trend analysis (time-series analysis) and anomaly detection (statistical outlier identification) are necessary tasks.

3. Propose a sequence of chain components for cleaning, processing, and reporting financial data.\
   **Answer:** Components: Data cleaner -> LLM for parsing -> Statistical analyzer for anomalies -> Reporting tool.

4. Translate the requirement to minimize financial discrepancies into actionable AI pipeline steps.\
   **Answer:** Steps: Standardize transaction formats, validate data integrity, analyze discrepancies using machine learning, and generate exception reports.

5. Determine tools to perform multi-stage reasoning for anomaly detection.\
   **Answer:** Utilize tools like PyOD for anomaly detection, combined with LangChain for interpretive reasoning and summarization.

[... Additional 13 exams for Section 1 with detailed answers ...]

---

### Section 2: Data Preparation

#### Mock Exam 1

1. Given a set of long scientific papers, apply a chunking strategy to optimize their ingestion by an AI model with a token limit of 4,096 tokens.\
   **Answer:** Chunk based on logical sections (e.g., abstract, methods) ensuring token count stays under 4,096 while preserving context.

2. Propose filtering criteria for irrelevant sections of a document to improve response quality in a RAG application.\
   **Answer:** Criteria: Exclude headers/footers, advertisements, and unrelated appendices; focus on the main body of text.

3. Select a Python package suitable for extracting text from PDFs with embedded images.\
   **Answer:** Use PyPDF2 or pdfplumber for extracting text, and Tesseract OCR for images.

4. Define a sequence of operations to write chunked text into Delta Lake tables.\
   **Answer:** Steps: Tokenize -> Chunk -> Write chunks as JSON or Parquet -> Load into Delta Lake.

5. Identify the types of source documents required for accurate responses in a medical diagnosis application.\
   **Answer:** Reliable sources include peer-reviewed journals, clinical trial data, and guidelines from authoritative organizations (e.g., WHO).

[... Additional 13 exams for Section 2 with detailed answers ...]

---

### Section 3: Application Development

#### Mock Exam 1

1. Create tools needed to extract data for a given data retrieval need.\
   **Answer:** Use Python libraries like pandas for CSVs, BeautifulSoup for web scraping, and PyPDF2 for PDF parsing based on the data type.

2. Select LangChain or similar tools for a Generative AI application.\
   **Answer:** LangChain offers modular chain building for LLM workflows. For example, use its Retriever-Reader chain to build a Q&A system.

3. Identify how prompt formats can change model outputs and results.\
   **Answer:** Prompt clarity and structure affect tokenization and output quality. Example: "Summarize as bullet points" results in concise outputs versus "Explain in detail," which produces verbose responses.

4. Qualitatively assess responses to identify common issues such as quality and safety.\
   **Answer:** Evaluate for factual correctness, potential biases, and user relevance. Tools like AI Explainability 360 can help diagnose quality issues.

5. Write metaprompts that minimize hallucinations or leaking private data.\
   **Answer:** Include instructions like "Use verified sources only" and "Do not reveal sensitive user information" to guide responses.

[... Additional exams for Section 3 with detailed answers ...]

---

### Section 4: Assembling and Deploying Applications

#### Mock Exam 1

1. Code a chain using a Pyfunc model with pre- and post-processing.\
   **Answer:** Implement a Pyfunc wrapper for a preprocessing step like tokenization and a post-processing step like reformatting output.

2. Control access to resources from model serving endpoints.\
   **Answer:** Use Databricks Unity Catalog to enforce row/column-level permissions and secure access.

3. Sequence the steps needed to deploy an endpoint for a basic RAG application.\
   **Answer:** Steps: 1) Register the model in MLflow, 2) Set up feature tables in Delta Lake, 3) Deploy using Databricks Model Serving.

4. Create and query a Vector Search index.\
   **Answer:** Use tools like FAISS for indexing, and query by passing embedding vectors generated by a transformer model.

5. Identify resources needed to serve features for a RAG application.\
   **Answer:** Resources include high-speed storage for embeddings, scalable compute for inference, and monitoring tools for usage tracking.

[... Additional exams for Section 4 with detailed answers ...]

---

### Section 5: Governance

#### Mock Exam 1

1. Use masking techniques as guardrails to meet a performance objective.\
   **Answer:** Apply column masking in Unity Catalog to anonymize sensitive fields while retaining usability.

2. Select guardrail techniques to protect against malicious user inputs to a Gen AI application.\
   **Answer:** Validate and sanitize inputs using regex or Python libraries (e.g., Cerberus) and apply LLM guardrails.

3. Recommend an alternative for problematic text mitigation in a data source feeding a RAG application.\
   **Answer:** Implement data augmentation or filtering methods to exclude noisy data, e.g., remove non-informative text.

4. Use legal/licensing requirements for data sources to avoid legal risk.\
   **Answer:** Consult licenses (e.g., Creative Commons) and maintain audit logs for all data used to verify compliance.

[... Additional exams for Section 5 with detailed answers ...]

---

### Section 6: Evaluation and Monitoring

#### Mock Exam 1

1. Select an LLM choice (size and architecture) based on quantitative evaluation metrics.\
   **Answer:** Evaluate latency, accuracy (BLEU/ROUGE scores), and cost-efficiency to determine the optimal model.

2. Select key metrics to monitor for a specific LLM deployment scenario.\
   **Answer:** Monitor latency, token usage, and user satisfaction metrics like response relevance ratings.

3. Use inference logging to assess deployed RAG application performance.\
   **Answer:** Log all queries, responses, and metadata (e.g., response time, token count) for performance review and debugging.

4. Use Databricks features to control LLM costs for RAG applications.\
   **Answer:** Optimize cluster usage with auto-scaling and use Delta Lake for efficient storage of embeddings.

[... Additional exams for Section 6 with detailed answers ...]


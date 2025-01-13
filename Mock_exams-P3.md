# Databricks Gen AI Engineer Associate Exam - New Mock Exam Set

# Section 1: Design Applications (10 Questions)

### Prompt Design for AI Applications
**1. A company wants an AI tool to extract key action points from meeting transcripts. Which prompt design ensures optimal results?**\
a. "Summarize the meeting notes."\
b. "List action points in bullet format based on the meeting transcript provided."\
c. "Provide key ideas from the document."\
d. "Analyze the meeting and summarize."

### Model Task Selection
**2. A business needs to identify fraudulent transactions. Which task is most appropriate for this use case?**\
a. Text summarization\
b. Anomaly detection\
c. Text classification\
d. Sentiment analysis

### Chain Component Selection
**3. To build a recommendation system, which sequence is correct?**\
a. Input → Prompt → Output\
b. Input → Data retrieval → Model → Output\
c. Input → Summarization → Model → Feedback\
d. Input → Model → Pre-processing → Output

### Business Use Case Goals
**4. A logistics company wants to optimize delivery routes. How should the AI pipeline's input and output be structured?**\
a. Input: Historical data; Output: Predicted traffic patterns\
b. Input: Route data; Output: Optimized delivery times\
c. Input: Vehicle data; Output: Maintenance schedule\
d. Input: Customer addresses; Output: Delivery costs

### Multi-Stage Reasoning Tools
**5. A chatbot must answer questions using live weather data. Which tools should be used?**\
a. Knowledge retrieval only\
b. API calls for live data\
c. Text generation and summarization\
d. Both b and c

### Prompt Structuring
**6. Which prompt structure best guides an AI to write a product review based on specifications?**\
a. "Write a review."\
b. "Based on the product details below, write a professional review addressing features, pros, and cons."\
c. "Summarize the product features."\
d. "Create a list of pros and cons for the product."

### AI Pipeline Design
**7. For a customer service chatbot, what is the correct pipeline flow?**\
a. User Input → Sentiment Analysis → Response Generation\
b. User Input → Response Generation → Knowledge Retrieval\
c. User Input → Knowledge Retrieval → Response Generation\
d. User Input → Pre-processing → Response Generation

### Business Requirements Translation
**8. How can AI assist in improving employee engagement survey analysis?**\
a. Extract keywords from responses\
b. Summarize survey results and identify trends\
c. Generate questions for the survey\
d. All of the above

### Designing Output Formatting
**9. Which output design ensures better usability in a business report generator?**\
a. Free-text paragraph summaries\
b. Structured tables with key metrics and insights\
c. Bullet points of general observations\
d. Unformatted raw data

### Selecting Chain Tools
**10. To evaluate customer satisfaction based on chat logs, what tools are needed?**\
a. Sentiment analysis and summarization tools\
b. Summarization tools only\
c. Text generation and pre-processing tools\
d. Retrieval tools and text classification

# Section 2: Data Preparation (10 Questions)

### Chunking Strategy for Academic Papers
**1. Which chunking strategy works best for extracting information from research papers?**\
a. Fixed-size chunking\
b. Section-based chunking (abstract, introduction, etc.)\
c. Random sampling\
d. Sentence-by-sentence chunking

### Document Filtering
**2. A knowledge base includes outdated technical documentation. What filtering strategy should be used?**\
a. Remove all old documents\
b. Use keyword filters to identify irrelevant content\
c. Classify documents by relevance using a machine learning model\
d. Both b and c

### Python Libraries for Document Parsing
**3. Which library is best for extracting content from .docx files?**\
a. PyPDF2\
b. Python-docx\
c. BeautifulSoup\
d. Tesseract

### Delta Lake Integration
**4. How should chunked data be stored in Delta Lake for efficient retrieval?**\
a. Store chunks as individual files\
b. Use a table schema with chunk ID, content, and metadata\
c. Combine all chunks into one large record\
d. Save chunks in raw format

### Source Document Identification
**5. What kind of source documents are most suitable for a product recommendation AI?**\
a. Customer reviews and transaction data\
b. Random social media posts\
c. Employee training documents\
d. Generic blog posts

### Evaluation Metrics for Retrieval Systems
**6. Which metric is most critical for evaluating document retrieval performance?**\
a. BLEU score\
b. Precision and recall\
c. Latency\
d. Word error rate

### Prompt-Response Alignment
**7. How do you ensure prompts and responses align with a summarization model task?**\
a. Include clear instructions in the prompt\
b. Use a fine-tuned model\
c. Optimize the output format\
d. All of the above

### Extraneous Content Filtering
**8. What is the best method to filter irrelevant images from a dataset?**\
a. Use image classifiers trained on labeled data\
b. Manually review all images\
c. Apply random sampling\
d. Rely on metadata filtering

### Document Storage Optimization
**9. For a multilingual RAG application, how should documents be stored?**\
a. Separate tables for each language\
b. Unified table with a language identifier\
c. Multiple Delta Lake schemas for different languages\
d. Combine all languages into one column

### Chunk Evaluation Techniques
**10. What is the best way to evaluate if chunked text is suitable for a model's context length?**\
a. Measure token count per chunk\
b. Check semantic continuity across chunks\
c. Test retrieval accuracy for each chunk\
d. All of the above

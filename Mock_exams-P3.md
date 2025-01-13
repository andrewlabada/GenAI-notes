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


# Section 3: Application Development (10 Questions)
### Choosing LangChain Tools
**1. For a document summarization application, which LangChain tool should be used?**\
a. Chains and memory\
b. Vector store retriever\
c. Prompt templates\
d. All of the above

### Prompt Impact on LLM Outputs
**2. How does adding specific domain jargon to prompts affect outputs?**\
a. Increases output relevance for the domain\
b. Decreases response quality\
c. Has no impact\
d. Always reduces accuracy

### Qualitative Response Assessment
**3. A generated text contains minor hallucinations. What should you do?**\
a. Ignore the issue if it’s minor\
b. Refine the prompt to reduce hallucinations\
c. Switch to a smaller model\
d. Add post-processing logic to remove hallucinations

### Selecting Chunking Strategy
**4. An application processes legal contracts with long clauses. Which chunking strategy is best?**\
a. Sentence-based chunking\
b. Fixed-size chunking\
c. Clause-based chunking\
d. Random chunking

### Augmenting Prompts with Context
**5. How can user-specific input be incorporated into an LLM's prompt?**\
a. Predefine all possible user inputs\
b. Dynamically append user input to the prompt\
c. Use only general context without user input\
d. Avoid using user input to prevent bias

### Response Baseline Adjustment
**6. To make an AI-generated response more concise, what should you do?**\
a. Include "Be concise" in the prompt\
b. Train the model on concise data\
c. Use a smaller context window\
d. Reduce the model size

### LLM Guardrail Implementation
**7. Which method helps prevent negative outcomes in generated responses?**\
a. Implement toxicity filters\
b. Use predefined output templates\
c. Set stricter decoding parameters (e.g., temperature, top-k)\
d. All of the above

### Creating Metaprompts
**8. A chatbot generates irrelevant information during conversations. What is the purpose of a metaprompt in this case?**\
a. To reduce hallucinations by guiding the response format\
b. To increase output diversity\
c. To enforce token limits\
d. To improve API efficiency

### LLM Selection
**9. Which model is best for generating answers from scientific papers?**\
a. A general-purpose pre-trained LLM\
b. A fine-tuned LLM on scientific data\
c. A small-sized embedding model\
d. A translation-specific model

### Embedding Model Context Length
**10. What is the main factor when selecting context length for an embedding model?**\
a. Token limits of the model\
b. Length of source documents and expected queries\
c. Memory constraints of deployment\
d. All of the above

# Section 4: Assembling and Deploying Applications (10 Questions)
### Building a Simple Chain with LangChain
**1. Which components are necessary to create a summarization chain?**\
a. A retriever and a pre-trained LLM\
b. A prompt template and an LLM\
c. A database and an evaluation metric\
d. A model card and metadata

### Endpoint Deployment Steps
**2. What is the correct order of steps to deploy a RAG application endpoint?**\
a. Register model → Prepare retriever → Create endpoint → Test endpoint\
b. Test endpoint → Register model → Deploy retriever → Prepare input data\
c. Create retriever → Test input data → Register endpoint → Deploy model\
d. Deploy model → Register endpoint → Prepare retriever → Test input data

### Vector Search Index Creation
**3. What is the primary requirement for creating a vector search index?**\
a. A labeled dataset\
b. A set of embeddings for the documents\
c. A pre-trained summarization model\
d. A tokenization strategy

### Model Registration in Unity Catalog
**4. Why is registering a model in Unity Catalog beneficial?**\
a. Allows centralized model management\
b. Enables tracking model lineage and versions\
c. Provides access control and auditing\
d. All of the above

### Model Serving Access Control
**5. Which technique ensures secure access to a model-serving endpoint?**\
a. API key authentication\
b. Role-based access control\
c. IP whitelisting\
d. All of the above

### Foundation Model API Integration
**6. What is a common challenge when using Foundation Model APIs?**\
a. Handling token limits for long queries\
b. Optimizing API call costs\
c. Ensuring secure API connections\
d. All of the above

### Dependencies for a RAG Application
**7. Which of the following is NOT a dependency for a RAG application?**\
a. A retriever\
b. A text-to-speech model\
c. An embedding model\
d. Input examples

### Simple Chain Coding
**8. What is the output of this simple LangChain code?**\

```python
from langchain.chains import SimpleChain
chain = SimpleChain(input="What is AI?", output="AI is artificial intelligence.")
print(chain.output)
``` 
a. What is AI?\
b. AI is artificial intelligence.\
c. An error\
d. None

### RAG Deployment Resources
**9. What resource is NOT needed to serve features for a RAG application?**\
a. Vector store\
b. A caching system\
c. A prompt engineering module\
d. A voice synthesis engine

### Control Costs in Databricks
**10. How can costs for RAG applications be minimized in Databricks?**\
a. Reduce cluster size and enable auto-scaling\
b. Limit API calls by optimizing queries\
c. Use smaller embedding models\
d. All of the above


# Section 5: Governance (10 Questions)
### Masking Techniques
**1. Which technique is best for anonymizing sensitive user data in a dataset?**\
a. Tokenization\
b. Data masking with pseudonyms\
c. Nullifying sensitive fields\
d. Encrypting all data

### Guardrail Techniques for Malicious Inputs
**2. What is the most effective guardrail for preventing SQL injection attacks?**\
a. Use regex to validate inputs\
b. Implement parameterized queries\
c. Sanitize inputs by removing special characters\
d. Restrict database user permissions

### Problematic Text Mitigation
**3. A dataset contains biased terms in user-generated content. What is the best strategy for mitigation?**\
a. Replace biased terms with neutral terms\
b. Train the model to ignore biased terms\
c. Remove all user-generated content\
d. Flag and review problematic content manually\

### Legal and Licensing Requirements
**4. Before using publicly available datasets, which legal consideration is most important?**\
a. File format compatibility\
b. Open-source licensing terms\
c. Dataset size\
d. Compatibility with your model

### Ethical Data Usage
**5. A team is building a sentiment analysis model on social media data. How can they ensure ethical data usage?**\
a. Avoid scraping without user consent\
b. Use anonymized data\
c. Follow platform-specific data usage policies\
d. All of the above

### Guardrails to Avoid Negative Outcomes
**6. Which of the following is NOT a guardrail technique?**\
a. Fine-tuning the model\
b. Toxicity filtering\
c. Response validation\
d. Logging model inputs and outputs

### Handling Sensitive Information in Prompts
**7. How can private data leaking in prompts be minimized?**\
a. Use metaprompts with strict formatting\
b. Replace sensitive information with placeholders\
c. Avoid using user data in prompts\
d. Encrypt all prompts

### Governance for Multi-User Applications
**8. What is an essential governance measure for applications serving multiple clients?**\ 
a. Hardcoding user roles into the app\
b. Enabling role-based access control\
c. Using a single shared database for all clients\
d. Logging only admin actions

### Mitigating Privacy Risks in Data Sources
**9. A RAG application is built using customer support emails. How can privacy risks be minimized?**\
a. Remove customer names and email IDs\
b. Encrypt all data in transit and at rest\
c. Use a data anonymization pipeline\
d. All of the above

### Governance for LLM Applications
**10. Which feature helps ensure compliance in AI applications?**\
a. Regular model updates\
b. Clear documentation of training data sources\
c. Both a and b\
d. None of the above

# Section 6: Evaluation and Monitoring (10 Questions)
### LLM Choice Based on Metrics
**1. Which of the following is NOT a standard evaluation metric for selecting an LLM?**\
a. BLEU score\
b. Token usage\
c. F1 score\
d. Perplexity

### Monitoring Metrics for Deployment
**2. What is a key metric to monitor in an LLM-based chatbot?**\
a. Token usage per response\
b. Latency for response generation\
c. User satisfaction scores\
d. All of the above

### Evaluating RAG Model Performance
**3. Which tool is best for tracking model performance in a Retrieval-Augmented Generation (RAG) application?**\
a. MLflow\
b. TensorBoard\
c. Hadoop\
d. Elasticsearch

### Inference Logging for Monitoring
**4. What is the primary benefit of inference logging in LLM applications?**\
a. Real-time debugging\
b. Analyzing input-output quality\
c. Tracking API call costs\
d. All of the above

### Cost Control in Databricks**
5. What is NOT a recommended strategy for controlling costs in LLM applications?**\
a. Using smaller models for experimentation\
b. Implementing caching for frequent queries\
c. Running models on larger-than-required clusters\
d. Optimizing input preprocessing

### Quantitative Metrics for Evaluation
**6. Which metric is best for evaluating LLM output accuracy?**\
a. Word error rate\
b. Recall\
c. BLEU score\
d. Accuracy

### Cost Optimization Techniques
**7. How can you reduce API costs for an LLM application?**\
a. Cache common responses\
b. Use lower temperature values\
c. Limit context length in prompts\
d. All of the above

### Real-Time Performance Evaluation
**8. What tool can be used for monitoring real-time performance in Databricks?**\ 
a. MLflow\
b. Spark UI\
c. Databricks SQL Analytics\
d. All of the above

### LLM Cost Monitoring Metrics
**9. Which metric directly reflects LLM usage costs?**\
a. Response latency\
b. Token count per query\
c. Model training duration\
d. User feedback

### Improving LLM Output Quality
**10. A deployed LLM provides inconsistent answers. What monitoring method can improve output quality?**\
a. Analyze inference logs\
b. Compare outputs with ground truth\
c. Implement automated quality tests\
d. All of the above

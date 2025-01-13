# Databricks Gen AI Engineer (Associate) Exam Preparations

## **Section 1: Design Applications (8 Questions)**
**Prompt Design**\
1.) Design a prompt that asks an LLM to return customer service summaries in JSON format, including "Issue," "Resolution," and "Customer Feedback."\
a. Provide a summary.\
b. Summarize using plain text.\
c. Return a JSON object with the required fields.\
d. Provide key highlights only. 

**Model Tasks**\
2.) Which task is most appropriate for a recommendation system to suggest products based on user preferences?\
a. Text classification\
b. Question answering\
c. Recommendation\
d. Image generation

**Chain Components**\
3.) For a multi-stage process that involves extracting data and generating a report, which chain components are best suited?\
a. Prompt chaining\
b. Tool chaining\
c. Retrieval chaining\
d. Text-to-image chaining

**Business Use Cases**\
4.) How would you define the input and output requirements for an AI system designed to provide legal document summarization?\
a. User provides a document; AI returns a bullet-point summary.\
b. User provides a query; AI generates relevant examples.\
c. AI identifies legal risks in bullet points.\
d. AI returns a full summary in paragraph form.

**Knowledge Gathering Tools**\
5.) Which tool is most effective for a multi-stage reasoning task that requires browsing the web for current information?\
a. Retriever agent\
b. Vector database\
c. Browser tool\
d. Prompt selector

**Scenario Analysis**\
6.) A retail company wants to predict sales trends. Which AI pipeline description is most suitable?\
a. Analyze past data and generate charts for trends.\
b. Use customer data and forecast product demand.\
c. Recommend products based on current inventory.\
d. Perform sentiment analysis on customer reviews.

**Reasoning Tools**\
7.) Which reasoning tool is used to handle complex multi-turn conversations?\
a. Conversational agents\
b. Zero-shot classification\
c. Data pipelines\
d. Knowledge distillation

**AI Pipeline Design**\
8.) How would you order tools for an application that takes user input, retrieves relevant documents, and generates a summary?\
a. Input → Retrieval → Summarization → Output\
b. Retrieval → Input → Summarization → Output\
c. Input → Summarization → Retrieval → Output\
d. Summarization → Retrieval → Input → Output

## Section 2: Data Preparation (8 Questions)
**Chunking Strategies**\
1.) What chunking strategy works best for a lengthy legal document?\
a. Fixed-size chunking\
b. Semantic-based chunking\
c. Random chunking\
d. Overlapping window chunking

**Extraneous Content**\
2.) Which content should be removed from a document being prepared for a RAG application?\
a. Metadata\
b. Formatting symbols\
c. Advertisements\
d. All of the above

**Python Packages**\
3.) Which Python package is most appropriate for extracting text from PDFs?\
a. pandas\
b. PyPDF2\
c. NumPy\
d. matplotlib

**Delta Lake Integration**\
4.) What operation is required to write chunked text into a Delta Lake table?\
a. Insert chunks as individual rows.\
b. Aggregate chunks into a single row.\
c. Store as JSON blobs.\
d. Combine text without chunking.

**Document Selection**\
5.) Which source document is most suitable for a financial RAG application?\
a. A blog post about investing\
b. Quarterly financial reports\
c. A user-generated forum post\
d. A Wikipedia article

**Prompt/Response Alignment**\
6.) Which pair best aligns with a text summarization task?\
a. Input: Text, Output: Key points\
b. Input: Question, Output: Answer\
c. Input: Image, Output: Caption\
d. Input: Text, Output: Sentiment score

**Retrieval Metrics**\
7.) Which metric is key for evaluating retrieval performance?\
a. Latency\
b. Recall\
c. Storage capacity\
d. Throughput

**Filtering Techniques**\
8.) How can irrelevant content from source data be effectively filtered?\
a. Predefined keyword filters\
b. Random sampling\
c. Neural network classifiers\
d. Both a and c

## Section 3: Application Development (8 Questions)
**Data Extraction Tools**\
1.) What tool is best for extracting customer data stored in an unstructured JSON file?\
a. pandas\
b. LangChain JSONLoader\
c. PyPDF2\
d. spaCy

**LangChain Tools**\
2.) Which LangChain module is best for constructing a chatbot that retrieves data from a knowledge base?\
a. Chains\
b. Memory\
c. Agents\
d. Prompts

**Prompt Formats**\
3.) How can changing the prompt format affect model outputs?\
a. Improves the model's accuracy without retraining\
b. Guarantees deterministic results\
c. Alters the structure and relevance of responses\
d. Reduces inference latency

**Response Assessment**\
4.) What is the most common issue when evaluating LLM responses for safety?\
a. Irrelevant outputs\
b. Hallucinations\
c. Overfitting\
d. Tokenization errors

**Prompt Augmentation**\
5.) Which technique can augment prompts with user context?\
a. Appending relevant terms and intents to the prompt\
b. Embedding user context into vectors\
c. Using a different LLM for context\
d. Random sampling

**LLM Guardrails**\
6.) How would you implement guardrails to prevent an LLM from generating harmful outputs?\
a. By filtering prompts with a blacklist\
b. By setting response length limits\
c. By using safety filters like moderation APIs\
d. All of the above

**Metaprompts**\
7.) What is the goal of a metaprompt?\
a. Improve the model's speed\
b. Minimize hallucinations and ensure compliance\
c. Enhance token embedding accuracy\
d. Generate better embeddings

**Model Selection**\
8.) When choosing an LLM for a customer support chatbot, what attribute is most important?\
a. Context length\
b. Generation speed\
c. Training dataset size\
d. Tokenizer efficiency






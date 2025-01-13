## 1. Prompt Engineering (10 Questions)
### 1.1 Which of the following is the primary difference between zero-shot and few-shot prompting?
A. Zero-shot does not provide examples, while few-shot provides several examples to guide the model.\
B. Zero-shot requires the model to generate responses based on prior knowledge only.\
C. Few-shot prompts are limited to 1-2 examples, while zero-shot provides more context.\
D. Zero-shot involves chaining multiple prompts together.

### 1.2 What is the purpose of prompt chaining in generative AI?
A. To improve response time by providing continuous inputs to the model.\
B. To break complex tasks into simpler sub-tasks by chaining multiple prompts together.\
C. To reduce the number of tokens used in each prompt.\
D. To limit the model's response options to a set of predefined answers.



### 1.3 What does a system prompt typically control in a generative AI pipeline?
A. The input provided by the user to the model.\
B. The specific actions or behavior the model should follow.\
C. The number of tokens in the response.\
D. The format of the generated content.

### 1.4 In which scenario would zero-shot prompting be more effective than few-shot prompting?
A. When the task requires minimal prior context.\
B. When the task has multiple possible correct answers.\
C. When the model has been trained on a specific dataset.\
D. When you have a large number of example responses available.


### 1.5 What is a common challenge associated with zero-shot prompting?
A. Generating too many examples for the model to process.\
B. The model may provide less accurate responses due to lack of context.\
C. The response generation time increases significantly.\
D. The model might repeat answers without introducing new information.


### 1.6 What type of task is most suited to few-shot prompting?
A. Tasks requiring high generalization from the model.\
B. Tasks where the model is unfamiliar with the domain.\
C. Tasks where providing examples helps the model better understand the desired response.\
D. Tasks requiring long outputs.

### 1.7 Which of the following is the best strategy for using a prompt when dealing with highly structured data?
A. Use zero-shot prompting to let the model infer patterns.\
B. Use few-shot prompting with examples of structured data outputs.\
C. Avoid using any prompts at all for structured data.\
D. Use a complex system prompt that controls the entire output process.

### 1.8 Which of the following would be considered a user prompt?
A. The instruction provided to the model to control its behavior.\
B. A sample of data that guides the model to generate a response.\
C. The expected output format for the generated text.\
D. The system-level configurations for managing tokens.

### 1.9 What is a common approach for testing the effectiveness of a prompt?
A. Generating the same output multiple times and selecting the best.\
B. Using a set of tasks with predefined answers to see how well the model matches\
C. Testing with a minimal amount of examples and seeing if the model generalizes.\
D. Avoiding feedback loops to maintain consistency in answers.

### 1.10 Which of the following is true about prompt engineering?
A. Prompt engineering focuses on creating prompts that are flexible and adaptable for different tasks.\
B. Prompt engineering is primarily concerned with the underlying architecture of the model.\
C. Prompt engineering is most useful for models with no prior training.\
D. Prompt engineering is only needed when dealing with unstructured data.


## 2. Retrieval-Augmented Generation (RAG) (10 Questions)
### 2.1 What is the role of vector search in Retrieval-Augmented Generation (RAG)?
A. It compresses the data for more efficient storage.\
B. It searches for relevant content from structured data sources like databases.\
C. It generates a summary of retrieved documents.\
D. It retrieves relevant information using vector embeddings to enhance model responses.

### 2.2 How does chunking improve the efficiency of Retrieval-Augmented Generation (RAG)?
A. By increasing the context window of the model.\
B. By breaking large documents into smaller pieces for efficient retrieval.\
C. By simplifying the model's response generation.\
D. By reducing the number of documents to retrieve.


### 2.3 What is a chunking strategy commonly used in RAG?
A. Sentence split and paragraph split\
B. Only sentence split\
C. Random chunking based on document size\
D. Splitting based on page numbers

### 2.4 In RAG, how does retrieval differ from generation?
A. Retrieval fetches relevant documents, while generation creates answers based on the retrieved content.\
B. Retrieval creates answers from scratch, while generation fetches information.\
C. Retrieval and generation are the same process in RAG.\
D. Retrieval requires predefined templates, while generation adapts to dynamic inputs.


### 2.5 How does Databricks’ Feature Store assist in Retrieval-Augmented Generation?
A. It provides external knowledge in unstructured formats for RAG tasks.\
B. It stores and retrieves structured data for enhancing responses in RAG.\
C. It converts structured data into embeddings for vector search.\
D. It is not related to RAG tasks.

### 2.6 Which tool in Databricks is specifically designed for efficiently querying document embeddings during RAG execution?
A. Databricks Lakehouse\
B. Databricks Feature Store\
C. Databricks Vector Search\
D. Databricks MLflow


### 2.7 What does the parsing step in RAG involve?
A. Organizing the data into vectors for fast search.\
B. Retrieving the best possible answers based on the query.\
C. Extracting relevant information from documents such as PDFs or text files.\
D. Generating summaries from the retrieved data.

### 2.8 In a RAG pipeline, which of the following best describes the generation step?
A. Searching the database for relevant documents.\
B. Producing a new document by combining content from multiple sources.\
C. Identifying which external documents are relevant.\
D. Cleaning and preparing raw data for further processing.


### 2.9 What would likely happen if chunking size is too large in a RAG setup?
A. The retrieval process becomes faster but less relevant.\
B. Retrieval becomes slower, and the model might miss important context.\
C. The retrieval process is unaffected by chunking size.\
D. The model generates more accurate answers.


### 2.10 What is the primary benefit of using RAG in generative AI?
A. Reduces the need for prompt engineering.\
B. Enhances model responses with external, relevant knowledge.\
C. Simplifies deployment pipelines for AI models.\
D. It allows the model to handle only structured data.

## 3. LangChain Framework (10 Questions)
### 3.1 What is the purpose of LangChain in generative AI workflows?
A. To manage model outputs and evaluate their quality.\
B. To connect different components (models, retrievers, etc.) in a structured workflow.\
C. To optimize resource allocation for generative AI models.\
D. To handle user interactions directly.


### 3.2 Which of the following is a core component of LangChain?
A. Models\
B. Prompts\
C. Retrievers\
D. All of the above

### 3.3 In LangChain, what role does a retriever play?
A. It generates content based on model responses.\
B. It processes the text to improve output quality.\
C. It retrieves relevant documents or data for further processing.\
D. It stores the final generated output for future use.

### 3.4 How can LangChain improve the efficiency of generative AI workflows?
A. By automating the entire AI development process.\
B. By organizing and chaining different components to ensure smooth transitions between steps.\
C. By reducing the model's size to increase performance.\
D. By eliminating the need for external data sources.

### 3.5 How would you use LangChain to integrate a language model with external APIs?
A. Use the prompt component to call external APIs.\
B. Use the model component to call APIs directly.\
C. Use the tools component to add external APIs as retrievers or actions.\
D. LangChain cannot be used for integrating external APIs.

### 3.6 In a typical LangChain workflow, which component retrieves documents from an external source?
A. Model\
B. Retriever\
C. Prompt\
D. Tool


### 3.7 What is an example use case for LangChain?
A. Creating a batch prediction pipeline.\
B. Building a multistage reasoning AI workflow that involves retrieving data, processing it, and generating outputs.\
C. Training a model from scratch.\
D. Performing a one-time query to a database.


### 3.8 Which of the following would likely require the use of LangChain?
A. Generating text responses from a language model.\
B. Retrieving data from an external API and generating a response based on it.\
C. Just querying a database.\
D. Simple one-time prompts with minimal data.


### 3.9 How does LangChain assist in creating a structured workflow for complex AI applications?
A. By reducing the number of components used in the process.\
B. By allowing you to link components like models, prompts, and tools in a logical sequence.\
C. By eliminating the need for external data.\
D. By simplifying the deployment of models to production.


### 3.10 What type of AI application is LangChain particularly useful for?
A. Simple text generation applications.\
B. Multistage reasoning workflows involving document retrieval, generation, and API integration.\
C. Real-time predictions in production environments.\
D. Only for unstructured text data tasks.

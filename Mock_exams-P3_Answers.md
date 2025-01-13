# Section 1: Design Applications
**d. Provide examples of input-output pairs.**\
Explanation: Examples clarify the desired behavior of the model, making the prompt effective.

**a. Translation.**\
Explanation: Translation is a straightforward one-to-one task for input-output mapping.

**d. Knowledge base retriever + summarizer.**\
Explanation: This setup retrieves and summarizes information effectively for FAQs.

**c. Outputs should meet accuracy and safety standards.**\
Explanation: Outputs must align with business and ethical goals.

**a. Output examples + input examples + intermediate chain logic.**\
Explanation: These elements define a multi-stage reasoning pipeline.

# Section 2: Data Preparation
**c. By logical sections like paragraphs.**\
Explanation: Logical sections maintain contextual integrity.

**b. Remove advertisements and footnotes.**\
Explanation: These elements are usually extraneous in content analysis.

**d. PyPDF2.**\
Explanation: PyPDF2 extracts text from PDFs effectively.

**c. Create a Delta table schema matching the chunk structure.**\
Explanation: A matching schema ensures correct data storage and retrieval.

**b. Documents containing high-quality, relevant information.**\
Explanation: Quality data is essential for accurate AI output.

**a. Conciseness and relevance.**\
Explanation: These qualities ensure the model aligns with its task.

**c. Precision, recall, and F1 score.**\
Explanation: These metrics evaluate retrieval accuracy and relevance.

# Section 3: Application Development
**d. All of the above.**\
Explanation: LangChain tools combine to handle retrieval, formatting, and processing.

**a. Increases output relevance for the domain.**\
Explanation: Domain-specific language enhances relevance.

**b. Refine the prompt to reduce hallucinations.**\
Explanation: Adjusting the prompt can guide the model toward accurate outputs.

**c. Clause-based chunking.**\
Explanation: Legal contracts are best processed clause by clause for contextual accuracy.

**b. Dynamically append user input to the prompt.**\
Explanation: This approach customizes responses based on user input.

**a. Include "Be concise" in the prompt.**\
Explanation: Clear instructions in prompts can guide the LLM to desired behavior.

**d. All of the above.**\
Explanation: Multiple techniques reduce risks of negative outcomes.

**a. To reduce hallucinations by guiding the response format.**\
Explanation: Metaprompts set guidelines for accurate and relevant outputs.

**b. A fine-tuned LLM on scientific data.**\
Explanation: Specialized data improves accuracy for specific tasks.

**d. All of the above.**\
Explanation: These factors ensure embedding models align with data and application goals.

# Section 4: Assembling and Deploying Applications
**b. A prompt template and an LLM.**\
Explanation: These components are essential for summarization chains.

**a. Register model → Prepare retriever → Create endpoint → Test endpoint.**\
Explanation: This sequence ensures proper deployment and functionality.

**b. A set of embeddings for the documents.**\
Explanation: Vector search indexes require document embeddings for similarity matching.

**d. All of the above.**\
Explanation: Unity Catalog centralizes model management, auditing, and lineage tracking.

**d. All of the above.**\
Explanation: These techniques secure access to endpoints.

**d. All of the above.**\
Explanation: API token limits, cost, and secure connections are common challenges.

**b. A text-to-speech model.**\
Explanation: Text-to-speech is not typically a dependency for RAG applications.

**b. AI is artificial intelligence.**\
Explanation: The output is the predefined response in the chain.

**d. A voice synthesis engine.**\
Explanation: Voice synthesis is unrelated to typical RAG application features.

**d. All of the above.**\
Explanation: Combining these strategies minimizes costs effectively.

# Section 5: Governance
**b. Data masking with pseudonyms.**\
Explanation: Pseudonymization replaces sensitive data while maintaining usability.

**b. Implement parameterized queries.**\
Explanation: Parameterized queries prevent injection vulnerabilities.

**a. Replace biased terms with neutral terms.**\
Explanation: Replacing terms ensures neutrality while retaining data usability.

**b. Open-source licensing terms.**\
Explanation: Licensing governs usage rights and restrictions.

**d. All of the above.**\
Explanation: Ethical data use combines multiple measures to ensure compliance.

**a. Fine-tuning the model.**\
Explanation: Fine-tuning is a model improvement technique, not a guardrail.

**b. Replace sensitive information with placeholders.**\
Explanation: Placeholders protect private data from leaking into responses.

**b. Enabling role-based access control.**\
Explanation: Role-based controls ensure data access aligns with user roles.

**d. All of the above.**\
Explanation: Multiple measures mitigate privacy risks effectively.

**c. Both a and b.**\
Explanation: Model updates and documentation ensure transparency and compliance.

# Section 6: Evaluation and Monitoring
**b. Token usage.**\
Explanation: Token usage measures costs, not model accuracy or quality.

**d. All of the above.**\
Explanation: These metrics evaluate efficiency, cost, and user experience.

**a. MLflow.**\
Explanation: MLflow provides tools for tracking and analyzing performance.

**d. All of the above.**\
Explanation: Logging aids debugging, quality assessment, and cost tracking.

**c. Running models on larger-than-required clusters.**\
Explanation: This increases costs unnecessarily.

**c. BLEU score.**\
Explanation: BLEU evaluates text accuracy compared to a reference.

**d. All of the above.**\
Explanation: Each technique optimizes API usage costs.

**d. All of the above.**\
Explanation: These tools monitor performance in real-time.

**b. Token count per query.**\
Explanation: Token usage directly correlates with cost.

**d. All of the above.**\
Explanation: Combining methods ensures consistent quality improvements.


## Section 1: Design Applications
**1. c. Return a JSON object with the required fields.**\
Explanation: To ensure a structured response suitable for further processing, prompts should explicitly request JSON-formatted output.

**3. c. Recommendation**\
Explanation: Recommendation tasks involve suggesting items based on user preferences or historical data.

**4. b. Tool chaining**\
Explanation: Tool chaining connects tools for extracting data and generating a report in a sequence.

**5. a. User provides a document; AI returns a bullet-point summary.**\
Explanation: This describes the input-output flow for a summarization task in legal documents.

**6. c. Browser tool**\
Explanation: Browser tools can fetch current information from the web, which is vital for multi-stage reasoning.

**7. b. Use customer data and forecast product demand.**\
Explanation: This approach aligns with sales trend prediction using AI.

**8. a. Conversational agents**\
Explanation: Conversational agents manage complex multi-turn conversations by maintaining context.

**9. a. Input → Retrieval → Summarization → Output**\
Explanation: This sequence ensures the AI retrieves relevant information before summarizing it.


## Section 2: Data Preparation

1. **b. Semantic-based chunking**\
Explanation: This approach preserves meaning, crucial for lengthy legal documents.

2. **d. All of the above**\
Explanation: Removing irrelevant content ensures cleaner input for AI models.

3. **b. PyPDF2**\
Explanation: PyPDF2 is a widely-used library for extracting text from PDF files.

4. **a. Insert chunks as individual rows.**\
Explanation: Writing chunks into separate rows ensures better storage and retrieval efficiency.

5. **b. Quarterly financial reports**\
Explanation: These reports provide structured, reliable data relevant to financial applications.

6. **a. Input: Text, Output: Key points**\
Explanation: Summarization tasks focus on condensing text into key points.

7. **b. Recall**\
Explanation: Recall measures how well relevant documents are retrieved, critical for RAG applications.

8. **d. Both a and c**\
Explanation: Keyword filters and classifiers are effective for filtering irrelevant content.


## Section 3: Application Development
**1. b. LangChain JSONLoader**\
Explanation: This module is tailored for extracting data from JSON files.

**2. c. Agents**\
Explanation: LangChain agents manage interactions with external knowledge bases.

**3. c. Alters the structure and relevance of responses**\
Explanation: Prompt formats guide the model to produce more relevant or structured outputs.

**4. b. Hallucinations**\
Explanation: Hallucinations occur when the model generates incorrect or irrelevant outputs.

**5. a. Appending relevant terms and intents to the prompt**\
Explanation: Adding user context improves relevance and specificity in model responses.

**6. d. All of the above**\
Explanation: Combining various guardrail techniques ensures robust safety measures.

**7. b. Minimize hallucinations and ensure compliance**\
Explanation: Metaprompts focus on guiding the model to produce safer, more accurate outputs.

**8. a. Context length**\
Explanation: A longer context length allows the chatbot to understand and respond effectively to longer user interactions.


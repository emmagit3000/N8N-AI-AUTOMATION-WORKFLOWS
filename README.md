# n8n AI Automation Workflows

This a collection of my early hands-on AI automation projects built while taking the AI Automation program at 10Alytics.

These workflows helped me practice building practical automations using n8n, Google Gemini, Pinecone, and AI agents.

## Workflows

### 1. Applicant Screening & Automated Follow-up
- Triggered when a new form is submitted  
- Appends the applicant data to Google Sheets  
- Filters and routes applicants based on their skills (Python/JavaScript developers vs others)  
- Sends personalized Gmail follow-up messages depending on the category  
- Includes a data minimization note to discard unqualified applicants' information

**File:** `applicant form.json`

### 2. Basic AI Agent Chat Workflow
- My first experiment with AI agents in n8n  
- Triggered when a chat message is received  
- Uses Google Gemini Chat Model with memory  
- Pulls relevant row data from Google Sheets  
- Sends automated replies via Gmail  

**File:** `Lombart Workflow.json`

### 3. RAG-based Document Retrieval Workflow
- Allows retrieval of information from a Pinecone vector database  
- Uses Google Gemini embeddings to search and return relevant context  
- Built to enable AI agents to access restricted/private data in a structured way  
- Includes document loading, text splitting, and vector storage components  

**File:** `Lombart Games.json`

## Technologies Used
- n8n (workflow orchestration, triggers, filters, switch logic)
- Google Gemini (chat model & embeddings)
- Pinecone (vector database)
- Google Sheets & Gmail integrations
- RAG (Retrieval-Augmented Generation) basics
- AI Agents with memory and tool calling

# Purpose
These are learning projects I created while building my foundational skills in AI automation. They focus on practical use cases like automated responses, applicant screening and retrieving information using vector databases.
## Purpose
These are learning projects I created while building my foundational skills in AI automation. They focus on practical use cases like automated responses, applicant screening, and retrieving information using vector databases.

# AI Agents Experiments

A collection of experiments exploring different AI agent patterns and capabilities.

## Current Experiments

### 🔍 RAG Engineering Advisor
An agent that uses retrieval-augmented generation to provide technical solutions from an engineering knowledge base.

**What it does:**
- Searches through engineering problems and solutions using BM25
- Returns relevant fixes, tools needed, and emergency procedures
- Built with LangChain and custom tool integration

### 🛠️ Multi-Tool Agent  
An agent that can handle various tasks through different tools:

**Capabilities:**
- Get current time in different time zones
- Generate images from text descriptions
- Perform web searches for current information
- Process real-time data

## Technical Details

**Tools & Frameworks:**
- LangChain for agent orchestration
- SmolAgents for tool integration
- BM25 for semantic search
- Various APIs for time, images, and web search

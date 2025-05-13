# Finance RAG

## Project Overview
This project demonstrates the development of an advanced financial Q&A agent built using LangChain and GPT-3.5-turbo. The system integrates structured tool-calling capabilities with custom Pydantic schemas and implements dynamic prompt routing to create an intelligent financial assistant that can retrieve and analyze stock information through a conversational interface.
The agent is designed to understand natural language queries about financial markets, intelligently select appropriate tools, and execute relevant API calls to fetch real-time financial data using the Yahoo Finance API (via yfinance) and web-based information using DuckDuckGo.


## Key Focus
- Recreates the OpenAI function calling process using LangChain's framework
- Uses Pydantic schemas to define structured inputs and outputs
- Applies these techniques to financial data retrieval and analysis

## Implementation
The project shows two parallel approaches:
1. Direct OpenAI function calling
2. LangChain implementation with equivalent functionality using Pydantic models

Both approaches enable an agent to:
- Understand financial queries
- Select appropriate tools
- Retrieve stock data from YFinance
- Return formatted financial information

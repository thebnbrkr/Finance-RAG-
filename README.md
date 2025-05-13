# Finance RAG

## Project Overview
This project demonstrates how to recreate OpenAI's function calling capabilities using LangChain and Pydantic for financial applications. It implements a financial Q&A system that can retrieve stock information and analyze market performance.

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

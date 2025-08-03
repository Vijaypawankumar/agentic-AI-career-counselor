# Architecture Overview

## 🎯 Goal
To build a personalized, intelligent agent using Watsonx + IBM Granite that guides students in career selection based on their strengths and interests.

## 🧱 Components
- **Frontend**: Watsonx Agent Chat UI
- **LLM**: Granite model for processing queries
- **Agent Framework**: LangGraph + ReAct for planning/decision making
- **Data**: User input stored in variables
- **Webhook**: Optional connection to Python backend

## 🔄 Flow
1. User greets → Agent asks 3 key questions.
2. Agent processes the answers using the prompt.
3. Agent generates 3 career suggestions based on real-world roles.

# E-commerce AI Agent using KumoRFM

## Project Description

An interactive analytics agent for ecommerce data, built with Python, pandas, and the KumoRFM predictive model. It enables users to query data, predict customer behavior, and generate marketing insights using natural language and custom tools.

## Project Explanation

This agent is designed for both technical and non-technical users:
- **Non-technical users** can ask questions in plain English (e.g., "Which customers are likely to churn?" or "Predict demand for product X") and receive actionable answers.
- **Technical users** can customize the agent, extend its workflow, and run advanced analytics using the notebook and codebase.

The agent uses a graph-based workflow to route queries to the right tool, ensuring flexible and context-aware responses. The workflow is visualized below:

![Agent Graph](Flowchart.jpeg)

## Key Terms and Features

- **Data Query Tool:** Run custom Python queries on ecommerce dataframes (transactions, articles, customers).
- **Predictive Query Tool:** Use KumoRFM’s Predictive Query Language (PQL) to forecast customer actions and demand.
- **Conversational Agent:** Ask questions in plain English; the agent uses LLMs and tools to answer.
- **Graph-based Workflow:** Modular nodes for data querying, prediction, and conversation management.

## How It Works

- The agent uses a graph structure to route user queries to the right tool (dataframe or predictive model).
- All interactions and tool calls are tracked in a conversation history for context-aware responses.
- The notebook demonstrates usage with example queries and a reusable chat function.

## Folder Structure

- `ecommerce-agent.ipynb`: Main notebook with code, explanations, and examples.
- `developer.py`: Tool and agent definitions. It is the PQL reference file, A link directly to the github of James Briggs is mentioned in the code.
- `pyproject.toml` & `uv.lock`: Dependency management.

## Attribution

This project is inspired by and originated from [jamescalam/ecommerce-agent](https://github.com/jamescalam/ecommerce-agent). It has been modified and extended by me as a hobbyist and student exploring new projects.


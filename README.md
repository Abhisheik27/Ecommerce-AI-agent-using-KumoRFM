# E-commerce AI Agent using KumoRFM

This project is an interactive analytics agent for ecommerce data, built using Python, pandas, and the KumoRFM predictive model. It enables both technical and non-technical users to query data, predict customer behavior, and generate marketing insights using natural language and custom tools.

## Features

- **Data Query Tool:** Run custom Python queries on ecommerce dataframes (transactions, articles, customers).
- **Predictive Query Tool:** Use KumoRFM’s Predictive Query Language (PQL) to forecast customer actions and demand.
- **Conversational Agent:** Ask questions in plain English; the agent uses LLMs and tools to answer.
- **Graph-based Workflow:** Modular nodes for data querying, prediction, and conversation management.

## How It Works

- The agent uses a graph structure to route user queries to the right tool (dataframe or predictive model).
- All interactions and tool calls are tracked in a conversation history for context-aware responses.
- The notebook demonstrates usage with example queries and a reusable chat function.

## Getting Started

1. Clone the repo and install dependencies (see `pyproject.toml` and `uv.lock`).
2. Open `ecommerce-agent.ipynb` in Jupyter or VS Code.
3. Follow the notebook cells to initialize the agent and run example queries.

## For Non-Technical Users

- You can ask questions like “Which customers are likely to churn?” or “Predict demand for product X.”
- The agent will handle the technical details and provide clear, actionable answers.

## For Technical Users

- Customize the tools, dataframes, or model integration in `developer.py`.
- Extend the graph workflow for new analytics or automation tasks.

## Folder Structure

- `ecommerce-agent.ipynb`: Main notebook with code, explanations, and examples.
- `developer.py`: Tool and agent definitions.
- `pyproject.toml` & `uv.lock`: Dependency management.

---

## Attribution

This project is inspired by and originated from [jamescalam/ecommerce-agent](https://github.com/jamescalam/ecommerce-agent). It has been modified and extended by me as a hobbyist and student exploring new projects.

---


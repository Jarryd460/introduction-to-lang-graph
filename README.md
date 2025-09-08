# Introduction to LangGraph

[![Python Version](https://img.shields.io/badge/python-3.13%2B-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository serves as a comprehensive introduction to working with LangGraph, a powerful library for building stateful, multi-actor applications with LLMs. It includes practical examples demonstrating various aspects of building and managing complex LLM workflows.

## 🚀 Features

- Stateful conversation management
- Multi-actor LLM applications
- Sequential agent workflows
- Visualized conversation flows
- Handling multiple inputs and complex workflows
- Easy integration with LangChain and other LLM frameworks
- Environment variable management with python-dotenv
- Poetry for dependency management

## 📦 Prerequisites

- Python 3.13+
- [Poetry](https://python-poetry.org/) for dependency management
- [Jupyter Notebook](https://jupyter.org/) for running examples (optional)

## 🛠️ Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/introduction-to-lang-graph.git
   cd introduction-to-lang-graph
   ```

2. **Set up the environment**
   ```bash
   # Create and activate a virtual environment
   python -m venv venv
   .\venv\Scripts\activate  # On Windows
   # OR
   source venv/bin/activate  # On macOS/Linux
   # OR
   poetry env activate # Creates/Activates the environment created by poetry
   ```

3. **Install dependencies**
   ```bash
   poetry install
   ```

## 🏃‍♂️ Getting Started

1. **Explore the examples**
   - Check out the `Graphs/` directory for Jupyter notebook examples
   - Start with `Hello_World.ipynb` for a basic introduction
   - Explore `Multiple_Inputs.ipynb` for handling complex workflows
   - Try `Sequential_Agent.ipynb` to understand sequential agent workflows
   - Practice with exercises in the `Exercises/` directory

2. **Run a notebook**
   ```bash
   jupyter notebook Graphs/Hello_World.ipynb
   ```

## 🛠 Project Structure

```
.
├── Exercises/               # Practice exercises
│   ├── Exercise_Graph1.ipynb # First exercise notebook
│   └── Exercise_Graph2.ipynb # Second exercise notebook
├── Graphs/                  # Example notebooks
│   ├── Hello_World.ipynb    # Basic LangGraph example
│   ├── Multiple_Inputs.ipynb # Example with multiple input handling
│   └── Sequential_Agent.ipynb # Sequential agent workflow example
├── .gitignore              # Git ignore file
├── poetry.lock             # Dependency lock file
├── poetry.toml             # Poetry configuration
└── pyproject.toml          # Project configuration and dependencies
```

## 💪 Exercises

Practice your LangGraph skills with hands-on exercises:

- `Exercise_Graph1.ipynb`: First exercise to practice basic LangGraph concepts
- `Exercise_Graph2.ipynb`: Second exercise with more advanced LangGraph concepts

## 🙏 Acknowledgments

- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [LangChain](https://www.langchain.com/)
- [Python Poetry](https://python-poetry.org/)
- [LangGraph Course by freeCodeCamp](https://github.com/iamvaibhavmehra/LangGraph-Course-freeCodeCamp) - Comprehensive course on LangGraph
- [LangGraph Crash Course - YouTube](https://www.youtube.com/watch?v=jGg_1h0qzaM) - Video introduction to LangGraph
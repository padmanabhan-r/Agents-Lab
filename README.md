# Agents-Lab 🤖

[![Python 3.12+](https://img.shields.io/badge/python-3.12%2B-blue.svg)](https://www.python.org/downloads/release/python-3120/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive laboratory for experimenting with multi-agent AI systems, featuring practical implementations using modern frameworks like CrewAI, SmolAgents, LlamaIndex, LangGraph, and Agno. This repository serves as both a learning resource and a foundation for building advanced AI agent applications.

## 🌟 Key Features

- **Multi-agent Orchestration**: Implement complex workflows with CrewAI and SmolAgents
- **Real-world Use Cases**: Customer support, office management, research, data analysis, and more
- **LLM Integration**: Connect with OpenAI, Gemini, Llama, and other leading language models
- **Tool Utilization**: Web search, scraping, visualization, and custom tool creation
- **Observability**: Telemetry and tracing with Phoenix and OpenInference
- **Framework Comparison**: See how different agent frameworks handle similar tasks

## 📂 Project Structure

- **`crewAI/`**: Sophisticated multi-agent systems demonstrating CrewAI capabilities
  - Role-based agent collaboration
  - Task planning and execution
  - Customizable workflows for business scenarios
- **`smolagents/`**: Lightweight, tool-enhanced agents using SmolAgents
  - Code generation and execution
  - Web-enabled agents
  - Integration with Gemini and Vertex AI
- **`llamaindex/`**: Data-driven agents using LlamaIndex
  - RAG (Retrieval-Augmented Generation) implementations
  - Document processing and knowledge retrieval
  - Query engines and structured outputs
- **`langgraph/`**: Flow-based agent systems with LangGraph
  - State management for complex agent interactions
  - Directed graph workflows
  - Conditional decision making
- **`agno/`**: Experiments with the Agno framework
  - Task planning and execution
  - Tool integration patterns
  - Multi-agent coordination
- **`pyproject.toml`**: Project dependencies and metadata

## 🚀 Getting Started

### Prerequisites

- Python 3.12+
- Jupyter or VS Code with Jupyter extension
- API keys for various LLM providers (as needed)

### Installation

```bash
# Clone the repository
git clone https://github.com/padmanabhan-r/Agents-Lab.git
cd Agents-Lab

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -e .
```

### Environment Setup

Create a `.env` file in the project root with your API keys:

```
OPENAI_API_KEY=your-openai-key
GOOGLE_API_KEY=your-google-key
# Add other API keys as needed
```

## 📓 Usage

1. Navigate to any notebook directory (e.g., `crewAI/`, `smolagents/`)
2. Open a notebook with Jupyter or VS Code
3. Read the documentation within each notebook
4. Execute cells to see agents in action
5. Modify parameters and prompts to experiment with different behaviors

### Example Workflows

- **Research Assistant**: Automatically gather, analyze, and summarize information on a topic
- **Customer Support**: Create multi-agent systems that handle user queries and escalate when needed
- **Data Analysis**: Use agents to clean, analyze, and visualize data with minimal human intervention

## 🔧 Dependencies

Key libraries (see `pyproject.toml` for the complete list):

- `crewai`, `crewai-tools`: Multi-agent orchestration
- `smolagents[litellm,telemetry]`: Lightweight agent framework
- `arize-phoenix`, `openinference-instrumentation-*`: Telemetry and tracing
- `plotly`, `geopandas`, `shapely`, `pandas`, `numpy`: Data visualization and analysis
- `google-cloud-aiplatform`, `google-auth`: Google AI integration
- `ipywidgets`, `ipykernel`: Jupyter notebook support

## 👨‍💻 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**Author:** Padmanabhan ([padmanabhan-r](https://github.com/padmanabhan-r))

If you find this repository useful, please consider giving it a star ⭐

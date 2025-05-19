# Agents-Lab

[![Python 3.12+](https://img.shields.io/badge/python-3.12%2B-blue.svg)](https://www.python.org/downloads/release/python-3120/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A collection of advanced multi-agent AI notebooks and experiments using CrewAI and SmolAgents, designed for research, automation, and educational purposes.

---

**Author:** Padmanabhan  ([padmanabhan-r](https://github.com/padmanabhan-r))

---

## Project Structure

- **crewAI/**: Notebooks demonstrating CrewAI for multi-agent workflows (e.g., customer support, office management, research writing).
- **smolagents/**: Notebooks using SmolAgents for code-based, tool-using, and web-enabled agents (e.g., Gemini, Vertex AI, multi-agent orchestration, retrieval).
- **pyproject.toml**: Project dependencies and metadata.

## Key Features

- Multi-agent orchestration with CrewAI and SmolAgents.
- Real-world agent use cases: customer support, office management, research, data retrieval, and more.
- Integration with LLMs (OpenAI, Gemini, Llama, etc.).
- Tool use: web search, web scraping, data visualization, and custom tools.
- Telemetry and tracing with Phoenix and OpenInference.


## Usage

- Open any notebook in `crewAI/` or `smolagents/` with Jupyter or VS Code.
- Follow the instructions in each notebook to run agent workflows.
- Enjoy

## Dependencies

Key libraries (see `pyproject.toml` for full list):

- `crewai`, `crewai-tools`
- `smolagents[litellm,telemetry]`
- `arize-phoenix`, `openinference-instrumentation-*`
- `plotly`, `geopandas`, `shapely`, `pandas`, `numpy`
- `google-cloud-aiplatform`, `google-auth`
- `ipywidgets`, `ipykernel`

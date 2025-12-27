# IntelligentAgentFramework

[![GitHub stars](https://img.shields.io/github/stars/Intelligent-Internet/ii-agent?style=social)](https://github.com/Intelligent-Internet/ii-agent/stargazers)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Blog](https://img.shields.io/badge/Blog-II--Agent-blue)](https://ii.inc/web/blog/post/ii-agent)
[![GAIA Benchmark](https://img.shields.io/badge/GAIA-Benchmark-green)](https://ii-agent-gaia.ii.inc/)

**IntelligentAgentFramework** is an open-source platform designed to streamline and enhance the development of intelligent AI agents. It represents a significant advancement in how we interact with technology—shifting from passive tools to intelligent systems capable of independently executing complex, multi-step tasks.

## Overview

IntelligentAgentFramework is architected around providing a robust agentic interface to state-of-the-art Large Language Models (LLMs), specifically leveraging Anthropic's Claude models. It is built to offer high flexibility and power through multiple interface options:

*   **CLI Interface**: A powerful command-line tool for direct interaction, scripting, and automation.
*   **WebSocket Server**: A real-time backend that powers dynamic, modern frontend applications (React-based).
*   **Cloud Integration**: Seamless integration with Google Cloud's Vertex AI for scalable and reliable API access to LLMs.

## Core Capabilities

IntelligentAgentFramework is a versatile assistant built to elevate productivity across diverse domains:

| Domain | Capabilities |
|--------|----------------------|
| **Research & Fact-Checking** | Multistep web search, source triangulation, structured note-taking, rapid summarization. |
| **Content Generation** | Blog & article drafts, lesson plans, creative writing, technical documentation, and automated website creation. |
| **Data Analysis & Visualization** | Data cleaning, statistical analysis, trend detection, charting, and automated report generation. |
| **Software Development** | Code synthesis, refactoring, debugging, test generation, and step-by-step tutorials across multiple languages. |
| **Workflow Automation** | Script generation, browser automation, file management, and process optimization. |
| **Problem Solving** | Complex problem decomposition, alternative-path exploration, stepwise guidance, and troubleshooting. |

## Architecture & Methods

The framework is built on a sophisticated methodology that ensures reliability and adaptability:

### 1. Core Agent Architecture & LLM Interaction
*   **Dynamic Context Management**: System prompting with tailored context and comprehensive history management to handle token limitations effectively.
*   **Intelligent Invocation**: Systematic LLM calls and capability selection based on the task at hand.
*   **Iterative Refinement**: Continuous improvement through execution cycles and feedback loops.

### 2. Planning & Reflection
*   **Structured Reasoning**: A robust framework for complex problem-solving.
*   **Decomposition**: Breaks down large problems into manageable, sequential steps.
*   **Transparent Decision-Making**: Logs and explains the agent's reasoning process.

### 3. Execution Capabilities
*   **File System Operations**: Intelligent code editing and file manipulation.
*   **Secure Command Execution**: Runs code and commands in a sandboxed environment.
*   **Advanced Web Interaction**: A powerful browser automation suite for navigation, data extraction, and interaction.

## Getting Started

To set up the project locally for development or testing:

1.  **Clone the repository:**
    bash
    git clone https://github.com/Intelligent-Internet/ii-agent.git
    cd ii-agent
    

2.  **Install dependencies:**
    It is recommended to use a virtual environment.
    bash
    pip install -r requirements.txt
    

3.  **Configure API Keys:**
    Set up the necessary environment variables for Google Cloud and Anthropic.
    bash
    export GOOGLE_APPLICATION_CREDENTIALS="/path/to/your/credentials.json"
    export ANTHROPIC_API_KEY="your_anthropic_key"
    

4.  **Run the CLI:**
    bash
    python main.py
    

## Documentation

For detailed usage, API reference, and examples, please consult our [official blog and documentation](https://ii.inc/web/blog/post/ii-agent).

## License

This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.

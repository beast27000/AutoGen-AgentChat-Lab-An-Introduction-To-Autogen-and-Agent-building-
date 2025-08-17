# AutoGen-AgentChat-Lab-An-Introduction-To-Autogen-and-Agent-building-

Exploring Multi-Agent Conversations with Microsoft’s AutoGen Framework

## Overview

The AgentSync Lab is a hands-on demonstration of building and running multi-agent conversational systems using the [AutoGen framework](https://microsoft.github.io/autogen/). This Jupyter notebook-based lab guides you through creating conversational AI agents powered by large language models (LLMs) that engage in structured, autonomous dialogues to simulate real-world problem-solving.

The goal is to illustrate the power of agentic AI beyond simple LLM queries, showcasing how agents can collaborate, reason, and iterate through multi-step conversations with minimal human intervention.

## Key Features

- **Multi-Agent Conversations**: Simulates structured, back-and-forth dialogues between AI agents.
- **Customizable Agent Roles**: Configure each agent with unique roles, goals, and constraints.
- **Autonomous Dialogue Loops**: Agents take turns responding, enabling emergent and coherent conversations.
- **Minimal Human Intervention**: Once initialized, agents run autonomously until a termination condition is met.
- **Educational Focus**: Designed as an interactive lab to learn AutoGen fundamentals and agentic AI concepts.

## Installation

Ensure you have Python >=3.10 and <3.13 installed on your system.

Install the required dependencies:

```bash
pip install pyautogen jupyter
```

For streamlined environment management, you can optionally use [uv](https://github.com/astral-sh/uv):

```bash
pip install uv
uv pip install pyautogen jupyter
```

## Usage

1. Launch Jupyter Notebook:

```bash
jupyter notebook 1_lab1_agentsync_conversation.ipynb
```

2. Follow the notebook cells in order:

   - **Setup**: Import libraries and configure logging.
   - **Agent Definition**: Define multiple conversational agents with distinct roles (e.g., "Professor" vs. "Student").
   - **Conversation Execution**: Run a multi-turn chat between agents.
   - **Analysis**: Review conversation transcripts, agent behaviors, and outputs.

3. Experiment by customizing:

   - Agent roles and goals (e.g., "Analyst" vs. "Critic").
   - Conversation rules (e.g., stop conditions, maximum turns).
   - Underlying LLM configurations (e.g., model selection, temperature).

## Example Outcome

By completing this lab, you’ll create a working demo of two or more AI agents engaging in autonomous conversations. The output will be a detailed transcript showcasing:

- Iterative dialogue loops with coherent exchanges.
- Collaborative problem-solving without continuous human prompting.
- A practical example of agentic AI in action.

This demonstrates that AutoGen-powered agents can autonomously manage multi-turn conversations, laying the groundwork for more complex collaborative AI systems.

## Project Vision

The AgentSync Lab serves as a foundation for building advanced multi-agent ecosystems. Future iterations could enable agents to:

- Debate complex solutions.
- Brainstorm creative ideas.
- Chain conversations into sophisticated workflows.

This lab is a stepping stone toward engineering teams of AI agents that replicate human-style collaboration, paving the way for autonomous systems that tackle real-world challenges.

## Project Structure

```
├── 1_lab1_agentsync_conversation.ipynb  # Main Jupyter notebook for the lab
├── .env                                 # Environment variables (e.g., API keys)
├── README.md                            # Project documentation
└── requirements.txt                      # Dependency list (optional, for uv)
```

## Configuration

- Add your LLM API key (e.g., `OPENAI_API_KEY`) to a `.env` file in the project root.
- Modify agent roles, goals, and conversation rules directly in the notebook cells to experiment with different setups.

## Support

- Explore the [AutoGen Documentation](https://microsoft.github.io/autogen/docs/).
- Join [GitHub Discussions](https://github.com/microsoft/autogen/discussions) for community support.
- Contribute examples, experiments, or feedback to the AutoGen open-source community.

Start building the future of collaborative AI with AgentSync Lab!

Made by Vishvvesh Nagappan

# Generative-AI-tool-Runnables-agents-etc-along-with-Weather-News-project-


# Generative AI Agent System


This repository contains the project code for building a complete AI Agent system from scratch, as covered in the Generative AI.
This project demonstrates how to create intelligent systems that can think, make decisions, and interact with the real world using LangChain and various APIs.


# Project Overview


This AI agent is designed to take user queries, decide whether to utilize specific tools to fetch real-time data, process that information, and generate an intelligent final response. Key features include:


Tool Calling & Integration: Implementing both built-in tools (e.g., Tavily Search) and custom tools (e.g., OpenWeather API).

Agentic Workflow: Establishing an agent loop (LLM → Tool → Result → LLM) for automated decision-making.

Modern LangChain Practices: Utilization of create_agent and advanced abstractions for more efficient control.

Human-in-the-Loop: Adding safety and control mechanisms for tool execution.

# Tech Stack


Language: Python
Framework: LangChain
LLMs: OpenRoute / Groq AI
Tools/APIs: Tavily API (Search), OpenWeather API


# Key Concepts Covered


Runnables & Sequences: Managing data flow through the AI pipeline.

Tool Creation: Defining custom Python functions with specific docstrings to act as tools .

Tool Binding: Informing the LLM about available tools (1:50:37).

Execution Loops: Manually handling tool calls and integrating results back into the LLM history (2:07:39).

Advanced Agent Abstractions: Using modern LangChain features for complex assistant behavior (3:27:16).

# Getting Started

Clone this repository to your local machine.
Install the necessary dependencies listed in requirements.txt (including langchain, langchain-community, and relevant provider SDKs).

Set up your environment variables (e.g., API keys for OpenAI/Mistral/OpenRoute/OpenRoute, Tavily, and OpenWeather) in a .env file.

Run the provided scripts to observe the AI agent's decision-making process in your terminal.


---
marp: true
theme: default
paginate: true
backgroundColor: #cac
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---


# Agent2Agent and Model Context Protocol

We are going to discuss the two protocols:
* MCP
* A2A

---

## MCP
The task of implementing context engineering via tools and datasets in agentic systems has always been a huge understanding to impelement and maintain before MCP. This is particulary challenging in scenarios where the same set of tools and datasets (resources) are leveraged across multiple apps and even across separate distinct programming languages. Having to copy-and-paste the same integration of these tools and resources can lead to regression issues that brings its own set of challenges.

The [MCP specification](https://modelcontextprotocol.io/specification/2025-06-18) is an internet standard that was designed to provide a standard for how AI agents can bring the LLMs powering these system with the ability to dynamically discover tools, resources and prompts that can be used to perform actions, manage memory, perform CRUD operations on datasets. The protocol simplifies how agents connect to tools, APIs, and resources with structured inputs/outputs.

---

## Key Features of MCP
* dynamic discovery of tools
* dynamic discovery of resources
* structured input
* structured output
* context engineering 
* standard protocol

---

## A2A
When designing effective AI agents, it is important to **allow 7 agents to do one thing right vs forcing 1 agent to do 7 things** correctly. 
This distribution of tasks and responsibilities allows our agents to be focused and **eliminates or significantly reduces the proability for hallucination** in results returned by the LLMs powering the agents.


The [Agent2Agent protocol](https://a2a-protocol.org/latest/) was designed to standardize how agents to reach out to other agents to collaborate effectively and efficient to solve a task. It facilitates dynamic, multimodal communication between different agents as peers. It's how agents collaborate, delegate, and manage shared tasks.

---

## Key Features of A2A

* Distribution of sub-tasks across agents
* Focus and reduction of distractions/hallucinations
* Dynamic capability discovery from other agents
* Multi-agent collaboration
* Standard protocol
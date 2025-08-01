# Building A2A and MCP Powered Agents in Production
This repository contains an outline for a talk on designing and building effective agents powered by MCP and A2A on Azure leveraging the fundamental pillars of effective agent design and implementation in production.

## Background
AI agents are gradually becoming the preferred and desired user experience for interacting with applications today. There are currently two internet standards today that are driving the design and implementations of agentic systems (MCP and A2A). This presentation focuses on the pillars of designing, building, deploying and maintaining secure, scalable, reliable and effective agents in production on Microsoft Azure.

We cover the 9 principles and pillars that drive effective agent architectures as well as the 3 core ingredients that enable you to design intelligent systems using the two internet standards (A2A and MCP)

## 9 Key Pillars for Effective Agents
These pillars are fundamental to the design of effective AI agents in production:
- User-Centric Design
- Security
- Data Quality
- Scalable Data Pipelines
- Tool-Calling Architecture
- Multi-Agent Collaboration
- LLM Selection
- Memory Design & Management
- Reflection & Validation

## 2 Foundational Protocols and Support These Pillars
In this segment, we introduce the audience to the two protocols, why they matter and how they are leveraged by AI agents to solve problems.

- MCP: providing AI agents with access to tools, resources and capabilities
- A2A: providing distributed agents with the ability to collaborate to accomplish specific goals.


## The 3 Most Important Ingredients that Power A2A and MCP on Azure
Here we cover various categories of data stores, infrastructure and services that are necessary for building these agentic systems with A2A and MCP.
- Data stores
- Infrastructure
- AI Services

#### Data stores Needed for MCP and A2A
AI agents leveraging MCP and A2A need a variety of data stores such as key-value stores, document stores, vector databases, graph databases, relational databases, queueing systems, messaging systems, object stores and wide-column stores to handle different design needs of the architecture. In this segment, we will cover how A2A and MCP leverages these categories of data stores on Azure with specific examples for different needs and scenarios.

#### Infrastructure Needed for MCP and A2A
Why do we need a proxy such as APIM to manage authentication, routing, load distribution, throthling and authorization? Why do we pick Azure Functions or Kubernetes and vice-versa? When do we use Search Indexers, Azure Stream Analytics, Azure Databricks or Apache Flink to handle the data pipe and data quality concerns? 

#### AI Services Needed for MCP and A2A
Why do we choose certain services such as Azure Document Intelligence, Azure Speech Service, Azure Content Understanding? Why would you choose certain language models over others from the AI Foundry catalog? What AI services do you need to create the right user experience based on your workflow and architecture needs?

## Summary and Reflection
These 2 protocols (A2A and MCP) are very important for effective multi-agent collaboration and empowerment. These 3 key ingredients enable architects and engineers to design, implement, deploy and maintain scalable, secure intelligent systems in production that leverages the MCP and A2A protocol to bring these solutions to live based on the 9 key principles and pillars that govern such design.


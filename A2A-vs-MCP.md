### Agent2Agent and Model Context Protocol

#### A2A
When designing effective AI agents, it is important to allow 7 agents to do one thing right vs forcing 1 agent to do 7 things correctly. 
This distribution of tasks and responsibilities allows our agents to be focused and eliminates or significantly reduces the proability for hallucination in results returned by the LLMs powering the agents.
The [Agent2Agent protocol](https://a2a-protocol.org/latest/) was designed to standardize how agents to reach out to other agents to collaborate effectively and efficient to solve a task.


#### MCP
The [MCP specification](https://modelcontextprotocol.io/specification/2025-06-18) is an internet standard that was designed to provide a standard for how AI agents can bring the LLMs powering these system with the ability to 
dynamically discover tools, resources and prompts that can be used to perform actions, manage memory, perform CRUD operations on datasets.

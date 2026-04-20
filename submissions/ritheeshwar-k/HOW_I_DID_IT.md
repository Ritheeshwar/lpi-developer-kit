\# How I Did It



I built an intelligent agent using the LPI developer kit that dynamically selects tools based on query intent.



The agent uses rule-based logic to map queries to relevant tools such as:

\- get\_methodology\_step

\- get\_case\_studies

\- get\_insights



It executes these tools using Node.js child\_process and aggregates the results into structured JSON output.



I tested the agent locally using the test-client and verified tool execution before integrating everything into a single workflow.


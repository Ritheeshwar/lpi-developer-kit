\# Level 3 Submission – Ritheeshwar K



\## What I Built

Built an intelligent agent that dynamically selects LPI tools based on user query intent. The agent analyzes the query, selects relevant tools, executes them, and returns structured outputs.



\## Agent Repository

https://github.com/Ritheeshwar/lpi-smart-agent



\## Tools Used

get\_methodology\_step  

get\_case\_studies  

get\_insights  



\## How to Run

1\. Install dependencies:

npm install



2\. Build project:

npm run build



3\. Run the agent:

node level3/agent.js "How to implement digital twin?"



\## Example Output

{

&#x20; "query": "How to implement digital twin?",

&#x20; "tools\_used": \[

&#x20;   "get\_methodology\_step",

&#x20;   "get\_case\_studies",

&#x20;   "get\_insights"

&#x20; ]

}



\## Error Handling

\- Handles empty or invalid queries  

\- Catches tool execution errors  

\- Ensures stable structured output  



\## Notes

This implementation demonstrates rule-based tool selection and multi-tool orchestration using the LPI developer kit.
Updated for leaderboard visibility


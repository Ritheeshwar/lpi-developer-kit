Here is the link to my Level 3 AI Agent repository:
https://github.com/jv-singh/smile-ai-agent

### My AI Agent Implementation
I built a custom AI agent using Python that interfaces directly with the LPI MCP server. It queries `smile_overview`, `query_knowledge`, and `get_case_studies`.

### Evidence of Execution and Explainability
Below is the exact output from my agent running locally, proving that it calls the tools and cites its sources:

```text
[1/3] Querying SMILE overview...
[2/3] Searching knowledge base...
[3/3] Checking case studies...

Sending to LLM (Ollama)...

============================================================
 ANSWER
============================================================
SMILE methodology prioritizes impact over data in its digital twin implementation process. It involves creating a shared reality canvas for establishing where and when, defining the scope (as is to to be), validating hypotheses virtually, connecting physical sensors, sharing ontologies, and leveraging knowledge across time periods.

============================================================
 PROVENANCE (tools used)
============================================================
 [1] smile_overview (no args)
 [2] query_knowledge ("query": "What is SMILE methodology?")
 [3] get_case_studies (no args)
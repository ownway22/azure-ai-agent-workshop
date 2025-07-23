# Azure AI Agent Workshop

2025 TrendMicro AI Hackathon x Microsoft Azure AI Agent Workshop

## Clone the repository
```bash
git clone https://github.com/LittleFish-Coder/azure-ai-agent-workshop.git
```

## 1. Prerequisite

Please refer to [Prerequisite.md](Prerequisite.md) for detailed instructions.

In the prerequisite step, you'll complete:
1. Set up your **Python 3.11+ environment** (install Python, create & activate a virtual environment, update pip, install dependencies).
2. Install and configure the **Azure CLI** (install, check version, login, select subscription).



## 2. Setup Azure Service Environment
Modify `.env` file with your Azure resource information.

```bash
# Azure AI Foundry Agent Service
AZURE_AI_AGENT_ENDPOINT = "xxx"
AZURE_AI_AGENT_API_KEY = "xxx"
AZURE_AI_AGENT_MODEL_DEPLOYMENT_NAME = "gpt-4o"

# Azure AI Search Service
AZURE_SEARCH_ENDPOINT = "xxx"
AZURE_SEARCH_API_KEY = "xxx"

# Azure OpenAI Service
AZURE_OPENAI_ENDPOINT = "xxx"
AZURE_OPENAI_API_KEY = "xxx"
AZURE_OPENAI_API_VERSION = "xxx"
AZURE_OPENAI_CHAT_DEPLOYMENT_NAME = "gpt-4o"
```


## 3. Run the Lab

We will go through the following labs:
- Single Agent: `s1_single_agent/`
- Ai Search: `s2_ai_search/`
- Multi-Agent: `s3_multi_agent/`

run the lab with the following command:
```bash
python s1_single_agent/lab_name.py
```







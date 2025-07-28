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
AZURE_AI_AGENT_ENDPOINT="https://<example-project-name>.services.ai.azure.com/api/projects/<example-project-name>"
AZURE_AI_AGENT_MODEL_DEPLOYMENT_NAME="gpt-4o"

# Azure Bing Search Service
AZURE_BING_CONNECTION_ID=""

# Azure AI Search Service
AZURE_SEARCH_ENDPOINT="https://<example-search-name>.search.windows.net"
AZURE_SEARCH_API_KEY=""

# Azure OpenAI Service
AZURE_OPENAI_ENDPOINT="https://<example-project-name>.openai.azure.com/openai/deployments/<example-model-deployment-name>/chat/completions?api-version=<example-api-version>"
AZURE_OPENAI_API_KEY="<example-api-key>"
AZURE_OPENAI_API_VERSION="<example-api-version>"
AZURE_OPENAI_CHAT_DEPLOYMENT_NAME="gpt-4o"
AZURE_OPENAI_GPT_MODEL="gpt-4o"         # for s2_ai_search
AZURE_OPENAI_GPT_DEPLOYMENT="gpt-4o"    # for s2_ai_search

# AZURE OpenAI Embedding Model Service
AZURE_OPENAI_EMBEDDING_MODEL="text-embedding-3-large"       # for s2_ai_search
AZURE_OPENAI_EMBEDDING_DEPLOYMENT="text-embedding-3-large"  # for s2_ai_search
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







## 📋 Hackathon 先備條件 Checklist

### 一、網路與硬體

1. **本機開發優先**
   儘量在你的筆電本機執行開發任務，避免透過遠端 VM（如 Azure VM、 SSH）進行，以降低因網路延遲、不穩定或 VM 身分認證等造成的開發阻礙。

2. **穩定網路**
   準備有線網路或高品質 Wi-Fi，確保比賽期間網路不中斷。

3. **電源與周邊**
   務必攜帶筆電充電器、延長線、滑鼠、耳機等必要設備，確保有充足電力與舒適的工作環境。

---

### 二、Azure 帳號

4. **Azure 訂閱**
   請確認隊伍每位成員都擁有可用的 Azure 訂閱，並可成功登入 [portal.azure.com](https://portal.azure.com)。

5. **Azure 權限**
   確認在指定資源群組中擁有 Owner 權限，便於建立、刪除與修改資源。

---

### 三、開發工具安裝

6. **安裝 Azure CLI**
   下載並安裝最新版 [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest&pivots=msi)，並執行 `az login` 測試。

7. **安裝 Python 3.11+**
   執行 `python --version` 確認安裝的是 3.11 以上版本。

8. **使用 VS Code（可選）**
   建議初學者使用 VS Code 來撰寫與除錯程式碼，熟悉的開發者可使用任意 IDE。

---

### 四、程式碼與相依套件 (可選，已預約種子成員做實際測試)

9. **下載並預覽 Repo**
   提前 clone 專案程式碼並閱讀 README、.env 等重要說明。

10. **測試安裝套件**
    在專案目錄中執行 `pip install -r requirements.txt` 安裝套件並排除錯誤。

11. **測試執行範例程式**
    嘗試執行任一 `.py` 檔案，確保 Azure CLI、Python SDK 與憑證正常運作。

---

### 五、核心技術與知識（建議預習）

12. **RAG（Retrieval-Augmented Generation）**
    理解 Chunking、Embedding、Indexing、Query Retrieval 等流程。

13. **MCP（Model Context Protocol）**
    瞭解 MCP 溝通協議的基本流程。

14. **Prompt Engineering**
    熟悉 Role-play、Chain-of-Thought、Few-shot 等技巧。

15. **雲端基本服務** (包括但不限於下列)

    * Resource Group：Azure [資源的邏輯階層](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/landing-zone/design-area/resource-org)
    * IAM：存取權限管理與角色設定
    * Managed Identity：服務間安全驗證方式

---

## 📄 Hackathon Prerequisites

### 1. Network & Hardware

1. **Local-first development**
   Try to develop directly on your laptop instead of remote VMs (e.g., Azure VM/SSH) to avoid latency or connectivity issues.

2. **Stable network**
   Prepare a wired or high-quality Wi-Fi connection to ensure a smooth experience.

3. **Power and peripherals**
   Bring chargers, extension cords, mouse, headset, and other necessary devices to stay productive.

---

### 2. Azure Account

4. **Azure subscription**
   Each team member should have a valid Azure subscription and access to [portal.azure.com](https://portal.azure.com).

5. **Azure permissions**
   Ensure you have `Owner` access to the specified resource group to create, delete, or modify Azure resources.

---

### 3. Development Tools

6. **Install Azure CLI**
   Install the latest [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?view=azure-cli-latest&pivots=msi) and confirm login via `az login`.

7. **Install Python 3.11+**
   Run `python --version` and confirm the Python version is 3.11 or above.

8. **Use VS Code (Optional)**
   Beginners are encouraged to use VS Code; experienced users can use their preferred IDE.

---

### 4. Code & Dependencies (Optional)

9. **Clone & review the repo**
   Clone the competition repository, review the README and check environment variable setup.

10. **Install dependencies**
    Run `pip install -r requirements.txt` inside the project folder to pre-check for errors.

11. **Run sample code**
    Test any `.py` example to ensure CLI, SDKs, and credentials are properly configured.

---

### 5. Core Concepts (Recommended)

12. **RAG (Retrieval-Augmented Generation)**
    Understand chunking, embedding, indexing, and querying processes.

13. **MCP (Model Context Protocol)**
    Learn the basics of MCP communication and execution flow.

14. **Prompt Engineering**
    Learn tips like role-play, chain-of-thought, few-shot learning for effective prompting.

15. **Cloud Service Concepts (Including but not limited to the following)**

    * **Resource Group**: [Resource organization for Azure resources](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/landing-zone/design-area/resource-org)
    * **IAM**: Identity & access management
    * **Managed Identity**: Secure service-to-service authentication without hardcoding credentials

# Semantic Kernel Python Agents Workshop

## 🎯 Workshop 簡介

歡迎參加 **Semantic Kernel Python Agents Workshop**！本次 Workshop 將帶您深入了解如何使用 Semantic Kernel 建立智能代理系統，涵蓋三大核心領域：

### 🚀 Workshop 內容概覽與學習路徑

| 順序    | 實驗室                       | 主題             | 核心技術               | 適用場景                 | 參考文件路徑                                                                                                      |
| ------- | ---------------------------- | ---------------- | ---------------------- | ------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| **0**   | **環境設定**                 | 基礎設定         | Python 環境、套件安裝  | 所有 SK Agent 開發       | [`workshop.md`](./workshop.md)                                                                   |
| **1**   | **Azure AI Agent Lab**       | 雲端託管代理服務 | Azure AI Agent Service | 企業級應用、工具整合     | [`1_azure_ai_agent_lab/azure_ai_agent.md`](./1_azure_ai_agent_lab/azure_ai_agent.md)                                 |
| **1.1** | **Azure AI Agent 實作任務**  | 實務應用         | 多功能學習助理         | 技術文件搜索、程式碼執行 | [`1-1_azure_ai_agent_lab_task/azure_ai_agent_lab_task.md`](./1-1_azure_ai_agent_lab_task/azure_ai_agent_lab_task.md)     |
| **2**   | **Multi-Agent Lab**          | 多代理協作系統   | 協調與編排             | 複雜任務、團隊協作       | [`2_multi_agent_orchestration_lab/multi.md`](./2_multi_agent_orchestration_lab/multi.md)                             |
| **2.1** | **Magentic 協調進階**        | 智能協調         | AI 指揮官架構          | 複雜問題分解與解決       | [`2_multi_agent_orchestration_lab/magentic.md`](./2_multi_agent_orchestration_lab/magentic.md)                       |
| **2.2** | **Sequential 協調詳解**      | 順序處理         | 取消機制、串流回調     | 流水線處理流程           | [`2_multi_agent_orchestration_lab/step2.md`](./2_multi_agent_orchestration_lab/step2.md)                             |
| **2.3** | **Connected Multi-Agent**    | Azure UI 多代理協作 | Azure AI Foundry 連接代理 | 專業團隊協作、任務分流  | [`2-1_multi_agent_orchestration_lab_ui/connected_multi_agent.md`](./2-1_multi_agent_orchestration_lab_ui/connected_multi_agent.md) |
| **3**   | **Chat Completion Lab**      | 本地代理開發     | Semantic Kernel Core   | 快速原型、本地部署       | [`3_chat_completion_lab/chat_completion.md`](./3_chat_completion_lab/chat_completion.md)                             |
| **3.1** | **Chat Completion 實作任務** | 技術問題解決中心 | 多代理群組聊天         | 技術支援、問題診斷       | [`3-1_chat_completion_lab_task/chat_completion_lab_task.md`](./3-1_chat_completion_lab_task/chat_completion_lab_task.md) |

### 🎓 學習目標與進階路徑

#### 基礎目標
- 掌握 Semantic Kernel Python 代理開發基礎
- 了解 Azure AI Agent 與 Chat Completion Agent 的差異
- 學會多代理協作模式的設計與實作
- 建立完整的 AI 代理應用系統

#### 進階路徑
1. **入門階段**: 完成環境設定，運行測試腳本
2. **基礎階段**: 實作單一代理 (Azure AI Agent 或 Chat Completion)
3. **進階階段**: 學習多代理協作模式
4. **專家階段**: 完成各實驗室實作任務
5. **整合應用**: 將所學技術應用於自訂專案

---

## 🧪 環境測試腳本

### 環境測試總覽
我們提供三個測試腳本來驗證不同實驗室的環境設定：

| 測試腳本                  | 測試內容                 | 對應實驗室          |
| ------------------------- | ------------------------ | ------------------- |
| `test_azure_ai_agent.py`  | Azure AI Agent 服務連線  | Azure AI Agent Lab  |
| `test_chat_completion.py` | Chat Completion 服務連線 | Chat Completion Lab |
| `test_multi_agent.py`     | 多代理協調功能           | Multi-Agent Lab     |

### 執行環境測試
```bash
$ az login
$ python test_azure_ai_agent.py
$ python test_chat_completion.py  
$ python test_multi_agent.py
如果一切順利, 可以看到環境測試完成的輸出
```

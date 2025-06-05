# 🤖 First AI Agent – Personal Assistant using n8n

This repository contains a basic AI-powered assistant agent built using [n8n](https://n8n.io). The agent listens to chat messages, processes them using OpenAI's Chat Model, and enhances its responses with memory and tools like SerpAPI and Calculator.

![Workflow Screenshot](![image](https://github.com/user-attachments/assets/6df14a34-c043-45dd-b7cf-5538a210b7e0)
)

---

## 🚀 Features

- ✅ Chat-based trigger input  
- ✅ Integrated with **OpenAI Chat Model**  
- ✅ Supports **Simple Memory** to maintain context  
- ✅ Uses **SerpAPI** for web search capabilities  
- ✅ Includes **Calculator** for math-related queries  
- ✅ Outputs direct responses to user input in chat

---

## 🛠️ Stack Used

| Component | Role |
|----------|------|
| **n8n** | Workflow automation platform |
| **OpenAI** | For generating chat-based intelligent responses |
| **Simple Memory** | To remember recent inputs in conversation |
| **SerpAPI** | For real-time search queries |
| **Calculator** | For arithmetic and logic operations |

---

## 🧩 Workflow Structure

1. **Trigger**: `When chat message received`
2. **AI Agent**: Connected to:
   - `OpenAI Chat Model` (Chat model)
   - `Simple Memory` (Memory)
   - `SerpAPI` (Tool)
   - `Calculator` (Tool)
3. **Response Output**: Returned directly in the same chat interface

---

## 📦 Setup & Usage

### 1. Export or Clone This Repo
Clone this repository or download the `assistant-agent.json` if exported.

```bash
git clone https://github.com/YOUR_USERNAME/n8n-personal-ai-agent.git

2. Import into n8n
Open your n8n cloud or self-hosted instance.

Click Import and select your .json workflow file if applicable.

Ensure credentials (OpenAI, SerpAPI) are added in n8n's credentials section.

3. Test the Agent
Open the Chat input box

Send a question like:

What's the capital of Canada?
or
Solve 18 * 9

Observe the response flow using OpenAI and tools.

📷 Preview

📜 License
MIT License

✨ Author
Manasa Vamsi

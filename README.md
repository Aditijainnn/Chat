# Asha AI Chatbot

**Asha AI Chatbot** is an AI-powered financial and business mentor designed to support rural Indian women in achieving financial independence and digital empowerment. It offers personalized assistance on entrepreneurship, government schemes, and financial literacy using culturally sensitive, easy-to-understand language.

---

## 🎯 Mission & Vision

**Mission**: To empower rural Indian women with accessible, AI-driven mentorship in business, finance, and digital tools—helping them become confident entrepreneurs and leaders in their communities.

**Vision**: To bridge the digital and financial literacy gap in rural India by creating an inclusive AI platform that transforms local women into economically independent changemakers.

---

## 🚀 Features

- **🧠 Conversational AI**: Built using LangChain and Google Generative AI for context-aware, intelligent chat.
- **📄 Document Retrieval**: Supports PDF, JSON, and TXT file ingestion to fetch accurate, relevant information.
- **📚 Vector Database**: Uses Chroma and Hugging Face embeddings for fast, semantic search.
- **📝 Custom Prompts**: Ensures responses are simple, structured, and culturally appropriate.
- **⚙️ FastAPI Integration**: RESTful API support for frontend/backend interaction.

---

## 🧩 Tech Stack

-  **Retrieval-augmented generation (RAG)**
- **Google Generative AI (Gemini)**
- **Hugging Face Transformers**
- **Chroma Vector Database**
- **FastAPI**
- **PyPDFLoader**

---

## 🏗️ Installation

```bash
git clone https://github.com/your-repo/Chat.git
cd 
pip install -r requirements.txt
🌐 Set Environment Variables
HUGGINGFACE_HUB_API_TOKEN: Your Hugging Face API token.

GEMINI_API_KEY: Your Google Generative AI API key.

▶️ Run the Application
bash
Copy
Edit
uvicorn main:app --reload
🔌 API Endpoints
POST /
Request Body:

json
Copy
Edit
{
  "query": "Your question here",
  "chat_history": [
    {"role": "user", "content": "Previous user message"},
    {"role": "assistant", "content": "Previous assistant response"}
  ]
}
Response:

json
Copy
Edit
{
  "response": "AI-generated response"
}
📄 Document Loading
Supports:

PDFs via PyPDFLoader

JSON via LangChain Document parser

.txt Files for additional context

🧠 Vector Embeddings
Model: sentence-transformers/all-MiniLM-L6-v2

Powered by Hugging Face

Stored and queried through Chroma DB

```


## 🔧 MVP (Minimum Viable Product)

The MVP of InspireHer Chatbot includes:

- **Conversational chatbot** interface powered by LangChain and Google Generative AI.
- **Query support** for common topics such as:
  - Government schemes
  - Basic financial literacy
  - Starting a small business
- **Local language support** (text-based in Hindi and English).
- **Document ingestion** (PDFs, JSON, text) with relevant retrieval using vector embeddings.
- **Simple UI or API endpoint** accessible via phone, kiosk, or NGO partner apps.
- **Offline mode planning** for remote deployment.

  
## 💼 Business Model
#### Target Users:
Rural Indian women (aspiring and current entrepreneurs)

NGOs and SHGs (Self Help Groups)

Local training institutes & cooperatives

#### B2B Opportunities:
Partner with rural banks, microfinance firms, NGOs, and government e-marketplaces.

Provide a white-labeled version of the chatbot to training organizations.

#### Value Proposition
Provides instant, free, and localized guidance on business registration, loans, subsidies, and digital finance tools.

Makes complex information accessible through simple conversations in local languages.

Helps women take the first step toward entrepreneurship or financial independence.

#### Service Tiers
Free Tier: Access to basic chatbot features including:

FAQs on business setup

Government schemes information

Basic financial education



## 📍 Example Use Case
#### User Query: "What are the government schemes for women entrepreneurs?"

#### Response:

Lists available schemes (e.g., Stand Up India, MUDRA Yojana).

Eligibility criteria, documents needed, how to apply.

Links or contacts to nearby Common Service Centers (CSCs).


### 📬 Contact
For questions or support, please contact [aditijain132005@example.com].




# **AI-Powered News Aggregator**

**An intelligent news aggregation platform that collects articles from multiple sources, leverages AI to generate concise summaries, and delivers organized, real-time news through a modern, responsive web interface.**

---

## **Overview**

With the overwhelming volume of news published every day, staying informed can be challenging. This project addresses that problem by automatically aggregating news from multiple sources, processing the content using AI, and presenting users with concise, easy-to-read summaries.

Built with a modern full-stack architecture, the application combines **React**, **FastAPI**, **PostgreSQL (Supabase)**, and **OpenAI-powered language models** to create an intelligent news platform capable of real-time updates, smart content organization, and scalable deployment.

---

## **Goals**

- Aggregate news articles from multiple trusted sources.
- Generate AI-powered summaries for quick and efficient reading.
- Organize and filter news intelligently based on relevance.
- Deliver real-time news updates through a responsive web application.
- Provide a scalable, production-ready architecture for deployment.

---

## **Architecture**

### **Application Workflow**

```
News Sources
      │
      ▼
 News Collection Service
      │
      ▼
 FastAPI Backend
      │
      ▼
 AI Processing
(OpenAI + LangChain + LangGraph)
      │
      ▼
 PostgreSQL (Supabase)
      │
      ▼
 React + Vite Frontend
      │
      ▼
 End Users
```

---

## **Project Structure**

The repository is organized into multiple branches, each representing a different stage of development.

| **Branch** | **Purpose** |
|------------|-------------|
| **master** | Core application with local development setup. |
| **deployment** | Deployment configuration and infrastructure setup. |
| **deployment-final** | Production-ready implementation with deployment optimizations. |

---

## **Features**

- 📰 AI-powered news aggregation from multiple sources.
- 🤖 Automatic AI-generated news summaries.
- ⚡ Real-time news collection and updates.
- 🔍 Intelligent news filtering and organization.
- 📱 Fully responsive user interface.
- 🚀 Production-ready architecture with Docker support.
- 🗄️ Persistent data storage using PostgreSQL (Supabase).
- 🔄 Modular backend architecture for future AI enhancements.

---

## **How It Works**

### **1. News Collection**

The backend continuously retrieves news articles from multiple sources and prepares them for processing.

### **2. AI Processing**

Using **OpenAI**, **LangChain**, and **LangGraph**, each article is analyzed to generate concise summaries and structured information for easier consumption.

### **3. Data Storage**

Processed articles and AI-generated summaries are stored in **PostgreSQL (Supabase)**, enabling efficient querying and persistent storage.

### **4. User Interface**

The React frontend fetches processed news from the FastAPI backend and displays it through a clean, responsive interface with real-time updates.

---

## **Tech Stack**

### **Frontend**

- **React**
- **Vite**
- **TypeScript**
- **Tailwind CSS**
- **ShadCN UI**

### **Backend**

- **Python**
- **FastAPI**

### **Database**

- **PostgreSQL (Supabase)**

### **AI & Automation**

- **OpenAI API**
- **LangChain**
- **LangGraph**

### **Deployment**

- **Docker**
- **Docker Compose**

---

## **Getting Started**

### **1. Clone the Repository**

```bash
git clone <repository-url>
```

### **2. Navigate to the Project Directory**

```bash
cd ai-news-aggregator
```

### **3. Install Dependencies**

Install both frontend and backend dependencies.

### **4. Configure Environment Variables**

Add the required API keys and database credentials in your environment configuration.

### **5. Run the Application**

Start the backend and frontend development servers (or use Docker Compose for a containerized setup).

---

## **Project Structure**

```text
.
├── frontend/
├── backend/
├── docker/
├── deployment/
├── deployment-final/
├── docker-compose.yml
├── README.md
└── ...
```

---

## **Key Technologies**

| **Technology** | **Purpose** |
|---------------|-------------|
| **React** | Frontend development |
| **Vite** | Fast build tool |
| **FastAPI** | Backend REST API |
| **PostgreSQL (Supabase)** | Database |
| **OpenAI API** | AI-powered summarization |
| **LangChain** | LLM orchestration |
| **LangGraph** | AI workflow management |
| **Docker** | Containerization |
| **Docker Compose** | Multi-container deployment |

---

## **Future Enhancements**

- Personalized news recommendations using AI.
- Category-based news feeds.
- User authentication and saved articles.
- Multi-language news summarization.
- Sentiment analysis and topic classification.
- Push notifications for breaking news.
- Advanced semantic search using vector embeddings.

---

## **License**

This project is intended for **educational, research, and development purposes**.

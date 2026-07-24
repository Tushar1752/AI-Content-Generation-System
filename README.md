🤖 AI-Content-Generation-System

A multi-agent AI content generation system built with LangGraph, LangChain, and Groq LLM. The project demonstrates how multiple AI agents collaborate to research, write, review, and refine marketing content using modern workflow orchestration.

⸻

✨ Features

* 🔍 Research Agent
* ✍️ Writer Agent
* 📝 Editor Agent
* 👨‍💼 Supervisor-based Workflow
* ⚡ Parallel Review Panel
* 🧠 Memory using LangGraph Checkpointer
* 📊 Execution Trail (workflow logs)
* 🔄 Reusable AI Crew Architecture

⸻

🛠️ Tech Stack

* Python
* LangGraph
* LangChain
* Groq LLM
* Streamlit
* python-dotenv

⸻

📂 Project Structure

.
├── step1_writer.py
├── step2_sequential.py
├── step3_editor.py
├── step4_supervisor.py
├── step5_parallel_review.py
├── step6_content_crew.py
├── app.py
├── requirements.txt
└── README.md

⸻

🚀 Workflow

START
   │
Researcher
   │
Writer
   ├──────────────┬──────────────┐
   │              │              │
Fact Checker   SEO Expert   Tone Expert
   └──────────────┴──────────────┘
                 │
              Editor
                 │
                END

⸻

📚 Concepts Demonstrated

* LangGraph StateGraph
* Multi-Agent Systems
* Sequential Workflow
* Supervisor Pattern
* Conditional Routing
* Parallel Execution (Fan-Out / Fan-In)
* Reducers
* Memory with Checkpointer
* AI Content Generation
* Workflow Orchestration

⸻

⚙️ Installation

Clone the repository:

git clone https://github.com/Tushar1752/AI-Content-Generation-System.git
cd LangGraph-Content-Crew

Install dependencies:

pip install -r requirements.txt

Create a .env file:

GROQ_API_KEY=your_groq_api_key

⸻

▶️ Run

Run the final workflow:

python step6_content_crew.py

Or, if your project includes a Streamlit interface:

streamlit run app.py

⸻

📌 Future Improvements

* Human approval workflow
* Web search integration
* Image generation agent
* Blog/article generation
* Multi-language support
* Export to PDF/DOCX

⸻

👨‍💻 Author

Tushar Verma

B.Tech CSE (Artificial Intelligence)
Babu Banarasi Das University, Lucknow

⸻

📄 License

This project is intended for learning and portfolio purposes.

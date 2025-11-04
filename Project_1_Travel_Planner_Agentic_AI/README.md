# 🧭 Travel Planner Agentic AI  
### *by Fictional Travel Co.*

---

## **Objective**
Demonstrate how a modular, agent-based AI system can help users plan a travel itinerary by selecting destinations, hotels, and flights — and generate contextual travel tips — using a lightweight, free, and secure AI model.

> **Note:**  
> This project is a fictional learning exercise created by *Fictional Travel Co.* for educational and demonstration purposes only.  
> No real travel data or paid APIs are used.

---

## **Strategic Approach**
- Implement a **multi-agent architecture**, where each agent performs a distinct task:
  - **Flight Agent** → suggests flight options.
  - **Hotel Agent** → recommends accommodation choices.
  - **Travel Tips Agent** → provides engaging, activity-based suggestions.
- A simple **orchestrator** coordinates all agents to simulate collaborative AI behavior.
- Use the **open-source and free model** `google/flan-t5-small` for lightweight natural language generation.
- Optimize prompts to balance clarity and efficiency within the constraints of small models.

---

## **Learning Value**
- Understand the **core principles of Agentic AI** — modular design, sequencing, and collaboration between AI components.
- Explore how **LangChain-style orchestration** can be simulated using plain Python and open-source tools.
- Learn to build **lightweight AI systems** that demonstrate real-world concepts without relying on costly or proprietary APIs.
- Gain hands-on experience in **AI project structuring**, including data setup, orchestration logic, and UI design.

---

## **Project Highlights**
100% **free and secure** — no external paid APIs.  
Built for **Google Colab compatibility** using `transformers` and `gradio`.  
**Detailed code comments** to make every step easy to follow.  
**Interactive Gradio interface** for smooth experimentation.  
Demonstrates **multi-agent sequencing** in a simplified travel-planning scenario.  

---

## **Learning Focus**
This project aims to help learners:
- See how AI can perform **task-specific reasoning** through multiple cooperating agents.  
- Understand how context and sequencing improve output coherence.  
- Appreciate the trade-offs between **lightweight models and output accuracy**.  

> **Important:**  
> Because this project uses the free model `flan-t5-small`, responses — especially in the *Travel Tips* section — may be **simplified or less accurate**.  
> The goal is to focus on understanding the *agentic structure and orchestration logic*, rather than model perfection.

---

## **Tech Stack**
- **Language Model:** `google/flan-t5-small` (free and open-source)  
- **Interface:** Gradio (interactive UI)  
- **Environment:** Google Colab (CPU runtime)  
- **Framework:** Python with modular agent design  

---

## **How It Works**
1. **User Input:**  
   The user selects a city (e.g., Paris, Tokyo, Rome) from the dropdown menu.  

2. **Agent Execution:**  
   - The **Flight Agent** suggests flight options for that city.  
   - The **Hotel Agent** lists suitable accommodations.  
   - The **Travel Tips Agent** provides activity-based suggestions related to the chosen city.  

3. **Orchestration:**  
   All agents run sequentially under a simple Python controller, simulating how multiple AI agents collaborate in a larger system.  

4. **Output Display:**  
   Results appear in three cleanly formatted sections — *Flight Options*, *Hotel Options*, and *Travel Tips*.

---

## **Educational Value**
This project shows how **Agentic AI concepts** can be adapted into lightweight, free setups:
- Multi-agent collaboration without complex infrastructure.
- Context-sharing and sequencing between agents.
- Focus on clear learning, transparency, and reproducibility.


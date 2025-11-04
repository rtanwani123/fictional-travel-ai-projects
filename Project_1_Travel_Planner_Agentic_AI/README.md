#  Travel Planner Agentic AI  
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

## **How to Run**
1. Open Google Colab in your browser: [https://colab.research.google.com](https://colab.research.google.com)  
2. Upload the notebook file `travel_planner_agentic_ai.ipynb` from the folder:
3. Run each cell sequentially:  
- **Step 1:** Install required Python libraries.  
- **Step 2:** Generate input data (destinations, hotels, flights, activities). The notebook will automatically create the necessary files in `fictional_travel_docs`.  
- **Step 3:** Initialize agents and orchestrator.  
- **Step 4:** Launch the interactive Gradio interface.  
4. Interact with the UI:  
- Select a city from the dropdown.  
- View Flight, Hotel, and Travel Tips outputs in three separate sections.  
5. Explore and modify the sample data or prompts to see how the agents respond differently.  

> **Note:** The notebook uses the free model `flan-t5-small`, so responses — particularly travel tips — may be simplified. The focus is on understanding agentic workflow and orchestration rather than perfect AI outputs.
 

## 🌍 Travel Itinerary Planner

A smart AI-powered travel assistant that generates a personalized day-trip itinerary based on the user's selected city and interests. Built using **LangChain, LangGraph, Groq Llama 3**, and **Gradio** for an interactive UI.

---

## 🚀 Features  

✅ **Personalized Itinerary** – Get customized travel plans based on your preferences.  
✅ **AI-Powered Suggestions** – Uses **Groq Llama-3** to generate relevant activities.  
✅ **Interactive UI** – Uses **Gradio** for an easy-to-use interface.  
✅ **Graph-based Execution** – Utilizes **LangGraph** to manage workflow.  

---

## 🛠️ Installation  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/suryansh2004/Travel_Itinerary_Planar_MultiAI_Agents
cd travel-itinerary-planner
```

### 2️⃣ Install Dependencies  
Run the following command in your Colab Notebook or local environment:
```python
!pip install langchain langchain_core langchain_groq langchain_community langgraph gradio
```

### 3️⃣ Set Up API Key  
Replace `your_groq_api_key` in the code with your actual Groq API key:
```python
groq_api_key = "your_groq_api_key"
```

---

## 🎯 Usage  

### 🔹 Running the Notebook
1. Open `Travel_Itinerary_Planar-MultiAI_Agents.ipynb` in **Google Colab** or Jupyter Notebook.  
2. Run all cells to initialize dependencies and workflow.  
3. Follow on-screen prompts to enter **city and interests**.  
4. View the **generated itinerary** in the output.

### 🔹 Running Gradio App  
Run the Gradio interface using:  
```python
interface.launch()
```
It will provide a **web-based UI** where you can enter your city and interests.

---

## 📂 Project Structure  
```
📆 travel-itinerary-planner  
 ┣ 📄 Travel_Itinerary_Planar-MultiAI_Agents.ipynb  # Jupyter Notebook with main logic  
 ┣ 📄 README.md  # Documentation  
```

---

## 📊 Technologies Used  
- **LangChain** – To interact with the AI model  
- **LangGraph** – For structured execution flow  
- **Groq Llama 3** – Large Language Model for generating itineraries  
- **Gradio** – User-friendly web interface  

---

## 📝 Example Output  

**Input:**  
```
City: Paris  
Interests: Museums, Cafés, Landmarks  
```
**Output:**  
```
- Morning: Visit the Louvre Museum  
- Afternoon: Have lunch at Café de Flore  
- Evening: Explore the Eiffel Tower and enjoy a Seine River cruise  
```

---

## 🏆 Future Enhancements  

🚀 Add real-time **weather updates**  
🚀 Fetch **live travel recommendations**  
🚀 Expand to **multi-day trip planning**  

---

## 🤝 Contributing  
Feel free to submit issues or pull requests if you'd like to improve the project!

---


# Enhanced Q&A Chatbot With OpenAI

## 1. Project Overview
This project is a **Q&A Chatbot** that utilizes **LangChain, OpenAI, and Ollama** to generate intelligent responses to user queries. It provides an interactive UI using **Streamlit**, allowing users to ask questions and receive AI-generated answers.

## 2. Objective
The goal of this project is to create a **simple yet powerful** chatbot that:
- Supports OpenAI models and **Ollama-based** local models.
- Enables **customization** of response parameters like temperature and max tokens.
- Provides an interactive UI using **Streamlit** for seamless user interaction.

## 3. Key Steps in the Project
1. **Set up Environment Variables**  
   - Load API keys and necessary configurations using `dotenv`.
  
2. **Define Prompt Template**  
   - The chatbot uses a **structured prompt template** to handle user queries.

3. **Create Response Generation Pipeline**  
   - Uses `LangChain` to generate responses via **Ollama** models.

4. **Build Streamlit UI**  
   - Sidebar for selecting models and tuning parameters.
   - A simple text input box for user queries.
   - Displays AI-generated responses dynamically.

## 4. Conclusions
- The chatbot is **lightweight and modular**, making it easy to extend.
- **LangChain and Ollama** provide a powerful backend for generating AI responses.
- **Streamlit** offers a user-friendly interface for real-time interactions.
- Future enhancements can include **more models**, **memory retention**, and **multilingual support**.

## 5. Technologies Used
- **Python** 🐍
- **Streamlit** (UI framework)
- **OpenAI API** (for AI responses)
- **LangChain** (LLM orchestration)
- **Ollama** (local AI model support)
- **dotenv** (for managing API keys)

## 6. How to Run
### Prerequisites
- Install **Python 3.8+**
- Install required dependencies:

  
  pip install streamlit openai langchain langchain-openai langchain-community python-dotenv

  Set up .env file with your API key:
  LANGCHAIN_API_KEY=your_api_key

Run the following command to start the chatbot:
streamlit run app.py

### 7. Future Work
- Support for additional models like GPT-4, Claude, and Llama.
- Enhancing UI with improved layout and chatbot avatar.
- Adding memory to retain context across multiple interactions.
- Deploying on cloud platforms like AWS, GCP, or Hugging Face Spaces.

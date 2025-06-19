# chatbot-using-hugging-face-LLM
# Ollama Llama 2 Chatbot (Streamlit)

A local chatbot interface using the Llama 2 model via Ollama and a modern web UI with Streamlit.

## Features
- Runs Llama 2 locally using Ollama
- Maintains short-term memory (last 5 exchanges)
- Easy-to-use web interface (Streamlit)
- Clear chat/reset functionality

## Requirements
- Python 3.8+
- [Ollama](https://ollama.com/) (for running Llama 2 locally)
- [Streamlit](https://streamlit.io/)

## Setup
1. **Install Ollama and pull the Llama 2 model:**
   ```sh
   ollama pull llama2
   ```
2. **Install Python dependencies:**
   ```sh
   pip install streamlit
   ```
3. **Start Ollama server:**
   ```sh
   ollama serve
   ```
4. **Run the chatbot app:**
   ```sh
   streamlit run interface.py
   ```

## Usage
- Type your message in the input box and press Send.
- The bot will reply using Llama 2, considering the last 5 exchanges.
- Click 'Clear Chat' to reset the conversation.

## Example Interaction
```
You: What is the capital of France?
Bot: The capital of France is Paris.
You: And what about Italy?
Bot: The capital of Italy is Rome.
```

## Exiting
- To stop the app, close the Streamlit tab or stop the server in your terminal.

---

**Demo Video:** (Add your video link here) 

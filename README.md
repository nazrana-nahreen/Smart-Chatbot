
A conversational AI chatbot built using **Hugging Face Transformers** and **DialoGPT-medium**, designed to run interactively in **Google Colab** using **Gradio**. The bot maintains context for a session and responds like a normal human conversation.

---

## Features

- Human-like conversational responses using **DialoGPT-medium**.
- Maintains conversation history within a session.
- Interactive **web interface** powered by **Gradio**.
- Works directly in **Google Colab** or **local Jupyter notebooks**.
- Stops generation gracefully to avoid endless repetitions.

---

## Project Structure

- **chatbot_colab.ipynb** → Main notebook with chatbot code for Colab.
- **README.md** → Project description and instructions.

> Optional: You can extend this to include a `requirements.txt` if you want to run locally.

---

## Dependencies

The project uses the following Python libraries:

- `transformers` → For loading the pretrained model (`DialoGPT-medium`)  
- `torch` → PyTorch for model computations  
- `gradio` → Web interface for interactive chat  
- `google-colab` → Optional, if running in Colab  

You can install them with:

```bash
pip install transformers torch gradio

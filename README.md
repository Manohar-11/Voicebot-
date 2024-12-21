# Voice Chatbot

A versatile and interactive voice chatbot built with FastAPI, HuggingFace models, and a responsive web interface. This chatbot assists users by providing hotel-related information in a conversational format, adapting to the user's language, and maintaining a natural dialogue flow.

---

## Features

- **Multilingual Support:** Responds in the user's language without altering it.
- **Natural Language Processing:** Powered by HuggingFace's Meta-Llama model for generating precise and relevant responses.
- **Dynamic Speech Integration:** Speech-to-text and text-to-speech capabilities for seamless communication.
- **Web Interface:** Interactive and modern interface designed using HTML, CSS, and JavaScript.
- **Context Awareness:** Maintains chat history to provide contextually appropriate responses.

---

## Requirements

Ensure the following are installed:

- Python 3.9+
- FastAPI
- Jinja2
- HuggingFace Inference Client
- Pydantic
- dotenv
- SpeechRecognition (for speech input)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Manohar-11/Voicebot-.git
   cd voice-chatbot
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Add your HuggingFace API token to a `.env` file:
   ```env
   HF_TOKEN=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
   ```

---

## Usage

1. Run the FastAPI server:
   ```bash
   uvicorn app:app --reload
   ```

2. Open your browser and navigate to:
   ```
   http://127.0.0.1:8000/
   ```

3. Interact with the chatbot using:
   - Typing messages
   - Speaking into the microphone

---

## Directory Structure

```
voice-chatbot/
|-- app.py               # Main FastAPI app
|-- static/
|   |-- index.html       # Web interface
|-- dataset_folder/      # Folder for hotel data PDF files
|-- vector_db/           # Persistent storage for the vector index
|-- .env                 # Environment variables
|-- requirements.txt     # Required Python packages
```

---

## Demo Screenshots

### Interface
![Screenshot (9)](https://github.com/user-attachments/assets/8812ce7a-868a-451f-b854-fc829be8bbd7)



### Voice and Text Input
![Screenshot (10)](https://github.com/user-attachments/assets/34c3bb7d-89dc-4d7b-81fe-4dae61124ab9)



---


## Acknowledgments

- [HuggingFace](https://huggingface.co/) for the Llama model.
- [FastAPI](https://fastapi.tiangolo.com/) for the backend framework.
- [Bootstrap](https://getbootstrap.com/) and [FontAwesome](https://fontawesome.com/) for web styling.

---

## Contact

For any questions or suggestions, feel free to reach out:

- Email: peketimanohar11@gmail.com
- GitHub: [Manohar-11](https://github.com/Manohar-11)


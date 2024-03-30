# Mistral Text-to-Text Chat App

### Author: Surya Pratap

This project is a text-to-text chat application powered by Mistral models from Hugging Face. It allows users to interact with large language models to generate creative text formats, answer questions, translate languages, and provide summarizations. Users can select from a variety of Mistral models, provide prompts or questions, and receive responses from the models.

### Getting Started

To run the Mistral Text-to-Text Chat App locally, follow these instructions:

1. Clone the repository:

```bash
git clone https://github.com/suryapratap344/mistral-chat-app.git
```

2. Navigate to the project directory:

```bash
cd Mistral_Chat_App
```

3. Set up your environment variables:

````bash
python -m venv venv
source venv/bin/activate || venv\Scripts\activate (for Windows)
```
````

4. Install the required dependencies:

```bash
pip install -r requirements.txt
```

5. Add your Hugging Face API token to the .env file:

```makefile
HF_TOKEN=your_hugging_face_api_token
```

6. Run the application:

```bash
streamlit run app.py
```

arduino
Copy code
streamlit run app.py
Access the application in your web browser at http://localhost:8501.

### Usage

- Select a Mistral model from the sidebar.
- Enter your message or prompt in the input box.
- Click "Send" or press Enter to submit your message.
- View the model's response in the chat interface.
- Follow proper usage tips provided in the sidebar for optimal results.

### About Mistral Models

The Mistral models provided in this application are large language models (LLMs) trained on a massive dataset of text and code. They offer various functionalities, including text-to-text generation, question answering, translation, and summarization.

### Proper Usage Tips

- Provide clear and concise prompts or questions for the model to understand your request.
- Break down complex tasks into smaller, more manageable steps for the model.
- Use the model's capabilities to explore ideas, generate creative text formats, or answer questions in an informative way.
- Be aware that LLMs are still under development and may sometimes produce incorrect or misleading outputs. It's important to critically evaluate the model's responses.

### Contributing

Contributions to the Mistral Text-to-Text Chat App are welcome! If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request on GitHub.

### License

This project is licensed under the [MIT License](https://opensource.org/license/gpl-3-0). See the LICENSE file for details.

© 2024 Surya Pratap. All rights reserved.

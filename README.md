📄✨ Custom PDF Summarizer with Gemini & LangChain A user-friendly web application built with Streamlit that leverages the power of Google's Gemini-1.5-flash model via LangChain to generate custom summaries of PDF documents based on user-provided prompts.

🚀 Overview This project provides a simple yet powerful interface for summarizing PDF files. Instead of a generic summary, users can provide a specific prompt (e.g., "Summarize this for a non-technical audience in five bullet points" or "Extract all key financial figures from this report") to guide the AI. The application handles document loading, text splitting, and interaction with the Gemini API through the LangChain framework.

✨ Features Upload PDFs: Easily upload any PDF document directly through the web interface.

Custom Prompts: Tailor the summarization task to your exact needs with a custom instruction prompt.

Powered by Google Gemini: Utilizes the fast and efficient gemini-1.5-flash-latest model for high-quality text generation.

Intuitive UI: A clean, sidebar-based layout built with Streamlit for a seamless user experience.

Secure API Key Handling: Uses a .env file to safely manage your Google Gemini API key.

🛠️ Tech Stack Backend: Python

Web Framework: Streamlit

LLM Framework: LangChain

LLM Provider: Google Generative AI (Gemini)

PDF Processing: PyPDFLoader

⚙️ Setup and Installation Follow these steps to run the application locally.

Clone the Repository Bash
git clone https://github.com/sathyam2003/GenAI-Summarization-with-Langchain.git cd GenAI-Summarization-with-Langchain 2. Create a Virtual Environment It's recommended to use a virtual environment to manage project dependencies.

Bash

For Unix/macOS
python3 -m venv venv source venv/bin/activate

For Windows
python -m venv venv .\venv\Scripts\activate 3. Install Dependencies Install all the required Python packages from the requirements.txt file.

Bash

pip install -r requirements.txt 4. Configure Environment Variables The application requires a Google Gemini API key.

Create a new file in the root directory named API.env.

Add your API key to this file as shown below:

Code snippet

GEMINI_API_KEY="YOUR_GOOGLE_API_KEY_HERE" You can obtain a free API key from Google AI Studio.

▶️ How to Run Once the setup is complete, you can run the Streamlit application with a single command:

Bash

streamlit run app.py

Your web browser should automatically open a new tab with the application running.

📖 Usage Upload PDF: Click the "Browse files" button in the sidebar to upload your PDF document.

Enter Prompt: In the text area below, enter the specific instructions for how you want the document to be summarized.

Generate: Click the "Generate Summary" button.

View Summary: The custom summary will appear in the main area of the page.

📜 License This project is licensed under the MIT License. See the LICENSE file for more details.

🙏 Acknowledgments This project was inspired by the "GenAI Summarization with Langchain" guided project on Coursera. A special thanks to my faculty, S Ratan Kumar Sir, for the valuable course recommendation that led to this hands-on learning experience.

GenAI-

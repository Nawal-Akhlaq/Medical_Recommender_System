**Medical-Recomendation-system**

🏥 Medical Chatbot with LLaMa-7B-GGML
An AI-powered chatbot that provides concise medical recommendations using the LLaMa-7B-GGML model and Streamlit. Easily interact with a large language model fine-tuned for factual medical responses, all through a clean and simple web interface.

🚀 Live Demo
👉 Your Streamlit App Link
(Replace the link with your deployed Streamlit app!)

✨ Features
✅ Streamlit-based web interface
✅ Uses LLaMa-7B-GGML via ctransformers
✅ GPU-accelerated (if available), fallback to CPU
✅ Customizable response parameters (temperature, top_p, etc.)
✅ Displays GPU memory usage when CUDA is available
✅ Lightweight, easy to deploy on Streamlit Cloud

📂 Project Structure
medical-chatbot/
├── app.py              # Main Streamlit app
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
🛠️ Installation (Run Locally)
1. Clone the repository
git clone https://github.com/yourusername/medical-chatbot.git
cd medical-chatbot
2. Install dependencies
It's recommended to use a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\\Scripts\\activate
Then install:

pip install -r requirements.txt
3. Run the app
streamlit run app.py
⚡ Requirements
streamlit
torch
tqdm
ctransformers
All handled via requirements.txt:

streamlit
torch
tqdm
ctransformers
🌐 Deployment on Streamlit Cloud
1. Push your code to GitHub
Make sure your repository includes:

app.py
requirements.txt
(Optional) README.md
2. Deploy
Go to Streamlit Cloud
Click New app
Select your GitHub repo
Choose app.py as the entry point
Deploy! 🚀
🖼️ Screenshots
(Replace with actual screenshots if you have them!)

Chatbot Interface	GPU Memory Display
Chatbot UI	GPU Memory
📌 Usage Guide
Enter a medical question (e.g., "What is Panadol used for?")
Click Generate Response
View the AI-generated answer below the input box
GPU memory usage is displayed if CUDA is available
⚠️ Disclaimer
This chatbot is for educational purposes only. It is not intended to provide professional medical advice, diagnosis, or treatment. Always consult a qualified healthcare provider for any medical concerns.

📜 License
This project is licensed under the MIT License.
See LICENSE for details.

🙌 Acknowledgements
TheBloke for the LLaMa-7B-GGML model
Streamlit for the web app framework
ctransformers for efficient model inference

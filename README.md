## 📦 Installation & Setup
```bash
1️⃣ Clone the repository
git clone https://github.com/<your-username>/personal-llm-assistant.git
cd personal-llm-assistant

2️⃣ Create a virtual environment

3️⃣ Activate the virtual environment

4️⃣ Install dependencies
pip install -r requirements.txt
🔑 Environment Variables
You need a .env file in the root directory to store your API keys.

5️⃣ Create a .env file
Inside the project folder:

6️⃣ Add the following variables:

OPENAI_API_KEY=your_openai_api_key_here
PUSHOVER_TOKEN=your_pushover_app_token
PUSHOVER_USER=your_pushover_user_key
(Add any other keys or secrets your project uses.)

▶️ Running the App
Once the environment is ready:

python app.py
If using a Gradio demo:

python gradio_app.py
The Gradio interface will appear with a localhost URL in your terminal.


# Conversational-Q-A-Chatbot-with-LangChain-and-Hugging-Face
This project demonstrates the creation of a Conversational Q&A Chatbot using LangChain for context management and deployment on Hugging Face Spaces. The chatbot retains conversation context, making it an interactive and user-friendly experience.

🌟 Features
Contextual Memory: The chatbot retains the conversation context across multiple interactions.
LangChain Integration: Utilizes LangChain's schemas for managing human, system, and AI messages.
Streamlit UI: Simplifies the interaction process with an intuitive user interface.
Error Handling: Demonstrates debugging during live coding.
Deployment: Designed for deployment on Hugging Face Spaces.
🚀 Quick Start
1. Clone the Repository
```
git clone https://github.com/your-username/conversational-chatbot.git
cd conversational-chatbot
```
2. Install Dependencies
```
pip install -r requirements.txt
```
3. Set Up Environment Variables
   Create a .env file in the root directory and add your OpenAI API key:
```
OPENAI_API_KEY=your-api-key
```
4. Run the Application
```
streamlit run app.py
```
📄 How It Works
Human, System, and AI Messages:

Human Message: Stores user input.
System Message: Provides chatbot instructions, such as acting as a "comedy assistant."
AI Message: Stores the chatbot's responses.
Session Management:

Retains context across interactions using Streamlit session state.
Streamlit Interface:

Offers an intuitive UI for querying the chatbot and visualizing responses.
Deployment:

Ready for deployment on Hugging Face Spaces, enabling a broader audience to interact with the chatbot.
📦 Project Structure
bash
Copy code
conversational-chatbot/
│
├── app.py                # Main Streamlit application
├── requirements.txt      # Python dependencies
├── .env                  # Environment variables (not included in the repo)
├── README.md             # Project documentation
🛠️ Key Libraries
LangChain: For message schema and context management.
Streamlit: For building the user-friendly web app.
Hugging Face: For deployment and showcasing the chatbot.
📊 Example Interactions
User: "Hey, what's my name?"

Chatbot: "I don't have access to personal information unless you provide it."
User: "Remember my name, it's Kish N."

Chatbot: "Of course, Kish N, I'll do my best to remember your name."
User: "What is my name?"

Chatbot: "Your name is Kish N."
🚀 Future Enhancements
Advanced prompt templates for more diverse interactions.
Improved deployment pipeline for Hugging Face Spaces.
Integration with additional data sources to enhance chatbot knowledge.
🤝 Contributing
Contributions are welcome! Please fork the repository, submit issues, or create pull requests to enhance the project.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

🙌 Acknowledgments
Special thanks to LangChain and Streamlit for providing robust tools for chatbot development.

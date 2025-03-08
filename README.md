# SmartBill Connect
Welcome to SmartBill Connect! This is an AI-powered web application that allows users to upload their phone bills (in PDF format), analyze the bill with Google's Gemini AI, and receive a detailed summary and personalized recommendations. It also stores summaries for users and helps in evaluating whether their current plan is optimal.

**Features 🌟**

- **User Authentication**: Secure login/signup with password hashing.
- **Phone Bill Upload**: Support for PDF file uploads to extract bill data.
- **AI-Powered Summary**: Summarizes the uploaded phone bill using the Gemini AI model.
- **Personalized Recommendations**: Provides actionable advice on how users can optimize their phone plans.
- **Simple Interface**: User-friendly web interface built with Streamlit.
- **Secure Password Storage**: Passwords are securely hashed for authentication.

**Prerequisites 📋**

- Python 3.9 or higher
- A **Gemini API key** (for AI-based summarization)
- Internet connection

**Setup Instructions 🚀**

**Clone the Repository**

`smartbill-connect`

**Create a Virtual Environment**

`python -m venv venv`

**Activate the Virtual Environment**

On **Windows**:

`venv\\Scripts\\activate`

On **macOS/Linux**:

`source venv/bin/activate`

**Install Dependencies**

`pip install -r requirements.txt`

**Get Your Gemini API Key**

1. Visit the [Google AI Studio](https://console.cloud.google.com/).
2. Sign in with your Google account.
3. Create a new API key.
4. Copy the API key for use in your project.

**Set Up Environment Variables**

1. Create a .env file in the project root.
2. Add your API key to the file: `GEMINI\_API\_KEY=your\_api\_key\_here`

**Running the Application 🏃‍♂️**

1. Ensure your virtual environment is activated.
2. Start the Streamlit server
3. Open your browser and navigate to [http://localhost:8501](http://localhost:8501/) to access the application.
`python -m streamlit run app.py4`

**Usage Guide 📖**

**First-Time Users**

1. Click the **"Signup"** button in the sidebar.
2. Create your username and password.
3. Log in with your credentials.

**Returning Users**

1. Enter your username and password.
2. Click **"Login"**.

**Getting Your Phone Bill Summarized**

1. Upload your phone bill (PDF format).
2. Wait while the AI analyzes and summarizes the bill.
3. View the summary and recommendations generated by Gemini AI.

**Security Notes 🔒**

- Passwords are securely hashed using SHA-256.
- Never share your API key publicly.
- Keep your .env file private to ensure API key security.

**Troubleshooting 🔧**

- If you encounter API errors, check that your **Gemini API key** is correctly set in the .env file.
- Ensure all dependencies are installed correctly.
- Verify that your uploaded bill is in **PDF format**.
- Confirm that you have a stable internet connection.

**Contributing 🤝**

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you want to change.

**License 📄**

MIT License

**Acknowledgments 👏**

- **Google Gemini AI** for the bill summarization.
- **Streamlit** for the awesome web framework.
- **Replit AI** for intelligent integration
- **PyMuPDF** for the PDF text extraction.
- All contributors and users of this project.

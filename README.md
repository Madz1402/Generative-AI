Environment Variables Setup
This project uses API keys, so the .env file is not included in this repository for security reasons.

Create a .env File
Create a file named .env in the root directory and add the following:

GROQ_API_KEY=your_api_key_here
GROQ_MODEL_NAME=llama-3.3-70b-versatile

Important Notes
Do not share your API key publicly
Never upload the .env file to GitHub
Always keep your credentials secure

.gitignore
Make sure your .gitignore file contains:

.env
Alternative (Optional)
You can also set environment variables manually:
Windows (PowerShell)
$env:GROQ_API_KEY="your_api_key_here"
$env:GROQ_MODEL_NAME="llama-3.3-70b-versatile"

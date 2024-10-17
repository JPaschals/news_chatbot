# News Chatbot

A chatbot that utilizes Cohere's API to generate headlines, detect tones, and summarize news articles. The application provides dynamic responses based on user queries related to the article content.

## Features

- **Generate Headlines**: Automatically creates engaging headlines for news articles.
- **Detect Tone**: Analyzes the tone of the article and categorizes it into themes like political, sports, crime, etc.
- **Summarize Articles**: Provides concise summaries of the articles in a few sentences.
- **Dynamic Conversation**: Engages in a conversation with users based on the context of the article.

## Tech Stack

- **Flask**: A lightweight WSGI web application framework for Python.
- **Cohere API**: Used for generating text and understanding tones.
- **Python**: The primary programming language used in this project.

## Getting Started

### Prerequisites

- Python 3.x
- pip (Python package installer)
- Git (for version control)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/JPaschals/ai-projects.git

2. Navigate to the project directory:
    ```bash
   cd news_chatbot
   
4. Create and activate a virtual environment (optional but recommended):
    ```bash
      python -m venv venv
  
# On Windows
   ```bash
   venv\Scripts\activate
```
# On macOS/Linux
 ```bash
    source venv/bin/activate
```
5. Install the required dependencies:
     ```bash
     pip install -r requirements.txt
   
6. Create a .env file in the root directory and add your API keys:
      ```bash
      COHERE_API_KEY=your_cohere_api_key


## Running the Application
To start the Flask application, run:
```bash
   python app.py
```
The application will be available at http://127.0.0.1:5000.

## Testing the Chatbot
You can test the chatbot using Postman or any other API testing tool.

Endpoint: POST /chat
Request Body:
  ```bash
 {
    "article": "Your article text here",
    "query": "Your question about the article here"
}
```
## Example Response
  ```bash
 {
    "headlines": "Generated headline here",
    "tone": "Detected tone here",
    "summary": "Summary of the article here",
    "dynamic_response": "Response to the user's query here"
}

```
## License
This project is licensed under the MIT License - see the LICENSE file for details.

##Acknowledgments
Cohere for their powerful NLP API.
Flask for providing a lightweight framework for web applications.

## SQL


### Customization Tips
- Replace `your_cohere_api_key` with a placeholder for actual API keys.
- If you have specific instructions for deployment or additional features, feel free to add them to the README. 
- Make sure to include any other relevant details or acknowledgments that are important for your project.

Let me know if you need any changes or additional information!


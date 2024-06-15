---
title: Interview Assistant
emoji: 🐢
colorFrom: indigo
colorTo: yellow
sdk: streamlit
sdk_version: 1.35.0
app_file: app.py
pinned: false
license: apache-2.0
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

# genai-interview-assistant
# Interview Assistant

This application uses Cohere's NLP capabilities to simulate an interviewee responding to interview questions. Users can input their resume and a job description, and then ask questions to get detailed and structured answers based on the provided context.

## Features

- Input resume and job description
- Ask questions based on the provided context
- Get detailed and structured answers generated by Cohere
- View all questions and answers in a scrollable format
- Clear context and Q&A to start a new session
- Follow the me on GitHub and LinkedIn

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/JyothiBasireddy/interview-assistant.git
   cd interview-assistant
    ```
2. Install the required packages:
```bash
pip install -r requirements.txt
```
3. Create a .env file in the root directory with your Cohere API key:
```
COHERE_API_KEY=your-cohere-api-key
```
4. Run the application:

```
streamlit run app.py
```



#   C h a t B o t  
 
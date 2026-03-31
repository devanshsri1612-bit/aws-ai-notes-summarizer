#**AWS-AI-NOTES-SUMMARIZER**

AI Notes Summarizer is a web application that summarizes long notes into short and useful points using Amazon Bedrock.

The project uses AWS Lambda for backend processing, API Gateway for API integration, and HTML/CSS/JavaScript for the frontend.

# AI Notes Summarizer

AI Notes Summarizer is a web application that helps users summarize long notes into short and useful points using AI.

The project uses Amazon Bedrock for text summarization, AWS Lambda for backend processing, API Gateway for API handling, and HTML/CSS/JavaScript for the frontend.

---

## Features

* AI-powered notes summarization
* Generates short summaries from long notes
* Dark mode toggle
* Copy summary button
* Clear notes button
* Word count display
* Responsive user interface
* Built using serverless AWS services

---

## Tech Stack

* HTML
* CSS
* JavaScript
* AWS Lambda
* Amazon Bedrock
* API Gateway
* IAM

---

## How It Works

1. User enters or pastes notes into the text area.
2. Frontend sends the notes to API Gateway.
3. API Gateway triggers the Lambda function.
4. Lambda sends the notes to Amazon Bedrock.
5. Amazon Bedrock generates a summary.
6. Lambda returns the summary to the frontend.
7. The summarized output is displayed to the user.

---

## AWS Services Used

* AWS Lambda – Handles backend logic
* Amazon Bedrock – Generates AI summaries
* API Gateway – Exposes Lambda as an API
* IAM – Manages permissions and roles

---

## Project Structure

```bash
AI-Notes-Summarizer/
│
├── index.html
├── README.md
```

---

## Sample Input

AWS Lambda is a serverless compute service provided by Amazon Web Services. It allows developers to run code without provisioning or managing servers.


## Sample Output


- AWS Lambda is a serverless compute service.
- It allows developers to run code without managing servers.
- It automatically scales with usage.
- It is commonly used for backend APIs and automation tasks.




## Future Improvements

* PDF upload support
* MCQ generation from notes
* Flashcard generation
* Download summary as PDF
* Save summary history
* User login and authentication
* Database integration using DynamoDB


## Author

Built as an AWS and AI project for learning serverless architecture and generative AI integration.


## Project UI

<img width="1908" height="982" alt="Screenshot 2026-03-31 113847" src="https://github.com/user-attachments/assets/5a84ae49-54ff-41e5-9442-0d8fd29948c3" />


### UI Preview

The application provides:

- Large notes input area
- Word count display
- AI-generated summary output
- Dark mode toggle
- Copy summary button
- Clear notes button
- Clean and responsive interface




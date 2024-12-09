<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chatbot Using NLP</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f9;
            color: #333;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 90%;
            max-width: 1100px;
            margin: auto;
            overflow: hidden;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        h1, h2, h3 {
            color: #333;
        }

        pre, code {
            background-color: #272822;
            color: #f8f8f2;
            padding: 10px;
            border-radius: 5px;
            display: block;
            overflow-x: auto;
            font-size: 14px;
        }

        .code-block {
            background-color: #272822;
            color: #f8f8f2;
            padding: 15px;
            border-radius: 5px;
            margin: 20px 0;
            overflow-x: auto;
        }

        ul {
            margin: 10px 0;
            padding-left: 20px;
        }

        li {
            margin-bottom: 10px;
        }

        a {
            color: #3498db;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .button {
            display: inline-block;
            background-color: #3498db;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
            border-radius: 5px;
            text-decoration: none;
        }

        .button:hover {
            background-color: #2980b9;
        }

        .footer {
            text-align: center;
            margin-top: 20px;
            font-size: 14px;
            color: #555;
        }
    </style>
</head>

<body>

<div class="container">
    <h1>Chatbot Using NLP</h1>

    <h2>Project Overview</h2>
    <p>This project focuses on building a chatbot using Natural Language Processing (NLP) techniques. The chatbot can understand user queries, recognize intent, and provide relevant responses. It utilizes NLP libraries like <strong>NLTK</strong> for text processing, <strong>Scikit-learn</strong> for machine learning, and <strong>Streamlit</strong> to provide an interactive web-based interface for user interaction.</p>

    <h2>Key Features</h2>
    <ul>
        <li><strong>Intent Recognition</strong>: Detects user intent from input (e.g., greetings, farewells, help requests).</li>
        <li><strong>Dynamic Responses</strong>: Responds to queries using pre-defined templates and patterns.</li>
        <li><strong>User Interaction</strong>: Offers an interactive web-based interface built using Streamlit.</li>
        <li><strong>Conversation History</strong>: Stores user interactions for analysis and future improvements.</li>
    </ul>

    <h2>Technologies Used</h2>
    <ul>
        <li><strong>Programming Language</strong>: Python</li>
        <li><strong>NLP Library</strong>: NLTK for natural language processing</li>
        <li><strong>Machine Learning</strong>: Scikit-learn for training and testing models</li>
        <li><strong>Web Interface</strong>: Streamlit for user interaction</li>
        <li><strong>Data Format</strong>: JSON for intent, pattern, and response definition</li>
    </ul>

    <h2>Installation Instructions</h2>

    <h3>Step 1: Clone the Repository</h3>
    <div class="code-block">
        <code>
git clone &lt;your-repository-url&gt;<br>
cd &lt;your-repository-directory&gt;
        </code>
    </div>

    <h3>Step 2: Set Up a Virtual Environment (Optional)</h3>
    <div class="code-block">
        <code>
python -m venv venv<br>
source venv/bin/activate  <!-- On Windows, use venv\Scripts\activate -->
        </code>
    </div>

    <h3>Step 3: Install Dependencies</h3>
    <div class="code-block">
        <code>
pip install -r requirements.txt
        </code>
    </div>

    <h3>Step 4: Download NLTK Data</h3>
    <div class="code-block">
        <code>
import nltk<br>
nltk

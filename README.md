# Ask the Pope AI

Ask the Pope AI is an Azure web app that hosts an AI chatbot designed specifically for Pope John XXIII Regional High School. This project utilizes Azure OpenAI and Azure AI Search to provide a ChatGPT-like experience tailored to questions about the school.

This was created by the [Pope John AI Club](https://sites.google.com/view/pj-ai-club), founded by James DeSilver.

NOTE: It is referenced as "Ask the Lion AI" on the website

## Features

- Chatbot experience tailored to Pope John XXIII Regional High School
- Provides information on school policies, events, faculty, and more
- Accessible online at [popejohn.org](https://popejohn.org) without the need to clone or download anything
- Built using GPT-4 for natural, context-aware responses
- Includes references to relevant sources for better accuracy and transparency

## Using the App

The Ask the Pope AI app is hosted directly on [popejohn.org](https://popejohn.org). To ask questions about the school, simply navigate to the website and interact with the AI chatbot. No special setup, login, or downloads are required.

## Technology Stack

- **Azure OpenAI Service**: Uses GPT-4o for natural language processing
- **Azure AI Search**: For indexing and retrieving school-specific information
- **Azure Web App**: Provides a hosted environment for the chatbot

## Getting Started

You don’t need to install anything to use Ask the Pope AI. Simply visit [popejohn.org](https://popejohn.org) to start chatting.

If you're interested in setting up a similar service, you can refer to [this sample repository](https://github.com/azure-samples/azure-search-openai-demo) for more details on how to use Azure OpenAI and AI Search.

## Features at a Glance

- **Multi-turn Conversations**: Engage in natural, context-rich dialogue with the chatbot.
- **Q&A Interface**: Ask one-off questions and get straightforward answers.
- **User-Friendly Interface**: A clean and intuitive design for easy interaction.

## How It Works

The Ask the Pope AI app uses Azure’s Retrieval Augmented Generation (RAG) pattern to provide information:
1. **Azure AI Search** finds relevant information in school documents.
2. **Azure OpenAI Service** then generates an answer based on this data.

This combination ensures that responses are accurate, detailed, and grounded in official school information.

## Credits

This project is based on the [Azure Search OpenAI Demo](https://github.com/azure-samples/azure-search-openai-demo) by Microsoft, which provides a foundation for integrating Azure OpenAI and AI Search.

# I am learing Multi AI Agent system.

From https://astra.datastax.com/langflow/ We can create a UI/Interface that will show the flow of our Model. We need to signup

AI Model FLow: Input -> Process in AI model -> Output

I used OPENAI model for learing. We need API key which we can get after signing up on https://platform.openai.com/api-keys

We created 2 Agent.

1. will take input and send it to model and get output in json format
2. another will tell LLM to give "Yes" or "No". Depending upon if the question is Math related or not.

We are using Astra DB Database to store our notes: It is a vector search database. Which means we can use RAG Component (Retrival Augmented Generation).

RAG will allow us to grab relevant notes and inject those inside of our prompt.

Vector Database:

1. Can store vectors (fixed-legth list of numbers) along with other data items.
2. Allows machine learning to be used to power search, recommendations, and text generation use-cases.

WE need to create a Astra DB DataBase from https://astra.datastax.com/org/d65a5f29-8d4d-4b81-adce-6a5e5d1f4907/database/d4f27c56-5f95-44c9-81aa-07da7f2fff09

Create NVIDIA API KEY: https://build.nvidia.com/explore/discover

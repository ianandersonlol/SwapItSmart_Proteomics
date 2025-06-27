# PTFI Proteomics Explorer Chatbot - User Guide

## Welcome to the PTFI Proteomics Explorer Chatbot!

This chatbot is designed to help you explore and understand the proteomics data from the Periodic Table of Food Initiative (PTFI). You can ask questions about food composition, nutritional values, and even get recommendations for food substitutions based on protein profiles.

## How to Use the Chatbot

Simply type your questions or requests into the chat interface. Here are some examples of what you can ask:

*   "What is the protein content of chicken breast?"
*   "Compare the nutritional profile of almonds and walnuts."
*   "Suggest a food substitute for dairy milk that is high in protein."
*   "Tell me about the proteomics of apples."
*   "Analyze this recipe: [paste your recipe here]" (The chatbot can analyze ingredients and suggest healthier alternatives.)
*   "Upload an image of a food item for analysis." (If image upload is enabled in your interface.)

## Understanding the Agent Structure (High-Level)

The PTFI Proteomics Explorer Chatbot operates using a sophisticated **multi-agent AI system**. This means that instead of a single AI trying to answer all your questions, there are several specialized AI "agents" working together behind the scenes.

Here's a simplified overview:

1.  **Your Query**: When you type a question, a central **Manager Agent** receives it.
2.  **Task Delegation**: The Manager Agent analyzes your request and decides which specialized agent(s) are best suited to handle it. For example:
    *   If you ask about protein content, a **Food Information Agent** might be engaged.
    *   If you ask for a food comparison, a **Food Comparison Agent** will take over.
    *   If you provide a recipe, a **Recipe Analysis Agent** will process it.
    *   If you upload an image, a **Food Image Agent** will be activated.
3.  **Tool Utilization**: Each specialized agent has access to a set of "tools" – these are like functions or databases they can use. For instance, they can access the PTFI proteomics database, perform web searches for additional information, or use analytical tools for calculations.
4.  **Collaboration**: Sometimes, multiple agents might work together. For example, a Recipe Analysis Agent might identify ingredients, and then a Food Information Agent might provide details on those ingredients.
5.  **Response Synthesis**: Once the specialized agents have gathered all the necessary information, a **Writer/Synthesis Agent** compiles their findings into a clear, concise, and helpful response for you.

This multi-agent approach allows the chatbot to handle a wide range of complex queries efficiently and accurately, drawing upon specialized knowledge and tools for each task.

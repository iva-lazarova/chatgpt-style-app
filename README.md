### What is this project about?

The project demonstrates how to build a simple Langchain app that allows users to have an interactive session with an LLM,
in this case (ChatGPT) if no front-end interface is required.

This is achieved by using Langchain's LLMChain and ConversationBufferMemory that transform the typically stateless interaction with an LLM into
a conversation where context is preserved in memory, which allows for asking follow-up questions.

The conversation memory is then saved in a .json file for persistence across sessions.


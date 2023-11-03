# LCEL
intro to langchain expression langchain

# LangChain components and the Runnable Protocol

Standard Interface
1. stream: stream back chunks of response
2. invoke: invoke chain with an input
3. batch: invoke chain with a list of input

---------

Input Types

1. Prompt: dictionary
2. Retriever: Single String
3. LLM, ChatModel: Single String, message list or PromptValue
4. Tool: single string and dictionary (which tool you are using)
5. OutputParser: depends on the parser

-------------

Output Types
1. LLM: string
2. Retriever: List of Documents
3. ChatModel: Chat Message
4. Prompt: PromptValue
5. OutputParser: depends on the parser
6. Tool: Depends on the tool
   

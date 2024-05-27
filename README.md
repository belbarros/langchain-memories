# Exploring LangChain: Four Powerful Memory Types for Conversational AI
This project showcases how to implement and utilize four distinct memory types in LangChain to enhance your language modeling projects. Each memory type is illustrated with code examples and further explanation can be found on its accompanying blogpost that's gonna be published soon!

## Memory Types Covered
- **ConversationBufferMemory:** Stores the entire raw conversation history in a buffer.
- **ConversationBufferWindowMemory:** Stores a fixed-size window (defined by "k") of the most recent exchanges in a conversation.
- **ConversationTokenBufferMemory:**  Stores the conversation history up to a specified token limit.
- **ConversationSummaryMemory:** Condenses the conversation history into concise summaries.

## Setup
1. Create a virtual enviroment
```
python3 -m venv .venv   
source .venv/bin/activate
```
2. Install dependecies
```
pip install -r requirements.txt
```
3. Set up OpenAPI key
```
# On a .env file:
OPENAI_API_KEY=your_key
```
4. Run the scripts!
```
python3 (filename).py
```

## Acknowledgment
This blog post was inspired by the insights and knowledge gained from the LangChain for LLM Application Development course offered by deeplearning.ai.

### Happy coding!

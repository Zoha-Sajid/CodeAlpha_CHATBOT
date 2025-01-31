

 **AI-Powered Chatbot** 🤖💬

 **Overview**  
This program is an interactive AI-powered chatbot built using Python’s **Tkinter** for the graphical user interface (GUI) and **spaCy** for Natural Language Processing (NLP). The chatbot can engage in meaningful conversations with users, answering various queries like greetings, jokes, questions about itself, and general inquiries like the weather.

 **Features**  
- **Greeting Responses**: The bot recognizes common greetings like "Hello" or "Hi" and responds with a friendly message.
- **Jokes**: The bot tells jokes when asked.
- **Questions about the Bot**: The bot can answer questions like "What is your name?" or "Who are you?" with a description of itself.
- **Weather and General Information**: While it can’t check the weather, it politely invites users to ask about other topics.
- **Entity Recognition**: The bot uses spaCy's NLP capabilities to recognize and address users by their names if mentioned.
- **Scrollable Chat Interface**: The GUI includes a scrollable chat area to display the conversation history and an input field for typing messages.
- **User Interaction**: The bot intelligently responds to user inputs using NLP-based understanding.

 **How It Works**  
1. **Greeting**: The bot welcomes the user and prompts them for input.
2. **User Input**: The user types a message and submits it.
3. **Response Generation**: The chatbot processes the message using spaCy to understand and generate an appropriate response.
4. **Chat History**: The conversation is displayed in a scrollable area, showing both the user’s messages and the chatbot’s replies.
5. **Entity Recognition**: If the user mentions a name, the bot recognizes and acknowledges it.

 **Requirements**  
- **Python 3.x**  
- **spaCy**: Install spaCy via pip:
  ```bash
  pip install spacy
  ```
- **spaCy English Model**: Download the small English model for NLP:
  ```bash
  python -m spacy download en_core_web_sm
  ```

 **Installation**  
1. Install Python 3.x from [python.org](https://www.python.org/).
2. Install the required libraries:
   ```bash
   pip install spacy
   python -m spacy download en_core_web_sm
   ```
3. Clone or download this repository to your local machine.

 **Running the Program**  
1. Open a terminal or command prompt in the project directory.
2. Run the program with:
   ```bash
   python chatbot.py
   ```
3. The chatbot window will appear, and you can start chatting with it by typing your messages.

 **Example Interaction**  

```
Bot: Hello! I'm here to chat with you. Type something!
You: Hi
Bot: Hi there! What can I do for you?
You: Tell me a joke
Bot: Why don't skeletons fight each other? They don't have the guts!
You: What's your name?
Bot: I'm a bot, your assistant. How can I assist today?
```
 **Customization**  
- **Add more responses**: Customize the chatbot’s behavior by editing the `greetings`, `jokes`, and `questions_about_bot` lists in the code.
- **Extend NLP capabilities**: Modify the `generate_response` function to handle more complex queries or entities.
- **Change the GUI design**: You can adjust the layout, fonts, or colors in the `Tkinter` GUI code.

------------------------------------------------------------------------------------------------------------------------------------------    
This project is open-source and free to use. You are welcome to contribute, customize, and share it! 😊


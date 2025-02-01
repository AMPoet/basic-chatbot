# Simple ChatBot with JSON Memory

This is a simple chatbot that learns from user input and stores questions and answers in a JSON file. If the chatbot doesn't know an answer, the user can teach it, and it will remember the response for future conversations.

---

## Features 🚀
- Loads questions and answers from a JSON file.
- Finds the closest matching question using `difflib`.
- If no answer is found, it prompts the user to teach the bot.
- Saves new questions and answers automatically.
- Supports quitting the conversation by typing `"quit"`.

---

## Installation & Setup 🔧

### 1. Install Python (if not installed)
Make sure you have Python installed. Download it from the official site:  
🔗 [Python Official Website](https://www.python.org/downloads/)

### 2. Clone or Download the Repository
```bash
git clone https://github.com/your-repo/chatbot-json.git
cd chatbot-json
```

### 3. Create a JSON Data File
Ensure you have a `data.json` file in the same directory. If it doesn't exist, create it with the following structure:
```json
{
    "questions": []
}
```

### 4. Run the ChatBot
```bash
python chatbot.py
```

---

## Documentation Links 📚

### 1. **JSON (JavaScript Object Notation)**
- [Python JSON Module Docs](https://docs.python.org/3/library/json.html)  
- [JSON Official Site](https://www.json.org/json-en.html)  

### 2. **difflib (Find Closest Matches)**
- [Python difflib Documentation](https://docs.python.org/3/library/difflib.html)

### 3. **Python Input & Output**
- [Python Input/Output Documentation](https://docs.python.org/3/tutorial/inputoutput.html)

---

## Usage 🛠️
1. Run the chatbot.
2. Type any question.
3. If the chatbot knows the answer, it will reply.
4. If it doesn’t, you can teach it by providing an answer.
5. Type `"quit"` to exit the chatbot.

---

## Example Usage 🤖
```
You: Hello
Bot: I don't know the answer, Can you teach me?
Type the answer or 'Skip' to skip: Hi there!
Bot: Thank you! I learned a new response.

You: Hello
Bot: Hi there!
```

---

## Future Improvements 🔥
- Implement Natural Language Processing (NLP) for better responses.
- Add a GUI using `Tkinter` or `PyQt`.
- Connect with a database instead of JSON.

Happy Coding! 🎉
```

##Keywords
`Python, Chatbot, JSON, AI Chatbot, Python Chatbot, Learnable Chatbot, difflib, Python JSON, Simple Chatbot, Python Projects, Natural Language Processing, Python Automation, AI, Machine Learning, Chatbot Training, Python Script, Python Input, Python Output, Python NLP, Python AI, Python difflib, Chatbot with Memory, Interactive Chatbot`

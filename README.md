# OOPs_ChatBot

Sure! Here's the updated `README.md` file that incorporates the `ChatBot` launcher class, includes a spot for a screenshot image, and reflects the full structure of your chatbot application.

---

### 📘 `README.md`

```markdown
# 💬 Java ChatBot GUI - Swing Application

A simple GUI-based ChatBot built using Java Swing that simulates basic AI responses using keyword matching and random reply logic.

---

## 📦 Package Structure

This application is part of the `ChatBot` package and contains two main classes:

### 🧾 `ChatBotMain.java`
- The GUI logic and chatbot functionality
- Handles user input, text display, and response logic

### 🚀 `ChatBot.java`
- Entry point of the program
- Launches the GUI window using:
  ```java
  ChatBotMain obj = new ChatBotMain();
  obj.setTitle("ChatBot(Lord Sen)");
  obj.setVisible(true);
  ```

---

## 📸 GUI Preview

![ChatBot Screenshot](https://github.com/Lord3008/OOPs_ChatBot/blob/main/Screenshot%202025-04-20%20224651.png)

---

## 💡 Features

- Responsive UI using Java Swing (`JTextArea`, `JTextField`, `JButton`)
- Keyword-based AI with random responses
- Supports greeting, status checks, and fallback replies
- Clears screen on command (`clear screen`, `clr`, `cls`)
- Randomized answers for more natural-feeling interaction
- Fully functional via both button click and `Enter` key press

---

## 🛠 Requirements

- Java Development Kit (JDK) 8 or above
- Any Java IDE (IntelliJ, Eclipse) or terminal

---

## 🧑‍💻 How to Run

### 1. 📁 Ensure Folder Structure:

```
YourProject/
└── ChatBot/
    ├── ChatBotMain.java
    └── ChatBot.java
```

### 2. Compile the Code:

```bash
javac ChatBot/ChatBotMain.java ChatBot/ChatBot.java
```

### 3. Run the Application:

```bash
java ChatBot.ChatBot
```

---

## 🧠 Sample Interaction

```
You -> hi
AI  -> Hey, Wssup?

You -> I'm fine
AI  -> Wish, you always remain fine

You -> clear screen
[Screen is cleared]
```

---

## 🌱 Ideas for Future Enhancements

- Add scrollable message view with `JScrollPane`
- Integrate with a chatbot API (like OpenAI or Rasa)
- Add user authentication or chat history saving
- Improve NLP using external libraries (e.g., Stanford NLP, Apache OpenNLP)

---

## 🧑‍🎓 Author

Made with 💙 by Lord Sen  
[GitHub Repo](https://github.com/Lord3008/OOPs_ChatBot)

---

## 📜 License

This project is open-source and available for educational and personal use.

```

Let me know if you’d like to include:
- Build a `.jar` file guide
- Sound effects or animations
- Dynamic themes or avatars

I’d be happy to help you expand it further!

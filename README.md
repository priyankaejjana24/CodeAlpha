# AI Commercial Chatbot

- A modern, responsive, and interactive **AI-powered chatbot** built with **HTML** and **CSS**. 
- The chatbot is designed to provide real-time support, answer frequently asked questions, and guide users through products, payments, shipping, and more.


## 🚀 Features

- **AI-driven responses** based on predefined patterns and categories.
- **Admin panel** to monitor:
  - Total messages
  - Average response time
  - Response confidence
- **Settings modal** for customizing chatbot behavior:
  - Adjust response delay
  - Set confidence threshold
  - Toggle typing indicator
- **Chat interface** with:
  - Welcome message and quick suggestions
  - Emoji support
  - Character limit and input validation
  - Typing indicator animation
- **Analytics tracking** for user engagement and session history
- **Minimize/maximize chat** for seamless user experience
- **Export data**, reset chat, and train bot functionalities
- Fully **responsive design** with dark mode support



## 📂 Project Structure

```
ai-chatbot/
├── index.html        # Main chatbot interface
├── styles.css        # Styling and animation
├── README.md         # Documentation
```


## 🛠 Technologies Used

- HTML5
- CSS3 (with gradients, animations, and responsive design)
- No backend required — runs entirely in the browser



## 📥 How to Run

1. **Download or clone the repository:**
   ```bash
   git clone https://github.com/yourusername/ai-chatbot.git
   ```

2. **Open `index.html` in a web browser:**
   - Double-click the file, or
   - Serve it using a local server (`Live Server` extension in VS Code or Python's simple HTTP server):
     ```bash
     python -m http.server
     ```

3. **Start chatting!** The bot will respond based on predefined topics like greetings, products, support, shipping, and more.




## ⚙️ Customization

You can easily update the chatbot’s knowledge base inside `chatbot.js` by modifying patterns, responses, and confidence scores.


### Example:
```
this.knowledgeBase.greetings = {
    patterns: ['hello', 'hi'],
    responses: ['Hi! How can I assist you today?'],
    confidence: 0.95,
    category: 'greeting'
};
```

You can also:
- Add new categories such as promotions, feedback, etc.
- Enhance responses for better user interaction
- Connect to backend services via API if required



## 📱 Responsive and Accessible

- Fully functional on desktops, tablets, and smartphones
- Dark mode support based on user preferences
- Keyboard navigation and accessible design elements



## 📂 Future Improvements

- Integrate with real AI APIs (OpenAI, Dialogflow)
- Connect to a database for dynamic knowledge
- Add voice input/output
- Improve learning through conversation history



## 🤝 Contributing

Feel free to fork the project, submit issues, or create pull requests to improve features, styling, or functionality.


## 📜 License

This project is open source and available under the MIT License.



## 📬 Contact

**Author:** Priyanka Keerthana Ejjana  
**Email:** priyankaejjana@gmail.com  
**GitHub:** [priyankaejjana24](https://github.com/priyankaejjana24)

---

**Happy coding!** ✨🚀

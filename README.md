# HopeBot

HopeBot is a web-based chatbot application designed to provide supportive and informative responses related to mental health in India. The chatbot does not provide medical advice but helps users find mental health resources and information.

## Features
- **AI-Powered Chat**: Engages in conversations related to mental health and directs users to appropriate resources.
- **Chat History Management**: Users can save, rename, and delete chat sessions.
- **Dark Mode Toggle**: Allows users to switch between light and dark modes.
- **Local Storage Support**: Saves chat history locally for easy retrieval.
- **Keyword Filtering**: Recognizes mental health-related queries and provides appropriate responses.
- **Emergency Resources**: Directs users to helpline numbers in case of crises.

## Installation

### Prerequisites
- Web browser (Chrome, Firefox, Edge, etc.)
- Internet connection
- API key for OpenRouter AI (replace the `#` in the script with your actual API key)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/HopeBot.git
   ```
2. Navigate to the project directory:
   ```sh
   cd HopeBot
   ```
3. Open `index.html` in a web browser.

## Usage
- **Starting a New Chat**: Click the "New Chat" button to start a conversation.
- **Sending a Message**: Type a message in the input field and press "Send."
- **Managing Chat Sessions**:
  - Rename a chat session by clicking the edit button next to it.
  - Delete a chat session by clicking the delete button.
  - Clear all chat history using the "Clear Chat History" button.
- **Dark Mode**: Toggle dark mode using the moon/sun icon.

## File Structure
```
HopeBot/
├── index.html         # Main HTML file
├── style.css          # Stylesheet for UI
├── script.js         # JavaScript logic for chat functionality
├── /img/              # Folder containing images and icons
└── /LoginPage/        # Contains login-related scripts
```

## API Integration
- HopeBot uses OpenRouter AI for chat responses.
- Update the `apiKey` variable in `script.js` with your actual API key to enable AI functionality.

## Mental Health Resources
In case of emergencies, users are directed to these resources:
- **Aasra**: 022-27546669 (24x7 helpline)
- **Vandrevala Foundation**: 9999666555 (24x7 helpline)
- **National Suicide Prevention Lifeline**: 988 (US-based, but can offer international support)

## Contributing
If you'd like to contribute to HopeBot, follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add new feature"`).
4. Push the changes (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contact
For questions or support, please contact **ritesh.kumar.cs28@iilm.edu**.


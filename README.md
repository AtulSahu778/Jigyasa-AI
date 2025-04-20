# Jigyasa AI Chatbot

## Overview

Jigyasa AI is a responsive, modern chatbot interface powered by Google's Gemini 2.0 Flash API. This application provides an intuitive interface for users to interact with AI, allowing them to send text queries and upload files for analysis.

## Features

- 💬 **AI-Powered Conversations**: Utilizes Google's Gemini 2.0 Flash API for intelligent responses
- 📂 **File Support**: Upload and analyze images, PDFs, TXT, and CSV files
- 🌓 **Dark/Light Theme**: Toggle between dark and light modes with automatic preference saving
- 📱 **Fully Responsive**: Optimized for all screen sizes from desktop to mobile devices
- ⚡ **Quick Suggestions**: Pre-defined prompts to get started instantly
- ⏹️ **Stop Generation**: Ability to stop AI response generation at any time
- 🔄 **Chat History**: View previous conversations in the session

## Live Demo

[View Live Demo](https://ai-jigyasa.vercel.app/) 

## Screenshots

<!-- Add screenshots of your application here -->

## Tech Stack

- **HTML5**: Semantic structure for the chat interface
- **CSS3**: Custom styling with CSS variables for theming
- **JavaScript**: Vanilla JS for all interactions and API integration
- **Google Gemini API**: AI backend for natural language processing

## Getting Started

### Prerequisites

- Web browser (Chrome, Firefox, Safari, Edge recommended)
- API key for Google's Gemini AI

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/AtulSahu778/jigyasa-ai.git
   cd jigyasa-ai
   ```

2. Replace the API key in `ai.js`
   ```javascript
   const API_KEY = "YOUR_GEMINI_API_KEY";
   ```

3. Open `index.html` in your browser or use a local server
   ```bash
   # If you have Python installed
   python -m http.server
   # Then open http://localhost:8000 in your browser
   ```

## How to Use

1. **Starting a Conversation**: Type your question in the input box at the bottom and press Enter or click the send button
2. **Using Suggestions**: Click on any suggestion card to quickly ask common questions
3. **Uploading Files**: Click the paperclip icon to upload images or documents for AI analysis
4. **Toggle Theme**: Click the theme icon to switch between dark and light modes
5. **Reset Conversation**: Click the delete icon to clear the current conversation history

## Project Structure

```
jigyasa-ai/
├── index.html        # Main HTML structure
├── style.css         # CSS styling and responsive design
├── ai.js             # JavaScript for chat functionality and API integration
└── gemini-chatbot-logo.svg  # Logo/avatar for the chatbot
```

## API Integration

The chatbot integrates with Google's Generative Language API (Gemini). The API is called when a user submits a message, with the response then being displayed with a typing effect for a more natural experience.

```javascript
const API_URL = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${API_KEY}`
```

## Responsive Design

The interface is built with a mobile-first approach, featuring:

- Fluid typography that scales based on device size
- Adaptable layout for screens as small as 320px
- Touch-friendly controls for mobile users
- Optimized scrolling for suggestion cards on small screens

## Future Enhancements

- Voice input capability
- Persistent chat history across sessions
- Export conversation feature
- Image generation capabilities
- Custom user preferences

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Google Gemini API for powering the AI functionality
- Material Symbols for the icon set
- Poppins and Roboto fonts from Google Fonts

---

Created with ❤️ by [AtulSahu778](https://github.com/AtulSahu778)

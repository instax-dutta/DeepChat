# DeepChat - OpenRouter Web Interface for DeepSeek Chat

A sleek, single-page web interface for interacting with DeepSeek Chat (deepseek/deepseek-chat-v3-0324:free) through OpenRouter API.

## Features

- 💬 Clean, modern chat interface with dark theme
- 🔒 Secure API key storage in browser localStorage
- 📝 Persistent chat history across sessions
- ✨ Markdown-style formatting support (bold, code blocks)
- 🚀 Direct integration with OpenRouter API
- 🧠 Powered by deepseek/deepseek-chat-v3-0324:free model
- 📱 Responsive design that works on mobile and desktop
- 🎨 Fun animations and visual effects

## Quick Start

1. **Download the project**  
   Simply download the `index.html` file to your computer.

2. **Open in browser**  
   Double-click the file to open it in your default browser.

3. **Enter your OpenRouter API key**  
   Get your API key from [OpenRouter](https://openrouter.ai/) and enter it in the input field at the top.

4. **Start chatting!**  
   Type your message and press Enter to send.

## Requirements

- Modern web browser (Chrome, Firefox, Edge, Safari)
- OpenRouter API key (free tier available)

## Configuration

The app automatically saves these in your browser's localStorage:

- **API Key**: Your OpenRouter API key
- **Chat History**: All your conversation messages

To clear these:
- Click the "Clear Chat" button to remove chat history
- Delete the API key field contents and click "Save Key"

## Development

This is a standalone HTML file with embedded CSS and JavaScript. No build system or dependencies required.

### Customizing

You can easily modify:
- Colors in the `:root` CSS variables
- Model parameters in the `fetch` request (temperature, max_tokens)
- UI elements by editing the HTML/CSS

## License

MIT License

```
Copyright (c) 2025 DeepChat

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Contributing

Contributions are welcome! Since this is a single-file project, please:

1. Fork the repository
2. Make your changes to index.html
3. Submit a pull request with a clear description of changes

## Support

For issues or questions, please open an issue on GitHub.

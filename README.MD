# Structured Prompt Builder

A modern, browser-based tool for crafting **structured AI prompts** with a beautiful minimal UI inspired by Claude.ai. Features live preview in multiple formats, persistent library storage, and direct testing with **OpenRouter AI models**.

> **Support Development**  
> If this tool saves you time, consider sponsoring to help maintain and add new features.  
> **👉 [Become a sponsor](https://github.com/sponsors/Siddhesh2377)**

[![Sponsor](https://img.shields.io/badge/Sponsor-@Siddhesh2377-ea4aaa?logo=githubsponsors&logoColor=white)](https://github.com/sponsors/Siddhesh2377)
[![GitHub Stars](https://img.shields.io/github/stars/Siddhesh2377/structured-prompt-builder?style=social)](https://github.com/Siddhesh2377/structured-prompt-builder)

## ✨ Features

### Core Functionality
- **Structured Fields**: Title, Role, Task, Context with organized input sections
- **Dynamic Lists**: Add/remove Constraints and Examples with intuitive controls
- **Live Preview**: Real-time updates in JSON, Markdown, and Plain Text formats
- **Built-in Editors**: Directly edit exported content in any format
- **Local Library**: Save, load, and delete prompts with persistent browser storage

### AI Testing
- **OpenRouter Integration**: Test prompts with 100+ AI models
- **Dynamic Model Loading**: Fetches available models directly from OpenRouter API
- **Advanced Parameters**: 
  - Temperature (0-2) - Control creativity
  - Max Tokens - Set response length
  - Top P - Nucleus sampling
  - Top K - Token selection limit
  - Frequency Penalty - Reduce repetition
  - Presence Penalty - Encourage new topics
  - Streaming Responses - Real-time output
  - JSON Mode - Structured outputs
- **Token Usage Stats**: Monitor prompt and completion tokens

### Design & UX
- **5 Beautiful Themes**: 
  - Default (Light/Dark split)
  - Dark Slate
  - Dark Midnight
  - Light Warm
  - Light Cool
- **Smooth Animations**: Subtle transitions and hover effects throughout
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile
- **Sample Prompts**: Pre-filled examples to get started quickly

## 🚀 Quick Start

### No Build Required

1. **Clone the repository**
   ```bash
   git clone https://github.com/Siddhesh2377/structured-prompt-builder.git
   cd structured-prompt-builder
   ```

2. **Open in browser**

   Simply open `index.html` in your browser, or use a local server:
   ```bash
   npx serve .
   ```

3. **Get an OpenRouter API Key**
    - Visit [OpenRouter](https://openrouter.ai/)
    - Sign up and get your API key
    - Enter it in the app (stored securely in your browser)

## 📖 Usage Guide

### Building a Prompt

1. **Fill Basic Information**
    - Enter a title for your prompt
    - Define the AI's role (e.g., "Expert technical writer")
    - Describe the main task
    - Add relevant context

2. **Add Constraints**
    - Click "Add" to create rules the AI must follow
    - Use the up/down arrows to reorder
    - Remove unwanted items with the × button

3. **Provide Examples**
    - Add input/output examples for few-shot learning
    - Format: "Input: ... → Output: ..."

4. **Preview & Edit**
    - Switch between JSON, Markdown, and Plain Text formats
    - Click in the editor to make direct changes
    - Copy the formatted output

### Saving & Loading

1. **Save to Library**
    - Click "Save to Library" to store your prompt
    - Prompts are saved in your browser's localStorage
    - No account or internet connection needed

2. **Load Sample**
    - Click "Load Sample" to see a pre-filled example
    - Great for understanding the structure

3. **Manage Library**
    - View all saved prompts below the form
    - Load any prompt with one click
    - Delete prompts you no longer need

### Testing with AI

1. **Enter API Key**
    - Paste your OpenRouter API key
    - It's saved automatically for future sessions
    - The key never leaves your browser except to call OpenRouter

2. **Select Model**
    - Models load automatically after entering your key
    - Popular models appear first (Claude, GPT-4, Gemini, Llama)
    - All OpenRouter models available in alphabetical order

3. **Configure Parameters** (Optional)
    - Click "Advanced Settings" to reveal parameters
    - Adjust temperature, max tokens, penalties, etc.
    - Enable streaming for real-time responses
    - Turn on JSON mode for structured outputs

4. **Test Your Prompt**
    - Enter test input in the text area
    - Click "Test Prompt"
    - View AI response with token usage statistics

## 🎨 Themes

Switch between 5 carefully designed themes using the color circles in the header:
- **Default**: Classic light theme with dark mode hint
- **Dark Slate**: Professional blue-gray dark theme
- **Dark Midnight**: Pure black theme for OLED displays
- **Light Warm**: Cozy amber-tinted light theme
- **Light Cool**: Fresh sky-blue light theme

Your theme choice persists across sessions.

## 🏗️ Project Structure

```
structured-prompt-builder/
├── index.html              # Main entry point
├── changelog.html          # Version history
├── public/
│   ├── favicon.ico
│   ├── robots.txt
│   └── sitemap.xml
└── README.md
```

## 🔒 Privacy & Security

- **No Backend**: Everything runs in your browser
- **Local Storage**: All prompts saved to browser localStorage
- **API Keys**: Stored locally, only sent to OpenRouter
- **No Tracking**: No analytics or third-party scripts
- **Open Source**: Full transparency, audit the code yourself

## 🛣️ Roadmap

Future enhancements under consideration:
- [ ] Export/Import prompt collections
- [ ] Prompt versioning and change history
- [ ] Collaborative prompt sharing (opt-in)
- [ ] Custom parameter presets
- [ ] Prompt templates marketplace
- [ ] Multi-model comparison testing
- [ ] Cost estimation per request

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Report Bugs**: Open an issue with details and steps to reproduce
2. **Suggest Features**: Share your ideas in the discussions
3. **Submit PRs**: Fork, create a branch, make changes, and submit
4. **Improve Docs**: Help make the documentation clearer

### Development Guidelines
- Keep the no-build philosophy (vanilla JS/React UMD)
- Maintain the minimal, clean aesthetic
- Ensure mobile responsiveness
- Add comments for complex logic
- Test across browsers (Chrome, Firefox, Safari)

## 📜 License

MIT License - See [LICENSE](LICENSE) for details.

## 🙏 Acknowledgments

- Design inspired by Claude.ai's minimal interface
- Icons from Lucide icon set
- Powered by OpenRouter for AI model access
- Built with React and vanilla JavaScript

---

**Made with ❤️ by [Siddhesh2377](https://github.com/Siddhesh2377)**

If this project helps you, please consider [⭐ starring it on GitHub](https://github.com/Siddhesh2377/structured-prompt-builder) and [💝 sponsoring development](https://github.com/sponsors/Siddhesh2377)!

![Star History Chart](https://api.star-history.com/svg?repos=Siddhesh2377/structured-prompt-builder&type=Date)
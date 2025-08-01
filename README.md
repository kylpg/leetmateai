# LeetMate 🤖

> Your AI companion for coding interviews and LeetCode practice

LeetMate is a Chrome browser extension that provides AI-powered hints and code analysis directly on LeetCode problem pages, helping you improve your coding skills and interview preparation.

## ✨ Features

- 🤖 **Multi-AI Provider Support**: OpenRouter, OpenAI, Anthropic Claude, Google Gemini
- 💡 **Smart Hints**: Interview-style guidance without giving away solutions
- 🔍 **Code Analysis**: Intelligent error detection and improvement suggestions
- 🎯 **Seamless Integration**: Non-intrusive resizable sidebar on LeetCode
- 🔒 **Privacy-First**: API keys stored locally, no data collection
- ⚡ **Real-time**: Instant AI assistance while solving problems

## 🚀 Installation

### From Chrome Web Store
1. Visit the [Chrome Web Store](https://chrome.google.com/webstore) (link coming soon)
2. Search for "LeetMate"
3. Click "Add to Chrome"

### Developer Installation
1. Download the latest release
2. Open Chrome → Extensions → Developer mode
3. Load unpacked → Select the extension folder

## 🛠️ Setup

1. Click the LeetMate extension icon
2. Choose your preferred AI provider
3. Add your API key:
   - **OpenRouter**: [Get free API key](https://openrouter.ai/keys)
   - **OpenAI**: [Get API key](https://platform.openai.com/api-keys)
   - **Anthropic**: [Get API key](https://console.anthropic.com/account/keys)
   - **Google**: [Get API key](https://aistudio.google.com/app/apikey)
4. Start solving LeetCode problems with AI assistance!

## 📖 How to Use

1. Navigate to any LeetCode problem page
2. The LeetMate sidebar will appear on the right
3. Click **"Get Hint"** for guidance or **"Analyze Code"** for debugging
4. Resize the sidebar by dragging the left edge
5. Learn and improve with AI-powered assistance!

## Project Structure

```
src/
├── types.ts              # TypeScript type definitions
├── pageRecognition.ts    # LeetCode page detection and data extraction
├── storage.ts            # User progress tracking
├── background.ts         # Extension background script with AI API
├── content.ts            # Content script that injects the UI
├── popup.tsx             # Extension popup for configuration
└── ui/
    └── FloatingPanel.tsx # Main floating UI component
```

## Development

```bash
# Install dependencies
npm install

# Build for development (with watch mode)
npm run dev

# Build for production
npm run build

# Run tests
npm test
```

## Tech Stack

- **TypeScript** - Type-safe development
- **React** - UI components
- **Webpack** - Bundling and build process
- **Chrome Extension Manifest V3** - Modern extension APIs
- **OpenRouter API** - AI model access (DeepSeek free tier)

## API Configuration

The extension uses OpenRouter's API with the `deepseek/deepseek-r1-0528:free` model. This provides:
- Free usage tier
- Good performance for coding assistance
- No rate limits for basic usage

## 🔒 Privacy & Security

- ✅ **No data collection**: We don't collect or store personal information
- ✅ **Local storage**: API keys stored securely on your device only
- ✅ **User control**: You choose what data to send to AI providers
- ✅ **Security audited**: Comprehensive security review completed
- ✅ **Open source**: Code available for review (private repository)

### Data Usage
- **Problem data**: Title, description, difficulty (public LeetCode content)
- **Your code**: Only sent to your chosen AI provider when using features
- **API keys**: Stored locally using Chrome's secure storage
- **No tracking**: No analytics, cookies, or user behavior monitoring

## 📋 Legal Disclaimers

### ⚠️ Important Notice
**LeetMate is a third-party browser extension not affiliated with LeetCode.** Use of this extension is subject to LeetCode's Terms of Service. Users are solely responsible for compliance with all applicable terms and policies.

### Terms of Use
By using LeetMate, you agree to:
- Use the extension responsibly and ethically for learning purposes
- Comply with LeetCode's Terms of Service
- Comply with your chosen AI provider's terms and policies
- Not violate any platform policies or academic integrity rules

### AI Provider Terms
Review the terms of service for your chosen AI provider:
- [OpenRouter Terms](https://openrouter.ai/terms)
- [OpenAI Terms](https://openai.com/policies/terms-of-use/)
- [Anthropic Terms](https://www.anthropic.com/terms)
- [Google AI Terms](https://ai.google.dev/gemini-api/terms)

### Warranty Disclaimer
LeetMate is provided "as is" without warranty of any kind. We make no guarantees about the accuracy, reliability, or effectiveness of AI-generated hints or analysis.

### User Responsibility
Users are responsible for:
- Obtaining proper AI provider API keys and complying with their terms
- Ensuring compliance with LeetCode's Terms of Service
- Using the extension ethically for learning and skill development
- Not using the extension to violate academic integrity or platform policies

## 🤝 Contributing

This is a private repository. If you'd like to contribute or report issues:
- Email: leetmate.ai@gmail.com
- Create detailed bug reports with steps to reproduce
- Suggest features with clear use cases

## 📄 License

Copyright (c) 2025 LeetMate™. All rights reserved.

This software is proprietary and confidential. Unauthorized copying, distribution, or use is strictly prohibited.

## 🔗 Links

- **Chrome Web Store**: Coming soon
- **Privacy Policy**: See [PRIVACY.md](./PRIVACY.md)
- **Legal Disclaimers**: See [LEGAL_DISCLAIMERS.md](./LEGAL_DISCLAIMERS.md)
- **Support**: leetmate.ai@gmail.com

## 📊 Stats

- **Version**: 1.0.0
- **Security Review**: ✅ Passed
- **Legal Review**: ✅ Approved
- **Chrome Web Store**: Ready for submission

---

**Made with ❤️ for the coding community**

*LeetMate helps you learn and grow as a developer. Use it responsibly and ethically to enhance your coding journey.*

## 🙏 Acknowledgments

- LeetCode for providing an excellent platform for coding practice
- AI providers for making advanced language models accessible
- The coding community for inspiration and feedback

---

### 📞 Support & Contact

For support, feature requests, or legal inquiries:
- **Email**: leetmate.ai@gmail.com
- **Issues**: This is a private repository - contact via email
- **Response time**: Within 24-48 hours

**Happy coding! 🚀**
# leetmateai

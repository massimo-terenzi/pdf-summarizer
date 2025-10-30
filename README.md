# 📄 PDF Summarizer with GPT

A client-side web application that uses OpenAI's GPT models to summarize long PDF documents. Extract text from PDFs and generate intelligent summaries in multiple languages with customizable length options.

![PDF Summarizer](https://img.shields.io/badge/OpenAI-GPT--4o-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

- 📱 **Client-side processing** - Your API key never leaves your browser
- 🌍 **12 languages supported** - Output summaries in English, Italian, Spanish, French, German, Portuguese, Dutch, Russian, Chinese, Japanese, Korean, or Arabic
- 📏 **Customizable length** - Choose from Brief, Moderate, Detailed, or Comprehensive summaries
- ⛔ **Stop functionality** - Cancel processing at any time and get partial results
- 💾 **Multiple export formats** - Save as TXT, Markdown, or JSON
- 📊 **Cost estimation** - See estimated costs before processing
- 🎨 **Modern UI** - Clean, responsive interface

## 🚀 Quick Start

### Option 1: Use Online (Recommended)

Visit: **[https://massimo-terenzi.github.io/pdf-summarizer-gpt/](https://massimo-terenzi.github.io/pdf-summarizer-gpt/)**

### Option 2: Run Locally

1. Clone this repository:
```bash
git clone https://github.com/massimo-terenzi/pdf-summarizer-gpt.git
cd pdf-summarizer-gpt
```

2. Open `index.html` in your browser

That's it! No installation or build process required.

## 🔑 Setup

1. Get your OpenAI API key from [platform.openai.com](https://platform.openai.com/api-keys)
2. Enter your API key in the application
3. Select your preferred model (GPT-4o recommended)
4. Upload a PDF and start summarizing!

## 💰 Cost Estimates

Approximate costs for a 300-page PDF (~150k tokens):

| Model | Brief | Moderate | Detailed | Comprehensive |
|-------|-------|----------|----------|---------------|
| **GPT-4o** | $0.50 | $1.20 | $2.50 | $5.00 |
| **GPT-4o Mini** | $0.03 | $0.07 | $0.15 | $0.30 |
| **GPT-3.5 Turbo** | $0.10 | $0.25 | $0.50 | $1.00 |

## 🎯 Summary Length Options

- **Brief** (~200-400 words) - Quick overview with essential information
- **Moderate** (~500-1000 words) - Balanced coverage of main points
- **Detailed** (~1000-2000 words) - Comprehensive with methodology and findings
- **Comprehensive** (~2000-4000 words) - Extensive analysis with all nuances

## 🌍 Supported Languages

English, Italiano, Español, Français, Deutsch, Português, Nederlands, Русский, 中文, 日本語, 한국어, العربية

## 🛠️ Technical Details

- **PDF Processing**: PDF.js for text extraction
- **API**: OpenAI Chat Completions API
- **Chunking**: Smart paragraph-based splitting
- **No Backend**: Runs entirely in the browser
- **Privacy**: API key stored only in localStorage

## 📋 Use Cases

- Academic research paper summaries
- Legal document analysis
- Business report synthesis
- Technical documentation overview
- Book chapter summaries
- Policy document analysis

## 🔒 Privacy & Security

- Your API key is stored only in your browser's localStorage
- No data is sent to any server except OpenAI's API
- All processing happens client-side
- You maintain full control of your documents

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- OpenAI for GPT models
- Mozilla for PDF.js library
- Inspired by the need for efficient academic paper analysis

## ⚠️ Disclaimer

This tool uses OpenAI's API which incurs costs. Please monitor your usage and set appropriate limits in your OpenAI account.

## 📧 Contact

Your Name - [@your_twitter](https://twitter.com/your_twitter)

Project Link: [https://github.com/massimo-terenzi/pdf-summarizer-gpt](https://github.com/massimo-terenzi/pdf-summarizer-gpt)

---

⭐ Star this repo if you find it useful!
```

**3. `LICENSE`** - File di licenza MIT:
```
MIT License

Copyright (c) 2025 [Your Name]

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

**4. `.gitignore`** - Per ignorare file non necessari:
```
# OS files
.DS_Store
Thumbs.db

# Editor files
.vscode/
.idea/
*.swp
*.swo

# Logs
*.log

# Test files
test.pdf

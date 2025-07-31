---
title: Text Summarization App
emoji: 📝
colorFrom: blue
colorTo: green
sdk: gradio
sdk_version: 4.44.0
app_file: app.py
pinned: false
license: cc0-1.0
short_description: AI-powered text summarization using Hugging Face's default model
---

# Text Summarization App

A simple and efficient AI-powered text summarization tool that transforms long text passages into concise, meaningful summaries.

## 🚀 Features

- **Smart Summarization**: Uses Hugging Face's default summarization model for high-quality text compression
- **Instant Results**: Real-time processing with immediate feedback
- **User-Friendly Interface**: Clean, intuitive design built with Gradio
- **No Setup Required**: Ready to use directly in your browser

## 🛠️ How It Works

1. **Input**: Paste or type your text in the input box
2. **Process**: The AI model analyzes and extracts key information
3. **Output**: Get a concise summary that captures the essence of your text

## 📊 Model Information

This app uses Hugging Face's default summarization model via `pipeline("summarization")`:
- **Auto-Selected Model**: Automatically chooses the best available summarization model
- **Current Default**: sshleifer/distilbart-cnn-12-6 (DistilBART)
- **Training Data**: CNN/DailyMail dataset
- **Optimization**: Balanced for speed and quality
- **Best For**: News articles, blog posts, reports, and formal text

## 💡 Usage Tips

- **Optimal Input**: Works best with 50+ words of coherent text
- **Content Types**: Most effective with news articles, academic papers, and structured content
- **Length**: Can handle various input lengths, automatically adjusts summary length

## 🔧 Technical Stack

- **Model**: Hugging Face Transformers
- **Interface**: Gradio
- **Backend**: PyTorch
- **Deployment**: Hugging Face Spaces

## 📈 Performance

- **Speed**: Fast inference optimized for real-time use
- **Quality**: Maintains key information while reducing length
- **Reliability**: Consistent results across different text types

## 🤝 Contributing

This project is open source! Feel free to:
- Report issues
- Suggest improvements
- Submit pull requests

**Repository**: [GitHub Link](https://github.com/MohamedMoustafa-UoG/HF-text-summarization-app)

## 📄 License

CC0 1.0 Universal

---

*Built with ❤️ using Hugging Face Transformers and Gradio*

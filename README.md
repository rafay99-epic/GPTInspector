# 🚀 GPTInspector - Human vs AI Text Detection

[![MIT License](https://img.shields.io/badge/license-MIT-green)](https://opensource.org/licenses/MIT)
[![NodeJS](https://img.shields.io/badge/Node.js-22.0-green.svg?style=flat-square&logo=node.js)](https://nodejs.org/)

👋 Welcome to **GPTInspector**, a simple tool to detect whether the text is written by a human 🧑 or generated by AI 🤖. This project uses the powerful [ChatGPT Detector RoBERTa model](https://huggingface.co/Hello-SimpleAI/chatgpt-detector-roberta) from Hugging Face, integrated through API calls and built with JavaScript, EJS, and Node.js.

## 🌟 Features

- 🌍 **Detect AI-Generated Text**: Quickly analyze if a text was produced by a human or AI.
- 📡 **Hugging Face API**: Leverages Hugging Face's state-of-the-art ChatGPT Detector.
- 💻 **User-friendly Interface**: Powered by EJS templating engine for dynamic and responsive UI.
- ⚡️ **Fast and Efficient**: Lightning-fast detection process with a simple API call.

## 🚧 How It Works

1. 📝 **Submit Text**: Enter a piece of text you want to analyze.
2. 🔍 **Detection**: The text is sent to the Hugging Face model through an API call.
3. 🧑‍🤝‍🧑 **Results**: The app tells you if the text is AI-generated or human-written based on model predictions.

## 🔧 Tech Stack

- **JavaScript**: Core programming language for the application.
- **Node.js**: Backend server runtime.
- **EJS**: Templating engine for dynamic rendering.
- **Express.js**: Web framework for Node.js.
- **Hugging Face API**: AI model integration.

## 🚀 Quick Start

1. **Clone the repository**:

   ```bash
   git clone https://github.com/rafay99-epic/GPTInspector.git
   cd GPTInspector
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Create your API key** from Hugging Face and add it to your environment variables:

   ```bash
   export HUGGINGFACE_API_KEY=your_api_key_here
   ```

4. **Run the app**:

   ```bash
   npm start
   ```

5. **Visit** the app in your browser at:

   ```bash
   http://localhost:1313
   ```

## ⚙️ Configuration

Make sure to configure your Hugging Face API key in the environment. You can set this up in a `.env` file:

```bash
HUGGINGFACE_API_KEY=your_api_key_here
```

## 📂 Project Structure

```bash
📦 GPTInspector
├── 📁 public              # Static files (CSS, images)
├── 📁 views               # EJS templates for the frontend
├── 📄 app.js              # Main Node.js application
├── 📄 package.json        # Project dependencies
├── 📄 .env                # Environment variables
└── 📄 README.md           # Project documentation
```

## 🤝 Contributing

Feel free to submit issues or pull requests. Let's make this project even better! 🎉

## 🛡️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💡 Inspiration

Inspired by the need for better understanding of AI-generated content in the growing world of NLP and generative AI. Special thanks to [Hugging Face](https://huggingface.co) for their incredible models!

## 📬 Contact

If you have any questions or feedback, feel free to reach out:

- **GitHub**: [rafay99-epic](https://github.com/rafay99-epic)
- **Email**: [99marafay@gmail.com](mailto:99marafay@gmail.com)
- **Website**: [rafay99.com](https://www.rafay99.com/contact-me/)

---

Enjoy using GPTInspector! 😊

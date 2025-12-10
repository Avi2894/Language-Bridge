# LanguageBridge 🌉

**LanguageBridge** is a modern React and Tailwind CSS web application designed for seamless transcription and translation using state-of-the-art AI models.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Avi2894/language-bridge)

> 🚀 **[Quick Start Guide](QUICKSTART.md)** - Deploy in 5 minutes!

## Features
- **Audio Transcription:** Converts speech to text using advanced Whisper models
- **Multi-language Translation:** Translates text between 200+ languages with high accuracy
- **Real-time Recording:** Record audio directly in your browser
- **File Upload:** Support for MP3 and WAV audio files
- **Modern UI:** Beautiful, responsive design with smooth animations

## AI Models

**Transcription:** Whisper Large V3 Turbo (OpenAI) via Groq API  
**Translation:** Llama 3.1 8B Instant (Meta) via Groq API

**Benefits:**
- ⚡ **Instant processing** - No model downloads, works immediately
- 🎯 **Best accuracy** - State-of-the-art models for both tasks
- 🆓 **Free tier** - Generous Groq API limits (30 req/min)
- 🚀 **Lightning fast** - Groq is optimized for speed
- 🔒 **One API key** - Same key for transcription and translation

## How It Works

**Transcription:**
1. Audio is processed in your browser
2. Sent to Groq API using your key
3. Whisper Large V3 Turbo transcribes
4. Results in 2-5 seconds

**Translation:**
1. Transcribed text sent to Groq API
2. Llama 3.1 8B Instant translates
3. Supports 50+ languages
4. Results in 1-3 seconds

**Privacy**: Your API key is stored locally in your browser only.

## Quick Start

1. **Get Free Groq API Key** (No credit card required!)
   - Visit [console.groq.com/keys](https://console.groq.com/keys)
   - Sign up and create an API key
   - Copy the key (starts with `gsk_...`)

2. **Use the App**
   - Open LanguageBridge
   - Click "Set API Key" button
   - Paste your Groq API key
   - Start transcribing instantly!

## Deploy

Deploy to any static hosting service:

**Vercel:**
```bash
npm run build
vercel --prod
```

**Netlify:**
```bash
npm run build
netlify deploy --prod --dir=dist
```

**GitHub Pages / Cloudflare Pages:**
- Just push to your repo
- Configure build command: `npm run build`
- Configure output directory: `dist`

No environment variables or backend needed!

## Local Development

### Prerequisites
- **Node.js** (v16 or higher)
- **Groq API Key** (free from [console.groq.com](https://console.groq.com))

### Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/Avi2894/language-bridge
    ```
2. **Navigate to the project directory:**
    ```bash
    cd language-bridge
    ```
3. **Install dependencies:**
    ```bash
    npm install
    ```
4. **Start development server:**
    ```bash
    npm run dev
    ```
5. **Open browser:**
    - Visit `http://localhost:5173`
    - Click "Set API Key" and enter your Groq API key
    - Start transcribing!

### Building for Production
To create a production build:
```bash
npm run build
```

The build output will be in the `dist` folder.

## Deployment

### Quick Deploy to Vercel
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/Avi2894/language-bridge)

Or follow the detailed [Deployment Guide](DEPLOYMENT.md) for step-by-step instructions.

## Contributing
We welcome contributions! Feel free to submit issues and pull requests.

## License
This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.

## Contact
Built with ❤️ by Avinash Ghodke

For questions or inquiries, reach out via GitHub: [@Avi2894](https://github.com/Avi2894)
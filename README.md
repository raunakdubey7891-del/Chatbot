<div align="center">

# 🎓 CampusBuddy

### A free, private AI assistant for students, running entirely in your browser.

No server · No API key · No usage limits

[**Live Demo →**](https://chatbot-beta-rose-99.vercel.app)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WebLLM](https://img.shields.io/badge/WebLLM-4F46E5?style=flat-square)
![WebGPU](https://img.shields.io/badge/WebGPU-005A9C?style=flat-square&logo=webgl&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</div>

---

## ✨ Overview

CampusBuddy is an open-source AI chat that runs the language model **directly on your device** using [WebLLM](https://github.com/mlc-ai/web-llm) and WebGPU. Your conversations never leave your browser, and there is no backend to maintain or API bill to pay.

Ask it about study tips, concept explanations, exam planning, coding, careers and campus life.

## 🚀 Features

| | |
|---|---|
| 🔒 **Private by design** | All inference happens locally, with no data sent to a server |
| 💸 **Free & unlimited** | No API keys, quotas or subscriptions |
| ⚡ **Two model options** | Switch between a fast model and a smarter one |
| 💬 **Streaming replies** | Responses appear token by token as they're generated |
| 📦 **Cached after first load** | The model downloads once, then loads quickly |
| 🌗 **Light & dark mode** | Follows your system theme automatically |
| 📱 **Responsive layout** | Clean chat UI that adapts to any screen |

## 🧠 Models

| Option | Model | Best for |
|---|---|---|
| **Fast (small)** | SmolLM2-360M-Instruct | Quick responses on modest hardware |
| **Smarter (1.5B)** *(default)* | Qwen2.5-1.5B-Instruct | Better reasoning and answers |

## ⚡ Getting Started

```bash
# Clone the repository
git clone https://github.com/raunakdubey7891-del/Chatbot.git
cd Chatbot

# Serve locally (ES modules need a server, not file://)
npx serve .
```

Open the local URL in a **WebGPU-enabled browser** (Chrome, Edge or Brave on desktop). The first visit downloads the model, so keep the tab open until the progress bar completes.

## 🎛️ Customize

Everything lives in `index.html`:

- **Persona:** edit the `SYSTEM` prompt to change how CampusBuddy behaves
- **Models:** add or swap entries in the `#model` dropdown using any model ID from the [WebLLM model list](https://github.com/mlc-ai/web-llm)

## 📁 Project Structure

```
Chatbot/
├── index.html    # UI and chat logic
└── style.css     # Styling
```

## ⚠️ Requirements

- A browser with **WebGPU** support (recent Chrome, Edge or Brave)
- A laptop or desktop is recommended; mobile support depends on the device and browser
- A one-time model download on first use

## 🤝 Contributing

Contributions, issues and feature requests are welcome. Feel free to open an issue or submit a pull request.

---

<div align="center">

Built with ❤️ by [Raunak Dubey](https://github.com/raunakdubey7891-del)

</div>

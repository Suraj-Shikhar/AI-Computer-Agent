# 🖥️ AI Desktop Assistant

A self-hosted desktop application that gives AI control over your computer, enabling automation of tasks via mouse and keyboard. Built with Python and PyQt, it utilizes Anthropic's [computer use](https://www.anthropic.com/news/3-5-models-and-computer-use) capabilities.

## 🎯 Features

- Automate tasks such as browsing, coding, and more.
- Cross-platform: Runs on macOS, Windows, Linux, and any Python-supported environment.

## ⚠️ Disclaimers

1. **Experimental Software**: AI controls your system, so monitor actions carefully.
2. **Privacy Notice**: Anthropic may capture screenshots. Avoid sharing sensitive data.

## 🛠️ Setup

1. Obtain an Anthropic API key from [here](https://console.anthropic.com/dashboard).
2. Install and run the application:
   ```bash
   # Python 3.10+ recommended
   python -m venv venv
   source venv/bin/activate  # or `venv\Scripts\activate` on Windows
   pip install -r requirements.txt
   
   # Add API key to .env
   echo "ANTHROPIC_API_KEY=your-key-here" > .env

   # Run the application
   python run.py

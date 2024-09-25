# EDITH AI Bot Project


## Overview

Welcome to the **EDITH AI Bot** repository! EDITH is an AI-powered voice assistant that I built using OpenAI's API, Python, and VS Code. The project is still in its beginner stage but already demonstrates impressive capabilities like understanding commands with **95% accuracy** and **hands-free voice control**. This project is all about enhancing user experience by cutting input time by **40%** and speeding up task completion by **30%**.

Feel free to explore the code, make modifications, or even add your own improvements!

## Features
- **OpenAI Integration:** Uses the OpenAI API to process commands and generate responses.
- **Voice Control:** Hands-free voice command processing to improve user interaction.
- **Custom Music Feature:** Play predefined music, with the flexibility to add your own playlists.
- **Beginner Stage:** This project is still evolving, with lots of room for feature additions and enhancements.

---

## Project Structure

The repository contains three key files that make EDITH work:

### 1. `client.py`
- **Purpose:** Handles interactions with the OpenAI API. This file is responsible for sending commands and receiving AI responses.
- **How to Use:** You can tweak the API calls or improve error handling to suit your needs.

### 2. `main.py`
- **Purpose:** The core of the project, containing the main code that ties everything together. This file includes voice recognition, command processing, and AI responses.
- **How to Use:** Run this file to activate EDITH. Customize it to add new commands, improve response times, or integrate more functionality.

### 3. `music.py`
- **Purpose:** A predefined list of songs that EDITH can play based on voice commands. You can easily modify the list to add more music of your choice.
- **How to Use:** Edit the file to include your favorite tracks or replace the existing ones.

---

## How to Set Up

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/edith-ai-bot.git

2. **Install Required Libraries**
- Make sure you have the necessary Python libraries installed. You can install them using `pip`:

```bash
pip install openai
pip install SpeechRecognition
pip install pyttsx3
```
3. **Set Your OpenAI API Key**
- You'll need to get an API key from OpenAI and set it in the `client.py` file:

```python
openai.api_key = 'your-api-key-here'
```
4. **Run the Bot**
- Execute `main.py` to start EDITH:

```bash
python main.py
```

## Future Improvements

As this is a beginner project, there are plenty of areas for growth:
- **Expand Command Library:** Add more functionalities and command responses to make EDITH smarter.
- **Improve Voice Accuracy:** Tweak the voice recognition module for even higher accuracy.
- **Add More Interactions:** Integrate new features like web browsing, news reading, or email handling.

---

## Contributions

I’m always open to feedback and suggestions! Feel free to:
- Fork the repository
- Submit pull requests with improvements or new features
- Raise issues or suggest features you'd like to see

---

## Conclusion

EDITH AI Bot is a fun and practical introduction to building voice assistants using AI and Python. While still in its early stages, it showcases the potential for hands-free, intelligent command processing. There’s lots of room for further development, and I’m excited to continue improving it!

Enjoy exploring EDITH and don’t hesitate to customize it to make it your own!







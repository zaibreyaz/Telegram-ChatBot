# Telegram-ChatBot
Telegram ChatBot using OPENAI chatGPT-3.5-turbo LLM Model

### Requirements:
- Python 3.7
- A Telegram Account
- An OpenAI account for API Key
### How to Run:
```
conda create -n Telegram-ChatBot python==3.7 -y
```
```
conda activate Telegram-ChatBot
```
```
pip install -r requirements.txt
```
```
python teleChatBot.py
```
#### Create a `.env` file in the root directory and add your OpenAI API key and Telegram BOT TOKEN as follows:

```ini
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxx
TELEGRAM_BOT_TOKEN=xxxxxxxxxx:xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```
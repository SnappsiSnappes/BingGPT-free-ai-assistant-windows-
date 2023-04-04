
# Audio-based Chatbot
### This is an audio-based chatbot that listens to voice prompts and responds with text-to-speech. The bot uses the Bing (free) and OpenAI API (not free🤡) for generating responses to user prompts.

## Requirements
- openai
- asyncio
- re
- whisper
- pydub
- speech_recognition
- pyttsx3
- EdgeGPT
- You'll need an OpenAI API key to use this bot.

## instructions
1) first register microsoft account and download microsoft edge (if you dont have one)
2) Use vpn if you are Russian 
3) go to https://www.bing.com/ and get accecess to the gpt based bing-chat
4) download extinsinon https://chrome.google.com/webstore/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm
5) go to bing home page and click export cookies.json format to your clipbord 
6) create a folder inside directory with script , name it - 'cookies.json' and paste your cookies in this file 
7) launch

## issuses with installing ffempeg correctly
1) https://chocolatey.org/install#individual install chocolately using this code in powershell ```Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))```
2) then using powershell  ```choco install ffmpeg```
## Usage
- Clone the repository: ```git clone https://github.com/[username]/audio-based-chatbot.git``` 
- Install requirements: ```pip install -r requirements.txt```
- Replace the [paste your OpenAI API key here] placeholder with your API key in the code.
- Run the script
- Say "bing" or "gpt" to wake the bot.
- Say a prompt to receive a response.
# Functionality
The bot uses the Bing and GPT-3.5-turbo APIs to respond to user prompts. The bot is initialized with a recognizer object and wake word variables. When the bot hears the wake word, it waits for the user to say a prompt. The prompt is then passed to the appropriate API, and the response is synthesized into speech and played back to the user.

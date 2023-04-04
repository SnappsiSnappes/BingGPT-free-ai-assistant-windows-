
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
6) create a file inside directory with script , name it - 'cookies.json' and paste your cookies in this file 
7) read USAGE

## issuses with installing ffempeg correctly
1) https://chocolatey.org/install#individual install chocolately using this code in powershell ```Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))```
2) then using powershell  ```choco install ffmpeg```
## Usage
- Install requirements: ```pip install -r requirements.txt```
- Replace the [paste your OpenAI API key here] placeholder with your API key in the code.
- Run the script
- Say "bing" or "gpt" to wake the bot.
- Say a prompt to receive a response.


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

## Инструкции
1) Сначала зарегистрируйте учетную запись Microsoft и загрузите Microsoft Edge (если еще этого не сделали).
2) Используйте VPN, если вы находитесь в России.
3) Перейдите на https://www.bing.com/ и получите доступ к чату на основе GPT в Bing (установите страну своей учетной записи как США).
4) Скачайте расширение https://chrome.google.com/webstore/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm.
5) Перейдите на домашнюю страницу Bing и нажмите кнопку "Export cookies" в формате json в буфер обмена.
6) Создайте файл внутри директории со скриптом, назовите его - 'cookies.json' и вставьте свои куки в этот файл.
7) Следуйте инструкциям USAGE.
## Проблемы с правильной установкой ffmpeg
Установите Chocolately, используя этот код в PowerShell:
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
Затем, используя PowerShell, выполните: choco install ffmpeg
## Использование
Установите зависимости: pip install -r requirements.txt
Замените заполнитель [вставьте ваш API-ключ OpenAI здесь] на свой API-ключ в коде.
Запустите скрипт
- Скажите Джарвис -  чтобы разбудить бота.
- Ваш запрос начинается на - "Скажи","Расскажи" - тогда Джарвис пойдет в интернет и спросит у BingGPT ответ на ваш запрос, во время запроса можно сказать слово ОТМЕНА - чтобы отменить.
- Используйте working_gui.py чтобы добавить свои команды , или working_gui.exe - это одно и то же.
вот так выглядит интерфейс добавления своих команд.
![image](https://user-images.githubusercontent.com/111605401/235350281-a9ed8476-584a-4f2c-aad8-0ec2447635ba.png)
Ваши команды находятся в базе данных mydatabase.db , если его удалить, тогда он создастся снова, и будет пуст.

# Слушающий бот

Бот, который умеет превращать ваши голосовые сообщения в текстовые


## Инструкции по использованию бота

В pycharm:
- Напишите в терминале pycharm: git clone https://github.com/aleksandrapp/stt_bot.git
- Получите токен в BotFather в telegram, создайте файл .env, вставьте токен в этот файл так: BOT_TOKEN=...
- Получите в yandexGPT IAM токен и folder_id, вставьте их в файле .env так: IAM_TOKEN=... и FOLDER_ID=...
- Запустите код

В telegram:
- Найдите бота @stt_speech_to_text_bot, запустите его командой /start
- Чтобы бот преобразовал текст в аудио, пишите /stt

Than you have to create config.py:

# Token of your telegram bot
# (https://core.telegram.org/bots#6-botfather)
TELEGRAM_TOKEN = '123456789:AAHdqTcvCH1vGWJxfSeofSAs0K5PALDsaw '

# Credtals for logging to vk
VK_LOGIN = 'bot@bot.ry'
VK_PASS = 'bot_password'

# List of admins and moders
# Example: [ '66303244', 'vk1' ]
ADMINS_IDS = [  ]
MODERS_IDS = ADMINS_IDS + [  ]

DATABASE_PATH = 'db.json'
USERS_PATH = 'users'
You don't have to write vk login and pass, if you wouldn't use it. Same with telegram token.

Launching

To launch telegram bot:

python3 ./main.py
or

To launch vk bot:

python3 ./main_vk.py
You can also build all bot to pyc files (Just for fun):

python3 ./build.py
cd build
python3 main.pyc
That's it.

You can write me via Telegram (@yegorf1) or VK.com (vk.com/yegorf1) if you have any questions.

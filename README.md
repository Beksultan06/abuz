
```
1. Установите необходимые модули

```python
pip install -r requirements.txt
```

2. Введите ваши данные и прокси (необязательно) в файле `config.env`

```
TELEGRAM_CHAT_ID=...
TELEGRAM_BOT_TOKEN=...
TELEGRAM_INIT_DATA=...
PROXY=user:pass@ip:port
PROXY_EXISTS=False
```

TELEGRAM_CHAT_ID: Ваш telegram ID можно найти в боте https://t.me/userinfobot <br>
TELEGRAM_BOT_TOKEN: Токен бота. Бот создается в боте https://t.me/BotFather. После создания появится токен. Вы должны начать разговор со своим ботом, чтобы получать уведомления о работе кликера <br>
TELEGRAM_INIT_DATA: Запустите telegram web- https://web.telegram.org. Нажмите ctrl + shift + i, откройте бота и нажмите "Играть". В разделе "Сеть" появится запрос на веб-сайт `
arbuz.betty.games/api/users/me`. Оттуда вам нужно скопировать свою сессию. <br>
![image](https://github.com/Beksultan06/abuz/blob/master/images/telega.png)

3. Запустите основной файл проекта

```python
python arbuzapp.py
```

#
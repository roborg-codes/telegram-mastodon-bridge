# Telebridge

![demonstration](https://github.com/cyborg-ubyvtsya/telegram-mastodon-bridge/blob/main/img/demo.gif)

Telegram/Mastodon bot for forwarding messages.

## Usage

- [Create a telegram bot](https://core.telegram.org/bots#3-how-do-i-create-a-bot)
- - Recieve telegram's access token
- [Create a mastodon bot](https://tinysubversions.com/notes/mastodon-bot/)
- - Give it the rights to write statuses
- - Save mastodon's access token
- Subscribe your telegram bot to channel(s) you need
- Install dependencies `pip install -r requirements.txt`
- Launch main.py and follow instructions
- Bot will start forwarding posts

### Limitations

- Only reposts plain text, images, and videos
- Image galleries are published as separate posts

# Телеміст

Телеграм/Мастодон бот, який дописи з тг в мастодон.

## Використання

- [Створіть бота в Телеграм](https://core.telegram.org/bots#3-how-do-i-create-a-bot)
- - Отримайте токен доступу
- [Створіть бота в Мастодон](https://tinysubversions.com/notes/mastodon-bot/)
- - Дайте йому доступ до створення дописів
- - Збережіть токен доступу
- Підпишіть бота на потрібні канали в телеграмі
- Встановіть залежності `pip install -r requirements.txt`
- Відкрийте main.py і змініть видимість постів в `mastodon_visibility = "direct"`
- Запустіть скрипт і слідуйте інструкціям
- Бот почне постити нові дописи з каналу на який він підписаний

### Обмеження

- Підтримуються лише текст, світлини, та відео
- Галереї публікуються в окремих дописах

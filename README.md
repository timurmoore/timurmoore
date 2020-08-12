# MOORE HELPER

<p align="center">
<img src="https://telegra.ph/file/1cfb6d07372fd5876e3ef.jpg" alt="MOORE USERBOT">


[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)



Лучший помощник для твоего аккаунта
## Эффективный и безопасный

### По всем вопросам пиши: 

<a href="https://t.me/timurmoore"><img src="https://img.shields.io/badge/Join-Telegram%20Group-blue.svg?logo=telegram"></a>

### Хостинг на Heroku

[![Поставить на Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/timurmoore/timurmoore)

### Без Heroku

Копируй репозиторий и вперед:
```sh
git clone https://github.com/timurmoore/timurmoore
cd timurmoore
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Создай local_config.py с нужными значениями, пример ниже.>
python3 -m userbot
```

Пример:

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```
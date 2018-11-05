## Установка зависимостей
```
pip3 install -r requirements.txt
```

## Авторизация
Возможны два способа аутентификации - с помощью пары логин-пароль или токена. При использовании токена сохранение аудио будет **невозможно**.

Для входа по токену необходимо передать аргумент `token` при запуске:
```
python3 dump.py --token your_token_here
```

## Поддерживаемые для сохранения данные
- [x] Фото
- [x] Аудио
- [x] Видео
- [x] Документы
- [x] Сообщения (txt)
- [ ] дополнительные форматы для сообщений и прочее, прочее, прочее ;)

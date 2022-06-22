# Задание по реализации дополнительной стратегии OAuth 2.0

Выбран провайдер авторизации ВКонтакте.

Стратегия: http://www.passportjs.org/packages/passport-vkontakte/

**Параметры страгегии:**

- `options` - реквизиты приложения, callback URL
- `verify` - callback для верификации пользователя

**Endpoints:**

- `/auth/yandex` - вход с помощью Yandex
- `/auth/yandex/callback` - redirect URL (callback URL)
- `/auth/vkontakte` - вход с помощью VK
- `/auth/vkontakte/callback` - redirect URL (callback URL)

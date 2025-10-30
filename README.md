# Лабораторная работа - Веб-приложение с аутентификацией

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

Веб-приложение для лабораторной работы с кастомной аутентификацией, интернационализацией и HTTPS поддержкой.

## 🚀 Технологический стек

- **Backend**: Node.js + Express.js
- **Frontend**: EJS templates + чистый CSS/JS
- **Web Server**: Nginx (реверс-прокси)
- **Containerization**: Docker + Docker Compose
- **Authentication**: Кастомная сессионная аутентификация
- **i18n**: i18next для интернационализации
- **Security**: HTTPS, базовая аутентификация


## 🚀 Быстрый старт

### Способ 1: Docker Compose (рекомендуется)

```bash
# Запуск всех сервисов
docker-compose up -d

# Просмотр логов
docker-compose logs -f

# Остановка
docker-compose down
```
Для генерации документации используйте:

```bash
npm run docs
```

Ведется поддержка 2-х языков русского и английского

Основные технологии
- Backend: Node.js + Express.js
- Frontend: EJS + чистый CSS/JavaScript
- Web Server: Nginx
- Containerization: Docker
- Authentication: Кастомная сессионная аутентификация
- i18n: i18next (русский/английский)
- Security: HTTPS, базовая аутентификация
- Documentation: JSDoc

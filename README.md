# Книга Отзывов

![Книга Отзывов](img/cover.jpeg)
**Книга Отзывов** — это простой веб-сайт, позволяющий пользователям оставлять и просматривать отзывы о книгах. Проект создан для изучения технологий контейнеризации (Docker), веб-сервера (Nginx), бэкенда (FastAPI) и настройки доменного имени и SSL-сертификата, знакомства с роботой REST.

### Функциональность
 - Просмотр списка книг и отзывов.
 - Добавление нового отзыва о книге.

### Технологии
 - Фронтенд: HTML, CSS, JavaScript, Tailwind
 - Бэкенд: FastAPI (Python)
 - Веб-сервер: Nginx 
 - Контейнеризация: Docker 
 - Оркестрация контейнеров: Docker Compose 
 - База данных: SQLite

### Установка и запуск

1. Клонируйте репозиторий:

``` bash
git clone https://github.com/yourusername/book-reviews.git
cd book-reviews
```

2. Создайте и настройте Docker контейнеры:

```bash
docker-compose up --build
```

3. Откройте браузер и перейдите по адресу http://localhost.


### Настройка DNS и SSL:
  1. Зарегистрируйте доменное имя (например, bookreviews.example.com) и настройте DNS-записи на ваш сервер.
  2. Установите Certbot и настройте SSL-сертификат:

```bash
sudo apt-get install certbot python3-certbot-nginx
sudo certbot --nginx -d bookreviews.example.com
```

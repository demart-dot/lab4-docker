# Вказуємо базовий образ
FROM nginx:latest

# Копіюємо файли з локальної директорії у контейнер
COPY ./ /usr/share/nginx/html

# Додаємо VOLUME для кореневої директорії веб-сервера
VOLUME ["/usr/share/nginx/html"]

# Виставляємо порт
EXPOSE 80
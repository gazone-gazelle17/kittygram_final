[![Build Status](https://github.com/gazone-gazelle17/kittygram_final/actions/workflows/main.yml/badge.svg)](https://github.com/gazone-gazelle17/kittygram_final/actions)
# Проект kittygram

### Для чего он нужен
##### Проект нужен для ведения учета котов, их возраста, способностей и цветов.
### Какие функции выполняет
- добавление котов;
- выбор цветов котов;
- определение возраста котов;
- определение способностей котов;
# Cтек использованных технологий
- Django
- Djoser
- Pillow
- Pytest
- Gunicorn
- Nginx
- Docker
# Как развернуть проект
- Соберите Docker-образ:
В терминале выполните команду для сборки Docker-образа. 
```python
docker build -t kittygram_final .
```
- Запустите Docker-контейнер:
Выполните команду для запуска контейнера:
```python 
docker run -p 8000:8000 myapp 
```
-Используйте Docker Compose:
```python 
docker-compose up
```
# Как заполнить env
- Откройте файл .env в текстовом редакторе и укажите ваши переменные в формате KEY=VALUE;
# Кто автор 
Автор - Саша Гасымов.

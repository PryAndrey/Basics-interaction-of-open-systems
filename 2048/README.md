# 2048 Game

Команды для инициализации образа
- docker pull node:14
- docker build -t 2048-game .

Запуск контейнера на основе образа
- docker run --rm -d -p 8080:8080 2048-game

Запуск docker compose 
- docker compose up -d
Выключение и зачистка образов
- docker compose down --rmi all
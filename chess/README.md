# Тихий ход

Мобильная шахматная игра на HTML/CSS/JavaScript. Stockfish 19 lite single-threaded работает локально в Web Worker и WASM: движок не блокирует доску и не требует сети после загрузки.

Откройте проект через локальный веб-сервер. Service Worker и установка на главный экран требуют HTTPS либо `localhost`; для доступа с телефона используйте HTTPS-хостинг. Бот и подсказки используют уровни Stockfish с различными ограничениями Elo, Skill Level и временем поиска.

Настройки интерфейса сохраняются в `localStorage`. Stockfish.js распространяется по GPLv3; текст лицензии находится в `Stockfish-LICENSE.txt`, исходный код движка: https://github.com/nmrugg/stockfish.js.

Tic_tac_toe_bot
Простой бот для игры в "крестики-нолики". Реализована только игра поочереди, где первым ходят "X".

Установка
Создаем виртуальное окружение и активируем его.
Выполняем установку зависимостей:
pip install -r requirements.txt

Настройка
Создайте файл settings.py и добавте настройки:

API_KEY = 'API ключ, котоырй вы получили у BotFather'

Запуск
В активированном виртуальном окружении выполните:

python main.py

Функционал
Две команды:

/start - небольшое описание
/start_game - начало игры
Правила игры
Игроки по очереди ставят на свободные клетки поля 3х3 знаки (один всегда крестики, другой всегда нолики). 
Первый, выстроивший в ряд 3 своих фигуры по вертикали, горизонтали или диагонали, выигрывает. Первый ход делает игрок, ставящий крестики.

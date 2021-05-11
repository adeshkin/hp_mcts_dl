# Поиск пути в частично наблюдаемой среде с использованием MCTS и DL. (Проект по эвристическому планированию)

Реализация агента способного по окну наблюдения и данным радара находить около-оптимальный путь к 
цели на картах [Movinag Ai: City/Street Maps](https://movingai.com/benchmarks/street/index.html).

## Установка
Сначала копируем репозиторий любым удобным способом. Открываем терминал в папке репозитория. Устанавливаем зависимости `pip install -r requerements.txt`. 
И устанавливаем `mcts_dl` командой `pip install .`.
## Запуск
Тестовый запуск производится командой `python mcts_dl/agent.py`. Метрики отслеживаются через [wandb](wandb.ai).

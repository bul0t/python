# Python

Запустить Анаконду через терминал:

    anaconda-navigator

Установка:
- можно установить только интерпретатор
- можно установить IDE Spyder или PyCharm, где Python уже встроен
- можно установить Anaсonda, где есть всё для разработки на Python, в том числе и IDE

## Редакторы
Редакторы Python: Spyder, PyCharm. Notebook оболочки - подходят для изучения языка.

## Anaconda
Команды:
- `conda info` - вывести информацию об инструменте conda
- `conda update conda` - обновление инструмента conda (да)
- `conda update anaconda` - обновление программы Anaconda (да)
- `conda list` - посмотреть список установленных пакетов
- `conda search pip` - найти нужный пакет
- `conda install имя-пакета` - устанавливаем пакет по его имени
- `conda remove имя-пакета` - удаляем пакет
- `rm -rf ~/anaconda3` - удаляем анаконду из убунту (не забываем удалить строчки в ~/.bashrc)
- `rm -rf ~/.condarc ~/.conda ~/.continuum` - удаляем скрытые папки

Conda это пакетный менеджер и менеджер окружений, можно создать несколько разных окружений с разными Python.
- `conda info --envs`   - посмотреть существующие окружения
- `conda activate base` - активировать окружение с именем base
- `conda deactivate`    - деактивировать текущее окружение

## Команды Python
- проверяем версию Python

## Разное
- установка и работа - https://www.youtube.com/watch?v=DY0DB_NwEu0
- установка - https://www.digitalocean.com/community/tutorials/how-to-install-the-anaconda-python-distribution-on-ubuntu-20-04-ru
- установка - https://losst.ru/ustanovka-anaconda-v-ubuntu

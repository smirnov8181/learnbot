LearnBot
========

LearnBot - это учебный бот для мессенджера telegram, который умеет присылать котиков.

Установка
---------

Создайте вирутальное окружение и активируйте его. Потом в виртуальном окружении выполните:
.. code-block:: text

    pip install -r requirements.txt

Положите картинки с котиками в папку images. Название файлов должно начинаться с cat, и иметь расширение .jpg или .jpeg. Пример: catingo.jpg

Настройка
---------

Создайте файл settings.py и добавьте туда следующие настройки:
.. code-block:: python 

PROXY = {'proxy_url': 'socks5://ВАШ_SOCKS5_ПРОКСИ:1080',
    'urllib3_proxy_kwargs': {'username': 'ЛОГИН', 'password': 'ПАРОЛЬ'}}


API_KEY = "Api ключ, который вы получите от BotFather"

USER_EMOJI = [':smiley_cat:', ':smiling_imp:', ':panda_face:', ':dog:']  


Запуск
------

В активированном виртуальном окружении выполните 
.. code-block:: text

    python bot.py

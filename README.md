# Telebot
 Style transfer, generate texture and super resolution
 
 В RRDBNet_arch.py лежит класс модели повышения разрешения.
esrinf.py содержит процедуру создания модели повышения разрешения, загрузки ее весов, и обработки подготовленного заранее файла.
Папка models содержит веса модели повышения разрешения.
transfer.py содержит все классы и функции для модели переноса стиля и генерации текстуры
Telebot.ipynb - основной модуль, обеспечивает функционирование бота и вызов всех необходимых функций.

Команды бота /start, /help - выводит список режимов:

/transfer - режим переноса стиля, после запуска этой команды следует прикрепить и отправить картинку контента, затем прикрепить и отправить кратинку стиля и получить результат

/texture - режим генерации текстуры, после запуска этой команды следует прикрепить и отправить картинку текстуры и получить результат.

/super - режим повышения изображения, после запуска этой команды следует прикрепить и отправить картинку низкого разрешения (не более 512 пикселей по любой координате) и получить результат.


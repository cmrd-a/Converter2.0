# Конвертер

Написан на Python 3,8

Скрипт позволяет сконвертировать файлы *.html в *.md.

Для корректной работы надо будет установить 'pypandoc'

'pip install pypandoc'

На Linux системах скрипт отрабатывает без ошибок.

На Windows может возникать ошибка перекодировки из-за некоторых символов.

Скрипт обрабатывает все файлы, которые находятся в одной папке с  conv.py.
По ходу конвертатор также убирает из полученных файлов артефакты html.
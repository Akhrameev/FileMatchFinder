# Readme

`FileMatchFinder` позволяет вам провести сортировку набора файлов в соответствии с имеющимся набором .torrent-файлов. Сортировка будет произведена так, что вы сможете снова запустить раздачу файлов в torrent-клиенте.

К сожалению строение .torrent-файлов таково, что мелкие файлы не обрабатываются данной программой и их придется перекачать заново. Также из-за отсутствия некоторых файлов torrent-клиент может считать, что нет начала или конца существующего файла.

# Release notes

## 0.0.2.5

 * Исправлена проблема зависания интерфеса во время работы программы
 * Добавлена возможность проверять весь файл, что дает большую точность при сортировке файлов

## 0.0.2.0

 * Изменен порядок обработки файлов
 * Уменьшено потребление памяти
 * Улучшена производительность

## 0.0.1.0

* First release

# Copyrights & License

This code licensed under GPLv2

Copyright © 2012, Grigory Parshikov

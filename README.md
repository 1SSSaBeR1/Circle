# Espresso
Создайте новый публичный репозиторий с произвольным именем, в котором разместите следующие файлы:
- main.py — программа для отображения информации о кофе из базы данных coffee.sqlite (ID, название сорта, степень обжарки, молотый/в зернах, описание вкуса, цена, объем упаковки)
- coffee.sqlite — sqlite база данных для хранения всей необходимой для отображения информации о кофе
- main.ui — файл с интерфейсом программы
- requirements.txt — файл с используемыми библиотеками

## Зависимости
Установка зависимостей в консоли
```pip install -r requirements.txt
```

## main.ui -> design.py
Для получения файла дизайна окна из .ui файла:
```pyuic5 main.ui -o design.py
```
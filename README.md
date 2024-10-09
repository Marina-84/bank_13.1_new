# Проект "Виджеты для клиента банка"

## Описание:

Данный проект осуществляет принятие информации от клиента и сортирует по дате, определенным условиям.

## Установка:

1. Клонируйте репозиторий:
```
git clone https://github.com/Marina_84/bank_10.1.git
```
2. Установите зависимости:
```
pip install -r requirements.txt
```

## Структура проекта:

1. tests/ - папка, в которой содержатся тесты проекта.
2. src/ - папка, содержащая файлы с функциями проекта.
3. .venv - виртуальное окружение, содержащее библиотеки и скрипты.

## Использование:

1. Откройте приложение в вашем веб-браузере.
2. Создайте новый проект и начните добавлять задачи.
3. Назначайте сроки выполнения и приоритеты для задач, чтобы эффективно управлять проектами.
4. Виджет включает в себя функцию маскировки ваших входных банковских данных
5. Модуль masks.py принимает на вход номер карты или счета и маскирует их.
6. Модуль widget.py принимает наименование карты или счет и номер и возвращает замаскированный номер.
7. Модуль processing.py принимает список операций и возвращает отсортированные списки.
8. Модуль generators.py принимает список транзакций и реализует работу генераторов для обработки данных.
9. Модуль decorators.py используется для размещения декораторов.
10. Модуль utils.py содержит функцию, которая принимает путь до JSON-файла и возвращает список словарей с данными о финансовых транзакциях.
11. Модуль external_api.py содержит функцию, которая принимает на вход транзакцию и возвращает сумму транзакции в рублях.

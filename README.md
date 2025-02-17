# Описание файла market.py

Скрипт предназначен для автоматизации обновления информации о товарах на маркетплейсе Яндекс Маркете. Скрипт поддерживает два типа доставки FBS и DBS, по которым можно загрузить товары и их артикулы, используя SKU (складской номер), обновить цену и узнать о количестве остатков на маркетплейсе, используя последние данные сайта https://timeworld.ru.

# Описание файла seller.py

Скрипт предназначен для автоматизации обновления информации о товарах на маркетплейсе Ozon. Скрипт загружает товары и их арктикулы, скачивает остатки с сайта https://timeworld.ru, обновляет количество остатков на Ozon и изменяет цены, используя последние данные сайта https://timeworld.ru.

# Вводные данные для запуска файлов

Для запуска seller.py создайте файл .env и присвойте значения переменных окружения `SELLER_TOKEN` и `CLIENT_ID`. Подробные инструкции о том, как настроить API для вашей компании, а также форматы запросов и порядок работы с методами, можно найти в [документации Ozon](https://docs.ozon.ru/api/seller/#section/Kak-poluchit-dostup-k-Seller-API). 

Для запуска market.py, в созданном файле .env, присвойте значения переменных окружения `MARKET_TOKEN`, `FBS_ID`, `DBS_ID`, `WAREHOUSE_FBS_ID`, `WAREHOUSE_DBS_ID`. Подробности о переменных можно найти в [документации](https://yandex.ru/dev/market/partner-api/doc/ru/concepts/authorization).
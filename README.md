# pythonProject_Unit28

Задание 28.9.11 - ИСПОЛЬЗОВАНИЕ БИБЛИОТЕКИ PYDANTIC В АВТОТЕСТАХ

По заданию написаны методы реализации API-интерфейсов http://restful-booker.herokuapp.com/apidoc/index.html и тесты с использованием библиотеки pydantic для проверки формата и обязательности данных запроса и ответа.

/api/booking.py - библиотека API-методов /resources/prepary_data.py - данные для тестов /resources/booking_model.py -объекты pydantic - модели для проверки данных запросов и ответов /tests/test_booking.py - тесты

Не проходят тесты на API-методы PUT и DELETE, т.к. эти методы, видимо, запрещены, имеют статус 403 - Запрещено. Проверено в Почтальоне, там то же самое.

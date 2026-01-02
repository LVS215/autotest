ЗАПУСК
# Установка зависимостей
pip install -r requirements.txt

# Запуск тестов
pytest tests/test_jsonplaceholder.py -v

# С генерацией отчета
pytest tests/test_jsonplaceholder.py --html=report.html

Особенности тестируемого API:

API фейковое, данные не сохраняются

Все операции возвращают успешные статусы

Реальные изменения на сервере не происходят

Идеально подходит для обучения и прототипирования

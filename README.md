# pytest_ui_api

## Шаблон для автоматизации тестирования на python

### Шаги:
1. Склонировать проект 'git clone https://github.com/Flabeba/pytest_ui_api.git'
2. Установить зависимости
3. Запустить тесты 'pytest'
4. Сгенерировать отчет 'allure generate allure-files -o allure-report'
5. Открыть отчет 'allure open allure-report'

### Стек:
- selenium
- requests
- pytest
- allure
- configparser
- json

### Струткура:
- ./test - тесты
- ./pages - описание страниц
- ./api - хэлперы для работы с API
- ./configuration - провайдер настроек
- test_config.ini - настройки для тестов
- ./testdata - провайдер тестовых данных
- test_data.json

### Полезные ссылки
[Подсказка по markdown](https://www.markdownguide.org/basic-syntax/)

### Библиотеки
- pip install pytest
- pip install selenium
- pip install requests
- pip install allure
- pip install webdriver-manager
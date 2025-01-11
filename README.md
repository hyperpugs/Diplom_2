#### Установить зависимости:

> pip install -r requirements.txt

#### Запустить все тесты:

> pytest -v

#### Посмотреть отчёт в браузере:

Запуск тестов с генерацией от allure
> pytest -v --alluredir=allure_results  
 
Просмотр тестов в браузере
> allure serve allure_results

# Тест-план возможности записи на обучение профессии "Тестировщик ПО" на сайте Нетологии
**1. Перечень автоматизируемых сценариев**

* Переход на страницу формы через каталог курсов в хеддере стартовой страницы
* Переход на страницу формы через каталог курсов в хеддере стартовой страницы через блок "Программирование"
* Переход на страницу формы через блок "Направления обучения" , направление "Программирование" на стартовой странице
* Переход на страницу формы через блок "Обучение", пункт "Популярные курсы" в футере сайта
* Переход на страницу формы через блок "Обучение", пункт "Программирование" в футере сайта
* Отправка заявки зарегестрированного пользователя (валидные данные\невалидные данные\пустая форма)
* Отправка заявки не зарегестрированного пользователя (валидные данные\невалидные данные\пустая форма)
* Доступность API (ответы сервера при отправке валидных\невалидных\пустых данных)

**2. Перечень используемых инструментов с обоснованием выбора**

Инструменты, выбранные на основе эмпирического опыта тестировщика, позволят сразу же приступить к процессу тестирования, не тратя время и ресурсы на изучение иного инструментария, что сэкономит деньги проекта
* intellij idea - интегрированная среда разработки, позволит связать весь проект в одном месте, от написания автотестов до внедрения системы автоматической сборки 
* Selenium\Selenide - даст возможность провести автоматизированное тестирование веб-приложения через использование элементов страницы
* Postman - позволит провести интеграционное тестирование - доходят ли запросы на запись курса в БД, коды ответа
* Gradle - упростит рабочий процесс за счет автоматизации типовых задач и веб-визуализации сборки, позволит собрать некоторую метрику тестирования

**3. Перечень необходимых разрешений/данных/доступов**
* Спецификация к проекту
* Документация по REST API проекта

--Доступ к коду и БД не требуется--

**4. Перечень и описание возможных рисков при автоматизации**
При обновлении веб-приложения с добавлением\удалением способов доступа к записи курса "Тестировщик ПО" регресс станет частично невозможен, необходима поддерживаемость тестов путем обновления и отслеживаемости изменений веб-приложения

**5. Перечень необходимых специалистов для автоматизации**
Тестировщик ПО с начальными навыками в автоматизации

**6. Интервальная оценка с учётом рисков (в часах)**
3ч настройка и подготовка проекта + 12ч написание тестов + 3ч оформление отчетности (4ч в неделю регресс + 5ч обновление тестов при необходимости)  

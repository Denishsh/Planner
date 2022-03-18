# Planner
Навигация к форме обратной связи
a. Открыть сайт https://netology.ru/
b. Перейти в каталог курсов ![image](https://user-images.githubusercontent.com/85746963/158998091-6c0e89a0-cbeb-4f25-a9f8-ad2138c4bd97.png)
c. Выбрать курс Тестировщик ![image](https://user-images.githubusercontent.com/85746963/158998223-e4056cae-34a2-4853-b13f-fcde27513e02.png)



1. Перечень автоматизируемых сценариев

   Позитивные:
    - Отправка формы с получением консультации. Нажать кнопку записаться. В форму ввести имя и номер телефона из 11 цифр (Андрей, 7911111111). Нажать кнопку Получить консультацию. Ожидаемый результат: отображается сообщение об успешной записи на консультацию
    - Отправка заявки через кнопку Записаться. Нажать кнопку записаться. В форму ввести имя и номер телефона из 11 цифр (Андрей, 7911111111). Нажать кнопку Записаться. Ожидаемый результат: отображается сообщение об успешной записи
    - Просмотр содержания модулей курса
    - Скролл списка преподавателей
    - Покупка курса
    - Просмотр акции
    - Просмотр политик

   Негативные:
    - Ввод неправильного промокода
    - Запись/консультация на курс без ввода имени или номера телефона
2. Перечень используемых инструментов с обоснованием выбора  
    - Java - язык программирования для автотестов
    - IntelliJ IDEA. Платформа для удобного написания кода, в том числе для тестов.
    - JUnit. Библиотека для написания и запуска авто-тестов.
    - Gradle. Система управления зависимости, которая позволит удобно ставить необходимые фреймворки без проблем с постоянной настройкой зависимостей.
    - Selenide. Фреймворк для автоматизированного тестирования веб-приложений.
    - Allure. Фреймворк, предназначенный для создания подробных отчетов о выполнении тестов.
    - Git и Github. Система контроля версий, для хранения кодов автотестов и настроек окружения.

3. Перечень необходимых разрешений/данных/доступов

   Требуется учётная запись для сайта

   Разрашение на автотестирование, доступ к данным и API сайта
4. Перечень и описание возможных рисков при автоматизации

    Проблемы при настройке окружения

    Проблемы при заполнении полей ввода

    Неработающий функционал сайта
5. Перечень необходимых специалистов для автоматизации

   1 ручной тестировщик, 1 автотестировщик
6. Интервальная оценка с учётом рисков (в часах)

   Подготовка окружения - 8 часов.

   Написание автотестов, тестирование и отладка автотестов - 24 часа.

   Формирование и анализ отчетов - 4 часа.


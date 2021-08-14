#  План автоматизации формы записи на курс или консультацию по курсу

![Form](https://github.com/netology-code/aqa-homeworks/blob/master/summary/pictures/form.jpg)



**Варианты путей перехода на форму:**

**Первый путь:**
Главная страница - Каталог курсов – Программирование - Тестировщик ПО;

**Второй путь:**
Главная страница - Каталог курсов - Полный каталог - Тестировщик ПО;

**Третий путь:**
Главная страница - Нео для начинающих - Тестировщик ПО;

**Четвертый путь:**
Главная страница - Каталог курсов (выбор в выпадающем списке) – Программирование (выбор в выпадающем списке) - Тестировщик ПО.

## РАЗДЕЛ 1 ПЕРЕЧЕНЬ АВТОМАТИЗИРУЕМЫХ СЦЕНАРИЕВ

**Сценарий №1:**
Запись на курс при переходе на форму *по первому пути* с вариантами значений в поле «Имя» и «Телефон».

**Сценарий №2:**
Запись на консультацию при переходе на форму *по первому пути* с вариантами значений в поле «Имя» и «Телефон».

**Сценарий №3:**
Запись на курс при переходе на форму *по второму пути* с вариантами значений в поле «Имя» и «Телефон».

**Сценарий №4:**
Запись на консультацию при переходе на форму *по второму пути* с вариантами значений в поле «Имя» и «Телефон».

**Сценарий №5:**
Запись на курс при переходе на форму *по третьему пути* с вариантами значений в поле «Имя» и «Телефон».

**Сценарий №6:**
Запись на консультацию при переходе на форму *по третьему пути* с вариантами значений в поле «Имя» и «Телефон».

**Сценарий №7:**
Запись на курс при переходе на форму *по четвертому пути* с вариантами значений в поле «Имя» и «Телефон».

**Сценарий №8:**
Запись на консультацию при переходе на форму *по четвертому пути* с вариантами значений в поле «Имя» и «Телефон».



### Варианты ввода в поля «Имя» и «Телефон»

+ **Вариант 1** 
  - Ввести в поле "Имя" в форме "Запишитесь или получите консультацию": случайное имя на кириллице.
  - Ввести в поле "Телефон" в форме "Запишитесь или получите консультацию": случайный телефон (11 символов).

+ **Вариант 2**
  - Ввести в поле "Имя" в форме "Запишитесь или получите консультацию": случайное имя на кириллице с цифрами. 
  - Ввести в поле "Телефон" в форме "Запишитесь или получите консультацию": случайный телефон (11 символов).

+ **Вариант 3**
  - Ввести в поле "Имя" в форме "Запишитесь или получите консультацию": случайное имя на кириллице с цифрами и спец символами.
  - Ввести в поле "Телефон" в форме "Запишитесь или получите консультацию": случайный телефон (11 символов).

+ **Вариант 4**
  - Ввести в поле "Имя" в форме "Запишитесь или получите консультацию": случайное имя на латинице.
  - Ввести в поле "Телефон" в форме "Запишитесь или получите консультацию": случайный телефон (11 символов).

+ **Вариант 5**
  - Ввести в поле "Имя" в форме "Запишитесь или получите консультацию": случайное имя на латинице.
  - Ввести в поле "Телефон" в форме "Запишитесь или получите консультацию": случайный телефон (11 символов).

+ **Вариант 6**
   - Ввести в поле "Имя" в форме "Запишитесь или получите консультацию": случайное имя на латинице с цифрами.
   - Ввести в поле "Телефон" в форме "Запишитесь или получите консультацию": случайный телефон (11 символов).

+ **Вариант 7**
  - Ввести в поле "Имя" в форме "Запишитесь или получите консультацию": случайное имя на латинице с цифрами и спец символами.
  - Ввести в поле "Телефон" в форме "Запишитесь или получите консультацию": случайный телефон (11 символов).

+ **Вариант 8**
   - Оставить поле "Имя" пустым.
   - Ввести в поле "Телефон" в форме "Запишитесь или получите консультацию": случайный телефон (11 символов).

+ **Вариант 9**
   - Оставить поле "Имя" пустым.
   - Оставить поле "Телефон" пустым.

+ **Вариант 10**
   - Ввести в поле "Имя" в форме "Запишитесь или получите консультацию": случайное имя на кириллице/латинице.
   - Оставить поле "Телефон" пустым.

+ **Вариант 11**
   - Ввести в поле "Имя" в форме "Запишитесь или получите консультацию": случайное имя на кириллице/латинице.
   - Ввести в поле "Телефон" в форме "Запишитесь или получите консультацию": случайный телефон (менее 11 символов).


## РАЗДЕЛ 2 ПЕРЕЧЕНЬ ИСПОЛЬЗУЕМЫХ ИНСТРУМЕНТОВ С ОБОСНОВАНИЕМ ВЫБОРА


Список инструментов:
+ Intellij idea c плагинами – для выполнения работ по автоматизации.
  - Плагин Junit.jupiter.api – для написания тестов и их запуска.
  - Плагин Selenide – для создания тестов по заполнению тестируемой формы на сайте Нетологии.
  - Плагин Lombok – для создания методов с генерацией значений Faker.
  - Плагин Faker – для генерации случайных значений для ввода в поля формы.
  - Плагин SQL – для проверки результатов тестов (какие данные попали в БД для менеджеров).
+ Репозиторий на Github с подключенным CI для возможности модификации тестов, откатов изменений и тд. 
+ ПО для работы отдела поддержки.
+ ПО для работы БД отдела поддержки.
+ ПО для связи тестов с ПО отдела поддержки.

## РАЗДЕЛ 3 ПЕРЕЧЕНЬ НЕОБХОДИМЫХ РАЗРЕШЕНИЙ/ ДАННЫХ/ ДОСТУПОВ

1.	Разрешение на тестирование от руководства Нетологии (письменное, если разработка идет не внутри компании).
1.	Доступ в систему Нетологии для получения требований по работе данной формы.
1.	Получить доступ к тест-кейсам для ручного тестирования в целях ускорения разработки.
1.	Доступ в системы связанных с работой тестируемой формы.
1.	Доступ и разрешения на корректировку данных в БД отдела поддержки. (чистить БД после прохождения тестов).
1.	Согласовать график проведения тестов, чтобы избежать перегрузки и/или сбоя в работе отдела поддержки.


## РАЗДЕЛ 4 ПЕРЕЧЕНЬ И ОПИСАНИЕ ВОЗМОЖНЫХ РИСКОВ ПРИ АВТОМАТИЗАЦИИ
1.	Неактуальность тестов при переработке формы на сайте. (добавление полей и тд.)
1.	Невозможность выполнения тестов при изменении названия каталогов и разделов в них, изменении названия профессии, изменении CSS классов на пути выполнения тестов.
1.	Необходимость привлекать для работы тестировщиков с навыками программирования и автоматизации.
1.	Высокая стоимость работ по автоматизации и необходимость поддержки этих авто тестов.
1.	Авто тесты не смогут проверить «окружение формы» они проверят только работу самой формы.


## РАЗДЕЛ 5 ПЕРЕЧЕНЬ НЕОБХОДИМЫХ СПЕЦИАЛИСТОВ ДЛЯ АВТОМАТИЗАЦИИ

1.	Представители из Нетологии (отделы разработки, тестирования, поддержки);
1.	Специалист по автоматизации;
1.	Специалист по SQL;
1.	Специалист по работе ПО служб поддержки;

## РАЗДЕЛ 6 ИНТЕРВАЛЬНАЯ ОЦЕНКА С УЧЁТОМ РИСКОВ (В ЧАСАХ)


| Операция | Затраченное время |
| ------ | ----------- |
| Получение разрешений и доступов   | 48 часов |
| Работа с документацией и требованиями | 48 часов |
| Разработка авто тестов    | 200 часов |
| Настройка взаимодействия между авто тестами и ПО служб поддержки    | 48 часов |
| **Итого примерно**    | **344 часа**|

## Авто тест кредитного калькулятора на сайте http://creditcalculator.pointschool.ru/ с использованием Selenium и Pytest
## Проект для портфолио
#### 1. Создан и добавлен json файл с тестовыми данными
#### 2. Написан метод для извлечения тестовых данных из json файла
#### 3. Добавлен метод для генерации тестовых данных с использованием библиотеки Faker. 
####    Генерируемые данные (ФИО, Паспорт, Дата, Наименование органа выдавшего паспорт, Сумма, Сроки кредита)
#### 4. Добавилен класс Clien для хранения данных, генерируемых генератором и обернуто все декоратором @dataclass

### Тест-кейс:
#### 1. Перейти на страницу http://creditcalculator.pointschool.ru# 
#### 2. Нажать кнопку «Рассчитать»
#### 3. В результатах расчета нажать на кнопку «Заполните анкету»
#### 4. В поле «Желаемая сумма кредита» ввести значение «100000»
#### 5. В поле «Первоначальный взнос» ввести значение «0»
#### 6. В поле «Срок кредита» ввести значение «12»
#### 7. В блоке «Данные заемщика» в поле «Фамилия» ввести «Ярцова»
#### 8. В поле «Имя» ввести данные «Злата»
#### 9. В поле «Отчество» ввести «Васильевна»
#### 10. В поле «Серия и номер паспорта» ввести значение «4300 542277»
#### 11. В поле «Кем выдан» ввести «Нижегородское ГОВД»
#### 12. В поле «Дата выдачи» ввести 11.11.2011
#### 13. В выпадающем списке «Образование» выбрать «высшее»
#### 14. В выпадающем списке «Общий трудовой стаж» выбрать «5-10 лет»
#### 15. В выпадающем списке «Срок работы на последнем месте (официальная занятость)» выбрать «более 3 лет»
#### 16. В выпадающем списке «Подтверждение дохода справкой 2НДФЛ» выбрать «Да»
#### 17. В выпадающем списке «Место работы в регионе регистрации банка?» выбрать «Да»
#### 18. В поле «Чистый доход в месяц (все денежные доходы минус обязательные платежи по кредитам)» ввести значение «35000»
#### 19. В выпадающем списке «Место прописки в регионе регистрации банка?» выбрать «Да»
#### 20. В выпадающем списке «Есть ли у вас судимость?» выбрать «Нет»
#### 21. В выпадающем списке «Есть ли у вас в собственности автомобиль?» выбрать «Да»
#### 22. В выпадающем списке «Есть ли у вас в собственности недвижимость?» выбрать «Да»
#### 23. Нажать кнопку «Рассчитать»
#### 24. Проверить результаты расчета

### Ожидаемый результат: 
#### Сообщение «Кредит предварительно одобрен». 
#### Результаты расчета: 
#### 1. Процентная ставка 28.61 %
#### 2. Ежемесячный платеж 9 680 Р
#### 3. Переплата по кредиту 16 165 Р
#### 4. Выплаты за весь срок кредита 116 165 Р
##### Tест-кейс https://docs.google.com/document/d/1ILdnEONI576Olapt5jUbUcfUe0i_DmFR/edit

# План тестирования возможности записи на обучение профессии "Тестировщик ПО"

# Виды тестирования:

В рамках проведения автоматизированного тестирования будут применены кейсы с позитивными и негативными сценариями.

## Предусловие:

# Открытие страницы профессии "Тестировщик ПО":


- Вариант 1:
1. На главной странице сайта нажать кнопу "Каталог курсов"

2. Нажать на блок "Программирование".

3. Выбрать курс "Тестировщик ПО".


- Вариант 2: 
1. На главной странице сайта нажать на кнопку блока "НЕО для начинающих".

2. В открывшемся списке курсов выбрать курс "Тестировщик ПО".


# Автоматизированные сценарии способов записи на курс

- Вариант 1:

1. Нажать на кнопку "Записаться".

2. В поле "Имя" ввести имя (Например Иван).

3. В поле с номером телефона ввести номер телефона(Например +7(999)999-99-99).

4. Нажать на кнопку "Записаться".

Ожидаемый результат: Появится всплывающая окно с надписью: "Ваша заявка отправлена, наш менеджер свяжется с вами в ближайшее время"



- Вариант 2:

1. Пролистать страницу до блока "Гарантия возврата денег".

2. В всплывающем окне в поле "Имя" ввести имя (Например Ivan).

3. В поле с номером телефона ввести номер телефона (Например +7(999)999-99-99).

4. Нажать на кнопку "Записаться на курс".

Ожидаемый результат: Появится всплывающая окно с надписью: "Ваша заявка отправлена, наш менеджер свяжется с вами в ближайшее время"

- Вариант 3:

1. Пролистать  страницу до блока "Запишитесь или получите консультацию".

2. В поле "Имя" ввести имя (Например Иван-Иванович).

3. В поле с номером телефона ввести номер телефона (Например 8(999)999-99-99).

4. Нажать на кнопку "Записаться".

Ожидаемый результат: Появится всплывающая окно с надписью: "Ваша заявка отправлена, наш менеджер свяжется с вами в ближайшее время"


# Негативные сценнарии отправки формы:

- Вариант 1:

1. В поле "Имя" ввести имя (Например И).

2. В поле с номером телефона ввести номер телефона(Например +7(999)999-99-99).

3. Нажать на кнопку "Записаться".

Ожидаемый результат: Под полем "Имя" появится надпись "Должно быть не короче 2 символов"


- Вариант 2:

1. В поле "Имя" ввести имя (Например Иван55).

2. В поле с номером телефона ввести номер телефона(Например +7(999)999-99-99).

3. Нажать на кнопку "Записаться".

Ожидаемый результат: Под полем "Имя" появится надпись "Должно состоять из букв"

- Вариант 3:

1. В поле "Имя" ввести имя (Например Иван!).

2. В поле с номером телефона ввести номер телефона(Например +7(999)999-99-99).

3. Нажать на кнопку "Записаться".

Ожидаемый результат: Под полем "Имя" появится надпись "Должно состоять из букв"

- Вариант 4:

1. Оставить поле "Имя" пустым

2. В поле с номером телефона ввести номер телефона(Например +7(999)999-99-99).

3. Нажать на кнопку "Записаться".

Ожидаемый результат: Под полем "Имя" появится надпись "Обязательное поле"

- Вариант 5:

1. В поле "Имя" ввести имя (Например Иван).

2. В поле с номером телефона ввести номер телефона(Например 99-99-99).

3. Нажать на кнопку "Записаться".

Ожидаемый результат: Под полем с номером телефона появится сообщение "Номер в формате +9 (999)999-99-99"

- Вариант 6:

1. В поле "Имя" ввести имя (Например Иван).

2. В поле с номером телефона ввести номер телефона(Например +9(999)999-99-99-99).

3. Нажать на кнопку "Записаться".

Ожидаемый результат: Под полем с номером телефона появится сообщение "Номер в формате +9 (999)999-99-99"

- Вариант 7:

1. В поле "Имя" ввести имя (Например Иван).

2. Поле с номером телефона оставить пустым

3. Нажать на кнопку "Записаться".

Ожидаемый результат: Под полем с номером телефона появится сообщение "Обязательное поле"



# Используемые инструменты:
- Intellig IDEA.

В Intellig IDEA можно подключить плагины, необходимиые для ускорения процесса автотестирования.

- Github

В Github есть возможность подключить CI на автотесты.

- Браузер Google chrome

Браузер Google chrome является наиболее популярным браузером.


# Необходимые разрешения/данные/доступы:
- Разрешение на автоматизированное тестирование рабочего сайта. 
- Доступ к базе данных и API сайта.

# Возможные риски при автоматизации:
- Вероятность уронить сайт в ходе автотестирования.
- Сложности с поиском правильных локаторов.
- Если произойдёт изменение в названии курса, используемых в тестах блоках на сайте, придётся редактировать тесты, так как они перестанут проходить.

# Необходимые специалисты для автоматизации:
Инженеры автоматизированного тестирования.


# Оценка времени с учётом рисков (в часах)
На автоматизированное тестирование потребуется 48 рабочих часов.


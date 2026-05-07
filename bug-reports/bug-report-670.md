# На странице товара "Sauce Labs Fleece Jacket" данные не соответствуют карточке товара

## id 670

**Описание:**
В каталоге имеется карточка товара с названием "Sauce Labs Fleece Jacket" и описанием (название, описание, цена). При открытии страницы данного товара видно, что данные не соответствуют карточке товара

**Окружение:**
1. ОС: Windows 10 pro 22h2 19045.6456
2. Браузер: Chrome Версия: 147.0.7727.117
3. Сайт: [Swag Labs](saucedemo.com)
4. Версия сайта: Production

**Тестовые данные:**
- Логин: problem_user
- Пароль: secret_sauce
- Сайт: [Swag Labs](saucedemo.com)

**Предусловие:**
1. Открыть браузер
2. Перейти на сайт [Swag Labs](saucedemo.com) 
3. Авторизоваться с тестовыми данными

**Шаги:**
1. В каталоге на карточке товара "Sauce Labs Fleece Jacket" нажать на название

**ФР:**
1. Открыта страница выбранного товара
2. Неверное название товара, вместо "Sauce Labs Fleece Jacket" написано "Item not found"
3. Неверное описание товара, вместо "It's not every day that you come across a midweight quarter-zip fleece jacket capable of handling everything from a relaxing day outdoors to a busy day at the office." написано "We're sorry, but your call could not be completed as dialled. Please check your number, and try your call again. If you are in need of assistance, please dial 0 to be connected with an operator. This is a recording. 4 T 1."
4. Неверная стоимость товара, вместо "$49.99" указано "$√-1"

**ОР:**
1. Открыта страница выбранного товара
2. Название на странице товара соответствует названию в карточке товара "Sauce Labs Fleece Jacket"
3. Описание на странице товара соответствует описанию в карточке товара "Sauce Labs Fleece Jacket"
4. Цена на странице товара соответствует цене, указанной в карточке товара "Sauce Labs Fleece Jacket"

**Приоритет:** *Medium*

**Серьезность:** *Major*

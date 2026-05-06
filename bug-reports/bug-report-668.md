# Не все товары из каталога добавляются в корзину
## id 668

**Описание:**
В каталоге товаров есть возможность добавить в корзину только определенные товары, а именно товары с названиями “Sauce Labs Backpack” “Sauce Labs Bike Light“ “Sauce Labs Onesie“

**Окружение:**
ОС: Windows 10 pro 22h2 19045.6456
Браузер: Chrome Версия: 147.0.7727.117
Сайт: [Swag Labs](saucedemo.com)
Версия сайта: Production

**Тестовые данные:**
- Логин: problem_user
- Пароль: secret_sauce

**Предусловие:**
1. Открыть браузер
2. Перейти на сайт [Swag Labs](saucedemo.com) 
3. Авторизоваться с тестовыми данными

**Шаги:**
1. Нажать кнопку “Add to cart“ на товаре “Sauce Labs Backpack”
2. Нажать кнопку “Add to cart“ на товаре  “Sauce Labs Bike Light“
3. Нажать кнопку “Add to cart“ на товаре “Sauce Labs Onesie“
4. Нажать кнопку “Add to cart“ на товаре “Sauce Labs Bolt T-Shirt“ 
5. Нажать кнопку “Add to cart“ на товаре “Sauce Labs Fleece Jacket“
6. Нажать кнопку “Add to cart“ на товаре  “Test.allTheThings() T-Shirt (Red)“
7. Нажать на иконку корзины в правом верхнем углу страницы

**ФР:**
1. При нажатии на кнопку “Add to cart“ на товарах с названием “Sauce Labs Backpack” “Sauce Labs Bike Light“ “Sauce Labs Onesie“ счетчик товаров в корзине увеличился на “3“
2. При нажатии на кнопку “Add to cart“ на товарах с названием “Sauce Labs Bolt T-Shirt“ “Sauce Labs Fleece Jacket“ “Test.allTheThings() T-Shirt (Red)“ счетчик товаров на корзине не увеличивается
3. Из 6 товаров в корзину добавлено 3

**ОР:**
1. При нажатии на кнопку “Add to cart“ на любых товарах в каталоге, счетчик товаров в корзине увеличится
2. При добавлении всех 6 товаров из каталога в корзину, счетчик на иконке корзины увеличится на “6”
Дополнительные материалы:

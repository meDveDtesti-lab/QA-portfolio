# Полный цикл от авторизации на сайте до оформления заказа

## id 139

**Тип:** *позитивный, функциональный*

**Тестовые данные:**
- Логин: standard_user
- Пароль: secret_sauce
- First name: Artem
- Last name: Naumov
- Postal code: 198216
- Сайт: [Swag Labs](saucedemo.com)

**Предусловие:**
1. Открыть браузер
2. Перейти на сайт [Swag Labs](saucedemo.com)

**Шаги:**
1. В поле ввода логина ввести "standard_user"
2. В поле ввода пароля ввести "secret_sauce"
3. Нажать кнопку "Login"
4. На карточке товара с названием "Sauce Labs Backpack" нажать кнопку "Add to cart"
5. На карточке товара с названием "Sauce Labs Onesie" нажать кнопку "Add to cart"
6. Справа сверху нажать на иконку корзины
7. В корзине нажать зеленую кнопку "Checkout"
8. На странице "Checkout: Your Information" в поле ввода First name ввести "Artem"
9. В поле ввода Last name ввести "Naumov"
10. В поле ввода Postal code ввести "198216"
11. Нажать зеленую кнопку "Continue"
12. На странице "Checkout: overview" нажать зеленую кнопку "Finish"

**ОР:**
1. При нажатии на кнопку "Login" происходит успешная авторизация под пользователем "standard_user"
2. Оба выбранных товара добавлены в корзину
3. При нажатии на иконку корзины происходит переход на страницу с выбранными товарами
4. В корзине отображаются товары с названием "Sauce Labs Backpack" и "Sauce Labs Onesie", другие товары отсутствуют
5. При нажатии на кнопку "Checkout" происходит переход на страницу Checkout: Your Information
6. При нажатии на кнопку "Continue" происходит переход на страницу "Checkout: overview"
7. На странице "Checkout: overview" отображаются товары с названием "Sauce Labs Backpack" и "Sauce Labs Onesie"
8. При нажатии на кнопку "Finish" происходит переход на страницу "Checkout: Complete!" с уведомлением "Thank you for your order!"

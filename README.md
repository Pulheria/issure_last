#Сценарий использования к функции системы «Добавление товара в корзину»
***************

<span style = "color: red">**Актор**</span style> - пользователь *зарегистрированный / не зарегистрированный*
После перехода на сайт интернет-магазина по [ссылке](http://www.7pizza.ru) в браузере Пользователю отобразится экранная форма [макет 1].

**Ветка 1**. ~~Пользователь~~ нажимает кнопку Добавить под изображением товара.
**********
**Ветка 2** Пользователь переходит к просмотру информации о товаре. Для выбора товара пользователь нажимает кнопку Добавить под изображением товара.
**********
1. Каждому товару присвоен идентификационный номер ~~(id)~~ не для обнаружения товара в БД. В результате операции обнаруженный товар отобразится в корзине пользователя.
2. Система выводит информационное сообщение: ***Товар добавлен в корзину***

3. Пиктограмма корзины в правом углу верхней панели измениться. Отобразится количество товаров, добавленных пользователем.


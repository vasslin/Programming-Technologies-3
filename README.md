# Техническое задание №3
## Проектирование мобильного приложения сервиса доставки еды.
### Технологии программирования, НИУ ВШЭ


В рамках задания было спроектировано приложение для сервиса доставки еды.
Проектирование осуществлялось при помощь составления UML-диаграмм:
- [x] диаграмма вариантов использования (use case diagram)
- [x] - диаграмма последовательности (sequence diagram)
- [x] - диаграмма состояний (state diagram)
- [x] - диаграмма действий (activity diagram)
- [x] - диаграмма классов (class diagram)

### Описание системы
Основная задача приложения - осуществить процесс реализации заказа, начиная с добавления товаров в корзину, заканчивая получения заказа пользователем.
Основные лица, с которыми взаимодействует программа: ```Пользователь```, ```Курьер```, ```Магазин/Ресторан```.
Также приложение взаимодействует с *банком* для осуществления оплаты заказа.

__Процесс оформление заказа__:
```Пользователь``` Может просмотреть товары в меню (каталоге) и добавить товары в корзину. В меню товаров отображаются только те товары, которые есть в наличии в магазине/ресторане и доступны для заказа.
Для того, чтобы сделать заказ, ```Пользователю``` необходимо:
+ войти в систему
+ добавить товары в корзину (для добавления товаров в корзину необходимо посмотреть товары в меню товаров)
+ оплатить заказ









Спроектируйте базу данных сервиса по заказу еды, используя mysql.

**Требования к базе:**
1) Есть сущность партнеров, у которых есть название, адрес, и может быть текстовое описание
2) У каждого партнера Может быть множество позиций доступных для заказа. Каждая поизиция включает в себя название, описание, стоимость и может включать адрес фотографии
3) Есть сущность клиентов. У них есть номер телефона.
4) Клиенты могут создавать заказы, у каждого заказа обязаны быть координаты доставки и адрес доставки, а также время создания и статус заказа (новый, принят рестораном, доставляется, завершен) а также айди пользователя, совершившего заказ
5) Заказ включает в себя множество позиций от партнеров
6) Каждый заказ может включать в себя позиции только от одного партнера. Сделать на уровне базы данных это проблематично, поэтому примем просто как соглашение. Обычно такая логика решается на уровне кода самого приложения


### Задания
Напишите скрипт, который создаст базу данных по приведенной схеме и выполните следующие действия.
1) Заполните базу тестовыми данными, не менее 3 партнеров, не менее 3 позиций для заказа у каждого из партнеров. 3 Пользователя, у каждого из которых от 1 до 5 заказов, в каждом из заказов от 1 до 3 позиций блюд
2) Напишите запрос, который будет выводить номера заказов (их ИД), номер телефонов клиентов, название партнера
3) Добавьте еще одного партнера и минимум 1 позицию для него. Но не создавайте заказы. Сделайте запрос, который выведет таких партнеров, у которых еще не было ни одного заказа
4) Напишите запрос, который по ID пользователя и ID заказа выведет названия всех позиций из этого заказа.

### Как выполнять задание
В качестве решения домашнего задания необходимо предоставить sql файл со скриптом для создания базы и дополнительными запросами из заданий

Для работы можно использовать программу **Dbeaver**

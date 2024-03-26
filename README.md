# SQL
In this repository i will solve tasks from karpov.courses sql simulator. I will post the most difficult and interesting tasks (in my opinion) on different topics of sql (join, group by, etc).

Изначальные данные:
имеются 6 таблиц - courier_actions, couriers, orders, products, user_actions, users. 
В каждой таблице есть столбцы с данными.

courier_actions (action CHARACTER VARYING, courier_id INTEGER, order_id INTEGER, time TIMESTAMP WITHOUT TIME ZONE)

couriers (birth_date DATE, courier_id INTEGER, sex CHARACTER VARYING)

orders(creation_time TIMESTAMP WITHOUT TIME ZONE, order_id INTEGER, product_ids ARRAY)

products(name CHARACTER VARYING, price NUMERIC, product_id INTEGER)

user_actions (action CHARACTER VARYING, order_id INTEGER, time TIMESTAMP WITHOUT TIME ZONE, user_id INTEGER)

users(birth_date DATE, sex CHARACTER VARYING, user_id INTEGER)

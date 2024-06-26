
# Домашние задания по модулю  «Отказоустойчивость»

В этом репозитории расположены ваши домашние задания к каждой лекции. 

Обязательны к выполнению задачи без звездочек. Их нужно выполнить, чтобы получить зачёт.

Задачи со звёздочкой (*) — дополнительные задачи или задачи повышенной сложности. Их выполнять не обязательно, но они помогут вам глубже понять тему.

Любые вопросы по решению задач задавайте в чате учебной группы. Ссылку вы найдёте в письме на вашей электронной почте.
=======
# Домашнее задание к занятию "Отказоустойчивость в облаке" - Лапшов Сергей
=======
### Задание 1

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
SELECT 
    staff.first_name,
    staff.last_name,
    city.city,
    COUNT(customer.store_id) AS total_customers
FROM 
    staff
JOIN 
    store ON staff.store_id = store.store_id
JOIN 
    address ON store.address_id = address.address_id
JOIN 
    city ON address.city_id = city.city_id
JOIN 
    customer ON store.store_id = customer.store_id
GROUP BY 
    staff.first_name,
    staff.last_name,
    city.city
HAVING 
    COUNT(customer.store_id) > 300;

```

`При необходимости прикрепитe сюда скриншоты
![1](https://github.com/DavyRoy/sflt-homeworks_8-03/blob/main/Снимок%20экрана%20от%202024-05-13%2015-42-33.png)
---

### Задание 2

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
SELECT 
    COUNT(*) AS film_count
FROM 
    film
WHERE 
    length > (SELECT AVG(length) FROM film);

```

`При необходимости прикрепитe сюда скриншоты
![2](https://github.com/DavyRoy/sflt-homeworks_8-03/blob/main/Снимок%20экрана%20от%202024-05-13%2015-44-56.png)


---

### Задание 3

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
SELECT 
    DATE_FORMAT(payment_date, '%Y-%m') AS month,
    SUM(amount) AS total_payments,
    COUNT(*) AS rental_count
FROM 
    payment
GROUP BY 
    DATE_FORMAT(payment_date, '%Y-%m')
ORDER BY 
    total_payments DESC
LIMIT 
    1;

....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![3](https://github.com/DavyRoy/sflt-homeworks_8-03/blob/main/Снимок%20экрана%20от%202024-05-13%2015-46-38.png)

### Задание 4

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![]()

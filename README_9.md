
# Домашние задания по модулю  «Отказоустойчивость»

В этом репозитории расположены ваши домашние задания к каждой лекции. 

Обязательны к выполнению задачи без звездочек. Их нужно выполнить, чтобы получить зачёт.

Задачи со звёздочкой (*) — дополнительные задачи или задачи повышенной сложности. Их выполнять не обязательно, но они помогут вам глубже понять тему.

Любые вопросы по решению задач задавайте в чате учебной группы. Ссылку вы найдёте в письме на вашей электронной почте.
=======
# Домашнее задание к занятию "Отказоустойчивость в облаке" - Лапшов Сергей
=======
### Задание 1

1. `Получите уникальные названия районов из таблицы с адресами, которые начинаются на “K” и заканчиваются на “a” и не содержат пробелов.`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
SELECT DISTINCT district
FROM addresses
WHERE district LIKE 'K%' AND district LIKE '%a%' AND district NOT LIKE '% %';

```

`При необходимости прикрепитe сюда скриншоты
![1](https://github.com/DavyRoy/sflt-homeworks_8-03/blob/main/Снимок%20экрана%20от%202024-05-13%2008-51-27.png)
---

### Задание 2

`Приведите ответ в свободной форме........`

1. `Получите из таблицы платежей за прокат фильмов информацию по платежам, которые выполнялись в промежуток с 15 июня 2005 года по 18 июня 2005 года включительно и стоимость которых превышает 10.00.`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
SELECT *
FROM payment
WHERE payment_date BETWEEN '2005-06-15' AND '2005-06-18' AND amount > 10.00;

```

`При необходимости прикрепитe сюда скриншоты
![2](https://github.com/DavyRoy/sflt-homeworks_8-03/blob/main/Снимок%20экрана%20от%202024-05-13%2009-04-20.png)


---

### Задание 3

`Приведите ответ в свободной форме........`

1. `Получите последние пять аренд фильмов.`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
SELECT *
FROM rental
ORDER BY rental_date DESC
LIMIT 5;

....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![3](https://github.com/DavyRoy/sflt-homeworks_8-03/blob/main/Снимок%20экрана%20от%202024-05-13%2009-05-27.png)

### Задание 4

`Приведите ответ в свободной форме........`

1. `Одним запросом получите активных покупателей, имена которых Kelly или Willie.

Сформируйте вывод в результат таким образом:

все буквы в фамилии и имени из верхнего регистра переведите в нижний регистр,
замените буквы 'll' в именах на 'pp'.`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
SELECT LOWER(REPLACE(first_name, 'LL', 'pp')) AS customer_name_lower 
FROM customer 
WHERE (first_name = 'Kelly' OR first_name = 'Willie') AND active = 1;

....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![4](https://github.com/DavyRoy/sflt-homeworks_8-03/blob/main/Снимок%20экрана%20от%202024-05-13%2009-11-51.png)
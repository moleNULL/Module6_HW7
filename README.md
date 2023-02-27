# &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NIX Solutions Module #6 Homework #7

                                                 Задача: 
                          Расширить проект Sample7 добавив Infrastructure.RateLimit
                    
● Создать новый проект Infrastructure.RateLimit\
● В нем создать middleware и фильтр в качестве атрибута, которые будут ограничивать запросы\
● Использовать Redis для реализации\
● В качестве ключа к данным использовать сложение двух значений:\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●  IP запроса откуда пришло\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;●  endpoint\
● Если же в течении 1 минуты пришло больше 10 запросов с одного и того же IP на один и тот же запрос,\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;то ограничить доступ с результатом статуса 429 Too Many Requests\
● Для демонстрации:\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;● middleware использовать в MSS каталога\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;● атрибут повесить на какой то из методов в MSS корзины

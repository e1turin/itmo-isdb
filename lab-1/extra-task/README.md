> Запрос: выведите имена персонажей, которые находились на локации, название
> которой начинается с буквы "А" и содержит хотя бы 5 букв, в то время как
> разрабатывался метод защиты биологических существ описание которого длиннее
> 10 букв. Метод разрабатывался для существ с именем, состоящим ровно из 5 или
> 7 букв. Причем, интервалы эпохи, когда это происходило в диапозоне: 15 - 16
> век 
> 
> Если таких персонажей несколько (нужно больше инсертов вставить в табличку!!!
> Так что не если??), то отсортируйте их по длине имени в убывающем порядке.
> 
> Вторая таска:
> 
> Ваша предметная область: Зоопарк  
> 
> Сами задания: 
> 1) Придумать ER модель и нарисовать даталогическую модель для
> предложенной предметной области (минимум 8 сущностей, в одной из сущностей
> минимум 6 атрибутов, связь вида многие-ко-многим, один-к-одному)
> 
> 2) Привести DDL для реализации сущностей, которые участвуют в связях
> многие-ко-многим, один-к-одному (связи тоже должны присутствовать в коде)
> 
> 3) Привести пример использования языка DML
 
- Запрос немного не подходит для моей модели, поэтому перефразирую его:

> Доброго дня, обнаружил, что запрос немного не подходит для моей модели,
> поэтому предлагаю перефразировать его: 

```
«выведите имена персонажей, 
- [x] которые находились на локации, 
    - [x] название которой  начинается с буквы "А" и содержит хотя бы 5 букв, 
- [x] 
- [x] знающих о ж. существе, 
    - [x] у  которого описание метода защиты длиннее 10 букв. 
        - [x] Метод защиты использовался  против существ с именем, 
            - [x] состоящим ровно из 5 или 7 букв. 
            - [x] Причем, интервалы  эпохи, когда эти существа жили, в диапозоне: 15 - 16 век»
```

> Дело в том, что методы защиты просто присущи определенным видам ж. существ и нельзя сказать, когда метод был разработан

Выполнение заданий 1 таски:

Нужный запрос составлен (см.  [extra-select.sql](./sql/extra-select.sql)). Для заполнения базы данных использовался pgAdmin и запросы из [workspace.sql](../sql/dml/workspace.sql)

Выполнения заданий 2 таски:

1. ER-Диаграмму по Зоопарку (см. [lab-1-extra-task.drawio.png](./res/lab-1-extra-task.drawio.png))  
2. (см. [ddl.sql](./sql/ddl.sql))
3. (см. [dml.sql](./sql/dml.sql))
    - так же примеры запросов, использовавшихся для заполнения таблицы в первой
    таске (см. [workspace.sql](../sql/dml/workspace.sql))
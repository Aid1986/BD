Сурмач Андрей Андреевич
# BD

# Задание_1
1.	Сотрудники
   o	идентификатор, первичный ключ, serial
   o	фамилия varchar(50)
   o	имя varchar(50)
   o	отчество varchar(50)
   o	зарплата numeric(10, 2)
   o	должность varchar(100)
   o	идентификатор структурного подразделения, внешний ключ, integer
2.	Структурные подразделения
   o	идентификатор, первичный ключ, serial
   o	название varchar(100)
   o	тип (отдел/группа/департамент) varchar(50)
   o	подробное название varchar(100)
3.	Адреса
   o	идентификатор, первичный ключ, serial
   o	регион varchar(100)
   o	город varchar(100)
   o	улица varchar(100)
   o	дом varchar(10)
   o	идентификатор сотрудника, внешний ключ, integer
4.	Проекты
   o	идентификатор, первичный ключ, serial
   o	название varchar(100)
   o	идентификатор сотрудника, внешний ключ, integer
5.	Дата приёма
   o	идентификатор, первичный ключ, serial
   o	дата приёма date
   o	идентификатор сотрудника, внешний ключ, integer
6.	Компетенции
   o	идентификатор, первичный ключ, serial
   o	компетенция varchar(100)
   o	идентификатор сотрудника, внешний ключ, integer
7.	Подразделения_и_проекты
   o	идентификатор, первичный ключ, serial
   o	идентификатор структурного подразделения, внешний ключ, integer
   o	идентификатор проекта, внешний ключ, integer

![1](https://github.com/Aid1986/BD/blob/main/BD.png)

![2](https://github.com/Aid1986/BD/blob/main/BD_v_Git.png)

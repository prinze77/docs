---
editable: false
---

# VAR

_Агрегатные функции_

#### Синтаксис


```
VAR( value )
```

#### Описание
Возвращает статистическую дисперсию всех значений в выражении на основе выборки из совокупности.

**Типы аргументов:**
- `value` — `Число`


**Возвращаемый тип**: `Дробное число`

#### Примеры

```
VAR([Profit])
```


#### Поддержка источников данных

`Материализованный датасет`, `ClickHouse 1.1`, `Microsoft SQL Server 2017 (14.0)`, `MySQL 5.6`, `PostgreSQL 9.3`.

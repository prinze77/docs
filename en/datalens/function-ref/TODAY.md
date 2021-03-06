---
editable: false
---

# TODAY

_Date/Time functions_

#### Syntax


```
TODAY()
```

#### Description
Returns the current date, depending on the data source and connection type:
- For a direct connection, the function returns the server date and time of the source.
- On materialization, the function returns the UTC+3 date and time.


**Return type**: `Date`

#### Examples

```
TODAY() = #2019-01-23#
```


#### Data source support

`Materialized Dataset`, `ClickHouse 1.1`, `Microsoft SQL Server 2017 (14.0)`, `MySQL 5.6`, `PostgreSQL 9.3`.

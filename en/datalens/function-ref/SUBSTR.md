---
editable: false
---

# SUBSTR

_String functions_

#### Syntax


```
SUBSTR( string, from_index [ , length ] )
```

#### Description
Returns the substring `string` starting from the index `from_index`.

If an additional argument `length` is specified, a substring of the specified length is returned.

**Argument types:**
- `string` — `String`
- `from_index` — `Number (whole)`
- `length` — `Number (whole)`


**Return type**: `String`

#### Examples

```
SUBSTR("Computer", 2) = "mputer"
```


#### Data source support

`Materialized Dataset`, `ClickHouse 1.1`, `Microsoft SQL Server 2017 (14.0)`, `MySQL 5.6`, `PostgreSQL 9.3`.

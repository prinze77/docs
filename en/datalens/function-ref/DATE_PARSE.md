---
editable: false
---

# DATE_PARSE

_Type conversion functions_

#### Syntax


```
DATE_PARSE( value )
```

#### Description
Converts the `value` expression to date format. Unlike [DATE](DATE.md), it supports multiple formats.

**Argument types:**
- `value` — `String`


**Return type**: `Date`

#### Examples

```
DATE_PARSE("2019-01-02 03:04:05") = #2019-01-02#
```

```
DATE_PARSE("2019-01-02") = #2019-01-02#
```

```
DATE_PARSE("20190102") = #2019-01-02#
```

```
DATE_PARSE("2019.01.02") = #2019-01-02#
```

```
DATE_PARSE("02/01/2019") = #2019-01-02#
```

```
DATE_PARSE("02/01/19") = #2019-01-02#
```

```
DATE_PARSE("2019 Jan 02") = #2019-01-02#
```

```
DATE_PARSE("2019 Jan") = #2019-01-01#
```

```
DATE_PARSE("201901") = #2019-01-01#
```

```
DATE_PARSE("2019") = #2019-01-01#
```


#### Data source support

`Materialized Dataset`, `ClickHouse 1.1`.

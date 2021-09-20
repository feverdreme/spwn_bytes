  
# **@byte**: 
 
## Constructors:

## **new**:

> **Printed:** 
>```spwn
>(data: @number | @string | @byte) { /* code omitted */ }
>``` 
>**Type:** `@macro` 
>## Description: 
> _Abstraction to store a byte_
>### Example: 
>```spwn
> byte1 = @byte::new('FF')
>byte2 = @byte::new(200)
>$.assert(byte1.hdata == 255)
>$.assert(byte2.hdata == 200)
>$.assert(byte1 == @byte::new(255))
>```
>## Arguments:
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | **`data`** | @number or @string or @byte | | |
>

## Macros:

## **convert\_number**:

> **Printed:** 
>```spwn
>(n: @number) { /* code omitted */ }
>``` 
>**Type:** `@macro` 
>## Arguments:
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | **`n`** | @number | | |
>

## **convert\_string**:

> **Printed:** 
>```spwn
>(s: @string) { /* code omitted */ }
>``` 
>**Type:** `@macro` 
>## Arguments:
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | **`s`** | @string | | |
>

## Operator Implementations:

## **\_equal\_**:

> **Printed:** 
>```spwn
>(self, other: @byte) { /* code omitted */ }
>``` 
>**Type:** `@macro` 
>## Arguments:
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | **`other`** | @byte | | |
>

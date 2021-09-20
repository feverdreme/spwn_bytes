  
# **@bytestream**: 
 
## Constructors:

## **new**:

> **Printed:** 
>```spwn
>(filepath: @string) { /* code omitted */ }
>``` 
>**Type:** `@macro` 
>## Description: 
> _Stream to read bytes_
>### Example: 
>```spwn
> bs = @bytestream::new('path/to/binary')
>```
>## Arguments:
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | **`filepath`** | @string | | |
>

## Macros:

## **read**:

> **Printed:** 
>```spwn
>(self, numbytes: @number = 1) { /* code omitted */ }
>``` 
>**Type:** `@macro` 
>## Description: 
> _Read a certain number of bytes, default is 1_
>### Example: 
>```spwn
> bs = @bytestream::new('bytes')
>$.assert(bs.read(5) == [22, 50, 92, 23, 105])
>```
>## Arguments:
>
>| # | name | type | default value | description |
>| - | ---- | ---- | ------------- | ----------- |
>| 1 | `numbytes` | @number | `1` | |
>

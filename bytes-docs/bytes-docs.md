# Documentation for `bytes` 
_Generated using `spwn doc [file name]`_
## Info:

- Uses 1 groups
- Uses 0 colors
- Uses 0 block IDs
- Uses 1 item IDs

- Adds 0 objects
# Type Implementations:
- [**@byte**](bytes-docs/byte.md)
- [**@bytestream**](bytes-docs/bytestream.md)
# Exports:
 **Printed:** 
```spwn
{byte: (data: @number | @string | @byte) { /* code omitted */ },bytestream: (filepath: @string) { /* code omitted */ }}
``` 
**Type:** `@dictionary` 

## Constructors:

## **byte**:

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

## **bytestream**:

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

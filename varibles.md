In Bear types are optional for varibles.

"var" makes a mutable varible so its value can change in the future.
"let" makes an immutable or constant varible so its value cant change in the future.

``` swift
let num: int = 5
let word: string = "Hello, world!"
let dec: float = 2.5
let letter: char = 'A'
```

In Bear you can also have strong types if you import the "types" namespace.

``` golang
import "types"
```
Integer types

Length | Signed | Unsigned |
--- | --- | --- |
8-bit | i8 | u8 |
16-bit | i16 | u16
32-bit | i32 | u32 
64-bit | i64 | u64
126-bit | i128 | u128
arch | isize | usize

Integer Literals

Number literals | Example |
--- | --- |
Decimal | 98_222
Hex | 0xff
Octal | 0o77
Binary | 0b1111_0000
Byte(```u8``` only) | b'A'

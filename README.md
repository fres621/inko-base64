> [!IMPORTANT]  
> As of 27/03/25, inko-base64 has been discontinued.
>
> base64 support is now available in the standard library as of Inko v0.18.1
>
> For more information refer to [inko docs / std.base64](https://docs.inko-lang.org/std/main/module/std/base64/)

# Inko Base64

This is an Inko package to encode and decode base64 strings

## Examples

```rb
import base64(Base64)

let encoded_string = Base64.encode("Hello Inko")

# Note that Base64.decode will return a Result.Error to an invalid input
let decoded = Base64.decode(encoded_string).get
```

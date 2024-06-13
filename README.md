# Inko Base64
This is an Inko package to encode and decode base64 strings

## Examples
```rb
import base64(Base64)

let encoded_string = Base64.encode("Hello Inko")

# Note that Base64.decode will return a Result.Error to an invalid input
let decoded = Base64.decode(encoded_string).get
```

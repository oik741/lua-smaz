# Lua smaz

simple compression library suitable for compressing very short strings

## Running the tests

TODO

## Usage
```lua
smaz = require("smaz")

test_string = "StringToEncode"

compressed_string = smaz.compress(test_string)

uncompressed_string, err = smaz.decompress(compressed_string)

if not uncompressed_string then
    print("Ooops, error: " .. err)
else
    print("Hooray!")
end
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


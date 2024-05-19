# static-asset

This PROS template enables users to encode regular files into PROS program binaries. It's meant to be more convenient than using an SD-Card or a C array

## Usage

To encode an asset into the program, put said file into a folder named `static` in the root project directory.

To read the encoded file, use the following macro:

```cpp
ASSET(example_txt)
```

The macro creates an object of type `asset`. Note that this has to be done in the global scope
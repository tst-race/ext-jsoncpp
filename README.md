# JsonCpp for RACE

This repo provides scripts to custom-build the
[JsonCpp library](https://github.com/open-source-parsers/jsoncpp) for RACE.

## License

The JsonCpp library is licensed under the MIT license.

Only the build scripts in this repo are licensed under Apache 2.0.

## Dependencies

JsonCpp has no dependencies on any custom-built libraries.

## How To Build

The [ext-builder](https://github.com/tst-race/ext-builder) image is used to
build JsonCpp.

```
git clone https://github.com/tst-race/ext-builder.git
git clone https://github.com/tst-race/ext-jsoncpp.git
./ext-builder/build.py \
    --target linux-x86_64 \
    ./ext-jsoncpp
```

## Platforms

JsonCpp is built for the following platforms:

* `linux-x86_64`
* `linux-arm64-v8a`
* `android-x86_64`
* `android-arm64-v8a`

## How It Is Used

JsonCpp is used by the <TO-BE-NAMED> encoding component.

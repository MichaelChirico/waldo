# Proxy for waldo comparison

Use this generic to override waldo's default comparison if you need to
override the defaults (typically because your object stores data in an
external pointer).

waldo comes with methods for a few common cases:

- data.table: the `.internal.selfref` and `index` attributes are set to
  `NULL`. Both attributes are used for performance optimisation, and
  don't affect the data.

- `xml2::xml_node`: the underlying XML data is stored in memory in C,
  behind an external pointer, so the we best can do is to convert the
  object to a string.

- Classes from the `RProtoBuf` package: like XML objects, these store
  data in memory in C++ and only expose string names to R. Fortunately,
  these have well-understood string representations that we can use for
  comparisons. See
  <https://protobuf.dev/reference/cpp/api-docs/google.protobuf.text_format/>

## Usage

``` r
compare_proxy(x, path = "x")
```

## Arguments

- x:

  An object.

- path:

  Path

## Value

A list with two components:

- `object`: the modified object

- `path`: an updated path showing what modification was applied

# Changelog

## waldo (development version)

## waldo 0.6.2

CRAN release: 2025-07-11

- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md) now
  goes into more details if you’re comparing an S3 object with a base
  object of the same type
  ([\#218](https://github.com/r-lib/waldo/issues/218)).
- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md)
  ignores read-only S7 properties, only comparing the underlying data
  stored in attributes
  ([\#219](https://github.com/r-lib/waldo/issues/219)).
- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md) can
  compare weakrefs.

## waldo 0.6.1

CRAN release: 2024-11-07

- Only use special bit64 comparison if package is installed.

## waldo 0.6.0

CRAN release: 2024-11-04

- waldo no longer imports tibble and rematch2
  ([@olivroy](https://github.com/olivroy),
  [\#196](https://github.com/r-lib/waldo/issues/196)), and requires R
  4.0.0.

- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md) now
  gives informative errors if you misspecify the argument types
  ([\#181](https://github.com/r-lib/waldo/issues/181)).

- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md)
  displays an extract digit in numeric comparisons, making it a bit
  easier to see the different
  ([\#141](https://github.com/r-lib/waldo/issues/141)). It can also show
  numeric differences between int64 objects and integers/doubles when
  `tolerance` is set
  ([\#159](https://github.com/r-lib/waldo/issues/159)).

- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md) gains
  basic support for S7 objects
  ([\#200](https://github.com/r-lib/waldo/issues/200)), and can now
  distinguish between objects that differ only in the value of their S4
  bit ([\#189](https://github.com/r-lib/waldo/issues/189)).

- `compare(list_as_map = TRUE)` now preserves attributes
  ([\#185](https://github.com/r-lib/waldo/issues/185)).

## waldo 0.5.3

CRAN release: 2024-08-23

- waldo no longer imports fansi ([@olivroy](https://github.com/olivroy),
  [\#192](https://github.com/r-lib/waldo/issues/192)).

## waldo 0.5.2

CRAN release: 2023-11-02

- Fixes for upcoming R-devel changes.

## waldo 0.5.1

CRAN release: 2023-05-08

- Tolerance is also taken into account when displaying differences
  ([\#173](https://github.com/r-lib/waldo/issues/173)).

- `NA_real_` and `NaN` are only treated as non-equal when tolerance is
  non-null. That means that `testthat::expect_equal(NaN, NA_real_)` will
  pass but `testthat::expect_identical(NaN, NA_real_)` will fail
  ([\#174](https://github.com/r-lib/waldo/issues/174)).

## waldo 0.5.0

CRAN release: 2023-05-01

- You can opt-out of quoting strings with `quote_strings = FALSE`
  ([\#145](https://github.com/r-lib/waldo/issues/145)).

- Improvements to missing value handling:

  - `NA_character_` and `"NA"` are no longer treated as equal
    ([\#162](https://github.com/r-lib/waldo/issues/162)).

  - `NA_real_` and `NaN` are no longer treated as equal
    ([@sorhawell](https://github.com/sorhawell),
    [\#150](https://github.com/r-lib/waldo/issues/150)).

  - Leading and trailing `NA`s are no longer omitted from output when
    the lengths of `x` and `y` are unequal
    ([\#109](https://github.com/r-lib/waldo/issues/109)).

- The `balanced` attribute used by some `POSIXlt` objects in R 4.3 and
  greater is now ignored
  ([\#160](https://github.com/r-lib/waldo/issues/160)).

- 3d (and greater) numeric arrays no longer cause an error
  ([\#148](https://github.com/r-lib/waldo/issues/148)).

- Support for complex numbers is improved
  ([\#146](https://github.com/r-lib/waldo/issues/146)).

- `ignore_attr = "class"` now works for more types of input
  ([\#143](https://github.com/r-lib/waldo/issues/143)).

## waldo 0.4.0

CRAN release: 2022-03-16

- Atomic S3 classes with format methods now use those methods when
  displaying comparisons
  ([\#98](https://github.com/r-lib/waldo/issues/98)). If the printed
  representation is the same, they fallback to displaying the underlying
  data.

- Rowwise data frame comparisons are now much much faster
  ([\#116](https://github.com/r-lib/waldo/issues/116)), and respect the
  `max_diffs` argument ([@krlmlr](https://github.com/krlmlr),
  [\#110](https://github.com/r-lib/waldo/issues/110)).

- Unnamed environments now compare by value, not by reference (i.e. if
  two environments contain the same values, they compare the same, even
  if they’re different environments)
  ([\#127](https://github.com/r-lib/waldo/issues/127)). Environments
  that contain self-references are handled correctly
  ([\#117](https://github.com/r-lib/waldo/issues/117)). Differences
  between pairs of environments are only ever reported once.

- In the unlikely event that you have bare CHARSXP objects, waldo now
  handles them ([\#121](https://github.com/r-lib/waldo/issues/121)).

- S4 objects are labelled with their class, not all superclasses
  ([\#125](https://github.com/r-lib/waldo/issues/125)).

- [`compare_proxy()`](https://waldo.r-lib.org/dev/reference/compare_proxy.md)
  ignores the `"index"` attribute for data tables
  ([@krlmlr](https://github.com/krlmlr),
  [\#107](https://github.com/r-lib/waldo/issues/107)), and works again
  for `RProtoBuf` objects
  ([@MichaelChirico](https://github.com/MichaelChirico),
  [\#119](https://github.com/r-lib/waldo/issues/119))

- Infinite values can be compared with a tolerance
  ([@dmurdoch](https://github.com/dmurdoch),
  [\#122](https://github.com/r-lib/waldo/issues/122)).

## waldo 0.3.1

CRAN release: 2021-09-14

- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md)ing
  data frames now works independently of `option(max.print)`
  ([\#105](https://github.com/r-lib/waldo/issues/105)).

- Fixed regression when comparing vectors with missing values
  ([\#102](https://github.com/r-lib/waldo/issues/102)).

## waldo 0.3.0

CRAN release: 2021-08-23

- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md) is now
  considerably faster when comparing complex objects that don’t have any
  differences (thanks to strategic use of
  [`identical()`](https://rdrr.io/r/base/identical.html))
  ([\#86](https://github.com/r-lib/waldo/issues/86)).

- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md) gains
  two improvements to low-level diffs:

  - Structurally identical data frames
    ([\#78](https://github.com/r-lib/waldo/issues/78)) and numeric
    matrices ([\#76](https://github.com/r-lib/waldo/issues/76)) gain a
    row-by-row diff that makes it easier to see where exactly values
    differ.

  - An element-by-element diff will be automatically used if it’s
    shorter than the “smart” diff. This improves diff quality when
    comparing two vectors that aren’t really related
    ([\#68](https://github.com/r-lib/waldo/issues/68)).

- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md) gains
  a `list_as_map` argument thanks to an idea from
  [@dmurdoch](https://github.com/dmurdoch). It allows you to compare the
  behaviour of two lists when they are used to connect names to values
  (i.e. the list is operating as a map or dictionary). It removes
  `NULL`s and sorts named components
  ([\#72](https://github.com/r-lib/waldo/issues/72)).

- The objects involved in
  [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md) (as
  opposed to the caller of
  [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md))
  gained much greater ability to control the comparison.

  - Objects can now contain a `waldo_opts` attribute, a list with the
    same names and valid values as the arguments to
    [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md),
    which overrides the default comparisons
    ([@dmurdoch](https://github.com/dmurdoch)).

  - [`compare_proxy()`](https://waldo.r-lib.org/dev/reference/compare_proxy.md)
    is now called earlier (before type comparison) making it more
    flexible ([\#65](https://github.com/r-lib/waldo/issues/65)).

  - [`compare_proxy()`](https://waldo.r-lib.org/dev/reference/compare_proxy.md)
    gains a second argument, `path`, used to report how the proxy
    changed the object. This makes it easier to see when and how a proxy
    is used ([\#73](https://github.com/r-lib/waldo/issues/73)).

  - Proxies now exist for comparing RProtoBuf objects, converting them
    to proto text format
    ([\#82](https://github.com/r-lib/waldo/issues/82),
    [@michaelquinn32](https://github.com/michaelquinn32)).

- Comparing a list with symbol to a list without that element no longer
  errors ([@mgirlich](https://github.com/mgirlich),
  [\#79](https://github.com/r-lib/waldo/issues/79)).

## waldo 0.2.5

CRAN release: 2021-03-08

- On platforms without UTF-8 support, strings that differ only in their
  encoding are now correctly considered to be identical
  ([\#66](https://github.com/r-lib/waldo/issues/66)).

## waldo 0.2.4

CRAN release: 2021-02-11

- Additional arguments to
  [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md)
  generate a more informative warning
  ([\#58](https://github.com/r-lib/waldo/issues/58)).

- Numbers use a better algorithm for picking the number of decimal
  places to show ([\#63](https://github.com/r-lib/waldo/issues/63)).

- ASTs with identical deparsed strings now show exactly how the AST
  differs. Source references are now more comprehensively stripped using
  `rlang::zap_srcrefs()`

- S3 objects now show the base type, and no longer fails when the types
  are incompatible.

## waldo 0.2.3

CRAN release: 2020-11-09

- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md) gains
  a new `max_diffs` argument that allows you to control the maximum
  number of differences shown. Set `max_diffs = Inf` to see all
  differences ([\#49](https://github.com/r-lib/waldo/issues/49))

- Logical vectors fall back to element-by-element comparison in more
  cases ([\#51](https://github.com/r-lib/waldo/issues/51)).

- Long-form diff no longer confuses additions and deletions
  ([\#52](https://github.com/r-lib/waldo/issues/52),
  [@krlmlr](https://github.com/krlmlr)).

## waldo 0.2.2

CRAN release: 2020-10-15

- Handle S4 objects that have attributes that are not slots.

- Additions are now coloured blue and deletions yellow (instead of the
  opposite).

## waldo 0.2.1

CRAN release: 2020-10-08

- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md) now
  labels output as `old` and `new`, since that’s the most natural way to
  use it.

- [`compare()`](https://waldo.r-lib.org/dev/reference/compare.md) can
  selectively ignore attributes by providing vector to `ignore_attr`
  ([\#45](https://github.com/r-lib/waldo/issues/45)).

- [`print()`](https://rdrr.io/r/base/print.html) method gets `n`
  argument to allow explicitly specifying number of differences to show
  ([@mnazarov](https://github.com/mnazarov)).

- Improvements to comparison display:

  - Zero length vectors compare robustly
    ([\#39](https://github.com/r-lib/waldo/issues/39))

  - Line-by-line comparisons show modifications as deletion then
    addition, rather than addition then deletion
    ([\#44](https://github.com/r-lib/waldo/issues/44)).

  - Differences between numeric vectors are more robust, particularly in
    the presence of missing values
    ([\#43](https://github.com/r-lib/waldo/issues/43)). The number of
    digits selected has also been slightly improved so that you’re more
    likely to get exactly the number of digits needed.

## waldo 0.2.0

CRAN release: 2020-07-13

- All objects: class ([\#26](https://github.com/r-lib/waldo/issues/26))
  and names ([\#31](https://github.com/r-lib/waldo/issues/31)) are
  ignored when ignoring attributes.

- Numeric and logical vectors: clearer display of differences. Numbers
  are right-aligned, and we show the numbers not the differences.

- Character vectors: a trailing newline is no longer ignored
  ([\#37](https://github.com/r-lib/waldo/issues/37)).

- Lists: all elements of the unnamed lists are compared, not just the
  last! ([\#32](https://github.com/r-lib/waldo/issues/32))

- Lists: unclassed prior to comparison
  ([\#21](https://github.com/r-lib/waldo/issues/21)).

- Data frames: The internal representation of row names is no longer
  used; instead we use the same result of
  [`rownames()`](https://rdrr.io/r/base/colnames.html)
  ([\#23](https://github.com/r-lib/waldo/issues/23)).

- Environments: New `ignore_formula_env` and `ignore_function_env`
  arguments to ignore formula and function environments for
  compatibility with
  [`all.equal()`](https://rdrr.io/r/base/all.equal.html)
  ([\#24](https://github.com/r-lib/waldo/issues/24)).

- Expression objects: can now be compared
  ([\#29](https://github.com/r-lib/waldo/issues/29)).

- Calls: srcrefs and attributes are ignored.

------------------------------------------------------------------------

- [`compare_proxy()`](https://waldo.r-lib.org/dev/reference/compare_proxy.md)
  is now exported so that you can provide methods if your objects need
  special handling (particularly needed for objects that contain
  external pointers) ([\#22](https://github.com/r-lib/waldo/issues/22)).

- Fixed a partial argument name in
  [`as.list()`](https://rdrr.io/r/base/list.html).

## waldo 0.1.0

CRAN release: 2020-04-16

- Added a `NEWS.md` file to track changes to the package.

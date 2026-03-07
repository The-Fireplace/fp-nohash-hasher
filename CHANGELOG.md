# Changelog

## 0.1.0 - 2026-03-07

### Added

- Initial release of this crate. The following changes are differences from the original `nohash-hasher` crate:
  - The `IsEnabled` trait is now implemented for `char` and `bool`.
  - `CharMap` and `CharSet` types when `std` feature is enabled as concise `char` equivalents of `IntMap` and `IntSet`.
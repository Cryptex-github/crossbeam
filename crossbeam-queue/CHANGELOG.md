# Version 0.3.7

- Improve support for custom targets. (#922)

# Version 0.3.6

- Bump the minimum supported Rust version to 1.38. (#877)

# Version 0.3.5

- Add `ArrayQueue::force_push`. (#789)

# Version 0.3.4

- Implement `IntoIterator` for `ArrayQueue` and `SegQueue`. (#772)

# Version 0.3.3

- Fix stacked borrows violation in `ArrayQueue` when `-Zmiri-tag-raw-pointers` is enabled. (#763)

# Version 0.3.2

- Support targets that do not have atomic CAS on stable Rust. (#698)

# Version 0.3.1

- Make `SegQueue::new` const fn. (#584)
- Change license to "MIT OR Apache-2.0".

# Version 0.3.0

- Bump the minimum supported Rust version to 1.36.
- Remove `PushError` and `PopError`.

# Version 0.2.3

- Fix bug in release (yanking 0.2.2)

# Version 0.2.2

- Fix unsoundness issues by adopting `MaybeUninit`. (#458)

# Version 0.2.1

- Add `no_std` support.

# Version 0.2.0

- Bump the minimum required version to 1.28.
- Bump `crossbeam-utils` to `0.7`.

# Version 0.1.2

- Update `crossbeam-utils` to `0.6.5`.

# Version 0.1.1

- Update `crossbeam-utils` to `0.6.4`.

# Version 0.1.0

- Initial version with `ArrayQueue` and `SegQueue`.

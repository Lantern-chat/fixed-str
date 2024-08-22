fixed-str
=========

Small fixed-size string type that can only be a given length, no more or less, exactly `N` bytes.

`no_std` compatible.

## Usage

```rust
use fixed_str::FixedStr;

static TEST: FixedStr<4> = FixedStr::new("TEST");
```

# Cargo Features

* `serde`: Enables serialization and deserialization support via `serde`.
* `rkyv`: Enables serialization and deserialization support via `rkyv`.
* `schemars`: JSON schema generation support via `schemars`.
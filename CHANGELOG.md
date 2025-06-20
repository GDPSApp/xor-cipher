# Changelog

<!-- changelogging: start -->

## [4.0.1](https://github.com/GDPSApp/xor-cipher/tree/v4.0.1) (2025-06-13)

No significant changes.

## [4.0.0](https://github.com/GDPSApp/xor-cipher/tree/v4.0.0) (2024-09-21)

### Changes

- `xor_slice` and `cyclic_xor_slice` were removed in favor of more general functions,
  `xor` and `cyclic_xor` correspondingly.
  ([#3](https://github.com/GDPSApp/xor-cipher/pull/3))

## [3.0.0](https://github.com/GDPSApp/xor-cipher/tree/v3.0.0) (2024-09-21)

### Changes

- `cyclic_xor` and `xor` are now generic via accepting `AsMut<[u8]>` and `AsRef<[u8]>`.

  Also, `xor_cipher::in_place` was deleted in favor of specifying the functions in the root.
  ([#2](https://github.com/GDPSApp/xor-cipher/pull/2))

## [2.0.0](https://github.com/GDPSApp/xor-cipher/tree/v2.0.0) (2024-09-20)

### Changes

- The following functions in `xor_cipher::in_place` were renamed:

  - `xor_in_place -> xor`;
  - `cyclic_xor_in_place -> cyclic_xor`.
  ([#1](https://github.com/GDPSApp/xor-cipher/pull/1))

## [1.1.0](https://github.com/GDPSApp/xor-cipher/tree/v1.1.0) (2024-06-26)

No significant changes.

## [1.0.0](https://github.com/GDPSApp/xor-cipher/tree/v1.0.0) (2024-06-25)

No significant changes.

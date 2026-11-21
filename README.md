# SigmaOS-disk-usage

Disk usage analysis (df/du-style filesystem monitoring, space reporting)

- **Category:** System Services
- **Engine:** disk-usage
- **Tier:** 2
- **Language:** Rust
- **Provides:** sigmadiskusage

Part of the [SigmaOS](https://github.com/AaryanSinghChauhan09/SigmaOS)
multi-repository component ecosystem.

## Build & Test

```sh
cargo build
cargo test
```

## Contract

This component declares its interface in `COMPONENT.toml`:

- `provides` — capabilities other components may depend on
- `depends_on` — component names this component requires

## License

Apache-2.0 — see [LICENSE](LICENSE).

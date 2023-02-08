# Mozilla's Rust Crate Audits

Mozilla uses [cargo-vet](https://mozilla.github.io/cargo-vet/) to ensure
third-party Rust dependencies have been audited by Mozilla or another trusted
entity.

This repository automatically
[aggregates](https://mozilla.github.io/cargo-vet/multiple-repositories.html)
Mozilla's audits from various repositories to make them easily reusable by
others.

To import Mozilla's audits into another cargo-vet instance, add the following
lines to your `config.toml`:

```
[imports.mozilla]
url = "https://raw.githubusercontent.com/mozilla/supply-chain/main/audits.toml"
```

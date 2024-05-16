# Obelisk configured with Nix Flake

[Obelisk](https://github.com/obsidiansystems/obelisk) configured on nix flake, modifying the [issue](https://github.com/obsidiansystems/obelisk/issues/1063#issuecomment-1988022736).


## How to run obelisk (both x86_64-linux / aarch64-darwin)

```bash
nix run --impure
```

See this [draft](https://github.com/obsidiansystems/obelisk/pull/964) for the initiative to move toward purer evaluation with nix flake.

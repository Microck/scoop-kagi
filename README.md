# scoop-kagi

Scoop bucket for the `kagi` CLI — an agent-native Rust CLI for [Kagi](https://kagi.com) subscribers with JSON-first output.

## Install

```powershell
scoop bucket add kagi https://github.com/Microck/scoop-kagi
scoop install kagi
```

## Upgrade

```powershell
scoop update
scoop update kagi
```

## Verify Installation

```powershell
kagi --version
kagi --help
```

## Uninstall

```powershell
scoop uninstall kagi
scoop bucket rm kagi
```

## Troubleshooting

- **"Could not find bucket"**: Run `scoop bucket list` to verify the bucket is added.
- **"Hash mismatch"**: Run `scoop update kagi` to fetch the latest manifest with correct hashes.
- **Stale version**: Run `scoop update` first to refresh all buckets, then `scoop update kagi`.

## Related

- [kagi-cli](https://github.com/Microck/kagi-cli) — the CLI source code
- [homebrew-kagi](https://github.com/Microck/homebrew-kagi) — Homebrew tap for macOS/Linux

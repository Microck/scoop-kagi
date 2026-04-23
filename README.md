# scoop-kagi

[Scoop](https://scoop.sh/) bucket for [kagi-cli](https://github.com/Microck/kagi-cli) — an agent-native Rust CLI for Kagi subscribers with JSON-first output.

## Install

```powershell
scoop bucket add kagi https://github.com/Microck/scoop-kagi
scoop install kagi
```

## Usage

```powershell
# Search the web
kagi search "rust async patterns"

# Get a quick answer
kagi quick "what is the capital of Portugal"

# Fetch news
kagi news

# Summarize a URL
kagi summarize https://example.com/article
```

## Update

```powershell
scoop update kagi
```

The manifest uses Scoop's autoupdate feature, so new releases are picked up automatically from the [kagi-cli releases page](https://github.com/Microck/kagi-cli/releases).

## Requirements

- [Scoop](https://scoop.sh/) package manager
- Windows x86_64
- A [Kagi](https://kagi.com/) subscription (for API features)

## License

The kagi-cli tool is licensed under [MIT](https://github.com/Microck/kagi-cli/blob/main/LICENSE).

# pdnhan/maintain

Homebrew tap for macmaintain - Mac maintenance and optimization checker

## Installation

```bash
# Add the tap
brew tap pdnhan/maintain

# Install
brew install macmaintain
```

## Usage

```bash
# Run all checks
macmaintain

# Show help
macmaintain --help

# Run with Docker cleanup
macmaintain --prune-docker

# View man page
man macmaintain
```

## What it does

macmaintain performs read-only health checks on your Mac:

- **Security**: macOS updates, Firewall, SIP, Gatekeeper, FileVault
- **Storage**: Caches, Xcode data, Docker images, Ollama models
- **Performance**: Uptime analysis, disk space warnings
- **CLI Tools**: Detects unused binaries (>1 year without access)

## More information

GitHub repository: https://github.com/pdnhan/mac-maintenance-script

## Formula

This tap contains:

| Formula | Description |
| ------- | ----------- |
| `macmaintain` | Mac maintenance and optimization checker |

## Troubleshooting

### Updating

```bash
brew update
brew upgrade macmaintain
```

### Uninstalling

```bash
brew uninstall macmaintain
brew untap pdnhan/maintain
```
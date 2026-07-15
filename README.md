# Chrome browser cyp package

This repository automatically builds cyp packages for Google Chrome across all platforms.

## Platforms

| Platform | Architecture | File |
|----------|-------------|------|
| macOS ARM | arm64 | `chrome-{version}-macosarm64.cyp` |
| macOS Intel | x64 | `chrome-{version}-macosintel.cyp` |
| Linux | x64 | `chrome-{version}-linux64.cyp` |
| Windows | x64 | `chrome-{version}-win64.cyp` |

## Install

```bash
cyp install chrome
```

## Auto Update

This package is automatically updated daily by GitHub Actions. When a new Chrome stable version is released, the Action will:

1. Detect the new version
2. Download Chrome for all platforms
3. Build `.cyp` packages
4. Create a GitHub Release with all platform packages

## Manual Trigger

Go to Actions → Update Chrome → Run workflow

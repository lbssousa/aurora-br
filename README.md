# aurora-br

[![Stable Images](https://github.com/lbssousa/aurora-br/actions/workflows/build-image-stable.yml/badge.svg)](https://github.com/lbssousa/aurora-br/actions/workflows/build-image-stable.yml) [![Latest Images](https://github.com/lbssousa/aurora-br/actions/workflows/build-image-latest-main.yml/badge.svg)](https://github.com/lbssousa/aurora-br/actions/workflows/build-image-latest-main.yml)

A Brazilian customization of [Aurora](https://github.com/ublue-os/aurora) — a delightful KDE desktop experience for end-users.

This image builds on top of Aurora and adds:
- **Epson printer support** (via ESC/P-R driver)
- **Big parental controls** (BigLinux parental controls integration)

## What Makes this Image Different?

### Added Packages (Build-time)
- **Epson printer drivers**: ESC/P-R driver for Epson printers common in Brazil
- **Parental controls**: BigLinux parental controls (big-parental-controls)

## Based on Aurora

aurora-br is based on [Aurora](https://github.com/ublue-os/aurora) and inherits all its features:

- KDE Plasma Desktop
- Immutable/atomic updates via bootc
- Universal Blue infrastructure

## Documentation

1. [Aurora Documentation](https://docs.getaurora.dev/)
2. [Aurora Contributing Guide](https://universal-blue.org/contributing.html)

## Secure Boot

Secure Boot is supported. After installation, enroll the secure boot key with the password `universalblue`.

```bash
ujust enroll-secure-boot-key
```

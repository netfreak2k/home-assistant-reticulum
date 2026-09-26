# Reticulum for Home Assistant

Run the **Reticulum Network Stack (RNS)** directly on Home Assistant.

This project provides a Home Assistant add-on for running a persistent Reticulum node without requiring a separate Raspberry Pi, server or additional Linux installation.

## Features

- Reticulum Network Stack (RNS)
- Runs `rnsd` directly inside Home Assistant
- Persistent Reticulum configuration and storage
- AutoInterface support
- Optional Reticulum Transport mode
- Configurable logging
- Automatic startup with Home Assistant
- Configuration survives add-on and Home Assistant restarts
- Home Assistant OS tested
- `amd64` support
- `aarch64` support

## Installation

Add this repository to the Home Assistant App/Add-on Store:

`https://github.com/netfreak2k/home-assistant-reticulum`

Then:

1. Open **Settings → Apps / Add-ons → Store**
2. Open **Repositories**
3. Add the repository URL above
4. Find **Reticulum**
5. Install and start the add-on

## Default configuration

The add-on starts with:

- AutoInterface: enabled
- Transport mode: disabled
- Log level: info

Reticulum configuration and runtime data are stored persistently and survive add-on and Home Assistant restarts.

Advanced users can extend the Reticulum configuration with additional interfaces and settings.

## Current Status

### v0.1.0

First stable release.

Successfully tested with:

- Home Assistant OS
- Installation from GitHub
- `rnsd` startup
- AutoInterface
- Persistent configuration
- Add-on restart
- Home Assistant restart
- Automatic Reticulum startup

## Planned

Future versions are planned to include:

- Home Assistant Ingress web interface
- `rnstatus` dashboard
- Interface status
- Peer information
- Traffic statistics
- Easier TCP interface configuration
- RNode / serial interface support
- Additional Reticulum diagnostics

## Reticulum

Reticulum is a cryptography-based networking stack designed for resilient communication across many different types of physical and virtual network interfaces.

This project packages Reticulum for convenient use inside Home Assistant.

## License

MIT License

## Maintainer

**Netfreak2k**

Project: `home-assistant-reticulum`

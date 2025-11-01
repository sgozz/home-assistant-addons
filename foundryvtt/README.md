# Home Assistant Add-on: Foundry VTT

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

Foundry Virtual Tabletop in a Home Assistant add-on using the felddy/foundryvtt container.

## About

This add-on allows you to run Foundry Virtual Tabletop on your Home Assistant instance. Foundry VTT is a virtual tabletop application for playing tabletop role-playing games online.

## Installation

1. Add this repository to your Home Assistant add-on store
2. Install the "Foundry VTT" add-on
3. Configure the add-on with your Foundry VTT credentials
4. Start the add-on

## Configuration

The add-on requires the following configuration:

- `FOUNDRY_USERNAME`: Your Foundry VTT username
- `FOUNDRY_PASSWORD`: Your Foundry VTT password
- `FOUNDRY_ADMIN_KEY`: Admin key for your Foundry VTT instance

See [DOCS.md](DOCS.md) for detailed configuration instructions.

## Support

For issues and questions, please open an issue on GitHub.

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg

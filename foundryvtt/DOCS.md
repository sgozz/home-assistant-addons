# Home Assistant Add-on: Foundry VTT

## Installation

Follow these steps to get the add-on installed on your system:

1. Navigate in your Home Assistant frontend to **Settings** -> **Add-ons** -> **Add-on Store**
2. Click on the 3-dots menu at top right and select **Repositories**
3. Add this repository URL: `https://github.com/sgozz/home-assistant-addons`
4. Find the "Foundry VTT" add-on and click it
5. Click on the "INSTALL" button

## How to use

To use this add-on, you need a Foundry VTT license. If you don't have one, you can purchase it from the [Foundry VTT website](https://foundryvtt.com/).

### Configuration

The add-on requires the following configuration options to be set:

- **FOUNDRY_USERNAME**: Your Foundry VTT account username (required)
- **FOUNDRY_PASSWORD**: Your Foundry VTT account password (required)
- **FOUNDRY_ADMIN_KEY**: An admin password/key for your Foundry VTT instance (required)

Example configuration:

```yaml
FOUNDRY_USERNAME: "your_username"
FOUNDRY_PASSWORD: "your_password"
FOUNDRY_ADMIN_KEY: "your_secure_admin_key"
```

### Starting the add-on

1. Set the configuration as shown above
2. Click on "SAVE" to save the configuration
3. Start the add-on by clicking on "START"
4. Check the logs to see if everything went well
5. Access Foundry VTT by clicking "OPEN WEB UI" or navigating to `http://[YOUR_HOME_ASSISTANT_IP]:30000`

## Configuration Options

### Option: `FOUNDRY_USERNAME` (required)

Your Foundry Virtual Tabletop account username. This is used to download and authenticate the Foundry VTT software.

### Option: `FOUNDRY_PASSWORD` (required)

Your Foundry Virtual Tabletop account password.

### Option: `FOUNDRY_ADMIN_KEY` (required)

The admin password for accessing the Foundry VTT setup and configuration screens. Choose a secure password.

## Data Persistence

The add-on stores all Foundry VTT data in `/data`, which persists across restarts and updates. Your worlds, systems, and modules will be preserved.

## Port Configuration

The add-on uses port 30000 by default. You can access Foundry VTT at:
- `http://[YOUR_HOME_ASSISTANT_IP]:30000`

## Support

For issues with the add-on, please open an issue on the [GitHub repository](https://github.com/sgozz/home-assistant-addons/issues).

For Foundry VTT support, please visit the [Foundry VTT Community](https://foundryvtt.com/community/).

## Additional Information

This add-on is based on the [felddy/foundryvtt](https://hub.docker.com/r/felddy/foundryvtt) Docker container.

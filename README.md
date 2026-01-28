# Digital Matter Device Manager for MyGeotab

A MyGeotab add-in for managing Digital Matter tracking devices, including configuration, battery monitoring, and recovery mode management.

## Features

- **Device Overview**: View all Digital Matter devices linked to your Geotab account
- **Battery Monitoring**: Real-time battery levels for all devices
- **Parameter Configuration**: Configure tracking parameters with preset templates or custom settings
- **Recovery Mode**: Enable/disable recovery mode for device troubleshooting
- **Filtering & Sorting**: Filter by device type, battery level, and recovery mode status
- **CSV Export**: Export device data for reporting

## Requirements

- MyGeotab account with Administrator security clearance
- Digital Matter devices inside MyGeotab database

## Installation

1. Log in to your MyGeotab account
2. Navigate to **System Settings** > **Add-Ins**
3. Click **Add New**
4. Enter the following details:
   - **Name**: Digital Matter Device Manager
   - **URL**: `https://traxxiscode.github.io/DigitalMatter-DeviceManager/public/index.html`
   - **Support Email**: support@traxxisgps.com
5. Click **OK** to save

The add-in will appear in your navigation menu.

## Architecture

This add-in uses serverless functions hosted on Netlify to securely communicate with the Digital Matter API, ensuring API credentials are never exposed in the client-side code.

## Development

To clone and modify this add-in:

```bash
git clone https://github.com/traxxiscode/DigitalMatter-DeviceManager.git
cd DigitalMatter-DeviceManager
```

Host the files on GitHub Pages or your own web server, then update the add-in URL in MyGeotab.

## Supported Devices

- Yabby 3 
- Oyster 3 
- Oyster 2
- Yabby Edge
- Remora
- Remora 3 

# IKEA Window Blinds Driver with Failsafe

This repository provides a Hubitat driver for controlling IKEA FYRTUR and TREDANSEN window blinds. The driver extends the original IKEA driver with additional features such as automatic refresh and improved state tracking.

## Files

- **IKEA-window-blind-driver-code** – Groovy driver code that can be manually imported into Hubitat.
- **packageManifest.json** – Manifest for installation via Hubitat Package Manager.

## Installation

### Hubitat Package Manager
1. In Hubitat Package Manager, choose **Install** and select **From a URL**.
2. Enter the raw URL to `packageManifest.json` from this repository.
3. Follow the prompts to install the driver.

### Manual Installation
1. Open the `IKEA-window-blind-driver-code` file.
2. Copy the contents into a new driver in the Hubitat UI.
3. Save and click **Configure** on the device page after assigning the driver.

## Usage
- Use the provided commands to open, close, pause, or set the position of the blinds.
- The driver includes periodic refresh and battery reporting.
- Configurable battery refresh interval and low battery notifications.

This code is distributed under the Apache 2.0 license as noted in the driver header.

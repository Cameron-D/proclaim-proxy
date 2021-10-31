# ProclaimProxy

Super simple proxy app for [Proclaim](https://faithlife.com/products/proclaim) remote control API as most functionality is only available from localhost.

Intended for use with [Companion](https://github.com/bitfocus/companion) and the Proclaim module when Companion is running on a different device to Proclaim.

## Usage

Download the appropraite build for the OS for the computer running Proclaim.

Start the proxy app on the computer running Proclaim.

Configure the firewall appropriately for port `52194/tcp` (no rules will automatically be created meaning there will be no external access).

In the configuration for the Proclaim Companion module instance change the port to `52194`.

On Windows you can probably set this as a scheduled task to run on login so it is always running without any window needing to be open.
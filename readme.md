# alfred-tailscale

An Alfred workflow to control tailscale and copy the ip address of a connected device to your clipboard.

![Screenshot of alfred-tailscale in action](./screenshot.png)

# Dependencies
You need to have the [official tailscale application](https://apps.apple.com/us/app/tailscale/id1475387142?mt=12) from the AppStore installed.

# Usage

1. Download the .alfredworkflow file and add it to Alfred.
2. Hit the `ts` command to either disconnect, if tailscale is connected or connect, if tailscale is disconnected:
* You may connect tailscale, if tailscale is currently disconnected.
* You may disconnect tailscale, if tailscale is currently connected.
* If tailscale is connected, a list of all available devices is displayed. Press return to copy the selected ip adress to your clipboard. 

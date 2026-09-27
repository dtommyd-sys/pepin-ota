# pepin-ota
Public OTA manifests + firmware binaries for Pepin Labs devices.
Each device polls its `manifest.json` over HTTPS and self-updates from anywhere on wifi.
Firmware stores wifi creds in NVS (not in the .bin), so these binaries are safe to host publicly.

## Devices

- `tdisplay/` — PepDisplay T-Display-S3 releases.
- `pepin-dial/` — Elecrow CrowPanel 2.1-inch round releases using the ESPHome HTTP-update manifest format.

Before publishing a binary, verify that its configured SSID and password
literals are absent and that the manifest checksum matches the file.

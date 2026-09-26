# pepin-ota
Public OTA manifests + firmware binaries for Pepin Labs devices.
Each device polls its `manifest.json` over HTTPS and self-updates from anywhere on wifi.
Firmware stores wifi creds in NVS (not in the .bin), so these binaries are safe to host publicly.

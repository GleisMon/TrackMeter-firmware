# TrackMeter Firmware

Firmware releases for the TrackMeter device (OTA updates).

The device checks its manifest automatically and offers the update in its web interface.
No manual action is needed here. Each device variant has its own folder: a binary for one
board does not run on the other.

| File | Purpose |
|------|---------|
| `firmware/version.json` | current release manifest (version, MD5, URL) |
| `firmware/TrackMeter.bin` | firmware binary |
| `firmware35/version.json` | TrackMeter35 (one 3.5" screen, JC3248W535EN) release manifest |
| `firmware35/TrackMeter35.bin` | TrackMeter35 firmware binary |

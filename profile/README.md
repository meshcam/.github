# MeshCam

Open, self-hostable LoRa mesh trail cameras. Cameras sleep in the woods and
wake on motion; solar relay nodes carry each photo back to whatever internet
the property already has. No cell modem per camera and no per-camera fees.

- [getmeshcam.com](https://getmeshcam.com) is the product
- [docs.getmeshcam.com](https://docs.getmeshcam.com) explains how it fits together
- [demo.getmeshcam.com](https://demo.getmeshcam.com) is a live read-only demo (no signup)

## The open core

| Repo | What it is |
|---|---|
| [meshcam-firmware](https://github.com/meshcam/meshcam-firmware) | Leaf, relay, and gateway firmware (ESP32-S3, Reticulum LoRa mesh, on-device tiny-ML). GPL-3 |
| [meshcam-api](https://github.com/meshcam/meshcam-api) | The device & ingest API spec. Bring-your-own hardware is first-class. CC-BY-4.0 |
| [meshcam-app](https://github.com/meshcam/meshcam-app) | Self-hostable gallery + ingest server (FastAPI + React). AGPL-3 |

Everything the hosted cloud does, a self-hosted instance can do too.

In active development: bench-validated end to end, field trials summer 2026.
Questions go to hello@getmeshcam.com or the Discussions tab on any repo.

# MeshCam

**Open, self-hostable LoRa mesh trail cameras.** Cameras sleep in the woods
and wake on motion; solar relay nodes carry each photo back to the internet
you already have — no cell modem per camera, no per-camera fees, ever.

- 🌐 [getmeshcam.com](https://getmeshcam.com) — the product
- 📚 [docs.getmeshcam.com](https://docs.getmeshcam.com) — how it fits together
- 🔭 [demo.getmeshcam.com](https://demo.getmeshcam.com) — live read-only demo, no signup

## The open core

| Repo | What it is |
|---|---|
| [meshcam-firmware](https://github.com/meshcam/meshcam-firmware) | Leaf, relay, and gateway firmware (ESP32-S3 · Reticulum LoRa mesh · on-device tiny-ML) — GPL-3 |
| [meshcam-api](https://github.com/meshcam/meshcam-api) | The device & ingest API spec. Bring-your-own hardware is first-class — CC-BY-4.0 |
| [meshcam-app](https://github.com/meshcam/meshcam-app) | Self-hostable gallery + ingest server (FastAPI + React) — AGPL-3 |

The hosted cloud is a convenience, never a lock-in: everything it does, your
own instance can do too.

In active development — bench-validated end to end, field trials summer 2026.
Questions: hello@getmeshcam.com or the Discussions tab on any repo.

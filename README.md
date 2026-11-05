English | [简体中文](./README.zh-CN.md)

# hubo-wadamesh

Firmware for the **Hubo S3 and Hubo P4 mesh terminals**, based on
[ALLFATHER-BV/wadamesh](https://github.com/ALLFATHER-BV/wadamesh) (GPL-3.0), which runs
[MeshCore](https://github.com/meshcore-dev/MeshCore) on touch-screen handhelds.

**Status: the source code will be published here.** We are finishing third-party license compliance
and removing internal information before the first release. This repository is GPL-3.0, the same as wadamesh.

## What will be published

- Hubo S3 terminal (ESP32-S3) and Hubo P4 terminal (ESP32-P4) variants
- Chinese user interface and input method
- Voice messages over the mesh (Codec2)
- GPS page fed by the MeshLoRa C3 radio
- Backpack ID card detection for the Hubo-Tack 30-pin connector

## Available now

| Repository | What it is |
|---|---|
| [hubo-meshlora-c3](https://github.com/hubosmart/hubo-meshlora-c3) | MeshLoRa C3 radio firmware (MIT) |
| [hubo-mesh-protocols](https://github.com/hubosmart/hubo-mesh-protocols) | CH32 serial protocol and companion extensions (CC BY 4.0) |
| [hubo-backpack-skill](https://github.com/hubosmart/hubo-backpack-skill) | AI skill for designing 30-pin backpacks in KiCad (MIT) |
| [hubo-backpack-template](https://github.com/hubosmart/hubo-backpack-template) | Blank KiCad backpack template (CERN-OHL-P v2) |
| [hubo-backpack-spec](https://github.com/hubosmart/hubo-backpack-spec) | 30-pin backpack interface spec (CC BY 4.0) |

Watch this repository to be notified when the code lands.

## License

GPL-3.0, see [LICENSE](LICENSE). "Hubo" and the Hubosmart logo are trademarks and are not licensed with the code.

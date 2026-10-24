# G85

LineageOS build for the **Motorola Moto G85** (codename `malmo`), built with GitHub Actions.

## Status

Early planning. The repo is being set up from scratch.

## Plan

- Fork the community device tree ([tmhakim/android_device_motorola_malmo](https://github.com/tmhakim/android_device_motorola_malmo)) and adapt it to the stock dump and kernel tag below.
- Build the ROM in the cloud using [Action-ROM-Builder](https://github.com/1ndevelopment/Action-ROM-Builder) as the workflow base.

## Sources

| Component | Source |
| --- | --- |
| Device dump | [Jiovanni-dump/motorola_malmo_dump](https://github.com/Jiovanni-dump/motorola_malmo_dump) |
| Kernel | [MotorolaMobilityLLC/kernel-msm](https://github.com/MotorolaMobilityLLC/kernel-msm/releases/tag/MMI-V1UO35H.74-16-4), tag `MMI-V1UO35H.74-16-4` |
| Workflow base | [1ndevelopment/Action-ROM-Builder](https://github.com/1ndevelopment/Action-ROM-Builder) |

## Device

- **Name:** Motorola Moto G85
- **Codename:** `malmo`

## Disclaimer

Flashing custom ROMs can brick your device and may void your warranty. Everything here is provided as is, with no guarantees. Back up your data and flash at your own risk.

# Android Port Roadmap

A personal roadmap for future Android ROM porting and customization projects. This repository is a planning catalog, not a distribution of ROMs or an announcement of completed ports.

> **Status: Planned / Future Projects.** No builds, working hardware support, release dates, or completed ports are claimed here. Technical feasibility remains to be evaluated for each project.

## Project catalog

| Codename | Target device | Target model | Target ROM | Status |
| --- | --- | --- | --- | --- |
| `bluerose` | OPPO Reno5 Lite | CPH2205 | One UI 7 | Planned |
| `purplerose` | Samsung Galaxy A05 | SM-A055M | ColorOS | Planned |
| `depression` | OPPO Reno5 Lite | CPH2205 | HyperOS | Planned |
| `bloodrose` | Motorola Moto G20 | Moto G20 | Nothing OS — Red Edition | Planned |
| `unloved` | OPPO Reno5 Lite | CPH2205 | PixelOS | Planned |

## Project concepts

### BlueRose (`bluerose`)
- Goal: explore a One UI 7 port to the OPPO Reno5 Lite.
- Concept: a blue rose as the project's visual identity.
- Hardware platform: MediaTek Helio P95.

### PurpleRose (`purplerose`)
- Goal: explore a ColorOS port to the Samsung Galaxy A05.
- Concept: a purple rose as the project's visual identity.
- Hardware platform: MediaTek Helio G85.

### Depression (`depression`)
- Goal: explore a HyperOS port to the OPPO Reno5 Lite.
- Target version and customization scope: to be determined.

### BloodRose (`bloodrose`)
- Goal: explore a modified Nothing OS port to the Motorola Moto G20 (Unisoc T700).
- Confirmed visual direction: black and red.
- Optional design ideas: crimson accents, dot-matrix rose boot animation, monochrome icons, and matching widgets.
- Proposed tagline: *Nothing, in crimson.*

### Unloved (`unloved`)
- Goal: explore a PixelOS port to the OPPO Reno5 Lite.
- Proposed visual direction: minimalism with cool blue-gray tones; preserve the Pixel experience.
- Proposed tagline: *A second chance.*

## Reserved codenames

These names are intended for possible future projects. No target device or ROM has been assigned.

| Codename | Status |
| --- | --- |
| `obsession` | Reserved |
| `untrust` | Reserved |
| `wantahug` | Reserved |

Other naming ideas under consideration: `lonelyfails`, `lonelyrose`, `fadingrose`, `unspoken`, `forgotten`, `misunderstood`.

## Development roadmap

The following is a proposed workflow, not a report of completed work:

1. Research target hardware, partition layout, bootloader requirements and donor ROM compatibility.
2. Determine the appropriate ROM base and evaluate kernel, vendor, HAL and VINTF compatibility.
3. Establish reproducible backups, recovery procedures and a test environment.
4. Attempt an initial boot and document logs and failures.
5. Validate display, touch, audio, storage, connectivity, cameras, sensors and power management.
6. Implement project-specific visual customization where appropriate.
7. Publish documentation or builds only when sufficiently tested and legally redistributable.

## Scope and naming

Codenames in this catalog are custom project identifiers, not claims about the manufacturer's official device codenames. Device and ROM names are used for identification. This is an independent project roadmap and is not affiliated with the manufacturers or ROM developers mentioned. No proprietary binaries are included.

## Updates

This catalog is intended to grow as new project concepts, devices and codenames are selected. Status should be updated only when supported by documented progress.

# FNIRSI 2D15P Community MOD v1.0.0.0

The first public MOD release is based on official FNIRSI firmware **V2.7.0.7**. 

## Changes

- Removed language selection. The MOD is **English only**; additional languages are not currently planned.
- Reorganized the main menu: revised titles and their order, parameter names and settings layout to follow conventions used in professional instruments.
- Added menu navigation using the upper encoder (sometimes labeled **Intensity**).
- Improved Multimeter labels for clarity and consistency.
- Corrected typos in the **Key Test** window.
- Expanded **Signal Generator (DDS)** controls:
  - Navigate using the upper (**Intensity**) encoder.
  - Adjust **Frequency** by turning the **Vertical** encoder.
  - Change **Step** by **pressing** the **Vertical** encoder.
  - Adjust **Amplitude** by turning the **Horizontal** encoder.
  - Adjust **Duty** using the large lower-right (**Trigger**) encoder.

See the [README](README.md) for original-versus-MOD screenshots.

## Firmware Details

- Device: **FNIRSI 2D15P**
- Original firmware: **V2.7.0.7**
- Original firmware date: **2026-08-26** (unchanged)
- MOD version: **App v1.0 / FPGA v0.0** (v1.0.0.0)
- MOD build date: **2026-10-26**
- Firmware filename: `2D15P_V2.7.0.7_260826.bin`
- File size: **1,203,945 bytes**
- SHA-256: `a1fb334cdc8c6d986fb74dedee1b8ded54045328bc9a2bdd02ac1339775a7e79`

The original FPGA payload remains unchanged, as do the official firmware version and update filename.

## Firmware Update

**Before installing the MOD, install official FNIRSI firmware V2.7.0.7 and verify that the instrument starts and works correctly.** Only then install the Community MOD.

Follow the [firmware update video](https://www.youtube.com/watch?v=0d-lKbbzeQs), download the firmware from the applicable [GitHub Release](../../releases), and check its SHA-256. Keep a known-working firmware copy and do not interrupt the update.

*Independent community project. Not affiliated with or endorsed by FNIRSI.*

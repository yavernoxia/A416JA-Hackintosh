# ASUS A416JA Hackintosh i3 10th gen
<img src="https://raw.githubusercontent.com/yavernoxia/A416JA-Hackintosh/refs/heads/main/Sonoma.jpg" alt="macOS Sonoma">

## ASUS A416JA SPECS

| COMPONENTS | MODEL                                 |
|------------|---------------------------------------|
| CPU        | Intel Core i3 1005G1                  |
| RAM        | 20 GiB@2667MHz DDR4                    |
| iGPU       | Intel(R) UHD Graphics G1              |
| WiFi       | Intel Wireless-AC 8265                |
| Storage    | NVME 256 GiB                          |

### WHAT WORKS
- [x] Intel integrated graphics
- [x] USB
- [x] Webcam
- [x] Brightness control
- [x] Battery percentage
- [x] TouchPad w/ Advanced Gestures
- [x] Intel WiFi
- [x] Speakers
- [x] Headset Combo Jack
- [x] Apple Services (iCloud, Apple Music, Apple TV, others..)
- [x] Intel Bluetooth
- [x] Sleep Mode
- [x] Universal Control
- [ ] HDMI (There is no support for HDMI on real macbooks with Ice Lake CPUs)
- [ ] DRM (DRM compatibility dropped since macOS 11 for iGPU only systems)

## GUIDE
### BIOS SETUP
- Disable "Fast Boot"
- Disable "Secure Boot"
- Disable "VT-d" and "VT-x"
- Set SATA mode to "AHCI"

### SETUP
- Generate your own SMBIOS

# Windows on ARM Status

| Feature                | Notes                                           | Status         |
|------------------------|-------------------------------------------------|----------------|
| ⌨️ Power button        |                                                 | ✅            |
| 🛜 ASIX Ethernet (LAN) |                                                 | ✅            |
| 🛜 AP6256 WiFi         |                                                 | ✅            |
| 📦 UFS                 |                                                 | ✅            |
| 📦 NVMe                |                                                 | ✅            |
| 🔌 40p GPIO            | Will be supported in the future with RhProxy    | ❌            |
| 🔵 Bluetooth           |                                                 | ✅            |
| ❄️ Fan control         | A few adjustments are still needed              | ⚠️            |
| 📷 Camera (CSI CAM1/2) | We do not have the necessary hardware to test this feature | ❌            |
| 🎆 LT9611 DSI2HDMI     | Works, and so does hotplugging                  | ✅            |
| 🎆 GPU                 | Works, but may not be binded correctly when applying driver | ⚠️            |
| 🪵 USB C               |                                                 | ✅            |
| 🪵 USB 2.0             |                                                 | ✅            |
| 🪵 2x USB 3.0          |                                                 | ✅            |
| 🔊 Audio (LT9611) (HDMI) |                                                 | ✅            |
| 🔊 Audio (ES8316) (AUX) | Frequent popping when using audio               | ⚠️            |
| 🛡️ TPM                 | Requires RPMB to be provisioned, UEFI will let the user know if it's required | ✅            |
| 🛡️ Virtualization      |                                                  | ✅            |

# UEFI Status

| Feature                | Notes                                           | Status         |
|------------------------|-------------------------------------------------|----------------|
| ⌨️ Power button        |                                                 | ✅            |
| 🛜 ASIX Ethernet (LAN) |                                                 | ✅            |
| 📦 UFS                 |                                                 | ✅            |
| 📦 NVMe                | Drives MUST be PCIe!! SATA drives will not work | ✅            |
| ❄️ Fan                 | Initial fan speed can be selected in the BIOS   | ✅            |
| 💾 UEFI Variables      | Requires RPMB to be provisioned, UEFI will let the user know if it's required | ✅            |
| 🎆 LT9611 DSI2HDMI     |                                                 | ✅            |
| 🪵 USB C               |                                                 | ✅            |
| 🪵 USB 2.0             |                                                 | ✅            |
| 🪵 2x USB 3.0          |                                                 | ✅            |
| ⚡ Weak PSU detection  | Soon                                            | ❌            |
| ⚡ EL2 Booting         | Uses QHEE Secure Launch                         | ✅            |
| ⚡ UEFI Boot Menu      |                                                 | ✅            |
| ⚡ UEFI Setup Menu     | WIP                                             | ⚠️            |
| 🪟 Windows boot        | Uses QHEE Secure Launch                         | ✅            |
| 🐧 Linux boot          | Soon                                            | ❌            |

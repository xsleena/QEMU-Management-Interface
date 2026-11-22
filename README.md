Dear friends, since there are no current GUI for the QEMU emulator for Windows, I decided to create one myself in Java with help from AI.

Here the features


## Profile Management
- Save, load (button or double-click), and delete VM profiles (`.properties`)
- Backward-compatible support for legacy single-disk profiles
- Dynamic UI state handling (automatically enables/disables inputs and browse buttons)

## General & System
- Custom QEMU executable path selector
- Hardware acceleration modes (`whpx`, `kvm`, `hvf`, `tcg`, `none`)
- Configurable boot target (`Disk`, `CD-ROM`, `Network`, `menu=on`) and machine type (`q35`, `pc`, `i440fx`, `isapc`, `microvm`)
- Custom extra CLI arguments field
- Adjustable RAM (MB), 35+ CPU models (x86, ARM, RISC-V/POWER/MIPS), and CPU topology (`Cores`, `Threads`, `Sockets`)

## Multi-Disk & Storage
- Multi-disk table supporting unlimited virtual drives per VM
- Per-disk active toggle, boot/load order controls (`Up` / `Down`), interface (`ide`, `virtio`, `sata`, `scsi`, `nvme`), and format (`qcow2`, `raw`, `vmdk`, `vdi`)
- Automatic bus indexing and NVMe controller assignment
- Built-in `qemu-img` disk creation wizard and disk file deletion
- ISO/CD-ROM mounting, Host Shared Folder (`vvfat` on Windows / `virtio-9p` on Linux/macOS), OVMF UEFI BIOS, and TPM socket support

## Devices & Network
- Audio backend selector (`dsound`, `wasapi`, `sdl`, `pa`, `alsa`, `none`) with Intel HDA audio
- Live Windows USB host device detection (`VID:PID` passthrough) with refresh button and `usb-tablet` fallback
- GPU adapter selection (`std`, `virtio`, `qxl`, `vmware`, `cirrus`, `none`)
- Network modes (`user` with `2222->22` SSH forwarding, `tap`, `none`) and custom MAC address configuration

## Execution & Tools
- One-click VM launch (`Run VM`)
- Command-line preview window with automatic clipboard copy
- Compact tabbed Swing GUI with live status bar feedback


Requirement to Run (Windows):
Place a portable Java (JRE) folder named "JAVA" in the same directory as QEMUManagementInterface.jar.

Folder setup:
- YourFolder/JAVA/bin/java.exe
- YourFolder/QEMUManagementInterface.jar
- YourFolder/run.bat

Note: If you already have Java installed on your PC, edit the .bat file and replace .\JAVA\bin\java with java.





<img width="862" height="508" alt="grafik" src="https://github.com/user-attachments/assets/0b43350b-e896-4c89-b14e-0a17a7e26b52" />

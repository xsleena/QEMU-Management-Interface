Dear friends, since there are no current GUI for the QEMU emulator for Windows, I decided to create one myself in Java.

Here all options available

Profiles Management:
  - Save VM profiles
  - Load VM profiles
  - Delete VM profiles
  - List all saved profiles
  - Preview QEMU command for a profile

General Settings:
  - Set QEMU executable path
  - Choose CPU acceleration (tcg, whpx, none, etc.)
  - Select boot device (disk, CD-ROM, network, menu)
  - Select machine type (pc, q35, i440fx, isapc, microvm)

System Configuration:
  - Configure memory (MB)
  - Enable/disable memory
  - Set CPU cores, threads per core, and sockets
  - Select CPU model (host, EPYC, Core-i7, ARM, etc.)

Storage & Firmware:
  - Attach primary disk image
  - Attach CD-ROM ISO
  - Mount shared folder
  - Enable/use OVMF BIOS
  - Enable/use TPM socket
  - Create new disk image (custom path, size, format)
  - Delete VM disk

Devices:
  - Enable/disable sound
  - Select sound backend (dsound, wasapi, sdl, none)
  - Enable/disable USB
  - Detect and attach USB devices automatically
  - Select GPU (std, qxl, vmware, cirrus)

Network:
  - Enable/disable network
  - Set network mode (user, tap, none)
  - Configure MAC address

Actions:
  - Launch VM
  - Preview full QEMU command (copies to clipboard)
  - Toggle CPU acceleration (tcg ↔ whpx)

GUI Features:
  - Split panel layout: left panel for profiles, right panel for settings tabs
  - Tabs for General, System, Storage, Devices, Network
  - Buttons for all major actions (Save, Load, Run, Delete, Preview Cmd, etc.)
  - Status bar showing messages



<img width="2552" height="973" alt="grafik" src="https://github.com/user-attachments/assets/340e2d79-6c1c-4a9c-80a7-a4020ef99059" />



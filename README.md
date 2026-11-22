Dear friends, since there are no current GUI for the QEMU emulator for Windows, I decided to create one myself in Java with help from AI.

Here all options available

• Profile Management
	• Save, load (via button or double-click), and delete VM configurations as .properties files
	• Backward-compatible loading for legacy single-disk profiles
	• Automatic UI control toggling (enabling/disabling fields and browse buttons based on checkboxes)
  
• General & System Configuration
	• Custom QEMU executable selection (qemu-system-x86_64.exe, etc.)
	• Hardware acceleration selection (whpx, kvm, hvf, tcg, none)
	• Boot order (Disk, CD-ROM, Network, menu=on) and Machine Type (q35, pc, i440fx, isapc, microvm)
	• Custom extra QEMU CLI flags input field
	• Configurable RAM (MB), CPU model selection (35+ x86/ARM/RISC presets), and topology (Cores, Threads, Sockets)
  
• Multi-Disk & Storage Management
	• Attach and manage multiple virtual hard disks simultaneously in a table
	• Per-disk toggle (On/Off), priority ordering (Up/Down), interface selection (ide, virtio, sata, scsi, nvme), and format selection (qcow2, raw, vmdk, vdi)
	• Automatic drive indexing and NVMe controller assignment without ID conflicts
	• Integrated qemu-img disk creation wizard and permanent disk file deletion
	• CD-ROM/ISO mounting, Host Shared Folder mounting (auto-switching vvfat on Windows / virtio-9p on Linux/macOS), OVMF UEFI BIOS, and TPM socket passthrough
  
• Devices & Networking
	• Audio backend configuration (dsound, wasapi, sdl, pa, alsa, none) with Intel HDA output
	• Live Windows USB host device detection (VID:PID passthrough) with refresh button and usb-tablet fallback
	• GPU selection (std, virtio, qxl, vmware, cirrus, none)
	• Network adapter configuration (user with SSH port forwarding 2222->22, tap, none) and custom MAC address support
  
• Execution & Diagnostics
	• One-click VM launch (Run VM)
	• Full CLI command preview dialog with automatic clipboard copy
	• Real-time status bar feedback



<img width="2552" height="973" alt="grafik" src="https://github.com/user-attachments/assets/340e2d79-6c1c-4a9c-80a7-a4020ef99059" />



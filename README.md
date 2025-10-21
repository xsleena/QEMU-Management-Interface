Dear friends, since there are no current GUI for the QEMU emulator for Windows, I decided to create one myself in Java.

In this GUI, most of the options work.


Here all features


1. Profiles
- Save profile – save current VM configuration
- Load profile – load a saved configuration
- Delete profile – remove a saved profile
- Profile list – view all saved profiles

2. QEMU Executable
- QEMU Path – select the QEMU executable
- Enable/Disable QEMU – checkbox to include/exclude in command

3. Virtual Disk
- Primary Disk Image – select disk image file (.qcow2)
- Extra Disks – add/remove multiple disks
- Create Disk – create a new disk image using qemu-img
- Resize/Convert/Check Disk – advanced disk tools for disk management
- Enable/Disable Disk – checkbox to include/exclude disk in VM

4. CD-ROM
- CD Image – select ISO file
- Enable/Disable CD-ROM – checkbox

5. Shared Folder
- Shared Folder Path – select host folder to share
- Enable/Disable Shared Folder – checkbox

6. Memory & CPU
- Memory (MB) – input field
- CPU Cores – input field
- CPU Model – dropdown (host, qemu64, etc.)
- Enable/Disable Memory & CPU – checkboxes

7. GPU & Sound
- GPU Mode – dropdown (std, qxl, virtio, etc.)
- Sound Backend – dropdown (dsound, none, etc.)
- Enable/Disable Sound Card – checkbox

8. Boot & Acceleration
- Boot Device – dropdown (c=HDD, d=CD-ROM, n=Network, menu)
- Acceleration – dropdown (tcg, hax, whpx)
- RTC – localtime (always applied)

9. TPM (Trusted Platform Module)

- TPM Socket Path – input field
- Enable/Disable TPM – checkbox
- Start TPM Emulator – optional, launches swtpm

10. OVMF BIOS
- OVMF Path – select UEFI BIOS file
- Enable/Disable OVMF – checkbox

11. Network
- Enable/Disable Networking – checkbox
- Default network configuration – NAT with a NIC (can be extended later)

12. USB Devices
- USB Dropdown – list detected USB devices
- Enable/Disable USB – checkbox (USB enabled by default)

13. Command Preview
- Preview QEMU Command – show full command before launching
- Copy to Clipboard – optional in preview dialog

14. Run / Launch VM
- Run VM – launches the VM using all selected options
- Console output – printed in real-time to console




<img width="1235" height="791" alt="grafik" src="https://github.com/user-attachments/assets/969f2dd7-e490-40dd-ae6d-9682cfb2c335" />

<img width="2552" height="973" alt="grafik" src="https://github.com/user-attachments/assets/340e2d79-6c1c-4a9c-80a7-a4020ef99059" />



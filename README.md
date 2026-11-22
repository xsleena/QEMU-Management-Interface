# QEMU Management Interface

A clean, lightweight desktop GUI under Windows for configuring, managing, and launching QEMU virtual machines without memorizing complex CLI flags.

## ✨ Features

### 🖥️ VM & Profile Management
* **Profile System:** Save, load, and delete VM configurations as `.properties` files.
* **Command Preview:** Inspect the generated QEMU command and auto-copy it to your clipboard.
* **Standalone `.exe`:** Compiled for easy, ready-to-run execution without extra setup.

### ⚙️ System & Hardware
* **Acceleration & Machine:** Supports `whpx`, `kvm`, `hvf`, and `tcg` alongside machine types like `q35` and `pc`.
* **CPU & Memory:** Choose from 35 CPU models, customize `Cores`/`Threads`/`Sockets`, and allocate RAM.
* **Custom Arguments:** Pass extra QEMU CLI flags directly via the `Extra Args` field.

### 💾 Storage & Firmware
* **Multi-Disk Support:** Attach, reorder, and toggle multiple disks (`ide`, `virtio`, `sata`, `scsi`, `nvme` / `qcow2`, `raw`, `vmdk`, `vdi`).
* **Built-in Disk Manager:** Create new disk images via `qemu-img` or delete existing ones directly from the UI.
* **Media, UEFI & TPM:** Mount CD/ISO images, configure `OVMF` BIOS, attach `TPM` sockets, and enable host-guest shared folders.

### 🌐 Networking & Devices
* **Multi-NIC Support:** Add multiple network adapters (`user`, `tap`, `bridge`) with selectable models (`e1000`, `virtio-net-pci`, `rtl8139`, `vmxnet3`), random MAC generation, and `hostfwd` rules.
* **USB, Audio & GPU:** Auto-detect host USB devices (VID/PID) for passthrough, and choose between multiple sound backends and GPU models.

<img width="884" height="550" alt="grafik" src="https://github.com/user-attachments/assets/e29846fc-fbd8-4ce9-9aa5-4803b6ccd0aa" />
<img width="881" height="549" alt="grafik" src="https://github.com/user-attachments/assets/d9f68e49-3170-4942-a296-44dbd157877f" />
<img width="884" height="549" alt="grafik" src="https://github.com/user-attachments/assets/fb7803d9-73c3-4967-8fdb-b42d73875db1" />

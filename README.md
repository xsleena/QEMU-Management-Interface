# QEMU Management Interface

A clean, lightweight desktop GUI under Windows for configuring, managing, and launching QEMU virtual machines without memorizing complex CLI flags made with AI.

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


<img width="885" height="590" alt="grafik" src="https://github.com/user-attachments/assets/9de80e2a-d07b-4d2f-9cec-0f96be702b1b" />
<img width="879" height="586" alt="grafik" src="https://github.com/user-attachments/assets/83a2e47b-97dd-4135-8a8f-2f4c4d243d27" />
<img width="881" height="588" alt="grafik" src="https://github.com/user-attachments/assets/3d99b373-b27d-45b1-88b4-af78294b6179" />

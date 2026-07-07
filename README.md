<img src="DD.png" alt="App Demo" width="500">

## [!] ddtui

ddtui is a tool that does drive stuff based on whiptail dialog menus for quick and safe disk management. It turns complex, dangerous terminal commands into a simple, automated interface.

## [!] Features
* **Automated Full Format:** Wipe drives, set GPT/MBR tables, and create file systems (ExFAT, EXT4, FAT32, NTFS).
* **OS Flashing:** Safely burn bootable Linux `.iso` images using the `dd` core engine.
* **Manual Layouts:** Instantly drops into `cfdisk` for custom partition sizing.
* **Storage Protection:** Includes optional built-in LUKS volume encryption.
* **Safety Lock:** Automatically hides and blocks your active root (`/`) system drive from accidental deletion.

## [!] Requirements
Ensure you have the following system utilities installed (most are built-in):
`lsblk`, `dd`, `parted`, `cfdisk`, `cryptsetup`, `whiptail`

## [!] Installation
Go to the Release page, The instructions are in there.

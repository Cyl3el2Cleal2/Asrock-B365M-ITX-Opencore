## My MacPro Spec

| #   | Products                    | Notes                           |
|-----|-----------------------------|---------------------------------|
| CPU | Intel i5 9400F              |                                 |
| M/B | Asrock B365M-ITX            | Replace Wifi card with DW1820A. |
| RAM | Kington Predator RGB 8*2 GB |                                 |
| SSD | SK hynix SC308 SATA         | OS X & EFI & First Boot         |
 GPU | MSI RX580                   |                                 |

## To Test This Opencore for ASRock B365M-ITX (Replace WiFi Card with DW1820A)

- Turn on os x
- Plug usb drive
- Open Disk Utility
- Erase USB drive as:
  - Format: Max OS Extended (Journaled)
  - Sheme: GUID Partition Map
- Mount USB EFI partition
- Copy EFI folder to put inside EFI partition
- Set BIOS for Opencore ([GUIDE HERE](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#intel-bios-settings))
- Boot to Opencore then RESET NVRAM
- And boot to Opencore then boot to OS X drive!
- Enjoy.

## Change Log

- 2020/11/15
  - Added support for Big Sur.
  - Update Kexts.

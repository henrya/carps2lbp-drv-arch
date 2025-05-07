# carps2lbp-drv-arch

**Canon UFRII LT / CARPS2 Printer Driver for Arch Linux**

I had difficulty getting the Canon LBP6030/6040 network printer to work on Arch Linux.  
Eventually, I created two patched versions of the following outdated AUR repositories:

- `cnrdrvcups-lb` — required for the `rastertoufr2` CUPS filter  
- `cnrdrvcups-sfp` — required for the `rastertosfp` CUPS filter and the LBP6030/6040 driver

## Installation

```bash
makepkg -si

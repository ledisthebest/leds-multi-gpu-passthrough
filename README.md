# LEDs-multi-gpu-passthrough

This is LED's Guide for Dual/Multi GPU passthrough using QEMU/KVM + Libvirt.

---

## About this Guide

My current setup is the same as was in my [Single GPU Passthrough Guide](https://gitlab.com/liucreator/LEDs-single-gpu-passthrough), just with an addition RTX 3070.
Two dedicated graphic cards, however, this should also work on intergrated graphic + dedicated graphic card(s), as commonly found on Intel platforms.

Laptops could work, possibly, but with many caveats that I am not familiar with.

This guide is best served as a compliment to the Arch Wiki: [PCI passthrough via OVMF](https://wiki.archlinux.org/index.php/PCI_passthrough_via_OVMF), please take a look at that first if you can, and I will be constantly referencing and linking to the articles in there.

You can reach me from here: [Contacts](https://liucreator.gitlab.io/en/contact/)

[![Followers](https://bilistats.lonelyion.com/followers?uid=589560036)](https://space.bilibili.com/589560036/channel/seriesdetail?sid=2031728)


## My PC Specs:

- CPU: AMD Ryzen 3900x 12 cores
- GPU0: MSI Ventus 2X RTX 3070 8GB LHR
- GPU1: MSI Radeon RX 560 4GB LP OC
- RAM: 32GB 3200Mhz dual channels
- OS: Arch Linux Zen Kernel 5.19.10
- DE: KDE Plasma 5.25(x11)

---

## Credit:

- Arch Wiki [PCI passthrough](https://wiki.archlinux.org/index.php/PCI_passthrough_via_OVMF) 
- Libvirt [XML format and explainations](https://libvirt.org/formatdomain.html)
- SubReddit [r/VFIO](https://www.reddit.com/r/VFIO/)
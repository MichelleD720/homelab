# 🏠 Home Lab

Self hosted lab for practicing systems administration, networking, storage, and backup strategy. Every change is documented here and logged in [it-journal](https://github.com/MichelleD720/it-journal).

## 🖥️ Hardware
| Device | Specs | Role | Status |
|---|---|---|---|
| Raspberry Pi 5 | 16 GB RAM, 256 GB NVMe (PoE+ HAT) | Network services: DNS, VPN, monitoring | 🟡 Parts in transit |
| Corsair Tower | i7 3770K, 16 GB RAM, 2x 3 TB HDD, SSD boot | Main server: Proxmox, Docker apps | ⚪ Planned |
| HP Tower | Core 2 Quad, 4 GB RAM, 2x 3 TB HDD | Backup target (wakes on schedule) | 🟢 Running as RAID 1 NAS, to be repurposed |
| HP Omen | Reserved | Future GPU and AI workloads | ⚪ Later |

## 🧩 Services
| Service | Host | Purpose | Status |
|---|---|---|---|
| WireGuard | Pi 5 | Remote access VPN | 🟢 Running (to be migrated) |
| Pihole | Pi 5 | Network ad blocking and local DNS | ⚪ Planned |
| Uptime Kuma | Pi 5 | Service monitoring | ⚪ Planned |
| Proxmox | Corsair | Hypervisor | ⚪ Planned |
| Jellyfin | Corsair | Media server | ⚪ Planned |

## 🗺️ Roadmap
- [ ] Phase 1: Pi 5 on NVMe with Pihole, WireGuard, Uptime Kuma
- [ ] Phase 2: Corsair on Proxmox with ZFS mirror and Docker apps
- [ ] Phase 3: HP as scheduled backup target (3 2 1 strategy)
- [ ] Phase 4: Network segmentation and CCNA practice labs

## 📚 Documentation
Coming soon: network layout, backup strategy, design decisions, and KB articles.

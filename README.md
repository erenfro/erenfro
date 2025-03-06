# 📈 GitHub Stats

[![Eric Renfro's GitHub stats](https://github-readme-stats.vercel.app/api?username=erenfro&show_icons=true&theme=tokyonight&hide_border=true&disable_animations=true)](https://github.com/anuraghazra/github-readme-stats)
<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=erenfro&layout=compact&hide=html&hide_border=true&theme=tokyonight" alt="Eric Renfro's top used languages" /></p>

## 👋 Introduction
- 🔭 I'm currently working on yadm and bash.
- 🌱 I'm currently learning nomad.
- 🤝🏻 I'm an active community supporter for Linux for various distributions.
- 👯 I'm looking to collaborate on my website, https://linux-help.org/
- 💬 Ask me about Linux, I've been using Linux for over 32 years and know quite a bit.
  - EndeavourOS is my primary distribution for Desktop/Laptop use. Debian for servers.
  - KDE Plasma 6.x is my current Desktop Environment. Alternatives I will use and recommend are Cinnamon and Xfce.
  - Previously have used GNOME for 6 years, KDE for 20 years, and always keeping Xfce in the mix.
  - Finally I'm able to use Wayland with KDE Plasma's support for libei and InputCapture, albeit still a little rough, constantly asking permission, but hey! It's a start.
  - My main text editors of choice are neovim, micro, kate, sublime text, and code-oss depending on usage.
  - Things I do recommend for people interested in Linux:
    - Distributions:
      - Linux Mint
      - Fedora
      - EndeavourOS
    - Cool Projects:
      - [Pacstall](https://pacstall.dev/) for custom package management and updates for improving life where needed in deb-based distributions.
- 📫 How to reach me:
  - Discord: https://discord.com/users/331909633759379466
  - Matrix: https://matrix.to/#/@psi-jack:matrix.org
  - Mastodon: https://social.linux-help.org/@psijack (@psijack@social.linux-help.org)

# Personal Computers

## 🖥️ Main Computer
- CPU: AMD Ryzen 7 5800X3D 8-Core Processor
- GPU: ASUS AMD RX 6700 XT
- RAM: G.Skill Ripjaws 3600 MHz DDR4 4x16 GB (64GB)
- 🖴 Storage:
  - NVMe: Samsung 980PRO 2TiB SSD for OS
  - NVMe: Samsung 980PRO 2TiB SSD for /home
  - SATA: OCZ Agility 3 224 GiB SSD for VirtualMachines
  - SATA: Samsung 860 465 GiB SSD for Secondary OS Testing
  - SATA: Seagate Baracuda 4 TiB HDD for additional slower /home storage

## 🧑‍💻️ Tabtop Computer
- Model: Lenovo Yoga C740-14IML
- CPU: Intel Core i5-10210U 1.6 GHz
- GPU: Intel CometLake-U Intel UHD iGPU
- RAM: 8 GB Soldered 2667 MHz DDR4
- 🖴 Storage:
  - NVMe: Samsung 970 EVO Plus SSD 1 TiB

## 🍎 MacBook Pro
- Model: MacBook Pro 16" 2019
- CPU: Intel Core i7 2.6GHz 8-Core
- GPU: AMD Radeon Pro 5300M 4GB
- GPU: Intel UHD Graphics 630 1.5GB
- RAM: 16 GB 2667 MHz DDR4
- 🖴 Storage:
  - NVMe: 512 GiB Soldered

# Servers

## 💻 Game "Server" Laptop
- Model: Toshiba Satellite C55t-B
- CPU: Intel Core i3-4005U 1.7 GHz
- GPU: Intel Haswell-ULT i915 iGPU
- RAM: G.Skill Ripjaws SODIMM 2x8 GB 1600MHz DDR3
- 🖴 Storage:
  - SATA: Samsung 840 SSD 240 GiB

## 🖥 Proxmox VE Cluster

### 🛠️ Hardware

| Name   | Device              | CPU            | OS Disk          | Data Disk   | RAM            | OS     | Purpose             |
|--------|---------------------|----------------|------------------|-------------|----------------|--------|---------------------|
| hv1    | Custom              | Ryzen 7 5700G  | 240 GiB SSD      | 3TiB, 4TiB  | 32 GB 3200 MHz | Debian | PVE, GlusterFS, ZFS |
| hv2    | Custom              | Ryzen 5 5600G  | 240 GiB SSD      | 3TiB, 4TiB  | 32 GB 3200 MHz | Debian | PVE, GlusterFS, ZFS |
| hv3    | Custom              | Ryzen 5 5600G  | 240 GiB SSD      | 3TiB, 4TiB  | 32 GB 3200 MHz | Debian | PVE, GlusterFS, ZFS |
| hv4    | BESSTAR UM700       | Ryzen 7 3750H  | 256 GiB NVMe SSD | None        | 16 GB 2667 MHz | Debian | PVE, ZFS            |
| hv5    | Intel NUC DN2820FYK | Intel N2820    | 112 GiB NVMe SSD | None        | 8 GB 1600 MHz  | Debian | PVE, ZFS            |

  - Total CPU: 50 threads
  - Total RAM: 120 GB

## 🗜️ Supporting Hardware

| Name   | Device         | CPU        | OS Disk   | Data Disk | RAM   | OS       | Purpose               |
|--------|----------------|------------|-----------|-----------|-------|----------|-----------------------|
| NAS    | Synology DS416 | 2x AL212   | 11TiB HDD | ZFS 56TB  | 1GB   | DSM 7.x  | NAS/NFS/Backup        |

## 📶 Networking/UPS Hardware

| Device         | Purpose                |
|----------------|------------------------|
| EdgeRouter PoE | Router/(BGP not used)  |
| 2xHP ProCurve  | 24-port Switches       |
| APC Back-UPS   | UPS hv1                |
| APC Back-UPS   | UPS hv2                |
| APC Back-UPS   | UPS hv3                |
| CyberPower     | UPS Network/Router/NAS |

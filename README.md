# linuxmirrors
linux  一键换源系统  

# Mirror Switcher - Linux 镜像源一键切换工具

🚀 一个支持多发行版、多版本的 Linux 镜像源自动切换 Bash 脚本，帮助你快速将官方源替换为国内高速镜像（阿里、清华、中科大等），大幅提升软件包下载速度。

---

## 支持的发行版与版本范围

| 发行版                       | 版本范围                    |
|------------------------------|-----------------------------|
| Debian                       | 8 ～ 13                     |
| Ubuntu                       | 14 ～ 25                    |
| Kali Linux                   | All                         |
| Linux Mint                   | 19 ～ 22 / LMDE 6           |
| Deepin（深度）               | All                         |
| Zorin OS                    | All                         |
| Armbian                      | All                         |
| Proxmox VE                   | All                         |
| Raspberry Pi OS              | All                         |
| Red Hat Enterprise Linux     | 7 ～ 10                     |
| Fedora                       | 30 ～ 42                    |
| CentOS                       | 7 ～ 8 / Stream 8 ～ 10     |
| Rocky Linux                  | 8 ～ 10                     |
| AlmaLinux                   | 8 ～ 10                     |
| openEuler（开源欧拉）        | 21 ～ 25                    |
| OpenCloudOS（鸥栖）          | 8.6 ～ 9 / Stream 23        |
| openKylin（开放麒麟）         | All                         |
| Anolis OS（龙蜥）            | 8 / 23                      |
| openSUSE                    | Leap 15 / Tumbleweed        |
| Arch Linux                   | All                         |
| Manjaro                     | All                         |
| Alpine Linux                 | v3 / edge                   |
| Gentoo                      | All                         |
| NixOS                       | 19 ～ 25                    |

---

## 功能特性

- ✅ 自动检测当前 Linux 发行版及版本  
- ✅ 备份原始镜像源配置，保障安全  
- ✅ 支持阿里云、清华大学、中国科技大学等国内主流镜像  
- ✅ 支持交互式选择及命令行参数指定  
- ✅ 多发行版、多版本全覆盖，适配 APT、YUM/DNF、Zypper、Pacman、APK 包管理器  
- ✅ 结构清晰，方便后续扩展与维护  

---

## 快速开始

### 克隆项目

```bash
git clone https://github.com/<你的用户名>/mirror-switcher.git
cd mirror-switcher
chmod +x switch.sh

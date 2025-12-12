# My Ubuntu Home Server Project

**Personal Ubuntu home server hosting a NAS, Jellyfin media server, Etherpad collaborative editor, Minecraft server, and WireGuard VPN, demonstrating Linux administration, networking, and self-hosted service deployment skills.**

This repository documents a personal project where I built and configured a fully functional home server on an old laptop using Ubuntu Server LTS. It demonstrates skills in Linux server administration, networking, self-hosted services, and deployment of multiple services.

---

## Project Overview
- **Operating System:** Ubuntu Server LTS (version: 24.04.2 LTS  )
- **Purpose:** Personal home server for storage, media streaming, collaborative editing, gaming, and secure remote access.
- **Networking:** Configured static IP via router admin settings. 
- **Hardware Specs:** Toshiba Laptop -- CPU: Intel(R) Pentium(R) CPU // Motherboard: Intel // RAM: 4 GB

---

## Services Installed

### 1. NAS with Samba
- Shared files and directories across devices on the home network.
- Skills demonstrated:
  - File server configuration
  - LAN file access management

### 2. Jellyfin Media Server
- Stream movies, TV shows, and music to multiple devices.
- Default port: 8096
- Skills demonstrated:
  - Media server deployment and configuration
  - Service management and updates

### 3. WireGuard VPN
- Secure remote access to home network.
- Configured with static IP to ensure stable connections.
- Skills demonstrated:
  - VPN setup
  - Network security configuration
  - Port forwarding and firewall management

### 4. Etherpad Collaborative Editor
- Real-time collaborative document editing accessible via browser.
- Default port: 9001
- Installed via Node.js
- Skills demonstrated:
  - Web service deployment
  - Real-time collaboration software setup
  - Node.js service management

### 5. Minecraft Server
- Game server hosted for LAN/friends.
- Default port: 25565
- Skills demonstrated:
  - Game server hosting
  - Network and port configuration
  - Server maintenance and backup

---


## Skills Demonstrated
- Linux server administration (Ubuntu Server LTS)
- Network configuration and static IP setup
- Deployment and management of multiple self-hosted services
- File sharing and NAS setup with Samba
- Media server deployment with Jellyfin
- Real-time collaborative editing with Etherpad
- Game server setup (Minecraft)
- VPN configuration and remote network access
- Following and adapting professional tutorials to create custom solutions

---

## Maintenance & Notes
- Regular system updates applied:
```bash
sudo apt update && sudo apt upgrade -y

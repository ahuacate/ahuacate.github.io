<h4><b>Easy Script Shortcuts</b></h4>

Our Proxmox LXC, VMs, and application installation and configuration processes are made easier with our Easy Scripts. These scripts are designed to automate the process and save you time. It's important to note that Easy Scripts are hardware type-dependent, so make sure to choose the appropriate script for your hardware.

Most Easy Scripts come with preset configurations. During installation, you can either accept or decline these configurations. If you decline, you will be prompted to input all required configuration settings. We recommend that you read our repository guides if you are unsure about any of the steps involved.

To get started, simply copy and paste our Easy Script command into an SSH terminal window, hit Enter, and follow the prompts and on-screen instructions. With our Easy Scripts, you can streamline your Proxmox LXC, VMs, and application installation and configuration processes, and make the most of your time.

<hr>
## PVE Host
GitHub Repository: [here](https://github.com/ahuacate/pve-host)

This toolbox is crucial and should be executed on all Proxmox hosts.

Use it to configure your Proxmox hosts to support our suite of LXC and VM applications, enabling the creation of a reliable Proxmox host.

**Toolbox**

```bash
bash -c "$(wget -qLO - https://raw.githubusercontent.com/ahuacate/pve-host/main/pve_host_toolbox.sh)"
```
<hr>

## PVE NAS
GitHub Repository: [here](https://github.com/ahuacate/pve-nas)

The Lightweight Ubuntu NAS (CT) is suitable for hardware with limited resources and offers LVM or ZFS Raid, a basic single disk ext4 file system or USB disk-based NAS. The OMV NAS (VM) is a more robust solution for demanding storage needs and requires direct attached storage or PCI SAS/SATA/NVMe HBA Card pass-through.
**Installer**
```bash
bash -c "$(wget -qLO - https://raw.githubusercontent.com/ahuacate/pve-nas/main/pve_nas_installer.sh)"
```
**Toolbox**

```bash
bash -c "$(wget -qLO - https://raw.githubusercontent.com/ahuacate/pve-nas/main/pve_nas_toolbox.sh)"
```
<hr>

## Hardmetal NAS
GitHub Repository: [here](https://github.com/ahuacate/nas-hardmetal)

For existing NAS hardware.

We offer Easy Scripts for Synology DiskStations and Open Media Vault (OMV). Our Easy Scripts will modify your NAS settings. At the [repository](https://github.com/ahuacate/nas-hardmetal), you can find further details before running our Easy Scripts.

**Toolbox**

```bash
bash -c "$(wget -qLO - https://raw.githubusercontent.com/ahuacate/nas-hardmetal/main/nas-hardmetal_installer.sh)"
```
<hr>

## PVE Medialab
GitHub Repository: [here](https://github.com/ahuacate/pve-medialab)

Medialab focuses on everything related to Home Media, providing a range of PVE CT-based applications such as Sonarr, Radarr, Jellyfin, and more.

**Installer**
```bash
bash -c "$(wget -qLO - https://raw.githubusercontent.com/ahuacate/pve-medialab/main/pve_medialab_installer.sh)"
```
**Toolbox**

```bash
bash -c "$(wget -qLO - https://raw.githubusercontent.com/ahuacate/pve-medialab/main/pve_medialab_toolbox.sh)"
```
<hr>

## PVE Homelab
GitHub Repository: [here](https://github.com/ahuacate/pve-homelab)

Homelab focuses on everything related to Home Media, providing a range of PVE CT-based applications such as UniFi-Controller, Guacamole, PiHole, ddclient and more. In addition, it offers an Easy Script Installer and Toolbox that automates many of the tasks, accompanied by step-by-step instructions.

However, before you begin using Homelab, it's crucial to ensure that your network, hardware, and NAS setup meet the prerequisites outlined in our guide. It's essential to read and follow this guide before proceeding.

**Installer**
```bash
bash -c "$(wget -qLO - https://raw.githubusercontent.com/ahuacate/pve-homelab/main/pve_homelab_installer.sh)"
```
**Toolbox**

```bash
bash -c "$(wget -qLO - https://raw.githubusercontent.com/ahuacate/pve-homelab/main/pve_homelab_toolbox.sh)"
```
<hr>



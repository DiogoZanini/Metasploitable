# Metasploitable
Intentionally vulnerable VMs for penetration testing practice and security training.

[**PT-BR**](./docs/README.pt-br.md)

![Metasploitable](./docs/metasploitable.png)

## 📦 Dependencies
- [Oracle VirtualBox](https://www.virtualbox.org/) — Virtualization platform;
- **Metasploitable 1** — No longer officially available; requires sourcing from archived mirrors or existing backups.
- [Metasploitable 2](https://sourceforge.net/projects/metasploitable/files/Metasploitable2/) - Official download from SourceForge.
- [Metasploitable 3](https://github.com/rapid7/metasploitable3) — Official repository on GitHub (requires build with Vagrant/Packer).

## 📋 Available Versions
<details>
  <summary>Version Information</summary>

  **Metasploitable 1:**
  - First generation with basic vulnerable services
  - Ubuntu 8.04 based
  - No longer officially available

  **Metasploitable 2:**
  - Enhanced version with additional vulnerabilities
  - Ubuntu 8.04 based
  - More services and misconfigurations
  - Officially available

</details>

## 🚀 Getting Started
<details>
  <summary>Default Credentials</summary>

  - **Username:** msfadmin
  - **Password:** msfadmin
  > 💡**Note:** Versions 1 and 2 share credentials: msfadmin/msfadmin. These credentials are intentionally weak for training purposes.

</details>

<details>
  <summary>Network Configuration</summary>

  In each Virtual Machine network configuration, attach one Network Interface Card (NIC):
  1. **Adapter 1** — LAN (Internal Network - homelab).

  > 💡**Note:** These intentionally vulnerable machines should never be exposed to an untrusted network.
</details>
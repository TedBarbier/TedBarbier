<h1 align="center">Ted Barbier</h1>

<p align="center">
  <b>Élève ingénieur INSA Centre-Val de Loire (STI) · Maîtrise en génie logiciel à l'ÉTS Montréal</b><br>
  Infrastructure as Code · Administration système · Réseau et sécurité
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ted-barbier/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://gitlab.com/TedBarbier"><img src="https://img.shields.io/badge/GitLab-TedBarbier-FC6D26?style=flat&logo=gitlab&logoColor=white" alt="GitLab"></a>
</p>

---

## 👋 Bonjour

J'aime comprendre une infrastructure de bout en bout, du câble au déploiement. Chez moi, ça donne un homelab Proxmox géré entièrement en code. À l'ÉTS, des projets autour de Kafka, de la sécurité applicative et de la qualité logicielle.

> Mes dépôts publics sont visibles des deux côtés : les projets récents vivent sur [GitLab](https://gitlab.com/TedBarbier) et sont recopiés ici en miroir automatique ; les plus anciens vivent ici, avec une copie archivée sur GitLab.

## 🛠️ Compétences

**Infra et virtualisation**<br>
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat&logo=proxmox&logoColor=white)
![OpenTofu](https://img.shields.io/badge/OpenTofu-FFDA18?style=flat&logo=opentofu&logoColor=black)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Réseau et sécurité**<br>
![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=flat&logo=opnsense&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat&logo=wireguard&logoColor=white)
![VLAN](https://img.shields.io/badge/VLAN-802.1Q-555555?style=flat)

**CI/CD et forge**<br>
![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat&logo=gitlab&logoColor=white)
![Forgejo](https://img.shields.io/badge/Forgejo-FB923C?style=flat&logo=forgejo&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Langages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-MariaDB-003545?style=flat&logo=mariadb&logoColor=white)
![Typst](https://img.shields.io/badge/Typst-239DAD?style=flat&logo=typst&logoColor=white)

## 🚀 Projets phares

### 🏠 Homelab en Infrastructure as Code
Cluster Proxmox à 2 nœuds avec QDevice, piloté par **OpenTofu** (état stocké sur GitLab) et **Ansible**. Pare-feu **OPNsense** avec VLAN segmentés, accès distant WireGuard, forge **Forgejo** et runner **GitLab CI** auto-hébergés, schéma réseau généré en Python.
→ [Architecture et choix techniques](https://github.com/TedBarbier/homelab_advanced) · [Version 1 (Raspberry Pi + NAS)](https://github.com/TedBarbier/HomeLab)

### 🛰️ Orion-Dynamic
Simulateur de plateforme PaaS : les workers s'enregistrent d'eux-mêmes auprès d'un control plane qui gère des baux de ressources, la migration en cas de panne et le nettoyage à expiration. API FastAPI derrière Caddy, MariaDB transactionnelle, autoscaler à boucle PID, isolation des clients par Ansible. Projet en binôme.
→ [projet_orion](https://github.com/TedBarbier/projet_orion)

### 📄 typst-thets
Gabarit Typst non officiel de l'ÉTS (portage de thETS) pour thèses, mémoires et rapports de projet.
→ [GitLab](https://gitlab.com/TedBarbier/typst-thets) · [miroir GitHub](https://github.com/TedBarbier/typst-thets)

### 🔐 CryptInsa
Application de médiation scientifique : chiffrement par substitution et attaque par analyse de fréquences, avec démo en ligne. Projet d'équipe à l'INSA.
→ [CryptInsa](https://github.com/TedBarbier/CryptInsa) · [démo](https://cryptinsa-app.onrender.com/)

### 😴 SomnoSafety
Kit à fixer sur des lunettes qui alerte le conducteur quand il somnole : Arduino Nano, capteur de réflexion infrarouge, buzzer.
→ [SomnoSafety](https://github.com/SomnoSafetyCorp/SomnoSafety)

---

<details>
<summary><b>🇬🇧 English version</b></summary>

### Hi, I'm Ted

Engineering student at INSA Centre-Val de Loire (STI) and Master's student in Software Engineering at ÉTS Montréal. I like understanding infrastructure end to end, from the cable to the deployment: at home, that means a Proxmox homelab managed entirely as code; at ÉTS, projects around Kafka, application security and software quality.

My public repositories are visible on both sides: recent projects live on [GitLab](https://gitlab.com/TedBarbier) and are mirrored here automatically; older ones live here, with an archived copy on GitLab.

### Featured projects

- **Homelab as code**: 2-node Proxmox cluster with a QDevice, managed with OpenTofu (state on GitLab) and Ansible; OPNsense firewall with segmented VLANs, WireGuard remote access, self-hosted Forgejo and GitLab CI runner, network diagram generated in Python. [Design](https://github.com/TedBarbier/homelab_advanced)
- **Orion-Dynamic**: PaaS simulator where workers self-register with a control plane handling resource leases, failover migration and cleanup. FastAPI behind Caddy, MariaDB, PID autoscaler, Ansible isolation. Two-person project. [Repo](https://github.com/TedBarbier/projet_orion)
- **typst-thets**: unofficial ÉTS Typst template (thETS port) for theses and reports. [GitLab](https://gitlab.com/TedBarbier/typst-thets)
- **CryptInsa**: science outreach app on substitution ciphers and frequency analysis, with a live demo. Team project. [Repo](https://github.com/TedBarbier/CryptInsa) · [Demo](https://cryptinsa-app.onrender.com/)
- **SomnoSafety**: glasses-mounted kit that alerts drowsy drivers (Arduino Nano, IR reflectance sensor, buzzer). [Repo](https://github.com/SomnoSafetyCorp/SomnoSafety)

### Contact
[LinkedIn](https://www.linkedin.com/in/ted-barbier/) · [GitLab](https://gitlab.com/TedBarbier)

</details>

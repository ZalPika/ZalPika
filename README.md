# Hi, I'm Henning 👋

**Infrastructure & Security Enthusiast** | Building enterprise-grade homelab environments for hands-on learning and skill development

> *Transforming theoretical IT knowledge into practical, production-ready infrastructure*

---

## 🎯 About Me

I'm a systems administrator and security researcher based in Oslo/Lillestrøm, Norway, with a passion for building robust, secure infrastructure. My homelab serves as both a learning platform and a showcase of enterprise-level competencies in networking, virtualization, and security.

**Current Focus:**
- 🏗️ Enterprise homelab infrastructure design
- 🔒 Defense-in-depth security implementations
- 🧪 Security research and malware analysis
- 📚 Continuous learning and skill development

---

## 🛠️ Technology Stack

### Virtualization & Containerization
```
Proxmox VE        ████████████████████ Expert
LXC Containers    ████████████████░░░░ Advanced
Docker            ███████████████░░░░░ Intermediate
KVM/QEMU          ████████████████░░░░ Advanced
```

### Security & Networking
```
OPNsense          ████████████████████ Expert
VLANs             ████████████████████ Expert
WireGuard VPN     ███████████████████░ Advanced
Firewall Rules    ████████████████████ Expert
ClamAV            ███████████████░░░░░ Intermediate
```

### Automation & Scripting
```
Bash              ████████████████░░░░ Advanced
Python            ██████████░░░░░░░░░░ Intermediate
Git               ████████████████░░░░ Advanced
Cron/Systemd      ███████████████░░░░░ Intermediate
```

### Infrastructure Services
```
Nginx             ███████████████░░░░░ Intermediate
Samba             ████████████████░░░░ Advanced
Unbound DNS       ███████████████░░░░░ Intermediate
Plex              ████████████████░░░░ Advanced
```

---

## 🚀 Featured Projects

### 🔒 [Homelab Scripts](https://github.com/ZalPika/homelab-scripts)
Production-ready automation scripts for homelab infrastructure management.

**Highlights:**
- ✅ Multi-layered malware detection (ClamAV + file type validation + manual approval)
- ✅ macOS GUI integration for remote server management
- ✅ Real-time monitoring via SwiftBar menu bar plugins
- ✅ Automated backup strategies with rotation

**Tech:** Bash, zsh, ClamAV, SSH automation, macOS scripting

---

### 🧪 [USB Dropper Malware Research](https://github.com/ZalPika/usb-dropper-research)
Academic cybersecurity research on USB-based attack vectors and Discord C2 infrastructure.

**Highlights:**
- ✅ 60+ page research paper on modern USB threats
- ✅ Comprehensive detection and prevention strategies
- ✅ YARA rules, Sysmon configs, and SIEM queries
- ✅ Ethical framework for security research

**Tech:** Python, PowerShell, Windows Security, Network Analysis

**Note:** Educational purposes only - demonstrates both offensive and defensive security skills.

---

## 🏗️ Current Infrastructure

### Network Architecture
```
┌─────────────────────────────────────────────┐
│          7-VLAN Segmented Network           │
├─────────────────────────────────────────────┤
│ VLAN 10 │ WAN        │ Internet Gateway     │
│ VLAN 20 │ LAN        │ Trusted Devices      │
│ VLAN 30 │ MGMT       │ Infrastructure       │
│ VLAN 40 │ SERVERS    │ Proxmox & Services   │
│ VLAN 50 │ IOT        │ Smart Devices        │
│ VLAN 60 │ IPTV       │ Media Streaming      │
│ VLAN 70 │ GUESTS     │ Isolated Network     │
└─────────────────────────────────────────────┘
```

### Core Components
- **Firewall:** OPNsense with policy-based routing
- **Hypervisor:** Proxmox VE 8.x
- **Network:** Zyxel GS1915 managed switches with PoE
- **Wireless:** LAPAC1750 access points
- **Storage:** Multi-tier with automated spindown
- **Backup:** 3-2-1 strategy with Kingston XS1000 2TB external

### Services Running
- 🔐 **OPNsense** - Firewall, VPN gateway, DNS
- 🎬 **Plex** - Media server (LXC 106)
- 🔄 **qBittorrent** - Policy-routed through VPN (LXC 104)
- 🌐 **Nginx Proxy Manager** - Reverse proxy (LXC 101)
- 📊 **Netbox** - Infrastructure documentation (LXC 107)
- 🔍 **Malware Scanner** - ClamAV with quarantine pipeline

---

## 💡 What I'm Building

### Active Projects

**🔧 Malware-Safe Download Workflow**
- Three-layer security: ClamAV → File validation → Manual approval
- macOS GUI for remote approval
- Real-time status in menu bar
- Zero trust approach to downloads

**🌐 VPN Policy Routing**
- NordVPN WireGuard integration with OPNsense
- Selective routing based on application
- Kill switch for critical services
- Automated failover handling

**📦 Automated Backup System**
- Proxmox host configuration backups
- LXC container snapshots
- Cross-platform automation (Linux + macOS)
- Rotation and cleanup strategies

**📚 Technical Documentation**
- Comprehensive setup guides
- Network diagrams and topology
- Troubleshooting playbooks
- Knowledge base with Markdown

---

## 📊 GitHub Stats

![ZalPika's GitHub stats](https://github-readme-stats.vercel.app/api?username=ZalPika&show_icons=true&theme=dark&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ZalPika&layout=compact&theme=dark&hide_border=true)

---

## 🎓 Learning Path

### Currently Studying
- 🔒 Advanced firewall configurations and threat prevention
- 🐍 Python for network automation
- 🔐 Cryptography and VPN protocols
- 📊 Infrastructure as Code (Terraform, Ansible)
- 🛡️ SOC analysis and incident response

### Certifications & Goals
- 📜 CompTIA Security+ (Planned)
- 📜 CCNA (Studying)
- 📜 Linux+ (Planned)
- 📜 CEH (Long-term goal)

---

## 🛠️ Skills & Competencies

### System Administration
- ✅ Linux server management (Debian/Ubuntu)
- ✅ Virtualization platforms (Proxmox, ESXi experience)
- ✅ Container orchestration (LXC, Docker)
- ✅ User and permission management
- ✅ System monitoring and logging

### Networking
- ✅ VLAN design and implementation
- ✅ Firewall configuration (OPNsense, pfSense)
- ✅ VPN technologies (WireGuard, OpenVPN)
- ✅ DNS management (Unbound, Pi-hole)
- ✅ Network troubleshooting and packet analysis

### Security
- ✅ Defense-in-depth architecture
- ✅ Malware detection and analysis
- ✅ Network segmentation strategies
- ✅ Access control and authentication
- ✅ Security hardening and best practices

### Automation
- ✅ Bash scripting for task automation
- ✅ Cron job scheduling
- ✅ Cross-platform scripting (Linux + macOS)
- ✅ Git version control
- ✅ CI/CD concepts

---

## 💼 Professional Goals

I'm actively seeking opportunities in:
- 🖥️ **System Administration** - Linux/Windows server management
- 🌐 **Network Administration** - Enterprise networking and security
- 🔒 **Cybersecurity** - Security operations, threat analysis
- 🛠️ **DevOps** - Infrastructure automation and monitoring
- 🧪 **IT Infrastructure** - Design and implementation

**What I bring:**
- Hands-on experience with enterprise-grade technologies
- Self-driven learning and problem-solving abilities
- Strong documentation and communication skills
- Passion for security and infrastructure automation
- Practical knowledge from real-world homelab deployments

---

## 📫 Connect With Me

🌐 **Website:** [henningbakke.no](https://henningbakke.no)  
💼 **LinkedIn:** [linkedin.com/in/henningbakke](#) *(Update with your actual link)*  
📧 **Email:** [Contact via website]  
📍 **Location:** Oslo/Lillestrøm, Norway  

---

## 🌟 Recent Activity

<!--START_SECTION:activity-->
*This section will automatically update with recent GitHub activity*
<!--END_SECTION:activity-->

---

## 📈 Contribution Graph

![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=ZalPika&theme=github-compact)

---

## 🎯 2026 Goals

- [ ] Publish 5+ homelab automation scripts
- [ ] Complete network security certification
- [ ] Contribute to open-source networking projects
- [ ] Build comprehensive homelab documentation wiki
- [ ] Achieve 100+ GitHub stars across repositories
- [ ] Land first professional IT role
- [ ] Present at local tech meetup

---

## 💭 Philosophy

> *"The best way to learn is by doing. Theory teaches concepts, but practice builds competence."*

My homelab isn't just a hobby—it's a **learning laboratory** where I can safely experiment, break things, and build enterprise-level skills that translate directly to professional environments.

Every script I write, every service I deploy, and every problem I solve contributes to a portfolio of **real-world experience** that goes beyond certifications and coursework.

---

## 🔧 Tools I Use Daily

**Development:**
- VS Code with Remote-SSH
- Git & GitHub
- Terminal (iTerm2 + zsh)
- SwiftBar for automation

**Infrastructure:**
- Proxmox Web UI
- OPNsense Dashboard
- SSH for remote management
- Tailscale for secure access

**Documentation:**
- Markdown for all docs
- Draw.io for network diagrams
- Notion for knowledge base
- Git for version control

**Monitoring:**
- Custom SwiftBar plugins
- Netdata (planned)
- Syslog aggregation
- Custom alerting scripts

---

## 📚 Blog & Articles *(Coming Soon)*

Planning to share knowledge on:
- 📝 Homelab setup guides
- 🔒 Security hardening tutorials
- 🌐 Network design best practices
- 🐛 Troubleshooting war stories
- 💡 Automation tips and tricks

---

## ⭐ Support My Work

If you find my projects useful:
- ⭐ Star my repositories
- 🔗 Share with others in the homelab community
- 💬 Open issues with suggestions or improvements
- 🤝 Contribute to my projects

Every star motivates me to create more quality content!

---

## 🙏 Acknowledgments

Inspired by the incredible homelab and self-hosting communities:
- r/homelab
- r/selfhosted
- r/proxmox
- Servethehome forums
- Lawrence Systems YouTube

Special thanks to everyone sharing their knowledge—your tutorials and documentation made my journey possible.

---

<div align="center">

### 🚀 Let's Build Something Great

*Passionate about infrastructure. Committed to security. Always learning.*

**Open to collaborations and networking opportunities!**

---

![Profile Views](https://komarev.com/ghpvc/?username=ZalPika&color=blue&style=flat-square)

*Last updated: February 2026*

</div>

## Beruk Gebru

Computer Engineering graduate working in cybersecurity, with a focus on penetration testing, network security and infrastructure. Currently studying AI and automation at University West.

[Website](https://berukgebru.com) · [LinkedIn](https://www.linkedin.com/in/beruk-gebru-b26854265) · [CTF Writeups](https://berukgebru.com/ctf/)

### Selected Projects

| Project | Description | Stack |
|---|---|---|
| [LLM-Driven Multi-Agent Manufacturing System](https://github.com/BERUK-GGG/LLM-Driven-Multi-Agent-Manufacturing-System) | Robotic crane cell controlled by LLM-powered agents that move parts between conveyors and processing machines. | Python |
| [Brain-Eye-Arm](https://github.com/BERUK-GGG/Brain-Eye-Arm) | YOLO on a Raspberry Pi 4 with a Basler camera detects shapes; a Dobot Magician E6 picks and places them. | Python, YOLO |
| [Sensor Calibration using AI](https://github.com/BERUK-GGG/Sensor-Calibration-using-AI) | Cross-sensor drift correction on 600k+ air quality readings. Up to R² 0.86 (PM2.5), 5 of 6 pollutants met targets. | pandas, scikit-learn, XGBoost |
| [Case Management System](https://github.com/BERUK-GGG/case-management-system) | Workshop management for mechanics: customers, bookings, journals, parts inventory. | React, .NET 8, SQL Server, Docker |
| [Home Lab & CI/CD](https://berukgebru.com/about.html) | Self-hosted pipeline that serves berukgebru.com. Push-to-deploy with staging and protected production. | Proxmox, Docker, Ansible, nginx, GitHub Actions |

Other work on the [projects page](https://berukgebru.com/projects.html): brute-force mitigation testing, ML-based network anomaly detection, RSA with LSB steganography, and a two-site enterprise network (CCNA).

### Home Server

Proxmox host running unprivileged LXC containers. Public traffic enters only through a Cloudflare Tunnel; no inbound ports are open.

- **Edge:** Cloudflare TLS, WAF and rate limiting
- **Ingress:** nginx load balancer with Fail2ban
- **App nodes:** Docker, private registry, self-hosted GitHub Actions runner, Ansible
- **Monitoring:** Prometheus, Grafana, Alertmanager with push alerts via ntfy
- **Access:** OpenVPN

### GitHub Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=BERUK-GGG&hide_border=true&theme=github-dark-blue&background=00000000">
  <img height="165" alt="Contribution streak" src="https://streak-stats.demolab.com?user=BERUK-GGG&hide_border=true&background=00000000">
</picture>

# 👋 Hi, I'm Joost

Infrastructure person who likes owning the whole stack: from the switch port and the hypervisor up to the app running on it. Big on **digital sovereignty**: if I can run it myself, I will.

- 🔐 Interested in cyber security, networking, virtualization and home automation (with a side of electrical engineering)
- 🏠 Run a self-hosted home infrastructure that replaces most cloud services I used to depend on
- 🛠️ Build small tools and apps as a hobby, usually self-hostable and DIY

---

## 🖥️ Home infrastructure

Everything below runs on my own hardware, at home, behind my own reverse proxy and VPN.

| Area | What I run |
|---|---|
| **Storage & hypervisors** | Unraid and TrueNAS for storage and containers/VMs |
| **Files & sync** | Nextcloud as the central cloud |
| **Cameras / NVR** | Frigate with object detection, fully local, no cloud |
| **Home automation** | Home Assistant integrated with Frigate, Zigbee devices and custom hardware |

A never-ending and ever-evolving adventure.

---

## 🎓 Infrastructure work during my studies

- **VMware vSphere cluster**: multi-node ESXi cluster with vCenter, shared storage (SAN via iSCSI), HA and vMotion
- **Proxmox VE cluster**: clustered nodes with shared storage (SAN via iSCSI), HA and live migration
- **Active Directory integration**: both clusters authenticated against Windows AD via LDAP, with role-based access for students and staff
- Network design for the above: VLAN segmentation, management/storage/VM traffic separation, firewalling

---

## ⌨️ Macropad v2: hardware and software, both mine

The project I'm proud of, because it goes from KiCad schematic to firmware to the key you press.

```
   [ Play ] [ Prev ] [ Next ]   ( Knob )
   [ F13  ] [ F14  ] [ F15  ] [ F16  ]
   [ F17  ] [ F18  ] [ F19  ] [ F20  ]
   [ F21  ] [ F22  ] [ F23  ] [ F24  ]
```

- **Hardware**: custom 2-layer PCB designed in KiCad (ERC 0, DRC 0), 4x4 diode matrix, EC11 rotary encoder, header for a Pro Micro, optional OLED and up to four 3.5 mm jacks for external buttons such as a foot pedal. Gerbers, BOM and ordering notes in the repo.
- **Firmware**: C++ on the Pro Micro using HID-Project. Non-blocking matrix scan with debouncing so keys can be held, interrupt-driven encoder that never misses a step, knob modes (volume, scroll, arrows) with long-press switching, hold-and-turn, and auto-return to volume.
- **Design choice**: keys send F13–F24, which no normal keyboard has, so they bind cleanly in AutoHotkey, OBS, Discord and games. Actions are plain data, so a web configurator can rewrite them later.

---

## 🧪 Tooling I reach for

`Docker` `Proxmox` ~~`VMware`~~ `TrueNAS` `Unraid` `Linux` `WireGuard` `Tailscale` `Home Assistant` `Frigate` `Nextcloud` `PostgreSQL` `KiCad` `Arduino`

---

## 📫 Reach me

- Open an issue on one of my repos, or find me via the links on this profile.

<!---
joosterws/joosterws is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

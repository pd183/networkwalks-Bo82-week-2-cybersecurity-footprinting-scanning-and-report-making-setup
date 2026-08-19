# networkwalks-Bo82-week-2-cybersecurity-footprinting-scanning-and-report-making-setup
# Week 2 – Cybersecurity & Ethical Hacking Internship

## 📌 Overview

This repository documents my **Week 2 practical activities** completed during my **Cybersecurity & Ethical Hacking Internship at Networkwalks**.

The activities focused on two important phases of cybersecurity:

- **W2-PM1:** Footprinting & Reconnaissance using Maltego
- **W2-PM5:** Network Scanning using Zenmap (Nmap GUI)

> ⚠️ **Disclaimer:** All scanning activities were performed only on authorized systems/networks or my own local network for educational and cybersecurity training purposes.

---

## 🔍 W2-PM1 – Footprinting & Reconnaissance using Maltego

### Objective

To perform reconnaissance and understand how publicly available information related to a target domain can be collected and represented graphically.

### Tool Used

**Maltego**

### Activities Performed

- Added the target domain to Maltego.
- Performed graphical reconnaissance using available transforms.
- Analyzed relationships between discovered entities.
- Identified an **email address associated with the target domain**.
- Studied how publicly available information can contribute to a target's digital footprint.

### Key Learning

Maltego helped me understand how different pieces of publicly available information can be connected and visualized as a relationship graph during the reconnaissance phase.

### Evidence

Screenshots of the Maltego footprinting graph are included in this repository.

---

## 🌐 W2-PM5 – Network Scanning using Zenmap

### Objective

To identify active hosts on my own local network using Zenmap/Nmap.

### Tool Used

**Zenmap (Nmap GUI)**

### Network Scanned

```
192.168.**.0/24

```

### Scan Type

**Ping Scan**

### Command

```
nmap -sn 192.168.**.0/24

```

### Scan Results

| ParameterResult      |                   |
| -------------------- | ----------------- |
| Network              | `192.168.**.0/24` |
| Scan Type            | Ping Scan         |
| IP Addresses Scanned | 256               |
| Live Hosts Found     | 1                 |
| Discovered Host      | `192.168.**.1`    |
| Host Status          | Up                |
| Scan Duration        | 11.82 seconds     |
| Nmap Version         | 7.99              |

### Observation

The Zenmap scan identified **one active host:** **`192.168.**.1` within the scanned local network.

This practical helped me understand the basic process of host discovery and network mapping using Nmap through the Zenmap graphical interface.

---

## 🧠 Key Learnings

Through these activities, I learned:

- Basics of **footprinting and reconnaissance**
- Using **Maltego** for graphical information gathering
- Understanding relationships between publicly available entities
- Identifying publicly exposed email information
- Basics of **network discovery**
- Using **Zenmap/Nmap** for Ping Scanning
- Identifying live hosts on a local network
- Understanding CIDR notation such as `/24`
- Documenting cybersecurity findings professionally
- The importance of performing security testing within an **authorized scope**

---

## 🛠️ Tools & Technologies

- Maltego
- Zenmap
- Nmap
- Windows CMD
- Cybersecurity & Ethical Hacking concepts

## 📸 Evidence

### Maltego – Footprinting

### Zenmap – Network Scanning

The Zenmap evidence shows the scan of `192.168.**.0/24` and the discovery of the live host `192.168.56.1`.

---

## 🎯 Conclusion

This week's practical activities gave me hands-on experience with **reconnaissance, footprinting and network scanning**.

Using Maltego helped me understand how publicly available information can be mapped and connected, while Zenmap helped me understand how active hosts can be identified within an authorized network.

I look forward to applying these concepts in more advanced cybersecurity labs and practical security assessments.

---

### 📚 Internship

**Program:** Cybersecurity & Ethical Hacking
**Organization:** Networkwalks
**Week:** 02
**Focus:** Footprinting, Reconnaissance & Network Scanning

# Threat Research [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://github.com/threatmaniac/threat-research/blob/main/threat_research.jpg" align="right" width="100">] (https://github.com/threatmaniac/threat-research)]


This list is to help all of those who are into Cyber Threat Intellience (CTI), threat hunting, or OSINT. From beginners to advanced. 


## 📖 Table of Contents

 - [Shodan](#-shodan-queries)
 - [FOFA Search Engine](#-google-dorks-tools)

---

## Shodan Queries

| Threat / Use Case | Shodan Query |
|------------------|-------------|
| Exposed RDP | `port:3389` |
| Exposed SSH | `port:22` |
| Exposed Telnet | `port:23` |
| C2 Panel | `http.title:"C2 Panel"` |


## FOFA Queries

| Threat / Use Case | Shodan Query |
|------------------|-------------|
| Finds new Remote Administration Tools | `title="Remote Administration Tool" ` |
| To Find new InfoStealers | `title="InfoStealer"` |
| C2 Panel | `title="C2 Panel"` |

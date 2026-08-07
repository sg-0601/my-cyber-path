# My Cybersecurity Path

A personal, hands-on cybersecurity learning repository. It combines foundational reference material with an interactive Jupyter Notebook that maps a beginner-to-practitioner path across offensive security, defensive security, cloud security, GRC, and specialization.

> This repository is for authorised learning, lab work, and ethical security practice only. Test tools and techniques only against systems you own or have explicit permission to assess.

## What's inside

```text
.
├── foundation/
│   ├── Linux and its basic commands       # Foundation reference PDF
│   └── Networking and its basic           # Foundation reference PDF
└── roadmap/
    └── Cybersecurity.ipynb                # Interactive master learning roadmap
```

The files in `foundation/` are PDFs without file extensions; open them with any PDF reader.

## Roadmap overview

The master notebook is a living plan intended for a steady pace of roughly **10–15 hours per week**. It includes estimated study time, suggested learning resources, certification checkpoints, and a status column to track progress.

| Area | Focus |
| --- | --- |
| Foundation | Networking, Linux, Kali Linux, and Python |
| Stage 1 | Advanced networking, Linux, scripting, and core technical skills |
| Stage 2 | Ethical reconnaissance, vulnerability assessment, web security, and red-team fundamentals |
| Stage 3 | SIEM, log analysis, incident response, malware analysis, forensics, and monitoring |
| Stage 4 | Web/API, mobile, cloud, container, and bug-bounty security |
| Stage 5 | Advanced Active Directory, red-team tradecraft, exploit development, and reverse engineering |
| Stage 6 | Governance, risk, compliance, NIST, ISO 27001, and MITRE ATT&CK |
| Stage 7 | A focused offensive, defensive/forensics, or bug-bounty specialization |
| Purple Teaming | Detection engineering and red/blue collaboration |

The notebook also lists practice platforms, free learning certificates, major certification milestones, portfolio habits, and optional niche domains such as IoT, OT/ICS, hardware, and cryptography.

## Getting started

1. Clone the repository.

   ```bash
   git clone https://github.com/sg-0601/my-cyber-path.git
   cd my-cyber-path
   ```

2. Install Jupyter if it is not already available.

   ```bash
   python -m pip install jupyter
   ```

3. Open the roadmap.

   ```bash
   jupyter notebook roadmap/Cybersecurity.ipynb
   ```

4. Update the status cells as you progress:
   - `⬜ Not Started`
   - `🟡 In Progress`
   - `✅ Completed`

## Suggested study workflow

- Begin with the networking and Linux foundation material.
- Work through the stages in order, while revisiting earlier topics when needed.
- Use only legal training environments such as TryHackMe, Hack The Box, PortSwigger Web Security Academy, Blue Team Labs Online, and deliberately vulnerable local labs.
- Keep notes, document lab work, and add your own scripts or write-ups as the portfolio grows.
- Treat the roadmap as adaptable: add resources, adjust estimates, and choose a specialization based on experience and interests.

## Prerequisites

- A PDF reader for the foundation material
- Python 3 and Jupyter Notebook (or JupyterLab) for the interactive roadmap
- A safe, authorised lab environment for practical exercises

## Contributing

This is a personal learning repository, but useful corrections and resource suggestions are welcome. Please keep contributions educational, ethical, and limited to authorised security testing.

## License

No license has been added yet. All rights are reserved unless the repository owner adds a license file.

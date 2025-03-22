# CyberHunt

## 📌 Overview  
This project analyzes the tactics, techniques, and procedures (TTPs) of Cyber Avengers and Voltzite, two prominent cyber threat groups. The research focuses on their attack methods, motivations, and effective mitigation strategies to enhance cybersecurity defenses. The project article can be found at: https://medium.com/@baborovanat/decoding-threats-how-cyber-avengers-and-voltzite-exploit-vulnerabilities-and-how-to-stop-them-6a0914466578

## 🔍 Key Findings  

- **Cyber Avengers:** 
   - Primary Targets: Israeli-made industrial control systems (ICS) and operational technology (OT).
   - Methods:
        Exploits default credentials, weak configurations, and outdated firmware on ICS devices.
        Uses open-source tools like Shodan to identify vulnerable systems.
        Focuses on low-effort, high-impact attacks for disruption and propaganda.
   - Motivations:
        IRGC-affiliated, primarily engaged in influence operations.
        Amplifies its attacks via Telegram, exaggerating its impact.

- **Voltzite:** 
   - Primary Targets: U.S. and African critical infrastructure (electric grids, telecom, and defense sectors).
   - Methods:
        Exploits unpatched networking devices, SOHO routers, and legacy hardware.
        Uses living-off-the-land (LOTL) techniques (e.g., PowerShell) to maintain persistence.
        Employs multi-hop proxies and compromised devices for stealthy command-and-control channels.
   - Motivations:
        Chinese state-sponsored espionage.
        Focuses on long-term network infiltration rather than immediate disruption.

## 🛡 Mitigation Strategies

- Patch Management: Regularly update and secure all devices, especially legacy hardware.
- Access Controls: Enforce least privilege principles and restrict administrative access.
- Monitoring & Detection:
        Implement anomaly detection for PowerShell activity and unauthorized access.
        Set up alerts for suspicious network traffic and credential stuffing attempts.
- Harden Entry Points:
        Secure ICS/OT devices with strong credentials and network segmentation.
        Update router firmware to prevent exploitation by botnets like KV Botnet.
  
## 📂 References 
A detailed list of references is included in the full report. Key sources include:  
- CISA & Microsoft Threat Intelligence reports 
- Dragos & SecureWorks analysis of threat actor tactics
- Recorded Future assessments on cyber threat trends

## 📌 Author 
**Natalie Baborova**  
Master’s in Cybersecurity, Georgia Institute of Technology 

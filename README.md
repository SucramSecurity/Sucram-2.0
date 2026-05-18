

Sucram 2.0 is a next‑generation cybersecurity suite focused on identity protection, threat detection, and account‑integrity monitoring. Built by The Village Brotherhood Project, Sucram 2.0 provides transparent, verifiable, and user‑controlled security tools designed to protect digital identities in real time.

## Features
- Real‑time threat detection
- Device‑trust architecture
- Identity protection and verification
- Tamper‑proof activity logging
- Privacy‑first design (no raw sensitive data stored)
## Mission
To give people control over their digital identity through transparent, open‑source, and self‑defending security tools.



🔐 Identity Discovery Module (IDM)
The Identity Discovery Module (IDM) is the foundation of Sucram 2.0. It defines who the system is interacting with, how identity is verified, and how risk is scored. Every other module — Threat Detection, Device Intelligence, and Session Monitoring — depends on this layer.

Identity Inputs
- Device fingerprint  
- Network signature  
- Behavioral patterns  
- Account metadata  
- Location consistency  

Identity Signals
- Typing rhythm  
- Login timing patterns  
- Device switching frequency  
- IP velocity  
- Session anomalies  

Identity Threats
- Account takeover attempts  
- Spoofed device fingerprints  
- Suspicious session chaining  
- Impossible travel events  
- Credential stuffing indicators  

Verification Flow
1. Collect identity inputs  
2. Compare against historical patterns  
3. Generate risk score  
4. Trigger ALLOW / BLOCK / REVIEW / RETRY  
5. Log event for audit and machine‑learning feedback  

Identity Confidence Score
- 0–30: High Risk — block or force verification  
- 31–70: Medium Risk — challenge with MFA or device check  
- 71–100: Trusted Identity — normal access  

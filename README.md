# Cybersecurity System Hardening: A Professional Implementation Study

*Submitted by: Hassan Ali Attallah*  

*Major: Cybersecurity Technology Engineering (2nd Year)*  

*Institution: Al-Hadi University , Iraq*  

*## 1. Project Overview*

*In this project, I applied system hardening techniques to secure my personal workstation based on cybersecurity best practices.*

*The main goal was to improve system security by reducing vulnerabilities and applying layered defense mechanisms based on the CIA triad: Confidentiality, Integrity, and Availability.*

*I also appreciate the CS50 course for providing a strong foundation in cybersecurity concepts.*

*​*

*.​2 Risk Assessment \& The CIA Triad*

*​Following the principles of Information Security I identified 26 critical vectors within my personal workstation (MSI Katana 15). My goal was to achieve a state of "Resilient Security" ensuring Confidentiality Integrity and Availability for all my engineering projects.*


*​3. Hardware \& Firmware Security (BIOS/TPM)*

*​I implemented BIOS-level protections and utilized the Trusted Platform Module (TPM 2.0) to ensure that the foundation of my system is untampered. This prevents low-level exploits and unauthorized boot-order modifications.*

*​4. Kernel-Level Defense (Secure Boot)*

*​By enforcing Secure Boot I ensured that only digitally signed and trusted Operating System loaders are executed effectively neutralizing rootkits and boot-level malware.*

*​5. Network Perimeter Orchestration (Firewall)*

*​I audited the Windows Defender Firewall implementing a "Default Deny" policy for inbound traffic. This minimizes the system's attack surface when connected to academic or public networks.*

*​6. Advanced Outbound Filtering*

*​Monitoring outbound connections to ensure that no background processes are communicating with unauthorized external servers maintaining total control over data egress.*

*​7. Cryptographic Implementation (BitLocker)*

*​I utilized AES-256 bit Full Disk Encryption. This ensures that all intellectual property and academic data remain confidential even in the event of physical hardware compromise.*

*​8. Multi-Factor Authentication (MFA) Integration*

*​In alignment with modern identity standards I enforced TOTP-based MFA across all my professional repositories and communication channels, moving beyond the vulnerabilities of static passwords.*

*​9. The Principle of Least Privilege (PoLP)*

*​I restructured my system's access control operating under a standard user profile to contain potential threats and prevent unauthorized administrative escalations.*

*​10. Proactive Patch Management*

*​Established a rigorous update lifecycle for the OS and all security-critical drivers ensuring immediate mitigation of newly discovered CVEs (Common Vulnerabilities and Exposures).*

*​11. DNS Security (DNS-over-HTTPS)*

*​By encrypting DNS queries I prevented local network adversaries from intercepting my browsing patterns or conducting DNS hijacking attacks.*

*​12. Secure Tunneling (VPN)*

*​Mandated the use of encrypted VPN tunnels for all remote sessions ensuring data integrity during transmission across untrusted network nodes.*

*​13. High-Entropy Credential Management*

*​Utilizing an encrypted vault to manage unique high-entropy passwords effectively eliminating the risk of brute-force and credential-stuffing attacks.*

*​14. Registry \& System Hardening*

*​Disabled legacy protocols and non-essential features within the Windows Registry that are historically exploited by advanced persistent threats (APTs).*

*​15. Port Stealthing \& Management*

*​Audited all logical ports and closed non-essential services (SMB, Telnet) to prevent lateral movement and unauthorized scanning.*

*​16. Browser Environment Hardening*

*​Configured my browsing environment with strict privacy controls and security extensions to mitigate web-based delivery vectors for malware.*

*​17. Peripheral Device Control*

*​Implemented policies to restrict unauthorized USB devices protecting the system against hardware-based "Rubber Ducky" or malicious HID attacks.*

*​18. Security Log Auditing (Event Viewer)*

*​Establishing a baseline for system behavior by regularly auditing Windows Security logs to detect and respond to anomalies.*

*​19. Digital Signature Verification*

*​Enforced strict execution policies where only software with valid trusted digital signatures can be executed on the workstation.*

*​20. Privacy \& Metadata Sanitization*

*​Implementing a workflow to strip sensitive metadata from all outgoing professional documents to prevent unintended information disclosure.*

*​21. Disaster Recovery \& Redundancy*

*​Applying the 3-2-1 backup rule to ensure data availability and resilience against ransomware or hardware failure.*

*​22. Wireless Protocol Optimization (WPA3)*

*​Prioritizing the latest encryption standards for wireless communication to defend against modern Wi-Fi cracking techniques.*

*23. Bloatware \& Surface Area Reduction*

*​Systematically removed all unnecessary pre-installed applications to eliminate hidden vulnerabilities and improve system performance.*

*​24. Defensive Social Engineering Awareness*

*​Applying the "Human Firewall" concept by critically analyzing all digital communications for phishing indicators.*

*​25. Ethical Responsibility \& Professionalism*

*​As a future leader in the cybersecurity industry I commit to using these skills to protect and serve the digital community with the highest ethical standards.*

*​26. Final Project Conclusion*

*​This project is more than a technical requirement it is a manifestation of the knowledge gained from CS50.I learned that cybersecurity is not just about tools, but about building multiple layers of protection. This experience helped me understand how to apply what I learned in real-world scenarios.



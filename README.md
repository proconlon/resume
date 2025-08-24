# James Conlon
📍 NYC Metro Area \
📧 [proconlon52@gmail.com](mailto:proconlon52@gmail.com) \
🔗 [GitHub](https://github.com/proconlon) \
🔗 [LinkedIn](https://linkedin.com/in/proconlon/)

---

## Education
**Boston University** \
**B.S. in Computer Engineering** \
**Minor in Computer Science** \
GPA: 3.56 \
*Sep 2022 – May 2026*

---

## Experience

### **ei³ : Industrial Internet Intelligence** — Pearl River, NY  
**Embedded Software and Security Intern**  
*Jun 2025 – Present*  
- Designed and implemented a novel OpenVPN-based TAP server solution using Linux network namespaces, policy
routing, and multiple "virtual proxy" VPN clients to resolve client-side NAT and subnet overlap issues for legacy
industrial devices.  
- Developed a comprehensive Python migration service to automate industrial router (Ewon, mGuard) configuration
by downloading, validating, and uploading new profiles, ensuring zero-downtime migration while parsing and
preserving full customer network topologies.  
- Collaborated with internal support teams to author the SOP for automated remote deployments, establishing a safe
migration process that preserves complex customer network topologies like VLANs and static routes.  
- Designed and owned the REST API and data model (Python/Flask) for managing device configurations and
firmware, allowing future expansion for new device models or new device-specific features.  

**Embedded Software and Security Intern**  
*Jun 2024 – Jun 2025* *(FT Summer, PT during semesters)*  
- Engineered a configurable OpenVPN TUN server in Docker, designed for deployment on edge hardware to establish
a migration path for third-party industrial devices onto the ei³ platform.  
- Simulated factory networks (OPC-UA, MODBUS, PLCs), and performed competitive benchmarking against key
competitors to evaluate technical capabilities, user experience, and security.  

---

### **BU Information Services and Technology** — Boston, MA  
**IT Support Specialist**  
*Aug 2022 – Dec 2024*  
- Diagnosed and resolved hardware/software issues: Windows/Mac/Linux, networking, and academic software. 

---

## Projects

### **[Predictive Maintenance Edge Data Logger](https://github.com/proconlon/pm-edge-data-logger)**  
*C, Python, AWS S3, Tailscale, BeagleBone* | *May 2025*  
- Developed an end-to-end connected edge device data logger on a BeagleBone Black, using C for data acquisition
from an OPC-UA server and Python for ML and cloud integration.  
- Designed a dual-rate logging system to minimize cloud costs, capturing high-frequency data locally for ML model
training and low-frequency data for long-term storage in AWS S3.  
- Implemented secure remote access using Tailscale, air-gapping a factory network while enabling remote device
management and data retrieval.  
- Deployed a local Python ML model for predictive maintenance, analyzing high-frequency data to forecast
equipment failures and automatically send email alerts to operators.  

---

### **[FPGA-Based Keyboard Synthesizer](https://github.com/proconlon/fpga-synth)**  
*Verilog, FPGA, Digital Signal Processing, Team Project* | *Dec 2023*  
- Developed a digital synthesizer on Artix-7 FPGA, enabling simulation of musical notes and octaves.  
- Designed a module for generating PWM signals with variable duty cycles to simulate sound waveforms including
square, sine, and triangle waves.
- Integrated PS/2 keyboard input for control, along with a 7-segment display and audio output for feedback. 
- Collaborated with team to address challenges such as sound generation and timing issues related to waveform
indexing. 

---

## Technical Skills
- **Languages:** Python, Go, C (systems-level), Bash, Verilog  
- **Frameworks & Tools:** Flask, Linux (Debian/Alpine/RHEL/Fedora), OpenSSL 
- **DevOps & Virtualization:** Docker, Docker Compose, Git, CI/CD (GitHub Actions), Jira 
- **Networking & Security:** TCP/IP, OpenVPN, NAT, VLANs, Policy Routing, PKI, Wireshark 
- **Relevant Coursework:** Systems: {Distributed, Embedded, Operating}, Cybersecurity, Client-Server Software, Intro Databases  

---

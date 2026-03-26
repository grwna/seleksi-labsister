# 2025-b-1 - Selection Part B, Stage 1

This folder contains the technical projects for the first stage of Part B in the Lab Sister 2025 selection process. These tasks focus on systems administration, security, parallel computing, and integrated systems technology.

## Projects and Documentation

### 1. [Arch Linux Installation Manual](./1-What%20you're%20referring%20to%20as%20Linux,%20is%20in%20fact,%20GNU-Linux/)
- **Objective:** Professional writing of a walkthrough for manual installation of a GNU/Linux distribution (Arch Linux) on a Virtual Machine.
- **Content:** A detailed tutorial/guide and a video walkthrough of the installation process. Installation includes the installation of a functional GUI, audio-visual capabilities, internet connectivity, package management, and a non-root user setup. 

### 2. [Certified Tech Frustration (CTF Challenges)](./2-Certified%20Tech%20Frustration%20-%20Sponsored%20By%20HTB/)
- **Objective:** Solve various cybersecurity challenges in Hack the Box to learn penetration testing and system security. Also includes complete writeups to detail the solutions I've used for each challenges
- **Challenge Categories:**
  - **Blockchain:** Smart contract interaction and auditing.
  - **Web/Patching:** Finding and fixing vulnerabilities in web applications.
  - **Penetration Testing:** Finding vulnerabilities within a web application, all the way down to gaining access to a remote shell instance.
  - **Forensics:** Investigating system breaches (Operation Blackout 2025).
  - **Cryptography:** Quantum-safe encryption algorithms (Learning with Errors).
  - **Reverse Engineering:** Crack the flag encryption using graph traversal analysis within a binary file.
  - **PWN:** Buffer overflow vulnerability exploitation to achieve shell access.

### 3. [DNS - DeeezNuddS (Network Simulation)](./3-DNS%20-%20DeeezNuddS/)
- **Objective:** Simulate a small-scale network using 4 Arch Linux Virtual Machines to understand DNS and traffic routing.
- **Architecture:** 
  - **VM 1:** DNS Server (pointing to the reverse proxy).
  - **VM 2:** HTTP Server (hosting a custom webpage).
  - **VM 3:** Client (interacts via a custom CLI program).
  - **VM 4:** Reverse Proxy (mediating traffic to the server).
- **Features:** DHCP automation and firewall rules to restrict traffic to specific ports (8080) and IP ranges.

### 4. [Mandelbrot of Madness (Mangelbrot Generator)](./4-Mandelbrot%20of%20Madness/)
- **Objective:** Create a high-performance Mandelbrot and Julia set generator in C++.
- **Implementations:** 
  - **Serial:** Baseline single-threaded calculation.
  - **Parallel CPU:** Multi-threaded acceleration using OpenMP or `std::thread`.
  - **GPU Acceleration:** High-speed rendering using CUDA or OpenCL kernels.
- **Features:** Interactive GUI (SFML/ImGui) with real-time zooming, panning, and benchmarking tools.

### 5. [BCM - Baka!! Chuunibyou Mode](./5-BCM%20-%20Baka!!%20Chuunibyou%20Mode/)
- **Objective:** Design a **Business Capability Model (BCM)** for an IT enterprise.
- **Scope:** Analysis of business processes and the technology stack required to support a startup or established IT service provider.

### 7. [TST - Integrated System Techbology Project](./7-Roses%20are%20red,%20kerjain%20TST,%20or%20sister-chan%20won't%20be%20your%20fiancé/)
- **Objective:** Develop a secure, integrated business service, according to the business's requirements. Also includes API documentation.
- **Requirements:** 
  - Detailed business documentation (Business Strategy, Service Model).
  - Technical diagrams (Use Case, Sequence, ERD, Application Architecture).
  - Secure API development using the **OAuth2** schema.

### 8. [Se mettre Requiem (Big Integer Multiplier)](./8-Se%20mettre%20Requiem/)
- **Objective:** Implement a massive integer multiplier in C restricted to bitwise operators and basic control flow and instructions.
- **Algorithm:** Uses **Number Theoretic Transform (NTT)** to achieve $O(N \log N)$ complexity, capable of handling multiplications of numbers up to $10^{1,000,000}$ digits in a reasonable time (~180 seconds).
- **Constraints:** No `malloc`, no `*` operator for variables, only `stdio.h` allowed.

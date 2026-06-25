 Honeypot Detection Lab

## Project Overview
A honeypot is a deliberately vulnerable system designed to lure attackers and log their activity. This project deploys a honeypot using OpenCanary to simulate network services, monitor unauthorized access attempts, and analyze attacker behavior core skills used in Security Operations Center (SOC) environments.

## Tools Used
- **OpenCanary** - Open source honeypot framework
- **GitHub Codespaces** - Cloud-based development environment (no local installation required)
- **Python 3** - Used to simulate attack traffic against the honeypot
- **GitHub** - Project hosting and documentation

 What I Did
1. Created a GitHub repository to host the project
2. Launched a free cloud environment using GitHub Codespaces
3. Installed OpenCanary honeypot software
4. Generated the default configuration file
5. Started the honeypot and verified it was running
6. Simulated an FTP connection attempt using Python to test detection
7. Reviewed the system logs to confirm the honeypot captured the activity

 Log Analysis
- **FTP Service Emulation** - OpenCanary successfully deployed a fake FTP service to attract attackers
- **Canary Running** - Confirmed the honeypot was active and listening for connections
- **Network Restriction Finding** - Codespaces environment limited full port binding. Future deployment will use AWS EC2 for full internet exposure and real attack traffic capture

 What I Learned
- How honeypots work as a deception-based security tool
- How to deploy and configure OpenCanary in a cloud environment
- How to read and interpret security logs
- How network ports and services work in a live environment

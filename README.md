### Johnny Meintel

I'm an IT specialist building hands-on experience in security operations and detection engineering. I run controlled attacks in my homelab, investigate the resulting telemetry, troubleshoot failures, and write up what I learn.

**[Portfolio and current homelab](https://purplepyram1d.github.io/#current-lab)** · **[Technical writeups](https://purplepyram1d.github.io/blog/)** · **[Resolved LabWatch cases](https://purplepyram1d.github.io/labwatch/)**

My current lab runs on two physical hosts and six VMs: an Active Directory domain controller, an application server, two Windows workstations, a Wazuh and Velociraptor server, and Kali. It brings identity, endpoint telemetry, applications and incident handling together so I can follow an exercise from the initial action through investigation and recovery.

- **Detection and investigation:** Sysmon and Windows/application logs feed Wazuh; LabWatch ingests Wazuh alerts directly for case triage. Velociraptor supports targeted endpoint evidence collection.
- **Identity and systems:** Active Directory, DNS, Group Policy, departmental file permissions, IIS, MySQL-backed applications, and lab mail services.
- **Web and API security:** Scoped exercises with DVWA, FakeCorp and BountyAPI, including a fixed comparison application for checking remediation.
- **Networking and recovery:** Packet-capture exercises, physical versus virtual traffic visibility, scheduled health checks, backups, and validation of alert delivery after shutdown and repair.

**Featured project:** [rmm-multiplicity](https://github.com/purplepyram1d/rmm-multiplicity) explores abuse of remote-access tools using Sysmon, custom Wazuh detections and endpoint evidence. [Read the first writeup](https://purplepyram1d.github.io/blog/posts/one-rmm-is-it-two-is-an-incident.html).

My writing records the evidence, limitations and troubleshooting behind each exercise. Historical writeups retain the environment used at the time; the portfolio's current overview describes the lab today.

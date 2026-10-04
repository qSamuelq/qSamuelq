## Sam Nwabunike

Second-year Cyber Security student at the University of Warwick, focused on **detection engineering and SOC work**: building telemetry pipelines, writing and tuning detections, and measuring whether they actually work.

I also do offensive security (Hack The Box, binary exploitation, pentesting coursework), and use it to write better detections. If I know how an attack runs, I know what it should leave behind.

**Currently**
- Studying for CompTIA Security+ (SY0-701), exam booked for November 2026
- doing certification-mapping research at WMG for the University of Warwick.

### Featured: [Home SOC / SIEM Detection Lab](https://github.com/qSamuelq/home-soc-lab)

Windows and Linux Sysmon telemetry into Microsoft Sentinel via Azure Arc, attacks emulated with Atomic Red Team, and a KQL + Sigma detection for each technique.

- **5 detections** across Execution, Persistence, Privilege Escalation, Command & Control and Collection
- **31 → 5 incidents (~84% fewer)** for identical attacker activity, by tuning Sentinel event and alert grouping in controlled before/after batches
- Caught a rule that was detecting the test harness instead of the technique, and documented a Sysmon blind spot that no query can fix

### Projects

| Project | What it is | Stack |
| --- | --- | --- |
| [home-soc-lab](https://github.com/qSamuelq/home-soc-lab) | Detection engineering lab with documented case files per technique | Sentinel, KQL, Sigma, Sysmon, Azure Arc |
| [KeyHunt](https://github.com/qSamuelq/KeyHunt) | Linux credential auditor: 25 filename signatures, 9 content regexes and a Shannon-entropy layer for secrets no pattern describes | Python |
| [NetFusion Network Design](https://github.com/qSamuelq/netfusion-network-design) | 90-host segmented enterprise network: VLANs, router-on-a-stick, OSPF, DHCP relay, PAT, departmental ACLs | Cisco Packet Tracer |
| [LogSentinel](https://github.com/qSamuelq/log-analysis-anomaly-detection-program) | Log ingestion, normalisation and rule-based anomaly detection (failed logins, blacklisted IPs, out-of-hours access) | Python (stdlib only) |
| [Binary Exploitation](https://github.com/qSamuelq/binary-exploitation-analysis) | Bypassing a hardcoded auth check, then a stack buffer overflow to code execution (ret2win) | GDB, Python |
| [nftables Firewall Hardening](https://github.com/qSamuelq/nftables-firewall-hardening) | Default-deny host firewall for an internet-facing Linux server, with rate-limited SSH, logging and automated deploy/rollback | nftables, Bash |
| [ML Bot Detection](https://github.com/qSamuelq/ML-Based-Network-Bot-Detection-System) | Supervised pipeline classifying human vs automated traffic; logistic regression vs random forest on deliberately noisy data | Python, pandas, scikit-learn |
### Tools

**Detection:** Microsoft Sentinel · KQL · Sigma · Sysmon · Atomic Red Team
**Infrastructure:** Azure Arc · Linux · nftables · Cisco IOS
**Offensive:** Nmap · Metasploit · GDB
**Languages:** Python · Bash

### Reach me
[LinkedIn](https://www.linkedin.com/in/samuel-nwabunike) · samuelqp8@gmail.com

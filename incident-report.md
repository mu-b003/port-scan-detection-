# Incident Report

## Incident

TCP Port Scan Detection

---

## Severity

Medium

---

## Source

Kali Linux

192.168.81.128

---

## Target

Ubuntu Server

192.168.81.129

---

## Attack Type

TCP Port Scan

Reconnaissance

---

## Tools Used

Nmap

---

## Open Ports

22/tcp

80/tcp

---

## Indicators

- Thousands of SYN packets
- Large number of RST responses
- Sequential destination ports
- Very short intervals between packets

---

## Conclusion

The captured traffic confirms automated reconnaissance activity performed using Nmap. The scan targeted thousands of TCP ports in a short period. Only SSH and HTTP services were accessible, while the remaining ports responded with TCP Reset packets.

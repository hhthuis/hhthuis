<h1 align="center">Hi, I'm Lê Hữu Hoàng 👋</h1>

<p align="center">
  <strong>Cybersecurity Student @ UIT · Web Security · Pentesting</strong>
</p>

<p align="center">
  <a href="mailto:lehoang.190206@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-58A6FF?style=flat-square&logo=gmail&logoColor=white">
  </a>
  <a href="https://github.com/hhthuis">
    <img src="https://img.shields.io/badge/GitHub-hhthuis-181717?style=flat-square&logo=github">
  </a>
</p>

---

## About Me

I'm a Cybersecurity student in the Honors Program at the University of Information Technology — VNU-HCM.

My current focus is **Web Application Security and Penetration Testing**, especially HTTP security, request parsing discrepancies, vulnerability validation, and reproducible security testing.

* 🔐 Interested in Web Pentesting and HTTP Security
* 🧪 Building reproducible security labs with Docker and virtual machines
* 🛠️ Working with Python, raw TCP, Burp Suite and Wireshark
* 📚 Practicing through CTFs, SEED Labs and web security wargames
* 🎯 Looking for opportunities to learn professional penetration-testing workflows

## Featured Projects

### [HTTP Desync Differential Fuzzer](https://github.com/TrinhQuangMinh123/NT140_http_desync_lab)

An HTTP/1.1 differential-testing framework inspired by the HDHunter research paper.

* Sends identical mutated HTTP payloads through reverse-proxy and backend-direct paths
* Uses raw TCP to preserve malformed and ambiguous request bytes
* Supports sequence-, message- and byte-level mutation strategies
* Compares observed responses and parser-related states to identify discrepancies
* Provides Docker environments for NGINX, HAProxy, Apache Traffic Server, Gunicorn and Tomcat
* Treats discrepancies as candidates requiring replay and manual validation, not confirmed vulnerabilities

`Python` `Docker` `HTTP/1.1` `Raw TCP` `Differential Testing`

### AutoPentester Benchmark

A reproducible benchmark for evaluating whether an AI-assisted pentesting system actually exploits vulnerabilities.

* Collects and analyzes web-related CVEs
* Recreates vulnerable environments with Docker Compose
* Prepares reference exploits and ground truth
* Uses independent oracles to verify real security impact
* Records both successful and failed reproduction attempts to reduce false positives

`Python` `Docker Compose` `CVE Research` `Security Evaluation`

### SEED Labs — Network Security

Hands-on security labs focused on understanding network attacks, protocol behavior, and defensive mechanisms in isolated environments.

* Built controlled environments for practicing network attacks safely
* Analyzed packets and protocol behavior with Wireshark
* Studied both exploitation techniques and corresponding mitigations
* Documented experiment setup, observations, results and security lessons

`Network Security` `TCP/IP` `Wireshark` `Linux` `Attack & Defense`

`Web Security` `PHP` `HTTP` `Wargame`

## Technical Skills

| Area              | Technologies                                              |
| ----------------- | --------------------------------------------------------- |
| Web Security      | Burp Suite, OWASP vulnerabilities, HTTP Request Smuggling |
| Network Analysis  | Wireshark, TCP/IP, HTTP/1.1, raw sockets                  |
| Programming       | Python, C++, SQL, socket programming                      |
| Systems & Labs    | Linux, Windows, Docker, Proxmox VE                        |
| Security Practice | SEED Labs, Natas, Web & Crypto CTFs                       |

## Currently Learning

* Web penetration-testing methodology
* Authentication, authorization and session security
* API security and business-logic vulnerabilities
* HTTP request parsing and desynchronization
* Vulnerability reporting and remediation

## Contact

* Email: **[lehoang.190206@gmail.com](mailto:lehoang.190206@gmail.com)**
* GitHub: **[@hhthuis](https://github.com/hhthuis)**

> I enjoy understanding why systems behave differently — and turning those differences into reproducible security findings.

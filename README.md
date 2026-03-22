# 🚀 OSCP Toolkit v2.0 – Production Ready

End‑to‑end offensive security toolkit for OSCP‑style labs: from recon and web vulns to privesc, exploitation and reporting.

## 🎯 Live features

- HTB‑style SQLi / XSS / directory brute‑force scanners  
- Linux & Windows privilege escalation enumeration  
- Metasploit automation + buffer overflow helpers  
- Full attack chain runner (recon → exploit → loot)  
- OSCP‑style report generator  
- GitHub Actions CI/CD  
- Docker production container

## 🏃 Quickstart

```bash
# Build container
docker build -t oscp-toolkit .

# Run against a target (example: 10.10.10.x)
docker run oscp-toolkit 10.10.10.x
```

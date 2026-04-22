# 📚 Certifications — Path & Cost

| Cert | Provider | Cost (INR) | Priority | Link |
|------|----------|------------|----------|------|
| **eJPT** | INE | ~₹8,000 | 🔴 Now | https://ine.com/learning/certifications/internal/elearnsecurity-junior-penetration-tester-cert |
| **BSCP** | PortSwigger | ~₹8,300 | 🟡 Phase 2 | https://portswigger.net/web-security/certification |
| **OSCP** | Offensive Security | ~₹1,25,000 | 🟢 Phase 3-4 | https://www.offensive-security.com/pwk-oscp |
| CEH | EC-Council | ~₹60,000 | ⬜ Skip — not worth it | — |

---

## Free Learning Paths

| Platform | Path | Link |
|----------|------|------|
| PortSwigger | Web Security Academy (ALL topics) | https://portswigger.net/web-security |
| TryHackMe | Jr Penetration Tester | https://tryhackme.com/path/outline/jrpenetrationtester |
| HackTheBox | Starting Point | https://app.hackthebox.com/starting-point |
| OWASP | Top 10 | https://owasp.org/www-project-top-ten |
| OWASP | API Security Top 10 | https://owasp.org/API-Security |

---

# 🐛 Bug Bounty — Platforms & Programs

## Platforms

| Platform | Focus | Link |
|----------|-------|------|
| HackerOne | Web, API, Mobile | https://hackerone.com |
| Bugcrowd | Web, API | https://bugcrowd.com |
| Intigriti | Web, API | https://intigriti.com |

## Recommended Programs (India focus)

| Company | Platform | Type | Notes |
|---------|----------|------|-------|
| Flipkart | HackerOne | VDP | Active — good scope |
| Meesho | HackerOne | VDP | You already have acknowledgment |
| Razorpay | HackerOne | Private | Apply once H1 rep is higher |
| CRED | Bugcrowd | VDP | Fintech, high impact |
| PhonePe | HackerOne | VDP | Payment APIs = high impact |

## BB Daily Recon Commands

```bash
# Subdomain enumeration
subfinder -d target.com -silent | httpx -silent -status-code

# JS file discovery
gau target.com | grep "\.js$" | sort -u

# Parameter discovery
waybackurls target.com | grep "=" | sort -u

# API endpoint fuzzing
ffuf -u https://api.target.com/FUZZ -w /usr/share/seclists/Discovery/Web-Content/api/api-endpoints.txt

# Nuclei quick scan
nuclei -u https://target.com -t ~/nuclei-templates/
```

---

# 🔧 Tools Reference

## Recon
| Tool | Purpose | Install |
|------|---------|---------|
| subfinder | Subdomain enum | `go install github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest` |
| httpx | HTTP probing | `go install github.com/projectdiscovery/httpx/cmd/httpx@latest` |
| gau | URLs from wayback | `go install github.com/lc/gau/v2/cmd/gau@latest` |
| waybackurls | Wayback URLs | `go install github.com/tomnomnom/waybackurls@latest` |
| nuclei | Vuln scanning | `go install github.com/projectdiscovery/nuclei/v3/cmd/nuclei@latest` |

## Testing
| Tool | Purpose |
|------|---------|
| Burp Suite CE | Manual testing, intercepting |
| ffuf | Fuzzing endpoints/params |
| sqlmap | SQL injection |
| jwt_tool | JWT attacks |
| OWASP ZAP | DAST scanning |

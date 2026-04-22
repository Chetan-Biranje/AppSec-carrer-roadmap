# 📅 Daily Routine — AppSec Career Build

> **Rule:** Log every day. Miss one day = restart streak. No excuses.

---

## ⏰ Daily Schedule (Weekdays)

### 🌅 Morning — 6:30 AM to 7:30 AM (1 hour)
**Skill Building — Rotate daily**

| Day | Task |
|-----|------|
| Monday | PortSwigger Web Security Academy — 1 lab |
| Tuesday | TryHackMe — 1 room or 1 task |
| Wednesday | PortSwigger — 1 lab |
| Thursday | eJPT study material (INE) — 1 module |
| Friday | PortSwigger — 1 lab |
| Saturday | HTB machine OR Burp extension lab |
| Sunday | Review week logs + plan next week |

**Links:**
- PortSwigger: https://portswigger.net/web-security
- INE eJPT: https://my.ine.com/path/eJPT
- TryHackMe: https://tryhackme.com/path/outline/jrpenetrationtester

---

### 💼 Work Hours — 9 AM to 6 PM
**ElevanceSkills + AI4See tasks**

During work, note down:
- Any interesting vulnerability pattern you saw
- Any new tool/technique encountered
- Any API endpoint behavior worth documenting

Log these in evening session.

---

### 🌆 Evening — 8 PM to 9:30 PM (1.5 hours)

**Alternate between two tracks:**

#### Track A — Bug Bounty (Mon / Wed / Fri)
```
1. Pick 1 target from active programs
   → Flipkart, Myntra, or new H1/Bugcrowd program

2. Run recon (30 min)
   → subfinder, httpx, gau, waybackurls
   → Check for new endpoints, JS files, params

3. Manual test (45 min)
   → Focus: IDOR, auth bypass, JWT issues, mass assignment
   → Use Burp Suite — always

4. Document findings (15 min)
   → Even if no bug — log what you tested, what you tried
   → File: progress/2026/week-XX.md
```

#### Track B — eJPT Study (Tue / Thu)
```
1. INE course — 1 module (45 min)
2. Practice what you learned in lab (30 min)
3. Note key concepts (15 min)
   → File: progress/2026/week-XX.md
```

---

### 🌙 Night — 10 PM to 10:30 PM (30 min)

**Daily log — mandatory, no skip**

Open `progress/2026/week-XX.md` and fill:

```markdown
## Day X — DD MMM YYYY

### ✅ Done today
- [ ] Morning: [what lab/module]
- [ ] Evening: [BB recon / eJPT study]
- [ ] Work: [anything security relevant]

### 🐛 Bug Bounty
- Target tested: 
- Endpoints checked: 
- Finding (if any): 
- Status: 

### 📚 Learned today
- 

### ❌ Skipped (be honest)
- 

### 🔥 Tomorrow plan
- 
```

---

## ⏰ Daily Schedule (Weekends)

### Saturday — Deep Work Day (3-4 hours)
```
9 AM  - 10 AM  → HTB machine OR full BB recon session
10 AM - 11 AM  → PortSwigger advanced lab
11 AM - 12 PM  → Write draft for Medium article (1 per month target)
12 PM onwards  → Free
```

### Sunday — Review + Plan (1 hour)
```
9 AM  - 9:30 AM  → Review week progress log
9:30 AM - 10 AM  → Plan next week tasks
                 → Update README.md phase tracker
                 → Push all logs to GitHub
```

---

## 📌 Non-Negotiables (Every Single Day)

| Rule | Why |
|------|-----|
| **Push to GitHub daily** | Contribution graph = credibility signal |
| **Log progress daily** | Track what's working, what's not |
| **1 PortSwigger lab/week minimum** | BSCP prep, skill depth |
| **Check H1/Bugcrowd programs weekly** | New programs = fresh attack surface |
| **1 Medium article/month** | Build public proof of work |

---

## 🚫 What NOT to Do Daily

- **New repos without finishing existing ones** — stop creating, start completing
- **Reading Twitter threads instead of labs** — consumption ≠ skill
- **Switching between domains** — Web/API only, no Android detour right now
- **Skipping logs** — if you didn't log it, it didn't happen

---

## 📊 Weekly Checkpoint Questions

Answer these every Sunday:

1. Kithi PortSwigger labs keli? (Target: 3+/week)
2. eJPT kitthe aahe? (Target: complete in 6 weeks)
3. BB var kithi targets tested? (Target: 2+/week)
4. Kahi writeup draft kelas? (Target: 1/month)
5. GitHub var daily commits aahet ka? (Target: 7/7 days)

---

## 🎯 Phase 1 Daily Focus (Now → Jul 2026)

**Every day pick one of these — no exceptions:**

```
Priority 1 → eJPT study module (if not done)
Priority 2 → PortSwigger lab
Priority 3 → Bug bounty recon session
Priority 4 → Meesho writeup draft
```

When eJPT is done → Phase 2 daily focus kicks in automatically.
See `phases/phase2-depth.md`.

# CEH v13 — Daily Checklist & Quick Reference
## Use this every morning for 90 days

---

## **DAILY STUDY SESSION CHECKLIST (70-90 minutes)**

### **Before You Start:**
- [ ] Turn off phone notifications (silent mode)
- [ ] Open Anki + Official CEH guide side-by-side
- [ ] Set timer for session
- [ ] Have notebook ready for diagrams
- [ ] Bathroom break (no interruptions mid-session)

---

### **RETRIEVAL BURST (10 minutes)**
- [ ] Open Anki app
- [ ] Review: 15-30 cards from PREVIOUS 3 days (randomized, not by module)
- [ ] Mark as "Easy" if correct immediately, "Again" if hesitation
- [ ] Stop after 10 minutes (don't overrun)
- [ ] **Checkpoint:** Should get 80%+ correct (if lower = weak area for deep dive later)

---

### **ENCODING PHASE (25 minutes)**
- [ ] Read TODAY'S TOPIC from official CEH guide (or course material)
- [ ] Highlight 3-5 KEY CONCEPTS
- [ ] Teach aloud for 5 minutes (Feynman Technique):
  - [ ] Simplify to layman's terms
  - [ ] Catch where you get stuck
  - [ ] Reteach that section immediately
- [ ] Draw 1 diagram (stick figures OK)
- [ ] Write 2-3 elaboration bullet points

---

### **ACTIVE RECALL (15 minutes)**
- [ ] Close all notes
- [ ] Answer 10-15 practice questions on TODAY'S TOPIC (online banks or mock exams)
- [ ] Time yourself (1 min per question)
- [ ] Score: Write down %
- [ ] **Minimum:** 70% (if lower, reread topic)

---

### **SPACED INTERLEAVING (20-25 minutes)**
- [ ] Create 3-5 NEW Anki cards from today's learning:
  - [ ] Front: [Concept Name] — [Specific Question]
  - [ ] Back: [Answer] + [Why this matters] + [Related concept]
- [ ] Review 30-40 mixed Anki cards (RANDOM order, from ALL modules covered so far)
- [ ] Do NOT study by module; shuffle everything
- [ ] Aim for 80%+ accuracy

---

### **OPTIONAL (If 2-hour session):**
- [ ] Full-length practice question set (20 questions, 15 min)
- [ ] OR weak area deep-dive (reread + reteach specific concept)
- [ ] OR teach concepts aloud to an imaginary audit panel (20 min)

---

## **WEEKLY CHECKPOINT (Friday Evening)**

- [ ] Count total NEW Anki cards created this week
- [ ] Count MATURED cards (cards you've reviewed 3+ times, 80%+ success)
- [ ] Identify WEAK AREAS (cards you got wrong 2+ times)
- [ ] Score on 20-question practice quiz (target: +5% from last week)
- [ ] Update error log (document what you got wrong + why)

---

## **ANKI DECK MAINTENANCE (Sunday)**

- [ ] Delete cards that are TOO EASY (basic definitions everyone knows)
- [ ] Merge duplicate cards
- [ ] Review "red flag" cards (consistently wrong) — reread that section
- [ ] Check card quality (clear question? Good back answer?)
- [ ] Reset any overdue cards (if life got crazy, catch up)

---

## **WEEKLY MOCK EXAM (Starting Week 5, Every Friday)**

- [ ] Take 125-question mock in timed conditions (4 hours)
- [ ] Record score + breakdown by module
- [ ] Review ALL wrong answers (minimum 30 min)
- [ ] Create 5-10 new Anki cards from mistakes
- [ ] Compare to previous week's mock (should improve +3-5%)

---

## **CEH v13 MODULE TIMELINE**

| Dates | Modules | Daily Topics | Anki Target | Mock Score Target |
|-------|---------|--------------|-------------|------------------|
| Days 1-7 | 1-2 | Basics + Recon | 50-80 | N/A |
| Days 8-14 | 2-3 | Recon + Scanning | 100-150 | N/A |
| Days 15-21 | 4-5 | Enumeration + Vuln | 150-220 | N/A |
| Days 22-28 | 6-7 | System Hacking + Malware | 220-300 | 50% |
| Days 29-35 | 8-10 | Sniffing + DoS | 300-380 | 55% |
| Days 36-42 | 11-12 | Hijacking + IDS/FW | 380-450 | 60% |
| Days 43-49 | 13-14 | Web Servers + Apps | 450-520 | 65% |
| Days 50-56 | 15-16 | SQLi + Wireless | 520-590 | 68% |
| Days 57-63 | 17-18 | Mobile + IoT | 590-660 | 70% |
| Days 64-70 | 19-20 | Cloud + Crypto | 660-750 | 72% |
| Days 71-77 | All (Mock #1-2) | Weak area drilling | 750+ | 75%+ |
| Days 78-90 | All (Final prep) | Final review + mocks | 750+ | 85-90% |

---

## **DAILY TOPIC MENU (Copy This & Replace [TOPIC] Each Day)**

### **Today's Topic: [INSERT FROM 90-DAY PLAN]**

**What I'm learning today:** [Concept name]  
**Why it matters on CEH exam:** [2-3 sentence explanation]  
**Key tools/frameworks:** [Tools mentioned today]

**Study checklist:**
- [ ] Read official guide section (time: ___ min)
- [ ] Teach aloud (time: ___ min)
- [ ] Draw diagram
- [ ] Answer 10-15 practice Qs (score: __/15)
- [ ] Create __ new Anki cards
- [ ] Mixed review: __ cards (score: __%)

**Weak areas to revisit:** [List 2-3 concepts that were hard]

---

## **ERROR LOG TEMPLATE**

**Date:** ___________  
**Question:** [Copy exact wording]  
**Your answer:** [What you chose]  
**Correct answer:** [Official answer]  
**Why you got it wrong:** [ ] Misread question | [ ] Didn't know concept | [ ] Careless mistake | [ ] Concept confusion  
**Concept to deep-dive:** [Which Anki card needs reinforcement]  
**Fix:** [Reteach this concept on _____ (date)]

---

## **ANKI CARD QUALITY CHECKLIST**

Before saving, ask:

- [ ] Front question is SPECIFIC (not vague)?
- [ ] Back answer is CONCISE (1-2 sentences max)?
- [ ] Back includes WHY this matters?
- [ ] Back includes RELATED concept or tool?
- [ ] Card is answerable WITHOUT context from other cards?
- [ ] No typos or formatting issues?

**Example GOOD card:**
```
Front: "What is CVSS v3 and how is it scored?"
Back:  "CVSS v3 = Common Vulnerability Scoring System v3
       Scored 0-10 (0=none, 10=critical)
       Components: Attack Vector (N/A/L), Attack Complexity (L/H), 
       Privileges Required (N/L/H), User Interaction (N/R)
       WHY: Determines vulnerability severity + prioritization
       RELATED: CVE, NVD databases, risk assessment"
```

**Example BAD card:**
```
Front: "Tell me about attacks"
Back:  "There are many types of attacks like DoS and XSS which can affect systems"
```

---

## **WEAK AREA PROTOCOL (When You Score <70% on Topic)**

**Time Allocation:** 2 hours  

1. **Reread (30 min):** Deep reread official guide chapter
2. **Teach Aloud (20 min):** Explain concept 3 times (each time slightly faster)
3. **Scenario Build (20 min):** Create 2-3 real-world scenarios using concept
4. **Anki Reboot (20 min):** Delete weak old cards; create 10 NEW, detailed cards
5. **Practice Qs (20 min):** 20 questions on topic (target: 90%+)
6. **Follow-up (10 min):** Schedule this topic for review in 3 days (calendar reminder)

---

## **EXAM DAY PREP (Final Week)**

### **Day -7 (One week before):**
- [ ] Take full mock exam #4 (target: 88%+)
- [ ] Identify ANY remaining weak areas (<80% score on module)
- [ ] Deep-dive 1-2 weak topics (2 hours each)

### **Day -3 (3 days before):**
- [ ] Light review of Anki "red flag" cards (30 min daily)
- [ ] No new content; ONLY revision
- [ ] 1 final mock exam (target: 90%+)

### **Day -1 (Day before exam):**
- [ ] 15-minute Anki review (weakest cards only)
- [ ] 30-minute walk (fresh air, clear mind)
- [ ] Early bedtime (8 hours sleep minimum)

### **Exam Day:**
- [ ] Light breakfast (carbs + protein)
- [ ] Arrive 30 min early
- [ ] DO NOT cram (your brain is ready)
- [ ] Trust your preparation
- [ ] **PASS:** 60-85% is passing; you'll likely hit 85%+

---

## **CRITICAL SUCCESS FACTORS (Print This & Post on Wall)**

✅ **NO SKIPPED DAYS** — Consistency beats intensity  
✅ **RANDOMIZED ANKI** — Don't study by module; shuffle everything  
✅ **WEEKLY MOCKS** — Real-time performance tracking  
✅ **ERROR LOG** — Every wrong answer = learning opportunity  
✅ **FEYNMAN TEACHING** — Weekly (Sundays) oral defense of modules  
✅ **WEAK AREA SPRINTS** — Deep dives on bottom 20% topics  
✅ **SPACED REVIEW** — Review BEFORE forgetting (every 3-5 days)  

---

## **DAILY MOTIVATION MANTRA**

"I am building a RETENTION SYSTEM, not cramming facts.  
Every Anki card = neuron connection.  
Every Feynman explanation = understanding gap closed.  
Every mock exam = weakness identified & fixed.  
In 90 days, I will be in the TOP 1% of CEH test-takers."

---

## **QUICK ANSWER GUIDE FOR COMMON CEH SCENARIOS**

### **Scenario: You're doing recon on target.com**
- [ ] Use Google Hacking (site:target.com filetype:pdf)
- [ ] WHOIS lookup → Registrant info
- [ ] DNS enumeration → Subdomains, nameservers
- [ ] Traceroute → Network path
- [ ] Email harvesting → User list
- [ ] Social media → Employee profiling
- **Tools:** Maltego, theHarvester, Recon-ng, SHODAN

### **Scenario: You found open ports on target**
- [ ] Nmap -sV → Service version detection
- [ ] Banner grabbing → OS fingerprinting
- [ ] Nikto (if web server) → Vulnerabilities
- [ ] SNMP enumeration (if port 161) → System info
- [ ] SMB enumeration (if 139/445) → Shares, users
- **Red flags:** Old OS, default credentials, unpatched services

### **Scenario: You cracked a Windows password hash**
- [ ] Identify hash type (MD5, NTLM, bcrypt, scrypt)
- [ ] Hashcat or John the Ripper → Crack
- [ ] Rainbow table (if weak hash) → Fast lookup
- [ ] Dictionary attack (most common method)
- [ ] Brute force (64-128 char passwords = expensive)
- **Defense:** MFA, account lockout, auditing, salting

### **Scenario: You found SQL injection vulnerability**
- [ ] Test: Single quote (') → Look for error
- [ ] Union-based injection → Extract data
- [ ] Boolean-based injection → Slow, but stealthy
- [ ] Time-based blind injection → Most stealthy
- [ ] sqlmap tool → Automate process
- **Prevention:** Parameterized queries, input validation, WAF

### **Scenario: DoS attack incoming**
- [ ] Identify attack type (SYN flood, UDP, HTTP GET)
- [ ] Rate limiting → Block excessive traffic
- [ ] Blackhole routing → Discard attacker traffic
- [ ] Scrubbing center → ISP-level mitigation
- [ ] CDN → Distribute load
- **Detection:** Sudden spike in traffic, incomplete connections, 100% bandwidth usage

---

## **PHONE WALLPAPER TEXT (Copy this, screenshot, set as lock screen)**

```
CEH v13: DAY __ OF 90
TODAY'S TOPICS: [INSERT]
ANKI CARDS: __/750 TARGET
MOCK SCORE: __%
WEAK AREAS: [LIST]

MANTRA: Consistency > Intensity
I study 1.5 hours daily.
I review before I forget.
I teach concepts aloud.
I track every mistake.
I am top 1%.
```

---

**Update this sheet DAILY.**  
**Print it. Post it. Live it.**

**Your goal:** 90 days to CEH mastery.  
**Your method:** Neuro-optimized learning.  
**Your result:** Top 1% performance.

---

**Let's ace this exam.** 💪


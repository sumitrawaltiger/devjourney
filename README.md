# 🚀 Sumit Rawal — 36 Months of Code

**1000 days · 3 years · 96 rest days built in · Jun 20, 2026 → Jun 19, 2029 · Tuesday · 5:30 AM – 8:30 AM daily**

Building in public from Bangkok while architecting FPO Cloud at NextStep.

---

## 📦 Structure

```
devjourney/
├── index.html              ← Home page (all days grid)
├── days/
│   ├── day-001.html        ← Day 1 (live!)
│   ├── day-002.html        ← Add daily
│   ├── DAY-TEMPLATE.html   ← Copy this for each new day
│   └── ...
├── assets/
│   ├── css/style.css
│   ├── js/
│   └── images/sumit.jpg   ← Add your photo here
└── README.md
```

## 🗺 36-Month Roadmap

| Block | Skills | Months | Days |
|-------|--------|--------|------|
| 🔧 DevOps | DevOps with AWS · SRE with AWS · QE with AWS | M01–M03 | D1–D93 |
| ⚡ Frontend | JavaScript · TypeScript · React · Next.js · React Native | M04–M08 | D94–D247 |
| 🐍 Python | Python · Agentic AI · Django | M09–M11 | D248–D337 |
| ☕ Java | J2SE · J2EE · JPA · Spring Boot · Microservices | M12–M36 | D338–D1000 |

---

## ✍️ How to Add a New Day (Daily Workflow)

### Step 1 — Duplicate the template
```bash
cp days/DAY-TEMPLATE.html days/day-002.html
```

### Step 2 — Edit the new file
Open `days/day-002.html` and update:
- Day number (DAY 002)
- Topic title
- Date
- What you learnt (4 bullet points)
- Code snippet
- Concept cards
- Quote
- Hashtags

### Step 3 — Add card to index.html
Open `index.html` and add a new `<a class="day-card">` block inside the correct block's `.days-grid`. Copy Day 1's card and update the number, title, topics and href.

### Step 4 — Push to GitHub
```bash
git add .
git commit -m "Day 002: AWS IAM, Users, Roles, Policies"
git push origin main
```

### Step 5 — Done ✅
Netlify auto-deploys in ~30 seconds. Your page is live!

---

## 🚀 Netlify Deploy Setup (one-time)

1. Go to [netlify.com](https://netlify.com) → Log in with GitHub
2. Click **"Add new site"** → **"Import an existing project"**
3. Choose **GitHub** → select `devjourney` repository
4. Build settings:
   - Build command: *(leave empty)*
   - Publish directory: `.` (root)
5. Click **"Deploy site"**
6. Optional: set custom domain like `sumit.dev` or `devjourney.netlify.app`

From then on — every `git push` auto-deploys! 🎉

---

## 🏷 Hashtags to use
`#36MonthsOfCode` `#3YearsOfCode` `#1000DaysOfCode` `#100DaysOfCode` `#365DaysOfCode`
`#AWS` `#DevOps` `#LearnInPublic` `#BuildInPublic` `#SumitrawalDev`

---

## 👤 About
**Sumit Rawal** · Senior Associate L2 · NextStep Bangkok · FPO Cloud  
12+ years · 7 AWS Certs · CKA · C# .NET 8 · Lambda · DynamoDB · Kafka

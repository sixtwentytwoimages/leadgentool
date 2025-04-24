# 🔍 Facebook Group Keyword Monitor

A keyword-monitoring tool for Facebook groups you’re a member of, built using Puppeteer and Docker. Designed to alert you when posts contain target keywords like “photographer” or “brand shoot.”

## 🚀 Features
- Keyword scanning of Facebook group posts
- Cookie-based session authentication
- Desktop notifications for keyword hits
- Google Sheets logging
- Runs in Docker container or scheduled via cron

## 🧰 Stack
- Node.js
- Puppeteer
- Docker
- Google Sheets API

## 📦 Setup
1. Clone this repo
2. Fill out `.env` using `.env.example`
3. Build Docker container:
   docker build -t fb-keyword-monitor .
4. Run:
   docker run --env-file .env fb-keyword-monitor


## Notes for Developers

### Test Directory
A `/test/` folder is included with a placeholder test file.  
This is here for future unit and integration tests.  
**Pull requests with tests are welcome.**


---

### Documentation Directory
A `/docs/` directory is included to organize internal guides and technical setup notes.

Current files include:


---

### Contributing
A `CONTRIBUTING.md` file is provided with basic guidelines.  
Make sure to read it before submitting a PR.

Main points:
- Assign yourself an issue before coding
- Use descriptive commit messages
- Open PRs into the `main` branch
- Update docs or README if your feature changes usage

---

### Issue Labeling and Milestones
All issues are labeled and grouped by milestone for clarity.

Labels used:
- `good first issue`
- `help wanted`
- `ready for dev`
- `blocked`

Current milestones:
- `v1.0 – MVP`
- `v2.0 – Slack/Email Alerts`
- `v3.0 – Multi-platform Monitoring`

---

### Getting Started Checklist (Pinned in Issues)
Be sure to check the pinned onboarding issue.

```markdown
## Getting Started Checklist

- [ ] Clone the repo
- [ ] Copy `.env.example` to `.env` and fill in credentials
- [ ] Run `npm install`
- [ ] Use `npm start` to test
- [ ] Look at open issues and assign yourself one


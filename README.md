# ContractGuard AI

### AI Contract Risk Analyzer — Know What You're Signing

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)]()
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)]()
[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react)]()
[![AI Powered](https://img.shields.io/badge/AI-Powered-412991?logo=openai)]()

> **Paste any contract. Get instant risk analysis.** AI identifies dangerous clauses, missing protections, and unfavorable terms — so you know exactly what you're agreeing to.

---

## The Problem

People sign contracts they don't fully understand every day. Hidden auto-renewal clauses, one-sided indemnification, unlimited liability exposure — these aren't edge cases, they're in most standard business contracts. Professional contract review costs **$300-700/hour**.

**In 6 years of legal practice, I've watched clients sign agreements that cost them thousands because they didn't know what to look for.**

## The Solution

ContractGuard AI reads your contract the way a lawyer would — clause by clause — and flags everything you should worry about. It gives you a risk score, explains each issue in plain English, and suggests improvements.

---

## Features

- **Instant Risk Scoring**: Overall contract risk rated Low / Medium / High with visual indicators
- **Clause-by-Clause Analysis**: Every risky clause identified with explanation and suggested fix
- **Perspective-Aware**: Choose your role (Party A, Party B, or Neutral) — risks differ based on which side of the table you sit
- **Missing Protection Detection**: Identifies clauses your contract *should* have but doesn't
- **Executive Summary**: 2-3 sentence overview for quick decision-making
- **Analysis History**: Save and revisit past contract reviews
- **Guard Mode**: Toggle stricter analysis for high-stakes agreements

---

## Quick Start

\`\`\`bash
git clone https://github.com/RLASAF12/contract-guard-ai.git
cd contract-guard-ai
npm install
npm run dev
\`\`\`

Open [http://localhost:5173](http://localhost:5173)

---

## What It Catches

| Risk Category | Examples |
|--------------|---------|
| **Liability Traps** | Unlimited liability, broad indemnification, consequential damages exposure |
| **Termination Issues** | Auto-renewal without notice, termination penalties, lock-in periods |
| **IP Risks** | Overly broad IP assignment, work-for-hire misclassification |
| **Payment Dangers** | Vague payment terms, net-90+ payment schedules, hidden fees |
| **Non-Compete Overreach** | Geographic scope too broad, duration too long, industry too vague |
| **Missing Protections** | No limitation of liability, no dispute resolution, no force majeure |

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18, Vite, Tailwind CSS |
| UI Components | Shadcn UI, Lucide Icons |
| AI Engine | LLM Integration (OpenAI / Claude) |
| Backend | Base44 (serverless functions, auth, database) |

---

## Who Is This For?

- **Business owners** reviewing vendor contracts, leases, or partnership agreements
- **Freelancers** evaluating client contracts before signing
- **Startups** reviewing investor term sheets and SaaS agreements
- **Procurement teams** vetting supplier contracts at scale
- **Anyone** about to sign something they're not 100% sure about

---

## Roadmap

- [ ] File upload (PDF, DOCX) with text extraction
- [ ] Side-by-side comparison of two contract versions
- [ ] Industry benchmark database (what's "normal" for this clause type)
- [ ] Export annotated contract with inline risk markers
- [ ] Bulk analysis for contract portfolios
- [ ] API for integration with contract management systems

---

## Important Disclaimer

> ContractGuard AI provides AI-generated risk analysis for educational and informational purposes. **This is not legal advice.** Always consult a qualified attorney before making legal decisions based on any contract analysis.

---

## Contributing

Legal professionals, AI engineers, and anyone passionate about contract transparency — PRs are welcome.

1. Fork the repo
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## License

MIT License

---

## Built By

**Harel Asaf** — Attorney turned legal tech builder. 6+ years of contract law experience. Now building AI tools that give everyone access to the contract review that used to be reserved for companies with $50K legal budgets.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/harel-asaf/)
[![GitHub](https://img.shields.io/badge/GitHub-RLASAF12-181717?style=flat&logo=github)](https://github.com/RLASAF12)

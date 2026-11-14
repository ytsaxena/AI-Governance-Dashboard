# AI Governance & Spend Dashboard

An intuitive, human-centered prototype of an **AI Governance & Spend Dashboard** designed to solve the **"Shadow AI"** problem and budget overruns across modern organizations.

---

## 🌐 Live Prototype Demo
- **GitHub Pages Link:** [https://ytsaxena.github.io/AI-Governance-Dashboard/](https://ytsaxena.github.io/AI-Governance-Dashboard/)
- You can also view the file locally by opening `index.html` in any modern web browser.

---

## 🎯 Problem & Context

Companies are rapidly adopting AI tools (ChatGPT, Claude Code, Figma AI, Midjourney, etc.) across Engineering, Sales, Design, and Leadership. However, organizations struggle with:
1. **Shadow AI:** Employees using unapproved personal accounts on work machines.
2. **Budget Blowouts:** Surprise bills caused by unmonitored tokens or runaway script loops.
3. **Mismatched Billing Models:** Some tools charge per token (Claude Code), others per seat (Figma AI), and others a mix of both (ChatGPT).

This dashboard is designed from the perspective of **"The Lead"**—a non-technical budget and operations owner who needs to keep spend on track and protect company data.

---

## 💡 Key Design Decisions

1. **Normalized Weekly Budget (₹):** 
   - Converts token usage, seat licenses, and API meters into a single, consistent weekly budget scale.
   - Resets every Monday at 00:00 UTC so the team can manage pace proactively instead of reacting to surprise monthly invoices.
2. **Individual-Level Visibility:**
   - AI overruns and risks are driven by specific people, not abstract teams.
   - The Lead can switch between **Team View** and **Person View** to see who is spending what, check runaway loops, and catch unsanctioned tools.
3. **Action-Oriented Governance:**
   - Not just charts: includes direct actions to approve/decline budget requests, update individual caps, and migrate users off unapproved personal accounts to corporate SSO.

---

## 📱 Prototype Features (Part 1)

| Section | What It Does |
|---|---|
| **Top Health Bar** | 4 simple KPI cards: Weekly Org Limit, Spent So Far (78%), Money Left (3 days), and Safety Alerts. |
| **Team View** | Shows Engineering (Claude Code), Sales (ChatGPT Enterprise), Design (Figma AI), and Leadership. |
| **Person View** | Shows individual spenders (e.g., Rohan Sharma, Arjun Mehta, Sneha Rao, Priya Nair, Vikram Malhotra). |
| **Search Bar** | Instant filter by person name or team. |
| **Action Queue** | 1-click approvals for budget extensions (e.g., Rohan's Q4 release sprint request). |
| **Safety Alerts** | Flags unapproved personal tools, runaway loops, and masked customer data. |
| **Interactive Modals** | Adjust team or personal weekly spending limits on the fly. |

---

## 🛠️ Tech Stack

- **HTML5 & Tailwind CSS** (Clean, responsive layout with high-contrast, accessible typography).
- **Vanilla JavaScript** (Zero dependencies, fast, interactive tabs, search, and action modals).

# 🤖 Professional GPT Library

> **90 Custom GPT system prompts for professionals. The ChatGPT companion to [pm-claude-skills](https://github.com/mohitagw15856/pm-claude-skills).**

A library of production-ready system prompts for ChatGPT Custom GPTs — covering product management, marketing, engineering, legal, finance, HR, sales, design, operations, and research. Each GPT is structured to produce consistent, professional-grade outputs for recurring workflows.

---

## ⚡ How to use any GPT in this library

Unlike Claude Skills (which install via a marketplace command), ChatGPT Custom GPTs are configured manually. Here's how — takes under 2 minutes:

1. Go to [chat.openai.com](https://chat.openai.com)
2. Click **Explore GPTs** → **Create** (top right)
3. Click the **Configure** tab
4. Open any `SYSTEM_PROMPT.md` file in this repo
5. Copy everything below the dashed line
6. Paste it into the **Instructions** field
7. Give your GPT a name and save it

Your GPT is now available in your ChatGPT sidebar. Use it privately or publish it to the GPT Store.

> **ChatGPT Plus or Team required** to create Custom GPTs.

---

## 📂 All GPTs by Profession

### 📣 Marketing & GTM
| GPT | What It Does | File |
|---|---|---|
| **Go-To-Market GPT** | Positioning statements, messaging pillars, feature/benefit mapping, use cases | [SYSTEM_PROMPT.md](gpts/marketing/go-to-market-gpt/SYSTEM_PROMPT.md) |
| **Content Calendar GPT** | Multi-channel content calendars with opening hooks and repurposing map | [SYSTEM_PROMPT.md](gpts/marketing/content-calendar-gpt/SYSTEM_PROMPT.md) |
| **Competitor Teardown GPT** | Full competitive analysis with positioning map, SWOT, and recommendations | [SYSTEM_PROMPT.md](gpts/marketing/competitor-teardown-gpt/SYSTEM_PROMPT.md) |

### 👩‍💻 Engineering
| GPT | What It Does | File |
|---|---|---|
| **Incident Postmortem GPT** | Blameless postmortems with timeline, root cause, and action items | [SYSTEM_PROMPT.md](gpts/engineering/incident-postmortem-gpt/SYSTEM_PROMPT.md) |
| **Architecture Decision GPT** | ADRs in Nygard format with options, consequences, and risks | [SYSTEM_PROMPT.md](gpts/engineering/architecture-decision-gpt/SYSTEM_PROMPT.md) |

### 📊 Data & Analytics
| GPT | What It Does | File |
|---|---|---|
| **Metrics Framework GPT** | North Star metric + metric tree + counter-metrics + dashboard tiers | [SYSTEM_PROMPT.md](gpts/data/metrics-framework-gpt/SYSTEM_PROMPT.md) |

### ⚖️ Legal
| GPT | What It Does | File |
|---|---|---|
| **Contract Review GPT** | Structured review with flagged clauses, risk rating, and plain English summary | [SYSTEM_PROMPT.md](gpts/legal/contract-review-gpt/SYSTEM_PROMPT.md) |
| **Compliance Checklist GPT** | GDPR, SOC 2, ISO 27001, FCA compliance checklists with gap analysis | [SYSTEM_PROMPT.md](gpts/legal/compliance-checklist-gpt/SYSTEM_PROMPT.md) |

### 💰 Finance
| GPT | What It Does | File |
|---|---|---|
| **Investor Update GPT** | Monthly/quarterly investor updates that investors actually read | [SYSTEM_PROMPT.md](gpts/finance/investor-update-gpt/SYSTEM_PROMPT.md) |
| **Financial Narrative GPT** | Turn P&L outputs into board-ready written narratives | [SYSTEM_PROMPT.md](gpts/finance/financial-narrative-gpt/SYSTEM_PROMPT.md) |

### 👥 HR
| GPT | What It Does | File |
|---|---|---|
| **Performance Review GPT** | Structured reviews from bullet-point notes — self, manager, peer | [SYSTEM_PROMPT.md](gpts/hr/performance-review-gpt/SYSTEM_PROMPT.md) |
| **Job Description GPT** | Inclusive, structured JDs with built-in language review | [SYSTEM_PROMPT.md](gpts/hr/job-description-gpt/SYSTEM_PROMPT.md) |

### 🤝 Sales
| GPT | What It Does | File |
|---|---|---|
| **Sales Battlecard GPT** | One-page competitive battlecards with objection responses | [SYSTEM_PROMPT.md](gpts/sales/sales-battlecard-gpt/SYSTEM_PROMPT.md) |
| **Discovery Call GPT** | Call briefs with research summary, hypothesis, and success criteria | [SYSTEM_PROMPT.md](gpts/sales/discovery-call-gpt/SYSTEM_PROMPT.md) |

### ⚙️ Operations
| GPT | What It Does | File |
|---|---|---|
| **Project Status GPT** | RAG status reports with milestones, risks, and decisions required | [SYSTEM_PROMPT.md](gpts/operations/project-status-gpt/SYSTEM_PROMPT.md) |
| **SOP Writer GPT** | Formal, audit-ready SOPs with version control and quality checks | [SYSTEM_PROMPT.md](gpts/operations/sop-writer-gpt/SYSTEM_PROMPT.md) |

### 🎨 Design
| GPT | What It Does | File |
|---|---|---|
| **Figma Design Brief GPT** | Convert PRDs into structured Figma design briefs | [SYSTEM_PROMPT.md](gpts/design/figma-design-brief-gpt/SYSTEM_PROMPT.md) |

### 🌐 Cross-Profession
| GPT | What It Does | File |
|---|---|---|
| **Executive Summary GPT** | Decision-ready summaries with bottom line upfront for any audience | [SYSTEM_PROMPT.md](gpts/cross/executive-summary-gpt/SYSTEM_PROMPT.md) |
| **Press Release GPT** | Journalist-ready press releases with headline rules and journalist test | [SYSTEM_PROMPT.md](gpts/cross/press-release-gpt/SYSTEM_PROMPT.md) |

---

## 🔄 How This Compares to Claude Skills

This repo is the ChatGPT companion to **[pm-claude-skills](https://github.com/mohitagw15856/pm-claude-skills)** — 90 Claude Skills for Claude Code. The underlying professional frameworks are the same. The implementation is completely different.

| | Claude Skills (pm-claude-skills) | Custom GPTs (this repo) |
|---|---|---|
| **Platform** | Claude Code (terminal) | ChatGPT (web/app) |
| **Install** | One command: `/plugin marketplace add mohitagw15856/pm-claude-skills` | Manual: paste system prompt into GPT builder |
| **Triggering** | Automatic — Claude detects when to use a skill | Manual — you open your saved GPT |
| **Context** | Reads your files, runs code, accesses terminal | Conversation only (unless you add tools) |
| **Best for** | Technical workflows, coding, file manipulation | Document creation, analysis, writing |

Neither is strictly better — they serve different use cases and different users. Many professionals use both.

---

## 🤝 Contributing

If you've built a Custom GPT system prompt that saves you time, share it here.

1. Fork this repo
2. Create a folder: `gpts/[profession]/[gpt-name]/`
3. Add `SYSTEM_PROMPT.md` following the format in any existing file
4. Raise a pull request with a short description of what the GPT does and why you built it

**What makes a good contribution:**
- Solves a recurring professional workflow
- Structured output that users can use directly
- Includes examples of what to say to trigger the right output
- Works without external API keys or paid services

---

## 📚 Related

- **[pm-claude-skills](https://github.com/mohitagw15856/pm-claude-skills)** — The Claude Code version of this library. 90 skills, 22 plugin bundles, installs in 2 minutes.
- **Article series:** [The Claude Skills Series on Medium](https://medium.com/product-powerhouse/claude-skills-the-ai-feature-thats-quietly-changing-how-product-managers-work-aad5d8d0640a)

---

## ⭐ If this is useful

Star the repo so others can find it. And if you use one of these GPTs in your work — raise a PR with any improvements, or share it with someone who needs it.

---

*Built by [Mohit Aggarwal](https://medium.com/@mohit15856) | Companion to [pm-claude-skills](https://github.com/mohitagw15856/pm-claude-skills)*

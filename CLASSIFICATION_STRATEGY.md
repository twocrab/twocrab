# Classification & Organization Strategy

## 📁 Folder Structure (Conceptual)

```
twocrab/
├── 🤖 AI Agents & Automation/
│   ├── agency-agents              # Core AI agent system
│   ├── AutoGPT                    # Accessible AI framework
│   ├── CLI-Anything               # Agent integration for CLI
│   ├── openclaw                   # Personal AI assistant
│   ├── skills                     # Agent skills repository
│   └── ZeroClaw-Android           # Mobile AI agent runner
│
├── 📊 Time Series & Forecasting/
│   ├── Time-LLM                   # LLM-based time series
│   ├── TimesNet                   # ICLR 2023 approach
│   ├── Time-Series-Library        # Deep learning library
│   ├── Informer2020               # AAAI 2021 paper
│   ├── Raindrop                   # Graph neural networks
│   ├── timesfm                    # Google foundation model
│   └── swift                      # Epidemiology forecasting
│
├── 🛠️ Tools & Frameworks/
│   ├── LightGBM                   # Gradient boosting
│   ├── spec-kit                   # Development toolkit
│   ├── spec-kit-cn                # Chinese version
│   └── visual                     # Blender visualization
│
├── 💻 Web Applications/
│   ├── digital-clock-timezones    # Multi-timezone clock
│   └── todo-list-app              # Task management
│
└── 📚 Learning & Reference/
    ├── build-your-own-x           # Learning resource
    └── CMeKG_tools                # Knowledge graphs
```

## 🏷️ Recommended Topics System

### Level 1: Primary Category
- `ai-agent` - AI agent and automation
- `time-series` - Time series forecasting
- `machine-learning` - ML frameworks
- `frontend` - Web applications
- `learning` - Learning resources

### Level 2: Technical Focus
- `deep-learning` - Deep learning based
- `llm` - Large language model based
- `graph-neural-network` - GNN based
- `gradient-boosting` - GBM based
- `local-storage` - Client-side storage

### Level 3: Additional Context
- `research` - Research papers/implementations
- `fork` - Forked repositories
- `abandoned` - No longer maintained
- `wip` - Work in progress

## 📊 Statistics by Category

### Maturity Distribution
```
Production Ready:  60% (13 repos)
Active Development: 25% (5 repos)
Learning/Research:  15% (3 repos)
```

### Technology Distribution
```
Python:       65% (Time Series, ML)
JavaScript:   10% (Web Apps)
Various:      25% (Tools, Frameworks)
```

### Purpose Distribution
```
Research:     35% (7 repos)
Production:   40% (8 repos)
Learning:     10% (2 repos)
Tools:        15% (3 repos)
```

## 🔄 Maintenance Strategy

### Archive Decision Tree
- No commits in 12 months? → Consider archiving
- Superseded by newer version? → Archive old version
- Personal learning only? → Tag with `learning`
- Fork of major project? → Tag with `fork`

### Naming Convention (Optional)
If you want to standardize naming:

```
Category Prefix Examples:
ai-*         (for AI/Agent projects)
ts-*         (for Time Series projects)
ml-*         (for ML frameworks)
web-*        (for Web applications)
tool-*       (for Utilities/Tools)
research-*   (for Research implementations)
```

Current example migrations:
```
agency-agents → ai-agency-agents
Time-LLM → ts-timellm
LightGBM → ml-lightgbm
```

## 🎯 Quick Reference URLs

### By Category
- AI Agents: `https://github.com/twocrab?tab=repositories&q=topic:ai-agent`
- Time Series: `https://github.com/twocrab?tab=repositories&q=topic:time-series`
- ML Tools: `https://github.com/twocrab?tab=repositories&q=topic:machine-learning`
- Web Apps: `https://github.com/twocrab?tab=repositories&q=topic:frontend`

### By Language
- Python: `https://github.com/twocrab?tab=repositories&language=python`
- JavaScript: `https://github.com/twocrab?tab=repositories&language=javascript`

### Special Filters
- All repositories: `https://github.com/twocrab?tab=repositories`
- Stars: `https://github.com/twocrab?tab=repositories&sort=stars`
- Recently updated: `https://github.com/twocrab?tab=repositories&sort=updated`

---

## Implementation Checklist

- [x] Create profile README
- [x] Create repository guide
- [x] Define classification strategy
- [ ] Add topics to all repositories
- [ ] (Optional) Implement naming conventions
- [ ] (Optional) Create GitHub Organizations
- [ ] (Optional) Setup GitHub Projects for tracking

---

**Last Updated**: 2026-09-04
**Total Repositories**: 21
**Organization Level**: Personal Account
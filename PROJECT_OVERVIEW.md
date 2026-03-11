# 📋 MiroFish Project Overview

## 🎯 Core Purpose

MiroFish is an innovative **AI-powered swarm intelligence engine** designed to predict and simulate complex scenarios by creating digital simulations of reality. It's a sophisticated system that combines multi-agent technology with advanced AI to enable predictive modeling across various domains.

MiroFish extracts seed information from the real world (breaking news, policy drafts, financial signals) and automatically constructs a **high-fidelity parallel digital world**. Within this simulation space:
- Thousands of AI agents with independent personalities, long-term memory, and behavioral logic interact freely
- Social evolution dynamics unfold autonomously
- Users can inject variables dynamically to precisely predict future outcomes

**The concept**: Upload seed materials (data reports or interesting stories) + describe prediction needs in natural language → Receive detailed prediction reports + interactive 3D digital world

---

## 🔬 Vision & Use Cases

### Macro Level (Decision Making)
- **Decision-maker's simulation lab** for policy and PR testing in a zero-risk environment
- Policy scenario planning and outcome forecasting

### Micro Level (Creative Exploration)
- **Personal creative sandbox** for exploring stories and scenarios
- Scenario exploration and "what-if" analysis
- Entertainment and interactive storytelling

---

## 🛠️ Technology Stack

| Component | Language | Composition |
|-----------|----------|------------|
| **Backend** | Python | 57.8% |
| **Frontend** | Vue.js | 41.1% |
| **Other** | - | 1.1% |

### Backend Architecture
- **Python 3.11-3.12** runtime
- **FastAPI** or similar REST API framework
- Uses `pyproject.toml` for dependency management
- Entry point: `backend/run.py`
- Dependencies managed via `uv` package manager

### Frontend Architecture  
- **Vue.js** with Vite bundler
- Modern SPA (Single Page Application)
- Node.js 18+ environment
- Build configuration via `vite.config.js`

---

## 📁 Project Structure

```
MiroFish/
├── backend/
│   ├── app/                 # Main application logic
│   ├── scripts/             # Utility scripts
│   ├── run.py              # Backend entry point
│   ├── pyproject.toml      # Python project configuration
│   ├── requirements.txt    # Python dependencies
│   └── uv.lock             # Dependency lock file
├── frontend/
│   ├── src/                # Vue components and source code
│   ├── public/             # Static assets
│   ├── index.html          # Main HTML file
│   ├── vite.config.js      # Vite configuration
│   ├── package.json        # Node dependencies
│   └── package-lock.json   # Dependency lock file
├── Dockerfile              # Container build config
├── docker-compose.yml      # Multi-container orchestration
├── .env.example            # Environment configuration template
└── README.md              # Project documentation
```

---

## 🔄 Core Workflow

1. **Graph Construction**: Extract reality seeds & inject memory + GraphRAG building
2. **Environment Setup**: Entity-relationship extraction, character generation, simulation parameters
3. **Simulation Start**: Parallel dual-platform simulation, auto-parse prediction needs, dynamic memory updates
4. **Report Generation**: ReportAgent uses rich tool sets to interact with simulated environment
5. **Deep Interaction**: Converse with simulated agents or ReportAgent for deeper analysis

---

## 🚀 Deployment & Setup

### Prerequisites
- **Node.js** 18+
- **Python** 3.11-3.12
- **uv** package manager

### Quick Start
```bash
# Configuration
cp .env.example .env

# Install dependencies
npm run setup:all

# Start services
npm run dev

# Services run on:
# - Frontend: http://localhost:3000
# - Backend API: http://localhost:5001
```

### Docker Deployment
```bash
cp .env.example .env
docker compose up -d
```

---

## 📊 Key Configuration

**Required Environment Variables:**
- `LLM_API_KEY` - Large language model API key
- `LLM_BASE_URL` - LLM endpoint (recommends Alibaba Bailian/Qwen-plus)
- `LLM_MODEL_NAME` - Model specification
- `ZEP_API_KEY` - Zep Cloud for memory management

---

## 🏢 Project Background

- **Status**: Fork of original repository (666ghj/MiroFish)
- **License**: GNU Affero General Public License v3.0 (AGPL-3.0)
- **Backing**: Shanda Group support & incubation
- **Engine**: Powered by **OASIS** (by CAMEL-AI team)
- **Network reach**: 1782+ forks on GitHub
- **Official site**: https://mirofish.ai

---

## 🎓 Demo Applications

1. **Wuhan University Opinion Simulation** - Predicting public opinion dynamics
2. **Dream of the Red Chamber** - Predicting lost story chapters using existing 80-chapter novel content
3. (Financial & Political predictions coming soon)

---

## 👥 Community & Involvement

- **Active Communication**: Discord, Twitter/X, Instagram
- **Hiring**: Open roles for full-time/internship positions interested in multi-agent AI
- Contact: mirofish@shanda.com

---

This is a cutting-edge project that bridges AI simulation with real-world prediction needs, combining swarm intelligence concepts with modern LLMs for interactive scenario modeling!
<<<<<<< HEAD
# 🌌 Dark Matter Classification System

An intelligent dark matter event classification and anomaly detection system powered by Claude AI.

## 🚀 Quick Start

### **Start Both Frontend & Backend (Easy Way)**

**Windows:**
```bash
start_dev.bat
```

**Mac/Linux:**
```bash
chmod +x start_dev.sh
./start_dev.sh
```

Then open: **http://localhost:5173**

---

### **Manual Start**

**Terminal 1 - Backend:**
=======
# 🌌 Dark Matter Detection System

An AI-driven full-stack platform for dark matter event classification and anomaly detection, designed to assist scientific research through intelligent data analysis, real-time visualization, and automated reasoning.

---

## 🚀 Overview

Dark matter research generates large volumes of complex astrophysical event data that require advanced computational techniques for interpretation.
This system provides an intelligent pipeline to classify dark matter events, detect anomalies, and deliver meaningful insights through an interactive dashboard powered by AI reasoning.

The platform integrates machine learning, statistical analysis, and large language model capabilities to support scientific exploration and decision-making.

---

## ✨ Key Features

* 🔬 **Event Classification** — AI-powered identification and categorization of dark matter events
* ⚠️ **Anomaly Detection** — Automatic detection of unusual or rare astrophysical patterns
* 📊 **Results Dashboard** — Real-time visualization of classification outputs and dataset statistics
* 📈 **Data Analytics** — Insightful exploration of event distributions and trends
* 📁 **Batch Processing** — Upload and analyze multiple event datasets simultaneously
* 🤖 **AI Reasoning Integration** — Advanced contextual analysis using Claude AI

---

## 🏗️ System Architecture

Dataset → Flask Backend API → Classification Engine → Anomaly Detection Module → AI Reasoning Layer → React Dashboard

---

## 🛠️ Tech Stack

### Frontend

* React + TypeScript
* Vite
* TailwindCSS
* Recharts
* Shadcn/ui

### Backend

* Python 3.11
* Flask
* Pandas
* NumPy
* Anthropic Claude API

---

## 📦 Installation

### Install Backend Dependencies

```bash
pip install -r requirements.txt
```

### Start Backend

>>>>>>> c9afdfc83e4a6ee296d40f47bf50940a75c01212
```bash
python webapp_backend.py
```

<<<<<<< HEAD
**Terminal 2 - Frontend:**
=======
### Install Frontend Dependencies

>>>>>>> c9afdfc83e4a6ee296d40f47bf50940a75c01212
```bash
cd webapp
npm install
npm run dev
```

<<<<<<< HEAD
Then open: **http://localhost:5173**

---

## 📚 Documentation

### Quick Access
- **[QUICK_START.md](QUICK_START.md)** - Complete usage guide
- **[DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md)** - How to deploy publicly

### Comprehensive Documentation
- **[USER_GUIDE.md](USER_GUIDE.md)** - Complete user manual with step-by-step instructions
- **[DEVELOPER_GUIDE.md](DEVELOPER_GUIDE.md)** - Development setup, coding standards, and contribution guide
- **[ARCHITECTURE.md](ARCHITECTURE.md)** - System architecture, components, and data flow
- **[AI_FUNCTIONALITY.md](AI_FUNCTIONALITY.md)** - Claude AI integration, prompt engineering, and workflows
- **[API_DOCUMENTATION.md](API_DOCUMENTATION.md)** - REST API reference with examples

---

## ✨ Features

- 🔬 **Event Classification** - AI-powered dark matter event analysis
- 📊 **Results Dashboard** - Real-time visualization and statistics  
- ⚠️ **Anomaly Detection** - Automatic detection of unusual events
- 📈 **Data Analytics** - Comprehensive dataset insights
- 🤖 **Claude AI Integration** - Advanced reasoning and analysis
- 📁 **Batch Processing** - Upload and analyze multiple events

---

## 📖 New! Complete Documentation

We've created comprehensive documentation to help you understand and use the system:

| Document | Description | Target Audience |
|----------|-------------|-----------------|
| **[USER_GUIDE.md](USER_GUIDE.md)** | Step-by-step instructions for using all features | End Users, Scientists |
| **[DEVELOPER_GUIDE.md](DEVELOPER_GUIDE.md)** | Setup, development workflow, and contribution guide | Developers, Contributors |
| **[ARCHITECTURE.md](ARCHITECTURE.md)** | System design, components, and data flow | Technical Leads, Architects |
| **[AI_FUNCTIONALITY.md](AI_FUNCTIONALITY.md)** | How Claude AI powers classification and analysis | AI/ML Engineers, Researchers |
| **[API_DOCUMENTATION.md](API_DOCUMENTATION.md)** | Complete REST API reference with examples | API Users, Integrators |

**New to the system?** Start with [USER_GUIDE.md](USER_GUIDE.md)  
**Want to contribute?** Read [DEVELOPER_GUIDE.md](DEVELOPER_GUIDE.md)  
**Building integrations?** See [API_DOCUMENTATION.md](API_DOCUMENTATION.md)

---

## 🛠️ Tech Stack

**Frontend:**
- React + TypeScript
- Vite
- TailwindCSS
- Recharts
- Shadcn/ui

**Backend:**
- Python 3.11
- Flask
- Anthropic Claude API
- Pandas
- NumPy

---

## 🌐 Deploy Your Own

1. **Deploy Backend:** [Render.com](https://render.com) (Free)
2. **Deploy Frontend:** [Vercel.com](https://vercel.com) (Free)

See [DEPLOYMENT_GUIDE.md](DEPLOYMENT_GUIDE.md) for details.

---

## 📝 Environment Variables

Create a `.env` file:

```bash
ANTHROPIC_API_KEY=your_claude_api_key_here
CLAUDE_API_KEY=your_claude_api_key_here
```

Get your API key from: https://console.anthropic.com/

---

## 📦 Installation

```bash
# Install Python dependencies
pip install -r requirements.txt

# Install frontend dependencies
cd webapp
npm install
```

---

## 🎯 Project Structure

```
Technologia_ClaudeSolvathon/
├── webapp/                    # React frontend
│   ├── src/
│   │   ├── pages/            # Dashboard pages
│   │   ├── components/       # Reusable components
│   │   └── lib/             # API integrations
│   └── package.json
├── anomaly_detection_system/  # Anomaly detection
│   └── mainAnomalyDetection.py
├── dataset/                   # Data files
│   └── dark_matter_synthetic_dataset.csv
├── webapp_backend.py          # Flask API server
├── mainClassify.py           # Classification logic
├── requirements.txt           # Python dependencies
├── start_dev.bat             # Windows launcher
├── start_dev.sh              # Mac/Linux launcher
└── .env                      # API keys (gitignored)
=======
Open in browser:

```
http://localhost:5173
```

---

## ⚡ Quick Start (Automated)

### Windows

```
start_dev.bat
```

### Mac / Linux

```bash
chmod +x start_dev.sh
./start_dev.sh
>>>>>>> c9afdfc83e4a6ee296d40f47bf50940a75c01212
```

---

## 🧪 Testing

<<<<<<< HEAD
**Test Backend:**
=======
Test backend health endpoint:

>>>>>>> c9afdfc83e4a6ee296d40f47bf50940a75c01212
```bash
curl http://localhost:5001/api/health
```

<<<<<<< HEAD
**Test Frontend:**
Open http://localhost:5173 in browser
=======
---

## 🌐 Deployment

* Backend Deployment → Render
* Frontend Deployment → Vercel

Refer **DEPLOYMENT_GUIDE.md** for full deployment instructions.

---

## 🔐 Environment Variables

Create a `.env` file in the root directory:

```
ANTHROPIC_API_KEY=your_api_key_here
CLAUDE_API_KEY=your_api_key_here
```

Get API key from:

https://console.anthropic.com/

---

## 📁 Project Structure

```
dark-matter-detection-system/
│
├── webapp/                     # React frontend
│   ├── src/
│   │   ├── pages/              # Dashboard pages
│   │   ├── components/         # Reusable UI components
│   │   └── lib/                # API integrations
│   └── package.json
│
├── anomaly_detection_system/   # Anomaly detection logic
│   └── mainAnomalyDetection.py
│
├── dataset/                    # Dataset files
│   └── dark_matter_synthetic_dataset.csv
│
├── webapp_backend.py           # Flask API server
├── mainClassify.py             # Classification engine
├── requirements.txt            # Python dependencies
├── start_dev.bat               # Windows launcher
├── start_dev.sh                # Mac/Linux launcher
└── .env                        # Environment variables (gitignored)
```

---

## 📚 Documentation

* **QUICK_START.md** — Fast usage guide
* **USER_GUIDE.md** — Step-by-step feature walkthrough
* **DEVELOPER_GUIDE.md** — Development setup and contribution workflow
* **ARCHITECTURE.md** — System design and data flow
* **AI_FUNCTIONALITY.md** — Claude AI integration details
* **API_DOCUMENTATION.md** — REST API reference
>>>>>>> c9afdfc83e4a6ee296d40f47bf50940a75c01212

---

## 📄 License

<<<<<<< HEAD
MIT License - Feel free to use and modify!

---


---

## 🙏 Acknowledgments

- Anthropic Claude AI
- Dark Matter Research Community
- Open Source Contributors

---

## 📞 Support

- 📖 Read the [QUICK_START.md](QUICK_START.md)
- 🐛 Report issues on GitHub
- 💬 Check browser console for errors

---

**Built with ❤️ for Dark Matter Research**
=======
MIT License — free to use, modify, and distribute.

---

## 🙏 Acknowledgements

* Anthropic Claude AI
* Dark Matter Research Community
* Open Source Contributors

---

Built with ❤️ to support intelligent dark matter research and scientific discovery.
>>>>>>> c9afdfc83e4a6ee296d40f47bf50940a75c01212

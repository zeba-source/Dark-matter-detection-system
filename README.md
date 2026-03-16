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

```bash
python webapp_backend.py
```

### Install Frontend Dependencies

```bash
cd webapp
npm install
npm run dev
```

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
```

---

## 🧪 Testing

Test backend health endpoint:

```bash
curl http://localhost:5001/api/health
```

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

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 🙏 Acknowledgements

* Anthropic Claude AI
* Dark Matter Research Community
* Open Source Contributors

---

Built with ❤️ to support intelligent dark matter research and scientific discovery.

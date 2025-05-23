# AmazonExplorer.AI

# 🌎 AmazonExplorer.ai — AI-Assisted Archaeology for the Amazon

AmazonExplorer.ai is an intelligent mapping tool for archaeologists and researchers to explore, analyze, and discover potential historical sites across the Amazon rainforest. Using open-source LIDAR and satellite data combined with OpenAI's GPT-4, it allows for guided research, anomaly detection, and expedition planning.

---

## 🧭 Features

- 🛰️ **Map-based LIDAR + Satellite Explorer**
- 🎯 **AI-assisted Research Task Launcher**
- 🧠 **GPT Summaries** of terrain, anomalies, and historical context
- 🧭 **Expedition Safety Analyzer** (risk, threats, routes)
- 🌐 **Multilingual Reports** (English, Spanish, Portuguese)
- 📂 **Save to Dashboard** for easy project management
- 📄 **PDF Reports** and 🎧 **Voice Notes** for offline review

---

## 🚀 Demo

> 🖼️ Screenshot 1: Drawing Area on Map  
> 📄 Screenshot 2: Generated Research Summary  
> 🎧 Screenshot 3: Voice Note + PDF Export  
> 🗂️ Screenshot 4: Saved Project in Dashboard

---

## 🧪 How It Works

1. Draw a region on the map
2. Define a research question (e.g., “Look for mounds or raised fields”)
3. The system:
   - Scans relevant LIDAR/satellite tiles
   - Uses GPT-4 to summarize terrain, anomalies, and text references
   - Outputs a short, actionable report
4. Save the results to your personal dashboard
5. Download PDF or listen to voice brief

---

## 🛰️ Data Sources

- LIDAR Tile: `SRTM-DEM-Tile-12x14` (NASA OpenDEM)
- Satellite Scene: Sentinel-2 `S2A_MSIL2A_20230415T143601`
- Historical Reference: DOI `10.1126/science.abj8202`  
(Heckenberger et al., 2021, Science)

---

## 🔧 Stack

- Frontend: HTML + CSS + Vanilla JavaScript
- Backend: FastAPI + Python
- AI: OpenAI GPT-4 + VIA PYTHON SDK
- Reports: Google TTS (voice) or whisper
- Storage:LocalJSON/sqllite
- Hosting: Github pages + python anywhere/stremlit for backend

---

## 📚 Contributors

- [Murugeshwari] – AI, Backend, LIDAR
- [Murugeshwari] – UI/UX, Data Visualization
- [Murugeshwari] – Research, Archaeology Mapping

---

## 📄 License

MIT

---

## 🤝 Acknowledgements

- OpenAI
- NASA & ESA for open satellite/LIDAR data
- Hackathon judges and organizing team

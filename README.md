# Multimodal Construction Intelligence Platform (BuildWise)

An AI-powered multimodal decision-support system designed to assist construction professionals across multiple stages of construction planning, site safety monitoring, structural defect analysis, and execution.

---

## 👨‍💻 Author & Developer
- **Developer:** Neeraj Thakur
- **GitHub:** [@Neeraj-programmer](https://github.com/Neeraj-programmer)
- **Repository:** [Multimodal Construction Intelligence Platform](https://github.com/Neeraj-programmer/multimodal-construction-inteliigence)

---

## 📌 Project Overview
The **Multimodal Construction Intelligence Platform** leverages multimodal artificial intelligence (Google Gemini Vision & LLMs) to analyze textual inputs, construction-site imagery, and structured project data to generate accurate, actionable, and context-aware insights.

Traditional construction management practices rely heavily on manual supervision and experience-based judgments. This platform bridges that gap by offering:
- Real-time intelligent safety & PPE screening
- Automated visual crack & surface-defect observations
- Indicative cost, quantity, and asset valuation estimates
- Weather-aware site checklists and intelligent assistant advisory

---

## 🚀 Key Features

1. **Safety & Hazard Review (PPE Detection):**
   - Upload site images (JPG/PNG) to analyze worker PPE compliance (helmets, vests, safety gear) and site hazards.
2. **Defect & Crack Observation:**
   - Detect and classify visible surface cracks and defects with uncertainty-aware guidance and severity level indicators.
3. **Planning & Material Estimates:**
   - Real-time rough estimation of construction costs, steel & cement requirements, and asset valuation based on built-up area and quality tier.
4. **Weather-Aware Protocol & Advisory:**
   - Site risk assessment and weather-specific protocols for high wind, heavy rain, extreme heat, or clear conditions.
5. **Construction AI Assistant:**
   - Interactive chat assistant for civil engineering, site workflow, compliance questions, and daily checklists.
6. **Report Generation:**
   - Export structured JSON inspection reports for site records and audit trails.

---

## 🛠️ Tech Stack
- **Frontend / UI:** Streamlit
- **AI / Multimodal Engine:** Google Gemini API (`gemini-2.0-flash`) / Google GenAI SDK
- **Language:** Python 3.10+
- **Image Processing:** Pillow (PIL)

---

## 💻 Local Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/Neeraj-programmer/multimodal-construction-inteliigence.git
cd multimodal-construction-inteliigence
```

### 2. Create a virtual environment
```bash
# Windows
python -m venv .venv
.venv\Scripts\activate

# macOS / Linux
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the application
```bash
streamlit run app.py
```
Open [http://localhost:8501](http://localhost:8501) in your browser.

---

## 🔑 Gemini API Configuration
1. Get a free API key from [Google AI Studio](https://aistudio.google.com/).
2. Launch the app and paste the API key in the sidebar input field.
3. *(Demo mode is automatically active if no API key is provided).*

---

## ⚠️ Disclaimer
This application is a decision-support prototype and does not replace certified safety audits, structural engineering diagnosis, or formal quantity surveying. Always consult qualified civil engineers and site safety officers for operational construction decisions.

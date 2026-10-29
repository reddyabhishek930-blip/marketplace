[README.md](https://github.com/user-attachments/files/34135175/README.md)
# SYNTHIA — AI Content Creator Marketplace
> **byteXL Hackathons — Challenge 2: AI Content Creator Marketplace**  
> **Sponsored by:** Kampus.VC  
> **Evaluation Criteria:** 100 Points + Bonus Features  

---

## 🚀 Quick Start (Running Locally)

### Option A: One-Click Run (Windows)
Double-click `run.bat` in this folder.

### Option B: Terminal Command
```powershell
python app.py
```
Then open your browser and navigate to:  
👉 **http://127.0.0.1:5000**

---

## 🎯 Problem Statement & Alignment

| Hackathon Requirement | Weight | How SYNTHIA Solves It |
| :--- | :---: | :--- |
| **Creator Profiles & AI Portfolios** | **30%** | Rich profiles with videos & stills, tools/models (Runway, Midjourney, ComfyUI, FLUX.1), skills (LoRA, ControlNet), and reproducible ComfyUI node graphs. |
| **Discovery & Filtering Engine** | **25%** | Instant faceted search by tool, skill, specialization, content format, rating, and verified badges. Includes sensible handling and recovery for empty results. |
| **Brief Definition Studio** | **20%** | Structured capture of content type, style, aspect ratio (`9:16`, `16:9`, `1:1`), 4K technical specs, and commercial-use requirements. |
| **User Experience (UX/UI)** | **15%** | Cyber-luxe dark glassmorphism, responsive controls, video playback, deep pipeline inspector, and intuitive workflows for both brands and creators. |
| **Presentation & Demo** | **10%** | Built-in **Interactive Pitch Deck** (5 slides) and live **Data Model Explorer** accessible directly within the application navbar. |

### 🌟 Bonus Credit Features Built-in:
1. **Creator Verification Signals:**
   - Cryptographic/API verified tool badges.
   - Verified ComfyUI node graphs and seed logs.
   - Enterprise client portfolio metrics (e.g. 2.4M views, Vogue feature).
   - Dynamic 0–100 Trust Score algorithm.
2. **AI-Assisted Brief Builder:**
   - Natural language prompt expansion engine.
   - Converts informal 1-sentence ideas into technical parameters (resolution, fps, recommended models, and commercial deliverables).

---

## 📁 Repository Structure

```
ai-creator-marketplace/
├── app.py                # Flask application & AI Prompt Decomposition REST API
├── run.bat               # Windows one-click execution script
├── DATA_MODEL.md         # Deliverable 2: Complete Data Model & Schema Documentation
├── README.md             # Project overview & demo guide
├── data/
│   └── seed_data.py      # Seed data for top-tier creators, portfolios & briefs
├── static/
│   ├── css/
│   │   └── style.css     # Cyber glassmorphism styling & animations
│   └── js/
│       └── app.js        # Frontend state management, filters, modals & pitch deck
└── templates/
    └── index.html        # Interactive single-page application UI
```

---

## 🎬 How to Demo to Hackathon Judges (Step-by-Step)

1. **Step 1: Explore Creator Profiles & AI Portfolios (30 pts)**
   - Click any creator (e.g. *Maya Lin* or *Alex Chen*).
   - Point out **Verified Pro** badges, **99% Trust Score**, and **Tools Used**.
   - Click on a portfolio item to open the **Pipeline Inspector**: showcase the step-by-step pipeline (*Midjourney $\rightarrow$ Runway Gen-3 $\rightarrow$ Topaz 4K*), locked seeds, and commercial rights terms.

2. **Step 2: Demonstrate Faceted Discovery & Filtering (25 pts)**
   - Click tool filter pills (e.g. `Runway Gen-3`, `ComfyUI`).
   - Toggle **Verified Signals Only**.
   - Type in the search box to filter live.
   - Type nonsense to trigger the **Sensible Empty Result State** with quick reset actions.

3. **Step 3: Test the AI-Assisted Brief Builder (20 pts + Bonus)**
   - Click **"Brand Brief Studio"** in the navbar.
   - Click one of the prompt presets (or type your own idea).
   - Click **"✨ Synthesize Structured Brief with AI"**.
   - Show how the AI automatically infers aspect ratio (`9:16`), resolution (`4K 60fps`), recommended AI tools, and commercial deliverables.
   - Click **"Publish Brief"** to add it to the live marketplace feed.

4. **Step 4: Review Proposals & Engagements**
   - Click **"Engagements & Bids"** to view active creator pitches, budgets, and milestone commitments.
   - Submit a new proposal on any published brief.

5. **Step 5: Review Deliverable 2 & 3**
   - Click **"Data Model Docs"** to inspect the formal JSON Schema.
   - Click **"🏆 Pitch Deck & Demo"** to present the 5-slide hackathon presentation.

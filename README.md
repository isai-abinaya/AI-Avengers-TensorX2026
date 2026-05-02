# AI-Avengers-TensorX2026
AI-powered healthcare navigator and cost estimator for India that analyzes symptoms, predict the Diseases, estimates treatment costs, and recommends hospitals to help patients make informed decisions.

---

# 🏥 MedPath AI
### *"Know Your Treatment Cost Before You Step In"*

> **AI-Powered Healthcare Navigator & Cost Estimator for India**  
> Built for hackathons. Designed for real impact.

---

## 👥 Team AI Avengers

| Member | Role |
|---|---|
| **Isai Abinaya S** | Full Stack + AI Logic |
| **Jafrin A** | UI/UX + Frontend |
| **Anushya V** | Data + Backend |

---

## 🚀 What is MedPath AI?

MedPath AI helps Indian patients:

- **Understand symptoms** → Know what condition they may have
- **Find the right specialist** → Skip the wrong doctor visits
- **Estimate treatment costs** → Before stepping into a hospital
- **Avoid overpaying** → Overpricing alerts built-in
- **Choose the right hospital** → Rated, accredited, affordable

---

## Live Demo

https://ai-avengers-tensor-x2026.vercel.app/ 

---

## ⚡ Quick Start

### 1. Clone / Download the project

```bash
cd medpath-ai1
```



### 2. Run the app

```bash
start index.html
```

---

## 🗂️ Project Structure

```
medpath-ai1/
│
├── app.py                    # Flask backend — all routes and API logic
├── requirements.txt          # Python dependencies (only Flask!)
├── README.md                 # This file
│
├── templates/
│   ├── index.html            # Homepage with hero, features, CTA
│   ├── analyzer.html         # Symptom Analyzer page
│   ├── cost.html             # Cost Estimation Engine
│   └── hospitals.html        # Hospital Recommendations
│
├── static/
│   ├── style.css             # Premium glassmorphism UI + animations
│   └── script.js             # All frontend JS — API calls, typing, scroll FX
│
└── data/
    └── healthcare_data.json  # India healthcare dataset (symptoms, costs, hospitals)
```

---

## 🌟 Core Features

### 🧠 Symptom Analyzer
- Input symptoms in plain English
- AI keyword matching to conditions
- Outputs: Possible condition(s), Recommended specialist, Urgency level

### 💰 Cost Estimation Engine *(Main Feature)*
- Inputs: Condition + City Tier (1/2/3) + Hospital Type
- Output: Estimated cost range ₹X – ₹Y
- Covers 15+ conditions across government, private, and corporate hospitals

### ⚠️ Overpricing Alert *(WOW Feature)*
- Three-tier alert system: 🔴 High / 🟡 Normal / 🟢 Low
- Warning: "You may be overpaying for this treatment"
- Personalized savings tips

### 🏥 Hospital Recommendations
- Top 3 hospitals per tier and type
- Ratings, accreditation (JCI/NABH), specialty, contact

---

## 🔌 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/` | Home page |
| GET | `/analyzer` | Symptom Analyzer page |
| GET | `/cost` | Cost Estimator page |
| GET | `/hospitals` | Hospital Recommendations page |
| POST | `/api/analyze` | Analyze symptoms → condition + specialist |
| POST | `/api/estimate` | Estimate treatment cost |
| POST | `/api/hospitals` | Get hospital recommendations |
| GET | `/api/conditions` | List all available conditions |

### Sample API Request — Symptom Analysis
```json
POST /api/analyze
{
  "symptoms": "chest pain and shortness of breath"
}
```

### Sample API Request — Cost Estimation
```json
POST /api/estimate
{
  "condition": "Migraine",
  "tier": "tier1",
  "hospital_type": "corporate"
}
```

---

## 🎨 Design Highlights

- **Glassmorphism** cards with blur + transparency
- **Animated gradient** background (blue → purple)
- **Typing effect** on homepage hero
- **Scroll reveal** animations
- **Loading spinners** before results
- **Result fade-in** animation
- **Mobile responsive** layout
- Fonts: **Syne** (display) + **DM Sans** (body)

---

## 🏆 Hackathon Demo Flow

1. Open `http://localhost:5000`
2. Click **"Analyze Symptoms"**
3. Type or click a symptom tag (e.g., "chest pain")
4. See: Condition + Specialist + Urgency
5. Click **"Estimate Treatment Cost"**
6. Select condition, Tier 1, Corporate Hospital
7. See: ₹X – ₹Y + **🔴 High Overpricing Alert**
8. Click **"Find Hospitals"** → See top 3 with ratings

---

## 📊 Dataset Coverage

- **12 symptom categories** (chest, head, fever, back, joints, lungs, stomach, skin, diabetes, vision, ear, fatigue)
- **15 medical conditions** with real India cost data
- **3 city tiers** × 3 hospital types = 9 price points per condition
- **10+ hospitals** across tiers with real names, ratings, accreditations

---

## 🌍 Real-World Impact

- Helps patients avoid unnecessary hospital visits
- Prevents overcharging in private hospitals
- Increases healthcare transparency in India
- Supports rural and tier-2/3 patients

---

## 🎥 Demo Video
[Watch Demo](https://drive.google.com/file/d/14DaKcXFgvif0tBLGhf6nNZPo5slsAP_u/view?usp=sharing)

---

## 📸 Screenshots
![Home](https://drive.google.com/file/d/1sPt0WMs51DUj1tEv2WFZIYBDJ25fzgQd/view?usp=sharing)
![Symptom Analyzer](https://drive.google.com/file/d/1Xw9IvJeh_sb-7bfy-SHqYux2n8nNRH3a/view?usp=sharing)
![Cost Estimator](https://drive.google.com/file/d/1xA6Yzy_aT2B9orsQ4-OYofvt4cMceJHA/view?usp=sharing)(https://drive.google.com/file/d/1tZ-NhTK3CocA4NPIjyzVHXcZEi_idfVK/view?usp=sharing)
![Hospital](https://drive.google.com/file/d/1sYbbw6YGck4gYal1_kxSXD-gNltLWIL6/view?usp=sharing)


---

## 🛡️ Disclaimer

MedPath AI is built for educational and informational purposes. It is **not a substitute for professional medical advice, diagnosis, or treatment**. Always consult a licensed healthcare professional.

---

*Built with ❤️ by Team AI Avengers for the TensorX 2026 National level AI Hackathon *

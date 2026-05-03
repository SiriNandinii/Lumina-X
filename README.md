# 🏅 LuminaX – AI-Powered Sports Talent Assessment Platform


**LuminaX** is an *AI-powered mobile platform* that enables athletes, coaches, and institutions to assess, track, and showcase sports performance using **pose estimation**, **on-device AI**, and **real-time feedback**.  
It democratizes sports talent discovery and ensures fair, data-driven, and accessible evaluation — *anytime, anywhere*.

---
**App Link:** https://luminaxx.netlify.app 

**Architecture Link:** https://luminax-seven.vercel.app
## 🚀 Overview

Current sports talent evaluation methods are subjective and inconsistent.  
**LuminaX** solves this challenge through:

- 🎯 **AI-driven motion analysis** for unbiased assessments.  
- 🧠 **On-device processing** using MediaPipe + OpenCV — works even on low-end devices.  
- 🔐 **Cheat-proof verification** with liveness checks and face authentication.  
- 📊 **Instant insights** and feedback for coaches and athletes.  
- 🏆 **Gamified dashboards** featuring badges, leaderboards, and rewards.  
- 🌐 **Centralized talent database** for SAI and policymakers.

---

## 🧩 Key Features

| Feature | Description |
|----------|-------------|
| **AI Talent Assessment** | Pose estimation and motion analysis for standardized sports tests (jump, sit-ups, shuttle run, endurance). |
| **Cheat Detection** | Liveness checks, face authentication, and tamper-proof mechanisms ensure fair results. |
| **Real-Time Feedback** | Instant performance insights with benchmark comparisons. |
| **Gamified Experience** | Leaderboards, badges, and progress tracking to boost motivation. |
| **Talent Profiles** | Verified digital portfolios for athletes. |
| **Offline-First Architecture** | Hive-based local storage with Firebase auto-sync. |
| **Scalable Design** | Extendable to domains like fitness, arts, and education. |
| **Privacy-First Approach** | Only results are uploaded — videos remain on the device. |

---

## 🏗️ System Architecture

### **Layered Overview**

| Layer | Technology Stack |
|-------|------------------|
| **Mobile App** | Flutter (Android/iOS) |
| **Web Dashboard** | React (TypeScript), TailwindCSS, Framer Motion |
| **Backend** | Node.js + Firebase |
| **Database** | Firebase Firestore + Hive (Offline-first) |
| **AI/ML Engine** | MediaPipe, OpenCV, Multi-modal AI (Camera + GPS) |
| **Security** | OTP, Face Auth, Liveness Detection, JWT Encryption |
| **Integration** | Modular APIs (SAI/Khelo India ready) |

---

## ⚙️ Technical Approach

1. **Pose Estimation & Motion Tracking** – Detect body landmarks using MediaPipe.  
2. **Action Recognition** – Analyze motion dynamics using OpenCV.  
3. **Cheat Detection** – Verify user identity and prevent replay/deepfake attempts.  
4. **Gamified Evaluation** – Award badges and maintain leaderboards.  
5. **Offline Support** – Hive stores results locally; Firebase syncs when online.  
6. **Dashboard Analytics** – Aggregate verified results for coaches and policymakers.

---

## 🧠 Innovation & Uniqueness

- 🪶 **Lightweight AI models** for rural and low-end mobile devices.  
- 🔒 **Privacy-first** processing — videos never leave the device.  
- 🎮 **Gamified ecosystem** that increases engagement.  
- 📶 **Offline-first architecture** ensures accessibility in low-connectivity regions.  
- 🏛️ **Policy-aligned** framework for national-level scalability under SAI/Khelo India.

---

## ⚖️ Feasibility & Risk Mitigation

| Challenge | Risk | Mitigation |
|------------|------|------------|
| Device limits | Low-end device performance | Optimized lightweight AI models |
| Connectivity | Rural sync delays | Offline-first + auto-sync |
| AI accuracy | Detection/pose errors | Continuous retraining with domain-specific datasets |
| User adoption | Hesitance toward new tech | Gamified tutorials and simple UI |
| Data privacy | Biometric sensitivity | Encrypted, results-only uploads |
| Integration | SAI/Khelo India APIs | Modular Node.js integration layer |

---

## 🎯 Target Users

- 🏃‍♂️ **Athletes** → Standardized evaluation & verified reports  
- 🧑‍🏫 **Coaches** → Tamper-proof analytics & dashboards  
- 🏛️ **SAI/Government Bodies** → Centralized, policy-aligned talent data  
- 👨‍👩‍👧 **Parents & Schools** → Early identification of potential  
- 🏅 **Sports Ecosystem** → Unified national database for talent discovery.  

---

## 🌍 Impact & Benefits

| Benefit | Description |
|----------|-------------|
| **Democratized Talent Discovery** | Equal opportunity for rural and urban athletes. |
| **Fair & Transparent** | AI ensures unbiased, cheat-proof evaluations. |
| **Time & Cost Efficient** | Reduces manual testing and logistics costs. |
| **Data-Driven Decisions** | Provides verified analytics for coaches and policymakers. |
| **Motivational** | Gamified experience keeps users engaged. |
| **Cross-Domain Scalability** | Extendable to fitness, arts, and education. |

---
## 🚀 *Installation & Setup*

### 🧱 Prerequisites

* Node.js ≥ 18
* Python ≥ 3.9
* Firebase Firestore database
* GitHub account with repository access

### 🔧 Steps

bash
# Clone the repository
git clone https://github.com/SiriNandinii/LuminaX.git

# Navigate into the project
cd LuminaX

# Set up backend
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

# Set up frontend
cd ../frontend
npm install
npm start



## 💼 Future Scope & Business Model

- 📈 **Cross-Domain Expansion** – Extend to fitness, arts, and education.  
- 🧩 **Personalized AI Coaching** – Smart training suggestions and performance analytics.  
- 🏫 **Institutional Integration** – Deployment in schools, academies, and federations.  
- 🤝 **CSR & Govt Partnerships** – Adoption by SAI and state bodies.  
- 💰 **Freemium Model** – Free basic tests, premium analytics, certificates, and academy tiers.  
- 📊 **Data Dashboard** – Policy-level insights for federations and sponsors.  

---

## 🔬 Research & References

1. Suryawanshi, V. et al. (2022) *AI-driven pose estimation for exercise correction* – IJRSI  
2. Mishra, Y. et al. (2023) *AI fitness tracker with MediaPipe* – IJRASET  
3. Shah, B. et al. (2022) *Pose estimation for sports performance* – Springer LNNS  
4. Siddiqui, H.U.R. et al. (2023) *Cricket performance analysis* – Sensors  

---

## 🌐 Project Resources

- 🎥 **Prototype Video:** [YouTube](https://youtu.be/s3lGsF4w0uU)   

**Documentation:**
- [MediaPipe](https://developers.google.com/mediapipe)
- [OpenCV](https://docs.opencv.org/)
- [Firebase](https://firebase.google.com/docs)
- [Hive](https://docs.hivedb.dev/)

---


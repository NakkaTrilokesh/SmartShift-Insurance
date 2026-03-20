<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=soft&height=180&section=header&color=gradient&customColorList=9,6,12&text=Smart%20Shift&fontSize=46&fontColor=fff&animation=fadeIn&fontAlignY=32&desc=AI%20Powered%20Insurence%20For%20India's%20Gig%20Economy%20&descSize=18&descAlignY=60"/>


*Protecting gig delivery workers from income loss caused by environmental disruptions and real-world uncertainties.*

<br/>

[![Phase](https://img.shields.io/badge/📋_Phase_1-Ideation_&_Foundation-00D9FF?style=for-the-badge)](.)
[![Team](https://img.shields.io/badge/👨‍💻_Team-Code_Blooded-FF6B6B?style=for-the-badge)](.)
[![Status](https://img.shields.io/badge/🚀_Status-In_Development-10B981?style=for-the-badge)](.)
[![License](https://img.shields.io/badge/📄_License-MIT-F59E0B?style=for-the-badge)](.)

<br/>
</div>

---

## 🧬 What is SmartShift?

```javascript
const SmartShift = {
    mission: "Protect gig workers from income loss due to environmental disruptions",
    type: "AI-Powered Parametric Insurance Platform",
    target: "Gig Delivery Workers across India",
    team: "Code Blooded",
    phase: "Phase 1 – Ideation & Foundation",
    approach: "Detect → Evaluate → Validate → Payout",
    superpower: "Automated payouts without manual claims",
    status: "Building the future of gig worker protection 🛡️"
};

const handleDisruption = async (event) => {
    const lossScore = await evaluateImpact(event);
    const fraudScore = await validateAuthenticity(event);

    if (lossScore > 60 && fraudScore === 'low') {
        return triggerPayout({ type: 'full', instant: true });
    }
};
```

---

## 📖 Overview

SmartShift is an AI-powered parametric insurance platform built for gig delivery workers whose earnings depend on consistent daily activity.

In cities across India, delivery partners frequently face unexpected disruptions such as heavy rainfall, extreme heat, or high pollution levels. These conditions directly reduce their ability to work and lead to immediate income loss. Despite this, there is no system today that compensates for these short-term disruptions in a fast and reliable way.

SmartShift addresses this gap by introducing an automated system that continuously monitors real-world conditions, evaluates how much a worker is affected, verifies authenticity, and triggers payouts instantly — without requiring manual claims.

> 🛡️ The system is also designed to remain robust in adversarial situations such as GPS spoofing and coordinated fraud attempts.

---

## 🎯 Key Features

<div align="center">

| | Feature | Description |
|:---:|:---|:---|
| 🤖 | **AI-Driven Decision Engine** | Intelligent scoring and automated decision-making |
| 📡 | **Real-Time Disruption Detection** | Continuous monitoring of environmental conditions |
| 💰 | **Impact-Based Payout System** | Compensation proportional to actual income loss |
| 🔒 | **Fraud Detection & Anti-Spoofing** | Multi-layered validation against manipulation |
| 📊 | **Dynamic Weekly Premium** | Risk-adjusted pricing aligned with income cycles |
| ✅ | **Multi-Signal Validation** | Cross-referencing multiple data sources for accuracy |
| ⚡ | **Instant Automated Payouts** | Zero manual claims, zero delays |

</div>

---

## 👤 Target Persona

### Delivery Partner – Example Profile

<div align="center">

| | Attribute | Value |
|:---:|:---|:---|
| 👤 | **Name** | Arjun Reddy |
| 🎂 | **Age** | 24 |
| 🍕 | **Platform** | Zomato |
| 🏙️ | **City** | Bangalore |
| 🛵 | **Vehicle** | Scooter |
| 💵 | **Daily Income** | ₹800 |
| 📅 | **Weekly Income** | ₹5,600 |

</div>

---

## 🌧️ Problem Scenario

Arjun typically works during evening peak hours when order demand is highest.

One day, sudden heavy rainfall hits his area:

- 🚧 Road conditions worsen
- 📉 Orders reduce significantly
- 🏠 He logs off earlier than usual

<div align="center">

| | Metric | Value |
|:---:|:---|:---|
| 💵 | **Normal Daily Income** | ₹800 |
| ⏰ | **Hours Lost** | 4 hrs |
| 📉 | **Estimated Loss** | ₹320 |

</div>

> ✅ SmartShift detects this situation and compensates Arjun **automatically** based on the actual impact.

---

## ❗ Problem Statement

Gig delivery workers form a critical part of India's urban economy, yet they remain financially vulnerable to short-term disruptions caused by environmental and external factors.

**Existing insurance systems:**

- ❌ Require manual claim filing
- ❌ Are slow and complex
- ❌ Do not address daily income fluctuations

> 💡 SmartShift introduces a system that automatically detects disruptions and provides timely financial support **without adding friction** for the user.

---

## 💡 Solution Approach

SmartShift follows a structured decision flow:

```
┌──────────────┐    ┌──────────────────┐    ┌─────────────────────┐    ┌─────────────────┐
│   🔍 DETECT  │───▶│  📊 EVALUATE     │───▶│  🔒 VALIDATE        │───▶│  💰 PAYOUT      │
│  Disruption  │    │  Impact (Loss    │    │  Authenticity       │    │  Trigger        │
│              │    │  Score)          │    │  (Fraud Score)      │    │                 │
└──────────────┘    └──────────────────┘    └─────────────────────┘    └─────────────────┘
```

The system continuously analyzes environmental data and user behavior to make real-time decisions.

**This ensures:**

- ✅ No manual claims
- ✅ Faster response time
- ✅ Fair and data-driven payouts

---

## 🧠 Core Decision Model

SmartShift's decision-making is based on two key components:

---

### 1️⃣ Loss Score (Impact Measurement)

Loss Score measures how much a worker's income is affected compared to their normal working pattern.

```
Loss Score = (0.35 × Eₛ) + (0.25 × Aᵈ) + (0.25 × Oᵈ) + (0.15 × Tᵢ)

Where:
  Eₛ  = Environmental Severity    → intensity of disruption (rain, heat, pollution)
  Aᵈ  = Activity Deviation        → difference between expected and actual working hours
  Oᵈ  = Order Deviation           → drop in completed deliveries vs normal trends
  Tᵢ  = Time Impact Factor        → higher weight for peak working hours
```

<div align="center">

#### 📊 Loss Score Decision Logic

| Score Range | Action | Status |
|:---:|:---|:---:|
| `< 40` | No payout | 🔴 |
| `40 – 60` | Partial payout | 🟡 |
| `> 60` | Full payout | 🟢 |

</div>

---

### 2️⃣ Fraud Score (Trust Measurement)

Fraud Score evaluates whether the user's behavior is genuine.

```
Fraud Score = (0.30 × Lₐ) + (0.30 × Bᵈ) + (0.20 × Aₘ) + (0.20 × Hᵢ)

Where:
  Lₐ  = Location Anomaly          → GPS inconsistencies or spoofing signals
  Bᵈ  = Behavior Deviation        → departure from established user patterns
  Aₘ  = Activity Mismatch         → conflict between reported and actual activity
  Hᵢ  = Historical Inconsistency  → contradictions with past behavior data
```

<div align="center">

#### 🔒 Fraud Score Decision Logic

| Risk Level | Action | Status |
|:---:|:---|:---:|
| **High** | Flag or block | 🔴 |
| **Medium** | Additional validation | 🟡 |
| **Low** | Proceed normally | 🟢 |

</div>

---

### ⚖️ Final Decision Matrix

SmartShift combines Loss Score and Fraud Score to ensure payouts are both fair and secure.

<div align="center">

```
                        FRAUD SCORE
                 Low        Medium       High
            ┌──────────┬──────────┬──────────┐
  High      │ ✅ APPROVED│ ⏸️ HELD  │ ❌ REJECTED│
            ├──────────┼──────────┼──────────┤
LOSS  Med   │ ✅ APPROVED│ ⏸️ HELD  │ ❌ REJECTED│
SCORE       ├──────────┼──────────┼──────────┤
  Low       │ 🔴 NONE   │ 🔴 NONE  │ ❌ REJECTED│
            └──────────┴──────────┴──────────┘
```

</div>

| Scenario | Outcome |
|:---|:---|
| 🟢 High Loss + Low Fraud | **Approved** — Instant payout |
| 🟡 High Loss + Medium Fraud | **Held** — Temporarily held for verification |
| 🔴 Any Loss + High Fraud | **Rejected** — Payout blocked |

---

## 🤖 AI / Machine Learning Integration

SmartShift uses machine learning to improve decision accuracy and adaptability.

<details>
<summary><b>🔍 Anomaly Detection</b> — Click to expand</summary>
<br/>

Identifies unusual drops in activity and suspicious behavior patterns. The system flags deviations from established baselines and escalates them for further evaluation.

</details>

<details>
<summary><b>📊 Behavioral Profiling</b> — Click to expand</summary>
<br/>

Builds a baseline for each user and compares real-time activity against it. This includes working hours, typical routes, order frequency, and session patterns.

</details>

<details>
<summary><b>🕵️ Fraud Pattern Recognition</b> — Click to expand</summary>
<br/>

Detects coordinated fraud attempts by analyzing similarities across multiple users. Identifies clusters of suspicious behavior that indicate organized manipulation.

</details>

<details>
<summary><b>📈 Adaptive Scoring</b> — Click to expand</summary>
<br/>

Continuously refines thresholds based on incoming data trends. The system learns from historical outcomes to improve future decision accuracy.

</details>

---

## 🛡️ Adversarial Defense & Anti-Spoofing Strategy

SmartShift is designed to remain reliable even under fraud attempts.

### 🔗 Multi-Signal Validation

Instead of relying on a single source, the system uses:

```
┌─────────────┐  ┌─────────────────┐  ┌────────────────┐
│  📍 GPS     │  │  📋 Activity    │  │  📦 Order      │
│  Data       │  │  Logs           │  │  Patterns      │
└──────┬──────┘  └───────┬─────────┘  └───────┬────────┘
       │                 │                     │
       └─────────────────┼─────────────────────┘
                         ▼
              ┌─────────────────────┐
              │  🧠 DECISION ENGINE │
              │   Multi-Signal      │
              │   Validation        │
              └──────────┬──────────┘
                         │
       ┌─────────────────┼─────────────────────┐
       │                 │                     │
┌──────▼──────┐  ┌───────▼─────────┐  ┌───────▼────────┐
│  🌤️ Weather │  │  📱 Device      │  │  🔐 Fraud      │
│  Conditions │  │  Signals        │  │  Score         │
└─────────────┘  └─────────────────┘  └────────────────┘
```

> ✅ A decision is made only when multiple signals align.

---

<details>
<summary><b>🕸️ Fraud Ring Detection</b> — Click to expand</summary>
<br/>

The system identifies large-scale fraud attempts by detecting:

- 🔄 Similar behavior across multiple users
- 📈 Sudden spikes in claims in a specific region
- 🔁 Repeated anomaly patterns

This helps detect coordinated fraud attacks where multiple users attempt to exploit the system simultaneously.

</details>

<details>
<summary><b>⚖️ Fairness Mechanism</b> — Click to expand</summary>
<br/>

- Small inconsistencies are tolerated
- No decision is based on a single signal
- Confidence-based validation ensures genuine users are protected

</details>

<details>
<summary><b>🔬 Differentiation: Genuine vs Fraudulent Users</b> — Click to expand</summary>
<br/>

SmartShift evaluates behavioral consistency rather than relying only on location data.

- ✅ **Genuine users** show natural movement, realistic routes, and consistent app usage
- ❌ **Fraudulent users** often show static positions, unrealistic jumps, or mismatched activity

The system compares real-time behavior with historical patterns to identify anomalies.

</details>

<details>
<summary><b>📡 Data Used Beyond GPS</b> — Click to expand</summary>
<br/>

SmartShift strengthens validation using multiple signals:

- 📍 GPS location data
- 📦 Order acceptance and completion patterns
- 📋 Session activity logs
- 🌤️ Environmental conditions
- 📱 Device motion consistency

A payout decision is made only when these signals align logically.

</details>

<details>
<summary><b>🤝 UX Balance: Protecting Genuine Users</b> — Click to expand</summary>
<br/>

SmartShift ensures that genuine users are not unfairly penalized.

- Minor inconsistencies are tolerated
- Medium-risk cases are not immediately rejected
- Payouts may be temporarily held for further validation

If supporting signals confirm genuine behavior, the payout is approved.

</details>

<details>
<summary><b>🚨 Handling Coordinated Fraud</b> — Click to expand</summary>
<br/>

The system identifies large-scale fraud scenarios by analyzing:

- Similar behavioral patterns across multiple users
- Sudden regional spikes in claims
- Repeated anomaly trends

This allows SmartShift to detect fraud rings and respond proactively.

</details>

---

## ⚙️ Parametric Trigger Logic

SmartShift uses predefined conditions to trigger payouts automatically.

```
┌──────────────────────────────────┐
│      PARAMETRIC TRIGGER          │
├──────────────────────────────────┤
│                                  │
│  Condition A:                    │
│  🌧️ Rainfall > Threshold        │
│            AND                   │
│  Condition B:                    │
│  📉 Activity drops significantly │
│                                  │
├──────────────────────────────────┤
│           ▼ BOTH MET?            │
├──────────────────────────────────┤
│                                  │
│  1️⃣  Impact is calculated        │
│  2️⃣  Fraud risk is evaluated     │
│  3️⃣  Payout is triggered         │
│                                  │
└──────────────────────────────────┘
```

---

## 💲 Pricing Model

SmartShift uses a weekly subscription model aligned with gig workers' income cycles.

```
Premium = Base × Zone Risk × Income Factor × Behavior Factor
```

**This ensures:**

- ✅ Fair pricing
- ✅ Risk-based adjustment
- ✅ Better affordability

---

## 🛠️ Technology Stack

<div align="center">

### 💻 Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### ⚙️ Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

### 🗄️ Database
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### 🌐 External APIs
![Weather API](https://img.shields.io/badge/🌤️_Weather_API-Rainfall_&_Temperature-4A90D9?style=for-the-badge)
![Air Quality](https://img.shields.io/badge/🌫️_Air_Quality_API-Pollution_Levels-8B5CF6?style=for-the-badge)
![Maps API](https://img.shields.io/badge/📍_Maps_API-Location_Validation-10B981?style=for-the-badge)
![Payment API](https://img.shields.io/badge/💳_Payment_API-Instant_Payouts-F59E0B?style=for-the-badge)

</div>

---

## 🚀 Deployment Strategy

<div align="center">

| | Component | Platform |
|:---:|:---|:---|
| 🌐 | **Frontend** | Vercel / Netlify |
| ⚙️ | **Backend** | Render / AWS |
| 🗄️ | **Database** | MongoDB Atlas |

</div>

---

## 🔮 Future Scope

- [ ] Integration with real delivery platforms
- [ ] More advanced ML models
- [ ] Mobile application development
- [ ] Detailed analytics dashboard

---

## 🏗️ System Architecture

The following diagram illustrates the overall architecture of SmartShift, including the AI decision engine, parametric trigger system, fraud detection layer, and external integrations.

<div align="center">

<img width="851" height="663" alt="SmartShift System Architecture" src="https://github.com/user-attachments/assets/1dd6e518-9cb1-4f82-a291-0fc7598e5c1d" />

</div>

```
┌─────────────────────────────────────────────────────────────┐
│                    SMARTSHIFT PLATFORM                       │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│   ┌───────────┐    ┌──────────────┐    ┌───────────────┐   │
│   │ 🌤️ Weather │    │ 📍 Location  │    │ 📦 Platform   │   │
│   │   Data    │    │   Service    │    │   Data        │   │
│   └─────┬─────┘    └──────┬───────┘    └──────┬────────┘   │
│         │                 │                    │            │
│         └─────────────────┼────────────────────┘            │
│                           ▼                                 │
│              ┌────────────────────────┐                     │
│              │   🧠 AI DECISION       │                     │
│              │      ENGINE            │                     │
│              ├────────────────────────┤                     │
│              │  Loss Score Calculator │                     │
│              │  Fraud Score Evaluator │                     │
│              │  Anomaly Detector      │                     │
│              └───────────┬────────────┘                     │
│                          │                                  │
│              ┌───────────▼────────────┐                     │
│              │   ⚖️ PARAMETRIC        │                     │
│              │     TRIGGER ENGINE     │                     │
│              └───────────┬────────────┘                     │
│                          │                                  │
│              ┌───────────▼────────────┐                     │
│              │   💰 PAYOUT SERVICE    │                     │
│              │   (Instant Transfer)   │                     │
│              └────────────────────────┘                     │
│                                                             │
│   Flow: Detect → Evaluate → Validate → Payout              │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 📝 Conclusion

SmartShift provides a practical and scalable solution to a real problem faced by gig workers.

By combining real-time monitoring, AI-driven decision-making, and automated payouts, the platform ensures that workers are supported when external conditions affect their income.

At the same time, its fraud detection and anti-spoofing mechanisms maintain system integrity without compromising fairness.

> 🎯 The result is a system that is **reliable**, **adaptive**, and **ready for real-world deployment**.

> 💬 *"SmartShift is designed not just to automate payouts, but to ensure trust, fairness, and resilience even under adversarial conditions."*

---

<div align="center">

<br/>

**⭐ From [Code Blooded](.) with ❤️**

<br/>

[![SmartShift](https://img.shields.io/badge/⚡_SmartShift-Protecting_Gig_Workers-00D9FF?style=for-the-badge)](.)

</div>


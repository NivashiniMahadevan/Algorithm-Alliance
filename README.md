# AI-Powered Income Protection for Zomato Delivery Partners

## Persona
Zomato delivery partner operating near SRM University, Kattankulathur, Chennai.

---

## 1. Problem Statement

Delivery partners rely heavily on continuous working hours to earn their daily income. However, external disruptions such as sudden heavy rainfall and waterlogging—common in Chennai suburbs—directly reduce their ability to work.

In areas like Kattankulathur, even 2–3 hours of intense rain can:
- Halt deliveries completely  
- Cause inactivity on delivery platforms  
- Lead to immediate income loss  

Currently, there is no mechanism to compensate for this loss. As a result, delivery partners are forced to bear the financial impact themselves.

---

## 2. Our Solution

We propose an AI-powered parametric insurance platform that compensates delivery partners for income lost due to heavy rainfall.

Key characteristics:
- No manual claim filing required  
- Fully automated detection and payout  
- Weekly subscription model aligned with gig workers  
- AI-driven fraud-resistant system  

The system ensures that when a verified disruption occurs, compensation is triggered automatically based on predefined conditions.

---

## 3. Real-World Scenario

Ravi is a Zomato delivery partner near SRM University.

At 6:30 PM, heavy rainfall begins. Within minutes:
- Orders drop significantly  
- Roads become waterlogged  
- Ravi stops receiving delivery requests  

The system:
- Detects rainfall intensity along with delivery inactivity  
- Confirms Ravi’s presence in the affected zone  
- Automatically triggers compensation  

Ravi receives the payout without needing to raise a claim.

---

## 4. System Workflow

1. User onboarding (location and delivery zone selection)  
2. Weekly plan subscription  
3. AI-based risk profiling of the delivery zone  
4. Continuous monitoring of:
   - Weather conditions  
   - Delivery activity  
5. Trigger detection (rainfall threshold exceeded)  
6. Fraud validation layer  
7. Automatic payout processing  

---

## 5. Weekly Pricing Model

The platform follows a weekly premium system aligned with gig workers’ earning cycles.

### Base Plan
₹30 per week  

### Dynamic Adjustments
- High rainfall risk zone → ₹40/week  
- Moderate risk zone → ₹30/week  
- Low risk zone → ₹25/week  

### Pricing Factors
- Historical rainfall data  
- Delivery density in the area  
- Past disruption frequency  
- Individual usage patterns  

This ensures fair and adaptive pricing for each user.

---

## 6. Parametric Trigger (Disruption Logic)

We focus on a clear and measurable trigger:

**Heavy Rainfall Disruption**

Trigger conditions:
- Rainfall intensity exceeds a predefined threshold (e.g., 20 mm/hour)  
- Simultaneous drop in delivery activity  
- Duration of disruption is at least 45 minutes  

Once these conditions are met, the payout is triggered automatically.

---

## 7. Fraud Prevention and Validation Strategy

Given the rise of GPS spoofing and coordinated fraud attempts, relying solely on location data is insufficient.

### 7.1 Real vs Spoofed Activity

The system compares:
- Physical movement vs reported location  
- Delivery activity vs claimed disruption  
- Behavioral patterns vs real-time data  

Example:  
If a user appears in a rain-affected zone but shows no movement or delivery attempts, the system flags the inconsistency.

---

### 7.2 Data Signals Used

The system validates claims using multiple inputs:
- Accelerometer and gyroscope data (movement tracking)  
- Delivery activity logs (orders accepted/completed)  
- Network consistency (real vs simulated movement)  
- Weather API data (actual rainfall verification)  
- Historical user behavior patterns  
- Active time during disruption  

---

### 7.3 Fraud Detection Logic

An AI-based anomaly detection model is used to:
- Detect unusual inactivity patterns  
- Identify repeated suspicious claims  
- Flag coordinated fraud attempts across users  

#### Confidence Scoring
- High confidence → Instant payout  
- Medium confidence → Delayed verification  
- Low confidence → Flagged for review  

---

### 7.4 User Experience Balance

The system is designed to protect genuine users:
- No immediate rejection of claims  
- Status shown as “Verification in progress”  
- Option to appeal decisions  
- Partial payout in uncertain cases  

This ensures fairness while maintaining system integrity.

---

## 8. AI/ML Integration

AI is used across multiple components:
- Risk prediction based on location and weather patterns  
- Dynamic premium calculation  
- Fraud detection using anomaly detection models  
- Behavioral pattern analysis  

---

## 9. Tech Stack

**Frontend:** Figma prototype (UI/UX demonstration)  
**Backend (planned):** Node.js / Python  
**AI/ML:** Python (Scikit-learn)  

**APIs:**
- Weather API (rainfall data)  
- Simulated delivery activity data  

---

## 10. Why This Works

- Fully automated system with no manual effort required  
- Real-time detection enables immediate response  
- Fraud-resistant architecture prevents misuse  
- Weekly pricing aligns with gig economy income cycles  

---

## 11. Future Scope

- Direct integration with delivery platform APIs  
- Real-time UPI payout system  
- Advanced fraud detection using graph-based models  
- Expansion to multiple cities and platforms  

---

## Summary

This system provides a reliable financial safety net for delivery partners. It ensures that uncontrollable external disruptions such as heavy rainfall do not directly impact their income, while maintaining strong fraud prevention through intelligent validation mechanisms.

---

## Final Note

We do not rely on GPS alone.  
The system uses multi-source validation combining sensor data, behavioral analysis, and delivery activity to prevent coordinated fraud.

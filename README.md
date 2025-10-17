# AI-Embedded Initial Diagnosis and Specialist Referral System for Sehaty

An AI-powered health triage and referral system designed as an extension to the Sehaty App, managed by the Saudi Ministry of Health (MOH).
The system provides initial medical assessments and automatically refers patients to the most relevant specialist, ensuring timely and accurate care while reducing waiting times in the healthcare system.

---

## Project Context

Sehaty is a digital health platform by the Saudi Ministry of Health that provides citizens with access to healthcare services, including appointment booking, medical records, and telemedicine.

This project builds on that foundation by introducing an AI-based Initial Diagnosis and Referral System that helps users receive instant, preliminary diagnoses and be directed to the appropriate specialist within Sehaty.

It supports the Saudi Vision 2030 goal of enhancing digital healthcare efficiency and accessibility.

---

## Project Goal

The primary goal of this project is to reduce patient misdirection and waiting times by using AI-based analysis to identify probable conditions and refer patients to the correct medical specialist immediately after the initial diagnosis.

By doing so, the system:

* Prevents delays in proper treatment
* Reduces unnecessary general consultations
* Enhances patient experience and trust in digital health tools

---

## Overview

The AI-Embedded Initial Diagnosis and Referral System receives user symptoms (through voice or text), processes them using Natural Language Processing (NLP) and machine learning models, and outputs:

1. A list of possible health conditions ranked by confidence.
2. The most suitable medical specialist (e.g., dermatologist, cardiologist, ENT).

This enables the Sehaty app to automatically schedule or recommend the appropriate medical service or teleconsultation.

---

## Key Features

* **AI-Driven Symptom Analysis:** Identifies likely conditions based on reported symptoms.
* **Specialist Recommendation Engine:** Refers users to the appropriate specialist instantly.
* **Voice and Text Input:** Supports both spoken and typed symptom entry.
* **Arabic and English Support:** Designed for inclusivity across Saudi Arabia.
* **Data Privacy Compliance:** Aligned with MOH data governance and AI ethics policies.
* **Seamless Integration:** Built to operate within Sehaty’s existing backend and user interface.

---

## System Architecture

```plaintext
User Input (Voice/Text)
        ↓
NLP Engine (Arabic + English)
        ↓
Symptom Classification Model
        ↓
Condition Prediction + Confidence Scoring
        ↓
Specialist Mapping Module
        ↓
Sehaty API Integration (Booking / Referral)
        ↓
User Feedback via App Interface
```

---

## Tech Stack

| Component           | Technology                       |
| ------------------- | -------------------------------- |
| Programming         | Python, C++                      |
| Machine Learning    | TensorFlow / PyTorch             |
| NLP                 | spaCy, Hugging Face Transformers |
| API                 | FastAPI / Flask                  |
| Embedded Deployment | Raspberry Pi / Edge TPU          |
| Interface           | Sehaty App (via REST API or SDK) |
| Voice Processing    | SpeechRecognition, pyttsx3       |
| Database            | SQLite / Sehaty Cloud Backend    |

---

## Model Details

* **Model Type:** Multi-label classification (symptoms → conditions → specialist)
* **Data Sources:** WHO datasets, symptom–disease mappings, and verified medical resources
* **Performance:**

  * Accuracy: ~91%
  * Specialist referral precision: 93%
  * Average response time: < 1.5 seconds
* **Languages Supported:** English and Arabic

---

## Future Development

* Integration with wearable health devices for continuous monitoring.
* Expanded dataset to include chronic and rare conditions.
* Integration with electronic medical records (EMR) for continuous learning.
* Real-time AI chat assistant for patient guidance.

---

## Collaboration and Contribution

This project aligns with the Saudi Ministry of Health’s innovation initiatives to enhance digital health and early diagnosis systems.
Contributions are encouraged — please fork the repository, create a branch, and submit a pull request with your improvements.

---

## Team

* Layan Esmat 
* Manahel Alahmadi  
* Yasmeen Alrashidi 
* Munifah Aljabri 
* Mawaddah Almowallad 

---

## Short Description

AI-Embedded Initial Diagnosis and Specialist Referral System for Sehaty: an AI-driven module that provides preliminary diagnoses and refers patients to the appropriate specialist within the Sehaty platform to reduce wait times and improve treatment outcomes.

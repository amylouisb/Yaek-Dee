# Yaek-Dee (แยกดี): AI-Powered Waste Sorting App

**Yaek-Dee (แยกดี)** is a cross-platform mobile application that leverages Vision AI to classify waste from images and promote correct recycling behavior. The application combines real-time AI inference with an intuitive user experience to make waste sorting simple, engaging, and impactful.

---

## Project Overview

Waste separation is often inconsistent due to unclear classification rules. Yaek-Dee addresses this problem by using **Vision Language Models (LVMs)** to automatically identify waste types from images.

The system runs **locally via Ollama**, enabling:
- Fast inference  
- Reduced dependency on cloud APIs  
- Better privacy  

---

## Key Features

-  **AI-Based Waste Classification**  
  Detect and classify waste using Vision AI (Qwen 2.5-VL via Ollama)

-  **User Impact Tracking**  
  Monitor waste sorting activity and environmental contribution

-  **Educational Content**  
  Learn proper waste separation and recycling practices

-  **Gamification**  
  Interactive features to encourage consistent usage

-  **Cross-Platform Application**  
  Built with Flutter for both iOS and Android

-  **Cloud Backend (Firebase)**  
  Authentication, Firestore database, and storage integration

---

##  Tech Stack

| Category   | Technology              |
|------------|------------------------|
| Frontend   | Flutter (Dart)         |
| AI / ML    | Ollama + Qwen 2.5-VL   |
| Backend    | Firebase               |

---

##  How It Works

1. User captures or uploads an image  
2. Image is sent to local Ollama server  
3. Vision Language Model processes the image  
4. Waste category is returned to the app  
5. Result is displayed and optionally stored  

---

## Getting Started

### 1. Prerequisites

- Flutter SDK  
- Firebase project (Auth + Firestore + Storage)  
- Ollama installed  

---

### 2. Clone Repository

```bash
git clone https://github.com/amylouisb/Yaek-Dee.git
cd Yaek-Dee


# NAMMA-VASTRA

AI-powered platform for Karnataka weavers to showcase sarees, identify market trends, calculate pricing, and connect directly with customers.

---

## 📌 Problem Statement

Traditional Karnataka weavers often depend on middlemen and wholesalers to sell their products. Due to lack of digital exposure and market trend awareness, many weavers struggle to reach customers directly and earn fair profits.

NAMMA-VASTRA solves this problem using AI-powered tools and a modern Android application that helps weavers:
- Analyze color and fashion trends
- Showcase products digitally
- Calculate product pricing
- Share their weaving stories with customers

---

## 🎯 Project Objective

To empower Karnataka weavers through a smart Android platform that combines:
- Artificial Intelligence
- Digital Catalog Management
- Trend Analysis
- Pricing Assistance
- Customer Connectivity

---

## 🧵 Features

### 1. Trend Board
- Displays trending saree colors and patterns
- Helps weavers understand current market demand
- Uses AI-based recommendations

### 2. Loom Gallery
- Upload and manage saree images
- Digital product showcase for customers

### 3. Price Calculator
- Calculates saree pricing based on:
  - Material cost
  - Labor cost
  - Profit margin

### 4. Weaver Story
- Allows weavers to share:
  - Personal stories
  - Craft history
  - Audio or text introductions

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Kotlin | Android App Development |
| Jetpack Compose | Modern UI Design |
| Firebase / SQLite | Data Storage |
| Generative AI | Trend Analysis |
| Android Studio | Development Environment |

---

## 🏗 System Architecture

```text
+-------------------+
|       User        |
+-------------------+
          |
          v
+-------------------+
|   Android UI      |
| (Jetpack Compose) |
+-------------------+
          |
          v
+-------------------+
|  Business Logic   |
|      (Kotlin)     |
+-------------------+
          |
   -----------------
   |               |
   v               v
+-----------+   +------------------+
| SQLite DB |   | Firebase Cloud   |
+-----------+   +------------------+
          |
          v
+-------------------+
|  Generative AI    |
+-------------------+
          |
          v
+-------------------+
|  Trend Suggestions|
|  Pricing Insights |
+-------------------+

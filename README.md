# 🔥 BlazeEdge - Competitive Product Analysis Tool

> **Designed to Dominate. Engineered for the Future!**

**BlazeEdge** is a GenAI-powered competitive product analysis tool designed to help manufacturers boost the market competitiveness of their products. By uploading a PDF of product data, manufacturers receive intelligent analysis and actionable insights, helping them strategically enhance their offerings.

---

## 🚀 Features

### 📊 Competitive Analyzer
- Upload product PDF to analyze specs, features, and pricing.
- Generate product competitiveness score.
- Compare with competitors within a custom price range.
- Get suggestions for:
  - ✅ Features to Add
  - ❌ Features to Remove
- View product strengths and weaknesses.
- See ranking before and after enhancement.
- Download a detailed PDF report.

### 🤖 ClarityBot – AI-Powered Assistant
- Interactively answers queries related to the analysis.
- Supports multi-PDF upload: Product Data, Competitive Report, and Consolidated Report.
- Provides reasoning behind scores, rankings, and suggested improvements.
- Powered by OpenAI GPT-3.5 Turbo.

---

## 🧠 Technology Stack

| Component        | Technology           |
|------------------|----------------------|
| Frontend         | HTML, CSS, JavaScript |
| Backend          | Python, Flask         |
| Scraping         | Scrapy (Flipkart)     |
| PDF Processing   | PyPDF2, ReportLab     |
| AI Model         | OpenAI GPT-3.5 Turbo  |
| Data Handling    | JSON                  |
| Visualization    | Flask Jinja Templates |

---

## 🛠️ How It Works

1. **Upload** your product's PDF document.
2. **Set** your desired price range.
3. **Analyze**: BlazeEdge scrapes competitor data from e-commerce sites, processes reviews/specs, and runs comparative analysis.
4. **Generate Report**: The tool outputs:
   - Product strengths/weaknesses
   - Score before & after enhancement
   - Feature recommendations
   - Market ranking
5. **Query the ClarityBot** for in-depth explanation of your results.

---

## 🧪 Sample Use Case

- Manufacturer uploads a PDF for their upcoming smartphone.
- Sets price range ₹15,000 - ₹20,000.
- BlazeEdge compares it against competitors on Flipkart.
- Returns:
  - Score = 63/100 (before)
  - Score = 92/100 (after improvements)
  - Weakness: No NFC, mediocre camera.
  - Suggests: Add OIS, remove unused bloatware apps.
- Manufacturer uses these insights to iterate product before launch.

---

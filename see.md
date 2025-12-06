---
marp: true
theme: custom_doc
paginate: true
style: |
  .doc-title {
    color: #4CAF50;
    font-size: 2.5em;
    font-weight: bold;
    text-shadow: 2px 2px 4px #000000;
  }
  .info-text {
    color: #00796B;
    font-size: 1.2em;
  }
  section {
    padding: 30px;
  }
---

<style>
/* Custom Marp Theme: custom_doc */
@import 'default';

:root {
  --color-background: #F0F4F8; /* Light blue-gray background */
  --color-foreground: #37474F; /* Dark text */
  --color-primary: #00897B; /* Teal accent */
}

section {
  background-color: var(--color-background);
  color: var(--color-foreground);
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

h1, h2, h3 {
  color: var(--color-primary);
  border-bottom: 2px solid var(--color-primary);
  padding-bottom: 5px;
}

/* Page number styling */
footer {
  color: #78909C;
  font-size: 0.8em;
  text-align: right;
  padding: 10px 30px;
}
</style>

# 🚀 Product Documentation Presentation

<p class="doc-title">NextGen Software Platform v2.0</p>

---

# Custom Background Slide

<!-- THIS IS THE CORRECT SYNTAX -->
![bg](/Users/hrithivk/Desktop/IITM/online/45FA21E0-CE2C-42C4-8446-FB127D3B061D_1_105_c.jpeg)

<div style="background: rgba(0,0,0,0.45); padding: 2rem; border-radius: 12px; color: white;">


---


## 📝 Introduction & Purpose

* This documentation provides a technical overview of the **NextGen Platform v2.0 API** features.
* **Target Audience:** Developers, QA Engineers, and Technical Writers.
* **Goal:** Ensure a smooth transition and integration with the new version.

<br>

<p class="info-text">Maintainable in version control (Markdown source) and easily convertible to formats like PDF/HTML.</p>

---

## 🛠️ System Architecture Overview



* The platform uses a **Microservices architecture**.
* **Key Components:**
    * Authentication Service
    * Data Processing Engine
    * Client Gateway (API)
* Communication is handled primarily via **RESTful APIs** and **internal message queues**.

---

## ⚙️ Algorithmic Efficiency

The new search algorithm achieves significant performance improvements.

* **Previous Algorithm Complexity:** Quadratic time complexity.
    $$O(n^2)$$
* **New Algorithm Complexity:** Log-linear time complexity, optimized for large datasets.
    $$O(n \log n)$$
    
<br>

> **Note:** This reduction is crucial for handling millions of concurrent search requests efficiently.

---

## 🌐 API Endpoint Details

<style scoped>
  section {
    color: white; /* Text color change for better contrast on image */
    text-shadow: 1px 1px 3px #000000;
  }
  h2 {
    color: #FFC107; /* Yellow heading */
    border-bottom-color: #FFC107;
  }
  ul {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent background for readability */
    padding: 20px;
    border-radius: 8px;
  }
</style>

* **New Endpoint:** `/api/v2/data/query`
* **Method:** `POST`
* **Purpose:** Enhanced, filtered data retrieval.
* **Rate Limits:** Increased to **500 requests per minute** per user token.

---

## 📧 Contact Information

This document was prepared by the Technical Writing Team.

<p class="info-text">For questions and feedback regarding this documentation:</p>

* **Author Email:** **24f2000717@ds.study.iitm.ac.in**
* **Internal Channel:** `#tech-doc-feedback` on Slack
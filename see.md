---
marp: true
theme: gaia
paginate: true
paginator: true
page_number: true
math: katex
header: "Product Documentation"
footer: "Contact: 24f2000717@ds.study.iitm.ac.in"
class: invert
size: 16:9

# Global custom styling
style: |
  section {
    font-family: "Helvetica Neue", Arial, sans-serif;
    color: #2d3748;
  }
  h1, h2, h3 {
    color: #2b6cb0;
    font-weight: 700;
  }
  footer {
    font-size: 0.75rem;
    color: #718096;
  }
  code {
    background: #f7fafc;
    padding: 2px 6px;
    border-radius: 4px;
  }
---

<!-- Title slide with background image -->
![bg](https://images.unsplash.com/photo-1461749280684-dccba630e2f6?w=1920&h=1080&fit=crop)

# Our Awesome Software  
Product Documentation

**Version 2.4** | Q4 2025  
Technical Writer

---

# Agenda

1. Overview & Architecture
2. Key Features
3. Performance & Algorithmic Complexity
4. Installation & Quick Start
5. API Reference
6. Frequently Asked Questions

---

# Core Features

- **Real-time data processing**
- **End-to-end encryption**
- **Scalable microservices architecture**
- **99.99% uptime SLA**

> Built for enterprises that demand reliability and speed.

---

# Algorithmic Complexity

Our core sorting engine uses **Timsort**-inspired hybrid algorithm.

$$
\begin{aligned}
\text{Best case:}    \quad & \Omega(n) \\
\text{Average case:} \quad & \Theta(n \log n) \\
\text{Worst case:}   \quad & O(n \log n)
\end{aligned}
$$

Auxiliary space complexity:

$$ S(n) = O(n) $$

---

<!-- Slide with a different beautiful background image -->
![bg opacity: 0.25
![bg](https://images.unsplash.com/photo-1518432031352-d6fc5c10da5a?w=1920&h=1080&fit=crop)

# Performance Benchmarks

| Dataset Size | Time (ms) | Memory (MB) | Compared to Python sorted() |
|--------------|-----------|-------------|-----------------------------|
| 100K         | 12        | 8.4         | **2.8× faster**             |
| 1M           | 145       | 92          | **3.1× faster**             |
| 10M          | 1,680     | 980         | **3.4× faster**             |

---

# Quick Start Guide

```bash
# 1. Install via pip
pip install awesome-software==2.4.1

# 2. Import and run
python -c "
from awesome import AwesomeProcessor
p = AwesomeProcessor()
p.run()
"
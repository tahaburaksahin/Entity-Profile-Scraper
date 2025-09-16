# 🏢 Entity Profile Scraper

**Entity Profile Scraper** is a simple Python tool that extracts basic company information (entity profiles) from public web pages such as registries, stock exchanges, or company websites.  

It is designed for research, prototyping, and educational purposes — demonstrating how legal entity profiles can be built using public sources.  

---

## ✨ Features

- Extracts key entity fields:
  - Company name  
  - Address  
  - Registration number  
  - Contact information (if available)  
  - Summary text (first few descriptive paragraphs)  
- Multilingual heuristic parsing (English + Turkish keywords supported)  
- Outputs structured data in **JSON**  
- Lightweight, no heavy dependencies (just `requests` + `beautifulsoup4`)  

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/entity-profile-scraper.git
cd entity-profile-scraper

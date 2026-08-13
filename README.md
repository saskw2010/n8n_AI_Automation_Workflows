# 🤖 Enterprise n8n AI Automation & Document Processing Workflows

![n8n](https://img.shields.io/badge/Automation-n8n%20Workflows-FF6D5A?style=for-the-badge&logo=n8n)
![Google Vision](https://img.shields.io/badge/AI-Google%20Vision%20OCR-4285F4?style=for-the-badge&logo=google)
![Gemini AI](https://img.shields.io/badge/LLM-Gemini%201.5%20Pro-8E44AD?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

> A production-ready repository of **n8n automation workflows** integrating **Google Vision OCR**, **Gemini LLMs**, and automated document processing pipelines for health licenses, PDFs, and data extraction.

---

## 🌟 Included Workflows Matrix

```
┌─────────────────────────────────────────────────────────────┐
│ Document Input (PDFs, Images, Scanned Licenses)             │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ n8n Pipeline: Google Vision OCR Node                       │
└──────────────────────────────┬──────────────────────────────┘
                               │
                               ▼
┌─────────────────────────────────────────────────────────────┐
│ Gemini LLM Data Structuring & JSON Export Engine            │
└─────────────────────────────────────────────────────────────┘
```

- 📄 **Google Vision OCR Pipeline** (`google_vision_workflow.json`): Automated text extraction from multi-page PDFs and images.
- 🏥 **Health License Extraction Engine** (`health_license_extraction.json`): Structured data parsing for medical and health facility licenses.
- ♊ **Gemini LLM Structuring Workflows** (`complete_gemini_workflow.json`): Multi-modal AI workflow formatting un-structured document text into clean JSON schemas.

---

## 📄 License

MIT License.

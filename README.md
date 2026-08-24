<div align="center">

<img src="https://avatars.githubusercontent.com/u/153294101?v=4" width="120" height="120" style="border-radius:50%;" alt="Soumya Ranjan" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=700&height=60&lines=SOUMYA+RANJAN;AI%2FML+Engineer+%E2%80%94+Document+AI+%26+OCR;I+restore+what+scanners+lose.)](https://github.com/SoumyaR01)

<img src="https://komarev.com/ghpvc/?username=SoumyaR01&label=Profile+Views&color=58A6FF&style=flat-square" alt="Profile Views"/>

<p align="center">
  <strong>AI/ML Engineer • Document Restoration • OCR Pipelines • Vision-Language Models</strong>
  <br/>
  <span>IIT Madras Research Park (IITM Pravartak Technologies Foundation) · Chennai, India</span>
</p>

<p align="center">
  <a href="https://soumyar01.github.io"><img src="https://img.shields.io/badge/Portfolio-soumyar01.github.io-58A6FF?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0d1117" alt="Portfolio"/></a>
  <a href="mailto:soumyaranjanbhanja8@gmail.com"><img src="https://img.shields.io/badge/Email-Gmail-58A6FF?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/soumya-ranjan-b385a91b9"><img src="https://img.shields.io/badge/LinkedIn-soumya--ranjan-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117" alt="LinkedIn"/></a>
  <a href="https://github.com/SoumyaR01?tab=repositories"><img src="https://img.shields.io/badge/GitHub-51_Repositories-58A6FF?style=for-the-badge&logo=github&logoColor=0d1117&labelColor=0d1117" alt="GitHub Repos"/></a>
</p>

</div>

---

## 🧭 About Me

I work on the parts of document AI pipelines that fail quietly — a stamp that breaks OCR, a Devanagari glyph a validator scores as an error, a scanned gazette page nobody double-checked. At **IIT Madras Research Park (IITM Pravartak Technologies Foundation)**, I build document restoration, OCR validation, and Vision-Language Model pipelines for large-scale government and institutional document processing.

<br/>

<table>
<tr>
<td width="25%" align="center">
  <strong>🔍 OCR Validation</strong><br/>
  <sub>HOCR-vs-PDF verification across bilingual, degraded scans</sub>
</td>
<td width="25%" align="center">
  <strong>🖼️ Document Restoration</strong><br/>
  <sub>Attention ResUNet & RealESRGAN pipelines for scan recovery</sub>
</td>
<td width="25%" align="center">
  <strong>🌐 Multilingual OCR</strong><br/>
  <sub>English + Devanagari, mixed tables, stamps, gazette layouts</sub>
</td>
<td width="25%" align="center">
  <strong>⚙️ Production Pipelines</strong><br/>
  <sub>Reproducible Python tooling, from ingestion to XLSX reporting</sub>
</td>
</tr>
</table>

---

## 🔬 Current Focus — IITM Pravartak Technologies Foundation

<table width="100%">
<tr>
<td width="50%" valign="top">

### 📄 PDF/HOCR Validation Pipeline
> **Multi-module accuracy validator for large-scale OCR quality assurance.**

- **The Problem:** Automated OCR accuracy scores on Indian Railway Board circulars and gazette notifications were misleading — corrupt Devanagari font layers pushed a document's true ~99.5% accuracy down to an automated score of ~81%.
- **The Solution:** HOCR parsing, PDF text extraction, Tesseract fallback, Indic-language support, bbox normalization, and IoU-based comparison, with results exported to XLSX reports.
- **Stack:** Python · PaddleOCR · Tesseract · OpenCV · OpenPyXL

</td>
<td width="50%" valign="top">

### 🖼️ Document Restoration Models
> **Deep learning pipeline for restoring degraded government scans.**

- **The Problem:** Decades of scanned railway and gazette documents suffer from noise, blur, and contrast loss that standard upscalers can't recover.
- **The Solution:** `DocRestoreNet` (Attention ResUNet) and a fine-tuned RealESRGAN pipeline, iterated across FrequencyLoss/LaplacianLoss variants and an 11-stage CV restoration pipeline (CLAHE, Sauvola binarization, morphological ops).
- **Stack:** PyTorch · RealESRGAN · OpenCV · Google Colab

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧪 OCR Engine Evaluation
> **Benchmarking OCR engines on real-world degraded documents.**

- **The Problem:** No single OCR engine handles degraded scans, mixed English/Devanagari text, tables, and stamps equally well.
- **The Solution:** Comparative evaluation of PaddleOCR (v2→v3 migration), Chandra OCR (vLLM → HuggingFace), and Baidu Unlimited-OCR against Indian railway and gazette documents.
- **Stack:** PaddleOCR · Chandra OCR · HuggingFace · vLLM

</td>
<td width="50%" valign="top">

### 🗂️ Document Taxonomy Normalization
> **Standardizing document classification across government archives.**

- **The Problem:** Raw category labels across archives were inconsistent and unusable for downstream retrieval.
- **The Solution:** Mapped raw labels to a fixed 10-label schema — ACT, RULE, GO, CIRCULAR, MANUAL, NOTIFICATION, ARTICLE, SCHEME, STANDARD, LETTER.
- **Stack:** Python · Pandas

</td>
</tr>
</table>

---

## 🚀 Open Source & Learning

<div align="center">

| Repository | Description | Stack |
|---|---|---|
| [Building-Chatbot-with-Multiple-Tools-like-Langgraph](https://github.com/SoumyaR01/Building-Chatbot-with-Multiple-Tools-like-Langgraph) | RAG chatbot with tool-calling across arXiv, Wikipedia & custom functions | LangGraph · Python |
| [Working-With-FAISS](https://github.com/SoumyaR01/Working-With-FAISS) | Vector similarity search experiments | FAISS · Python |
| [Embedding-Technique-Using-HuggingFace](https://github.com/SoumyaR01/Embedding-Technique-Using-HuggingFace) | Embedding generation workflows | HuggingFace |
| [Pydantic-Base-Model](https://github.com/SoumyaR01/Pydantic-Base-Model) | Structured data validation patterns | Pydantic · Python |
| [lead_scoring_18Dec2023](https://github.com/SoumyaR01/lead_scoring_18Dec2023) | Lead scoring case study | Jupyter · scikit-learn |
| [SoumyaR01.github.io](https://github.com/SoumyaR01/SoumyaR01.github.io) | Personal portfolio site | HTML |

[Browse all 51 repositories on GitHub &rarr;](https://github.com/SoumyaR01?tab=repositories)

</div>

---

## 🛠️ Technical Arsenal

<div align="center">

| Layer | Technologies |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **Deep Learning & CV** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) |
| **Document AI & OCR** | ![PaddleOCR](https://img.shields.io/badge/PaddleOCR-58A6FF?style=flat-square) ![Tesseract](https://img.shields.io/badge/Tesseract-58A6FF?style=flat-square) ![HOCR](https://img.shields.io/badge/HOCR-58A6FF?style=flat-square) ![VLMs](https://img.shields.io/badge/Vision--Language_Models-58A6FF?style=flat-square) |
| **NLP & Agents** | ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![FAISS](https://img.shields.io/badge/FAISS-00758F?style=flat-square) |
| **Data & Reporting** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![OpenPyXL](https://img.shields.io/badge/OpenPyXL-58A6FF?style=flat-square) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square) |
| **Tooling** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) |

</div>

---

## 📈 GitHub Stats

<div align="center">

<img src="https://raw.githubusercontent.com/SoumyaR01/SoumyaR01/main/generated/overview.svg" alt="Soumya's GitHub Stats" width="48%"/>
<img src="https://raw.githubusercontent.com/SoumyaR01/SoumyaR01/main/generated/languages.svg" alt="Top Languages" width="48%"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SoumyaR01/SoumyaR01/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SoumyaR01/SoumyaR01/output/github-contribution-grid-snake.svg"/>
  <img src="https://raw.githubusercontent.com/SoumyaR01/SoumyaR01/output/github-contribution-grid-snake.svg" width="100%" alt="Contribution Snake"/>
</picture>


</div>

---

## 🤝 Connect

I'm open to collaborating on document AI, OCR, and computer vision projects.

<div align="center">

<a href="mailto:soumyaranjanbhanja8@gmail.com"><img src="https://img.shields.io/badge/Send_an_Email-Gmail-58A6FF?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117" alt="Email"/></a>
<a href="https://www.linkedin.com/in/soumya-ranjan-b385a91b9"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-soumya--ranjan-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117" alt="LinkedIn"/></a>
<a href="https://bsky.app/profile/SoumyaR01"><img src="https://img.shields.io/badge/Follow_on_Bluesky-@SoumyaR01-0285FF?style=for-the-badge&logo=bluesky&logoColor=white&labelColor=0d1117" alt="Bluesky"/></a>

</div>

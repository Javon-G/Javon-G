# Hi, I'm Javon Garcia 👋

**Computer Science student at the University of Tennessee, Knoxville** (Honors College, May 2028). I build AI-powered document-processing tools for UT Libraries' digital archives.

I'm looking for **Summer 2027 software engineering internships and co-ops**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-javon--garcia-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/javon-garcia)
[![Email](https://img.shields.io/badge/Email-jgarci51%40vols.utk.edu-FF8200?logo=gmail&logoColor=white)](mailto:jgarci51@vols.utk.edu)

---

## 🔭 What I'm building

**Digital Production Lab, University of Tennessee Libraries** (Aug 2026 – present)
I'm on a 7-developer team that digitizes and preserves UT's theses and dissertations. My work lives in the lab's public repo, [**utkdigitalinitiatives/td-processing**](https://github.com/utkdigitalinitiatives/td-processing): 72 commits and about 11,000 lines of Python and JavaScript so far.

### 🖥️ [OCR Pipeline Studio](https://github.com/utkdigitalinitiatives/td-processing/tree/main/ocr_pipeline_studio)
A desktop app that turns scanned theses into clean, reviewed text. I built it so the lab's student staff could stop running scripts from a terminal.

- Drag-and-drop intake, **duplicate-page detection** (fuzzy text matching), automatic **rotation correction**, OCR, and a **live-preview editor**
- Used by the lab's 10 student staff to process **~1,000 theses in its first week**
- Cut per-file review and editing from **~15 minutes to ~2 minutes** (87% faster)

`Python` `Flask` `pywebview` `PyMuPDF` `RapidFuzz` `PaddleOCR` `JavaScript`

### 📄 [auto_abstract](https://github.com/utkdigitalinitiatives/td-processing/tree/main/auto_abstract) *(co-author)*
Extracts abstracts from scanned theses. PaddleOCR reads the pages, then a **Qwen vision-language model** reviews and consolidates the output. The model runs **locally through Ollama** with CUDA, so unpublished theses never leave university machines.

`Python` `PaddleOCR` `Ollama` `Qwen VLM` `CUDA`

### ⚡ Performance work
Optimizations I made across the pipeline, measured on a 50-file batch:

| Workflow | Before | After | Improvement |
|---|---|---|---|
| OCR only | 12m 51s | 3m 52s | **3.3× faster** |
| OCR + VLM | 52m 30s | 36m 05s | **31% faster** |
| OCR + VLM + dedupe + rotation | 1h 16m 32s | 43m 18s | **43% faster** |

---

## 🧰 Tech stack

**Languages:** Python · JavaScript · C++ · HTML/CSS · PowerShell
**AI & document processing:** PaddleOCR · PyMuPDF · Ollama · Qwen VLM · Anthropic Claude API · CUDA
**Web & tools:** Flask · Node.js · Express · REST APIs · Google OAuth · AWS · Git/GitHub

---

## 🕰️ Earlier work

**St. Jude / ALSAC with CodeCrew, Memphis** (2018 – 2020)
I was on a small student dev team that built interactive fundraising apps with Node.js and AWS. That included the **St. Jude Art augmented-reality app**, which brings patient-art murals at five Memphis landmarks to life with each patient's story and a way to donate.

---

## 🤝 Outside the code

President of the **Beta Kappa Chapter of Lambda Phi Epsilon** at UT. I led the largest new member class in the history of UT's Multicultural Greek Council, and I've run cultural events with 50+ campus organizations and 300+ students.

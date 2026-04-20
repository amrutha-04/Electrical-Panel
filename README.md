# ⚡ Microgrid Panel Designer

Microgrid Panel Designer is a desktop-based application designed to streamline electrical panel design and documentation.

---

## 📌 Overview

This tool enables engineers to efficiently configure low-voltage panel parameters and generate complete design outputs within a single workflow. It integrates electrical calculations, diagram generation, and export functionalities to minimize manual effort and enhance design accuracy.

---

## 🚀 Key Features

- Automated current calculation and busbar sizing  
- Generation of Single Line Diagrams (SLD)  
- Creation of General Arrangement (GA) drawings  
- Automatic Bill of Materials (BOM) generation  
- Export options for:
  - PDF reports  
  - GA drawings  
  - BOM in Excel format  

---

## 🖥️ Technology Stack

The application is built using **pywebview**, combining:
- Python backend for core logic
- Web-based frontend for UI

This approach ensures a lightweight yet efficient desktop experience while maintaining centralized processing.

---

## 🏗️ System Architecture

The application follows a layered architecture:

1. **Application Entry Point** (`main.py`)  
2. **API Communication Layer** (`api/bridge.py`)  
3. **Core Processing Modules** (`core/`)  
4. **Business Logic Layer** (`src/`)  
5. **User Interface** (`ui/`)  

For detailed insights into system flow and module interactions, refer to:
- `architecture.md`

---

## ⚙️ Getting Started

### Install dependencies
```bash
pip install -r requirements.txt

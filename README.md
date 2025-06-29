# 4PL/EDI Integration SaaS (MVP)

**Automate logistics workflows with no-code EDI mapping and pre-built carrier/ERP integrations.**  
Built for SMBs to simplify complex supply chain data exchanges.

---

## 🚀 Core Features
- **No-Code EDI Mapper**  
  Drag-and-drop UI to transform data between formats (EDI X12, CSV, JSON) with pre-loaded templates.
- **Pre-Built Integrations**  
  FedEx, UPS, Shopify, and QuickBooks support out of the box.
- **Unified Dashboard**  
  Real-time view of shipments, orders, and error alerts.
- **Automation Rules**  
  "If X, then Y" workflows (e.g., auto-send tracking emails).

---

## 🛠️ Tech Stack
| Component       | Technology              |
|-----------------|-------------------------|
| Backend         | Python + FastAPI        |
| Database        | PostgreSQL              |
| Integration     | Celery + Redis (async)  |
| Frontend        | React (or Retool for MVP) |
| Auth            | Firebase/JWT            |
| Hosting         | AWS/GCP (Docker-ready)  |

---

## 📦 Installation
1. **Backend Setup**:
   ```bash
   git clone https://github.com/your-repo/4pl-edi-saas.git
   cd backend
   pip install -r requirements.txt
   uvicorn main:app --reload

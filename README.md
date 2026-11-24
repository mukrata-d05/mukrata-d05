<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&pause=800&color=00cc00&center=true&vCenter=true&multiline=true&width=600&height=80&lines=Hi+There!+%F0%9F%91%8B+I'm+Piyawat+Ounruen" alt="Hi, I'm Piyawat Ounruen" />
</p>

<p align="center">
  <b>ERP data · Data pipelines · Data quality · Dashboards</b><br/>
  📍 Lamphun, Thailand · ✉️ <a href="mailto:piyawat.dreamd@gmail.com">piyawat.dreamd@gmail.com</a>
</p>

----------------------------------------

I work with real operational data at a food manufacturer. I take messy data from the ERP, Google Sheets and customer files, check it for errors, and turn it into tools and reports that the sales and purchasing teams, and staff in every department, use every day.


## 🧭 What I do · งานที่ผมทำ

| | Area | What it means in practice |
|---|---|---|
| 🔄 | **Data pipelines** | Pull data from the ERP database, Google Sheets and Excel/CSV/PDF files, then clean and load it automatically |
| ✅ | **Data quality** | Catch bad rows before they reach a report, and reconcile every number against the figures the team already trusts |
| 📊 | **Dashboards** | Build dashboards that answer the team's daily questions: stock on hand, defects in baht, sales trends |
| 🔗 | **ERP integration** | Connect the ERP with the tools people already use (Google Sheets, web forms, company chat) through its API |

## 🛠️ How my data flows · เส้นทางของข้อมูล

```mermaid
flowchart LR
    subgraph S["Sources"]
        A[("ERP database")]
        B["Google Sheets"]
        C["Customer files<br/>Excel · CSV · PDF"]
    end
    subgraph P["Python"]
        D["Extract"] --> E["Clean & normalise"] --> F{"Validate &<br/>reconcile"}
    end
    subgraph O["Outputs"]
        G["Streamlit dashboards"]
        H["Looker Studio"]
        I["ERP via API"]
        J["Data-error reports"]
    end
    S --> D
    F --> G & H & I
    F -.->|rows to fix| J
```

## 🗂️ Projects · ผลงาน

> 🔒 Internal company projects: the code and data stay private. Each page covers the problem, the approach, the data flow and the results, with no company or customer data.

**Data Engineering**

| Project | Problem → Result |
|---|---|
| 🧾 [**Purchase-Order Validation → ERP**](projects/02-purchase-order-validation.md) | POs were retyped by hand from many customer formats → **32 formats** from 20+ customers (incl. OCR for image PDFs) read, checked against agreed prices, and sent to the ERP after one confirmation |
| 🔁 [**Monthly Retail Sales Pipeline**](projects/04-retail-sales-pipeline.md) | Monthly files were copy-pasted into the dashboard sheet → one command, **safe to re-run**, no duplicates |
| 🗄️ [**ERP Sales Data Quality**](projects/03-erp-sales-data-quality.md) | Bad ERP records reached reports unnoticed → repeatable checks before any KPI is built |

**Data Analysis & Dashboards**

| Project | Problem → Result |
|---|---|
| 📦 [**Finished-Goods Stock Dashboard**](projects/01-stock-dashboard.md) | Stock was checked by filtering a sheet by hand → stock by SKU and lot, **100% reconciled**, with entry errors flagged by row |
| 🏭 [**Production QC Loss Dashboard**](projects/05-qc-loss-dashboard.md) | Defects were tracked only as piece counts → defects shown **in baht**, with Pareto charts of top causes and products |

**ERP Integration & Automation**

| Project | Problem → Result |
|---|---|
| 📥 [**PO Email Inbox Bot**](projects/07-po-email-inbox-bot.md) | PO emails were mixed with invoices and easy to miss → a bot that sorts **7 kinds** of PO email into one shared list, with chat alerts and status synced from the ERP |
| 🧮 [**Marketplace Orders → Accounting POs**](projects/08-marketplace-orders-to-accounting.md) | Every online purchase was retyped into the accounting software → receipts and screenshots become **draft POs in a few clicks** via the accounting API, with a backlog cleaner |
| 🛒 [**Purchase Request Tools**](projects/06-purchase-request-tools.md) | ERP screens were hard for occasional users → a simple PR form **used by every department**, plus a Kanban/chat-approval prototype |

## 🧰 Tools by stage · เครื่องมือตามขั้นตอนงาน

**Extract**<br/>
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-%23336791.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Google Sheets API](https://img.shields.io/badge/Google%20Sheets%20API-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)

**Clean & validate**<br/>
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-%230A9EDC.svg?style=for-the-badge&logo=pytest&logoColor=white)
![Jupyter](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

**Visualise**<br/>
![Streamlit](https://img.shields.io/badge/Streamlit-%23FF4B4B.svg?style=for-the-badge&logo=Streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker%20Studio-%234285F4.svg?style=for-the-badge&logo=Looker&logoColor=white)

**Integrate & automate**<br/>
![Odoo](https://img.shields.io/badge/Odoo%20API-%23714B67.svg?style=for-the-badge&logo=Odoo&logoColor=white)
![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-%234285F4.svg?style=for-the-badge&logo=Google%20Apps%20Script&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Chrome Extension](https://img.shields.io/badge/Chrome%20Extension-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![Tesseract OCR](https://img.shields.io/badge/OCR-Tesseract-5A5A5A?style=for-the-badge)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

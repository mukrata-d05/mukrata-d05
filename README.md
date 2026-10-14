# 👋 สวัสดีครับ · Hi, I'm PIYAWAT OUNRUEN

**Data Engineer / Data Analyst** · ทำงานกับข้อมูลจริงในโรงงานผลิตอาหาร ตั้งแต่ดึงข้อมูลจาก ERP และ Google Sheets ไปจนถึง Dashboard ที่ทีมใช้ทุกวัน

**Data Engineer / Data Analyst** working with real operational data at a food manufacturer, from ERP and Google Sheets extraction to dashboards that teams use every day.

📧 [piyawat.dreamd@gmail.com](mailto:piyawat.dreamd@gmail.com) · 📍 Lamphun, Thailand

> 🔒 **หมายเหตุ:** โปรเจกต์ทั้งหมดเป็นงานภายในองค์กร โค้ดและข้อมูลจริงจึงเก็บเป็นส่วนตัว
> หน้านี้อธิบายปัญหา วิธีคิด ขั้นตอน และผลลัพธ์ โดยไม่เปิดเผยข้อมูลของบริษัทหรือลูกค้า
>
> 🔒 **Note:** These are internal company projects, so the code and real data stay private.
> This page covers the problem, the thinking, the process and the results, without revealing any company or customer data.

---

## 🗂️ ผลงาน · Projects

| | โปรเจกต์ · Project | สิ่งที่ทำ · What it does | ทักษะเด่น · Highlights |
|---|---|---|---|
| 📦 | [**Finished-Goods Stock Dashboard**](projects/01-stock-dashboard.md) | Dashboard สต็อกราย SKU และราย LOT พร้อมหน้าตรวจหาแถวที่กรอกผิด · Stock by SKU/lot with a data-error finder | ETL, data validation, reconciliation, Streamlit, OAuth |
| 🧾 | [**Purchase-Order Validation → ERP**](projects/02-purchase-order-validation.md) | อ่าน PO จากลูกค้า 17 รูปแบบ ตรวจ แล้วส่งเข้า ERP · Normalise 17 customer PO formats, validate, push to ERP | Multi-format ingestion, adapter pattern, validation rules, API |
| 🗄️ | [**ERP Sales Data Quality**](projects/03-erp-sales-data-quality.md) | ดึงยอดขายจากฐานข้อมูล ERP ตรวจคุณภาพ ทำ KPI · Extract ERP sales, profile, build KPIs | SQL, PostgreSQL, SSH tunnel, data profiling |
| 🔁 | [**Monthly Retail Sales Pipeline**](projects/04-retail-sales-pipeline.md) | Clean ไฟล์ยอดขายรายเดือน แล้วส่งขึ้น Looker Studio · Clean monthly retailer files into Looker Studio | Idempotent pipeline, dedup, testing |
| 🏭 | [**Production QC Loss Dashboard**](projects/05-qc-loss-dashboard.md) | แปลงของเสียจากการผลิตเป็นมูลค่าเงินบาท · Turn production defects into baht | Analytics, Pareto, data-gap transparency |
| 🛒 | [**Purchase Request Tools**](projects/06-purchase-request-tools.md) | ฟอร์มเปิดใบขอซื้อ + Kanban อนุมัติผ่านแชต · PR form + Kanban with chat approvals | ERP API, Google Apps Script, FastAPI |

---

## 🧰 ทักษะ · Skills

| ด้าน · Area | เครื่องมือ · Tools |
|---|---|
| ภาษา · Languages | Python, SQL, JavaScript (Google Apps Script) |
| ข้อมูล · Data | pandas, openpyxl, pdfplumber, Jupyter |
| ฐานข้อมูลและ ERP · Databases & ERP | PostgreSQL, Odoo (JSON-RPC API), SSH tunnelling |
| Dashboard / BI | Streamlit, Plotly, Looker Studio |
| คลาวด์และการเชื่อมต่อ · Cloud & integration | Google Sheets / Drive API, OAuth 2.0, Service Accounts, Lark API, FastAPI |
| วิธีทำงาน · Practices | Git / GitHub, pytest, secrets management, data validation & reconciliation |

---

<sub>ภาพการไหลของข้อมูลในแต่ละหน้าวาดด้วย Mermaid และแสดงผลบน GitHub ได้โดยตรง · Data-flow diagrams are Mermaid and render directly on GitHub.</sub>

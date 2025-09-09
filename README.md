# Modernes Data Warehouse mit Medaillon-Architektur

Dieses Projekt zeigt, wie ein modernes Data Warehouse nach der **Medallion-Architektur** aufgebaut wird – mit klar getrennten **Bronze**, **Silver** und **Gold**-Schichten – von CSV-Quellen (ERP & CRM) 
<img width="1390" height="657" alt="Data_Flow" src="https://github.com/user-attachments/assets/6a5511ad-c260-411f-9a1f-c037b745310f" />
<sub><b>Abb. 1 – Dataflow:</b> CSV → Bronze (Raw) → Silver (Cleansed) → Gold (Business) mit <code>fact_sales</code>, <code>dim_customers</code>, <code>dim_products</code>.</sub>
<img width="1456" height="707" alt="How_tables_are_related" src="https://github.com/user-attachments/assets/eebcbcb6-9682-4f18-afff-741c04bec52d" />
<img width="1366" height="526" alt="Star Schema" src="https://github.com/user-attachments/assets/fb89a219-fc90-40bf-8f08-27592befa272" />

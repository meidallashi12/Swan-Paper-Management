# Swan Paper Fabrics — Operations Management System

<p align="center">
  <img src="https://img.shields.io/badge/Status-In%20Development-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Database-SQL%20%2F%20PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Scale-Medium%20Enterprise-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Industry-Tissue%20Paper%20Manufacturing-lightgrey?style=for-the-badge" />
</p>

---

Swan Paper Fabrics is a medium-scale tissue paper manufacturer running multiple production lines, a live supply chain, and a workforce that needs clear direction every shift. SPF-OMS is the management system built to match that complexity — a structured, relational database solution that connects every operational layer of the facility into one coherent source of truth.

The system covers the full production lifecycle: materials arrive, get logged against suppliers, move through the line, and exit as finished goods tied to a specific batch, machine, and shift. Nothing moves without a record, and every record connects back to the people and resources behind it.

Inventory, sales orders, workforce scheduling, and outbound logistics are all modeled within the same database, meaning a delay on the floor surfaces immediately in fulfillment, and a low stock alert ties directly back to the relevant supplier. The relationships between departments are not implied — they are enforced at the data level.

Reporting is built into the system rather than bolted on. Pre-written views and stored procedures produce the numbers management needs — yield rates, stock turnover, delivery performance, cost per unit — without anyone assembling them by hand.

SPF-OMS was designed with one principle in mind: every operation the facility runs should be visible, traceable, and impossible to lose.

# User Cards 

A structured set of user cards covering all 12 stakeholders in the Swan Paper Management system. Each card defines the stakeholder's goal, operational context, pain points, and key scenarios.

---

## UC-01 - Board of Directors

| Field | Detail |
|---|---|
| **Role** | Board of Directors |
| **Domain** | Executive |
| **Goal** | Maintain strategic oversight of manufacturing performance, capital allocation, and executive accountability across the organisation. |
| **Context** | Operates at the highest governance level, reviewing aggregated reports quarterly. Does not interact with day-to-day operations but holds ultimate accountability for the company's direction and financial health. |

**Pain Points**
- Limited visibility into operational KPIs without timely, consolidated reporting
- Difficulty assessing capex ROI without standardised evaluation frameworks
- Risk of misaligned strategy if ESG and compliance data is not surfaced clearly

**Key Scenarios**
- When the annual ESG report is submitted, the Board reviews Scope 1 and 2 emission trends and approves updated sustainability targets.
- When a major capex proposal is escalated by the CFO, the Board evaluates the NPV analysis and votes on capital allocation.
- When executive KPI dashboards are presented at a quarterly meeting, the Board challenges underperformance and sets accountability actions.

---

## UC-02 - Chief Executive Officer (CEO)

| Field | Detail |
|---|---|
| **Role** | Chief Executive Officer |
| **Domain** | Executive |
| **Goal** | Drive overall company strategy, align cross-functional performance, and maintain investor and stakeholder confidence. |
| **Context** | Sits at the top of the operational hierarchy, translating board direction into organisational priorities. Relies on consolidated reporting from all functional heads to monitor company health. |

**Pain Points**
- Fragmented reporting across departments makes cross-functional alignment difficult
- Inability to quickly identify which operational area is driving a margin decline
- ESG and regulatory changes require rapid strategic response with incomplete data

**Key Scenarios**
- When a pulp price spike threatens margins, the CEO convenes an emergency cross-functional review to adjust sourcing and pricing strategy.
- When the monthly board pack is prepared, the CEO reviews P&L, OEE trends, safety performance, and ESG scorecard before the board meeting.
- When EUDR regulatory changes are announced, the CEO leads a strategic review of the fibre sourcing policy with the CSCO and ESG lead.

---

## UC-03 - Chief Operating Officer (COO)

| Field | Detail |
|---|---|
| **Role** | Chief Operating Officer |
| **Domain** | Executive |
| **Goal** | Ensure day-to-day manufacturing, quality, and logistics operations meet output, cost, and safety targets. |
| **Context** | Acts as the operational nerve centre, receiving daily KPI reports from the Plant Manager, QA Manager, and Chief Engineer. Chairs the weekly operations review and escalates critical issues to the CEO. |

**Pain Points**
- Unplanned downtime events are often reported reactively rather than flagged early
- Lack of unified view across OEE, quality, and cost makes root-cause analysis slow
- Maintenance backlog growth is not always visible until it causes a production impact

**Key Scenarios**
- When the weekly operations review is due, the COO chairs a cross-functional meeting covering OEE, yield, cost-per-tonne, quality KPIs, and safety metrics.
- When a key customer requests an urgent order pull-forward, the COO approves a production schedule change and coordinates with logistics.
- When a site audit reveals ISO 45001 non-conformances, the COO authorises a corrective action plan and assigns accountability to the HR & HSE Manager.

---

## UC-04 - Chief Financial Officer (CFO)

| Field | Detail |
|---|---|
| **Role** | Chief Financial Officer |
| **Domain** | Executive |
| **Goal** | Maintain financial health through sound budgeting, cost accounting, treasury management, and accurate reporting. |
| **Context** | Oversees the Finance Controller and interfaces with all functional heads on cost management. Presents financial performance to the Board and CEO, and approves significant capex and procurement decisions. |

**Pain Points**
- Cost-per-tonne visibility is inconsistent across production lines without a daily cost flash
- Capex proposals often lack rigorous NPV and payback analysis, making approval decisions difficult
- Working capital fluctuations driven by pulp price volatility are hard to forecast accurately

**Key Scenarios**
- When month-end closes, the CFO reviews the P&L with the Finance Controller and challenges margin compression on Away-From-Home SKUs.
- When the Finance Controller raises an adverse purchase price variance, the CFO escalates to the CSCO and requests a sourcing review.
- When Engineering submits a capex request for a new wire section, the CFO reviews the DCF model and approves or rejects the proposal.

---

## UC-05 - Chief Supply Chain Officer (CSCO)

| Field | Detail |
|---|---|
| **Role** | Chief Supply Chain Officer |
| **Domain** | Executive |
| **Goal** | Manage end-to-end supply chain performance, vendor relationships, and material flow to ensure uninterrupted production. |
| **Context** | Leads the Procurement Manager and coordinates with the Plant Manager and CFO on material availability and cost. Responsible for strategic sourcing decisions and supply chain risk management. |

**Pain Points**
- Single-source supplier dependencies create vulnerability to lead time disruptions
- Fibre blend changes driven by ESG targets require re-costing of all affected SKUs
- Purchase price variance reports are often available too late to inform buying decisions

**Key Scenarios**
- When a primary chemicals supplier fails a quality audit, the CSCO directs the Procurement Manager to initiate an alternative supplier qualification.
- When ESG targets are revised, the CSCO approves a shift in fibre sourcing mix and coordinates re-costing with the Finance Controller.
- When monthly supply chain KPIs are reviewed, the CSCO presents material flow performance and vendor scorecard results to the COO.

---

## UC-06 - Plant Manager

| Field | Detail |
|---|---|
| **Role** | Plant Manager |
| **Domain** | Operations |
| **Goal** | Maximise on-site production performance while ensuring safety, quality, and team accountability across all shifts. |
| **Context** | Manages the full production site on a 24/7 basis, coordinating across 4-crew rotating shifts. Receives daily OEE, quality, and safety reports and escalates issues to the COO. Acts as the primary accountability point for the site. |

**Pain Points**
- OEE degradation on individual machines is often identified late due to manual reporting delays
- Crew performance inconsistencies across shifts are difficult to track without a structured skills matrix
- Broke accumulation spikes are not always connected back to a specific upstream quality issue

**Key Scenarios**
- When a tissue machine falls below the 78% OEE threshold, the Plant Manager flags the issue at shift handover and assigns a root-cause investigation to the Chief Engineer.
- When a broke accumulation spike occurs, the Plant Manager escalates to the QA Manager to investigate a potential upstream tensile strength deviation.
- When next month's shift plan is submitted by HR, the Plant Manager reviews and approves the 4-crew rotation schedule.

---

## UC-07 - Procurement Manager

| Field | Detail |
|---|---|
| **Role** | Procurement Manager |
| **Domain** | Operations |
| **Goal** | Ensure timely, cost-effective procurement of fibre, chemicals, packaging, and energy while managing supplier risk. |
| **Context** | Manages day-to-day purchasing workflows and vendor relationships. Uses ABC/XYZ inventory classification to set safety stock levels and monitors purchase price variance to control costs. |

**Pain Points**
- Supplier lead time volatility makes safety stock calibration difficult, especially for virgin pulp
- Spot-buy decisions under supply disruption are made without sufficient market price visibility
- Supplier qualification processes are slow when a replacement vendor is needed urgently

**Key Scenarios**
- When the ABC/XYZ classification is updated, the Procurement Manager reviews safety stock levels for fibre ahead of seasonal demand peaks.
- When the primary jumbo roll core supplier reports a 3-week delay, the Procurement Manager triggers an emergency spot-buy from an approved alternate.
- When a 12% adverse movement appears in the packaging cost variance report, the Procurement Manager escalates the finding to the CFO with a sourcing recommendation.

---

## UC-08 - QA Manager

| Field | Detail |
|---|---|
| **Role** | QA Manager |
| **Domain** | Operations |
| **Goal** | Maintain product quality standards aligned with ISO 9001 and EN 12625, and manage non-conformances through structured CAPA processes. |
| **Context** | Oversees in-line and finished goods quality management across all production lines. Manages the QA Technician team and interfaces with the Plant Manager, Finance Controller, and customers on quality issues. |

**Pain Points**
- SPC drift alerts are sometimes acted on too slowly due to lack of direct line to the production supervisor
- NCR documentation is inconsistent when raised by shift teams rather than QA staff
- Customer complaints linked to specific production lots require rapid traceability that manual systems cannot always support

**Key Scenarios**
- When a batch fails EN 12625 absorbency testing, the QA Manager opens an NCR, places the batch on hold, and assigns a CAPA owner.
- When SPC charts show a process drift on tissue machine 3, the QA Manager flags the deviation to the Plant Manager and requests a machine inspection.
- When a customer requests a Certificate of Analysis, the QA Manager prepares the traceability documentation pack for the relevant production lot.

---

## UC-09 - Chief Engineer

| Field | Detail |
|---|---|
| **Role** | Chief Engineer |
| **Domain** | Operations |
| **Goal** | Ensure asset reliability through structured preventive and predictive maintenance, and manage capex projects effectively. |
| **Context** | Leads the maintenance team and owns the TPM programme. Responsible for annual shutdown planning, spare parts policy, and energy management. Presents maintenance KPIs and capex proposals to the COO and CFO. |

**Pain Points**
- Overdue PM work orders accumulate when production pressure deprioritises scheduled maintenance
- Predictive maintenance sensor alerts are not always actioned before they escalate to unplanned downtime
- Shutdown planning is complex when cross-functional dependencies between maintenance tasks are not mapped

**Key Scenarios**
- When the weekly PM compliance report shows overdue work orders, the Chief Engineer escalates to maintenance team leads and adjusts the schedule.
- When a vibration sensor flags an anomaly on the press section, the Chief Engineer investigates and decides whether to schedule an immediate intervention or monitor.
- When Engineering submits a capex proposal for a new creping blade auto-changer, the Chief Engineer prepares the NPV and payback analysis for CFO review.

---

## UC-10 - HR & HSE Manager

| Field | Detail |
|---|---|
| **Role** | HR & HSE Manager |
| **Domain** | Support |
| **Goal** | Ensure workforce capability, safety compliance, and labour relations across 24/7 rotating shift operations. |
| **Context** | Manages the skills matrix, incident reporting, and shift scheduling. Responsible for ISO 45001 compliance and succession planning. Interfaces with the Plant Manager, COO, and shift team leaders on workforce issues. |

**Pain Points**
- Skills gaps on specific shifts are not visible until a machine changeover exposes an under-qualified operator
- Incident reporting is inconsistent across shifts, making trend analysis unreliable
- Succession planning is reactive rather than proactive due to limited visibility of competency development progress

**Key Scenarios**
- When three operators complete a tissue machine wet-end certification, the HR & HSE Manager updates the skills matrix and notifies the Plant Manager.
- When a lost-time incident occurs, the HR & HSE Manager opens an investigation, prepares the RIDDOR report, and presents root-cause findings to the COO.
- When the quarterly succession planning review is due, the HR & HSE Manager identifies key-person risk on the night shift and proposes a development plan.

---

## UC-11 - Sales & Marketing Director

| Field | Detail |
|---|---|
| **Role** | Sales & Marketing Director |
| **Domain** | Support |
| **Goal** | Manage customer relationships, drive revenue growth, and align product pricing and channel strategy with operational capabilities. |
| **Context** | Acts as the primary interface between the market and internal operations. Relies on production scheduling visibility to manage customer commitments, and on Finance for margin analysis by SKU and channel. |

**Pain Points**
- Production schedule changes made without sales input lead to missed customer delivery commitments
- Pricing decisions are made without real-time cost-per-tonne visibility, compressing margins unintentionally
- Customer quality complaints are not always communicated back to QA quickly enough to prevent recurrence

**Key Scenarios**
- When a key retail customer requests an expedited order, the Sales Director coordinates with the COO to assess schedule feasibility before confirming.
- When a new product SKU is proposed, the Sales Director works with the Finance Controller to model the margin impact before committing to a launch.
- When a customer quality complaint is received, the Sales Director logs the issue and routes it to the QA Manager with the production lot reference.

---

## UC-12 - Finance Controller

| Field | Detail |
|---|---|
| **Role** | Finance Controller |
| **Domain** | Support |
| **Goal** | Deliver accurate product costing, variance analysis, and management reporting to support operational and financial decision-making. |
| **Context** | Reports to the CFO and works closely with the Plant Manager, Procurement Manager, and QA Manager to capture cost data accurately. Produces daily, weekly, and monthly reporting across variable cost categories. |

**Pain Points**
- Daily cost flash is only as accurate as the production and consumption data entered by shift teams
- Standard cost models become stale quickly when fibre blend or chemical formulations change
- Variance explanations require cross-referencing multiple data sources, slowing down month-end reporting

**Key Scenarios**
- When the daily production data is submitted, the Finance Controller produces the cost flash report showing cost-per-tonne by line against standard.
- When the fibre blend changes, the Finance Controller updates the standard cost model and recalculates product costs for all affected SKUs.
- When month-end closes, the Finance Controller runs variance analysis and prepares explanations for all material adverse movements for the CFO.

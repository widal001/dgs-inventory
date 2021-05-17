# Integrify

## Overview

### Description
A cloud-based workflow automation software used by the Business Process Improvement Office to promote paperless workflow processes within the agency and record information about these workflows for future analysis.

### Subject Matter Experts
- **Vendor:** Integrify (for support log a ticket at https://support.integrify.com)
- **DGS - Business:** Babila Lima
- **DGS - Technical:** Jason Jozwiak
- **ISMT:** Olufunso Adewumi, Francine Kane
- **BCIT:** Sri Perivilli

### Divisions using system
- All Divisions and Business Units
- Facilities
- Fleet
- CP&E
- BPIO
- HR

## Business Details

### Relevant KPIs or reporting requirements
<This might be a question for the Business SME>

- {KPI 1}
- {KPI 2}

### Relevant Business Processes
<The goal of this is to provide examples of what operations this system supports>

#### Finance Workflows

|Process|Description|
|-------|-----------|
| **Office Supply Purchasing** | **Administration -> Processes -> Finance Workflows -> Office Supply Purchasing Request** <br/> A process where users can submit an order for office supplies. The requests are routed to Accounts Payable who submit the order on behalf of the requester.|
| **HVAC Invoices** | **Administration -> Processes -> Invoices Processes -> HVAC** <br/> The invoice approval workflow for HVAC related invoices. Once invoices are approved they trigger a child process (AP Invoice Processing) where an AP Analyst is assigned to process the invoice for payment through CitiBuy. |
| **FMD Invoices** | **Administration -> Processes -> Invoices Processes -> FMD -> Facilities Urgent Work Order Invoice** <br/> The invoice approval workflow for Facilities Maintenance. Approved invoices trigger the AP Invoice Processing workflow.|
| **Energy Office Invoices** | **Administration -> Processes -> Invoices Processes -> Energy -> Energy Invoice Submission and Approval** <br/> The invoice approval workflow for any Energy office invoices. Approved invoices trigger the AP Invoice Processing workflow. |
| **General Invoices** | **Administration -> Processes -> Invoices Processes -> FMD -> General Invoice Submission and Approval** <br/> The invoice approval workflow for any invoices not in HVAC, FMD, or Energy. Approved invoices trigger the AP Invoice Processing workflow. |
| **AP Invoice Processing** | **Administration -> Processes -> Invoices Processes -> AP -> AP Invoice Processing** <br/> The invoice processing workflow for Accounts Payable. All other invoice processes filter into this process and are its parent process. |
| **Change Order Process** | **Administration -> Processes -> Finance Workflows -> Change Order Request** <br/> Process used to request change orders from Fiscal. |
| **P-Card Process** | **Administration -> Processes -> Finance Workflows -> P Card** <br/> Process used to request payment for services using the agency's P-Card |

#### Human Resources Workflows

|Process|Description|
|-------|-----------|
| **HR Routing Form** ||
| **Position Description Approval** ||

## Administration

### Access
- **System Admin:** Jason Jozwiak
- **Level of Access for BPIO:**
    - Full access for BPIO

### Documentation
- **User Guide:** <link to user guide>
- **ERD:** <link to ERD>
- **Data Dictionary:** <Link to data dictionary>
- **Steps to Access**

### Common Reports
- <Jason will add these>
- <Jason will add these>

## Budgetary Details

### Contract
- **License Type:** <Choose an option below>
    - Free subscription
    - Paid Subscription (Monthly)
    - Paid Subscription (Annually)
    - Desktop Software
    - Custom Built Software
- **Renewal Date (if applicable):**

### Cost
- **Total Subscription Cost:** <Annual Cost>
- **Cost Per License:** <Annual Cost>
- **Maintenance Cost:** <Estimated Cost>

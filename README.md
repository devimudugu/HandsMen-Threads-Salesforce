# HandsMen Threads – Salesforce CRM Project
## Project Overview

**HandsMen Threads** is a Salesforce CRM implementation for a premium men's fashion and bespoke tailoring business. The solution centralizes customer, product, order, inventory and marketing information while improving data quality, customer communication, security and operational efficiency.

## Business Requirements

- **Automated Order Confirmations:** send an automated email after an order reaches the configured confirmation state.
- **Dynamic Loyalty Program:** maintain customer loyalty status based on purchase history.
- **Proactive Stock Alerts:** notify the warehouse/operations team when stock falls below five units.
- **Scheduled Bulk Order Updates:** process bulk orders daily at midnight and update the required financial and inventory information.

## Salesforce Features Covered

- Data Modelling
- Data Quality / Validation
- Custom Objects and Fields
- Custom Tabs
- Lightning App / App Manager
- Profiles
- Roles and Role Hierarchy
- Users
- Permission Sets
- Email Templates
- Email Alerts
- Record-Triggered Flows
- Apex
- Apex Triggers
- Asynchronous Apex
- Batch Jobs
- Scheduled Processing
- Testing and Verification

## Core Data Model

The completed implementation evidence contains these custom objects:

| Object | Business Purpose |
|---|---|
| HandsMen Customer | Customer information |
| HandsMen Product | Fashion product/catalogue information |
| HandsMen Order | Customer order information |
| Inventory | Stock and inventory information |
| Marketing Campaign | Marketing campaign information |

## Automation Architecture

```text
Customer / Order / Inventory Records
                |
                v
       Salesforce Automation
        /       |               /        |             Flow       Apex     Batch/Schedule
      |          |           |
      v          v           v
 Email Alerts  Business   Bulk Order
               Logic      Processing
      |                       |
      v                       v
Customer / Warehouse     Financial + Inventory
Communication               Updates
```

## Documentation Structure

The repository is divided into **three documents** so Skills Wallet modules can be verified separately.

### 01 – Project Overview, Data Model & Configuration
`01_Project_Overview_Data_Model_Configuration.docx`

Covers:
- Project Overview
- Business Problem
- User Story / Requirements
- Objectives
- Solution Architecture
- Salesforce Credentials Setup
- Data Management – Objects
- Data Management – Tabs
- Data Management – App Manager
- Data Management – Fields
- Data Configuration
- Data Quality / Validation Rules
- Foundation Testing

### 02 – Data Security & Customer Communication
`02_Data_Security_Communication.docx`

Covers:
- Security Model
- Data Security – Profiles
- Data Security – Roles
- Data Security – Users
- Data Security – Permission Set
- Email Templates
- Email Alerts
- Security and Communication Testing

### 03 – Automation, Apex & Asynchronous Processing
`03_Automation_Apex_Batch.docx`

Covers:
- Automation Strategy
- Record-Triggered Flows
- Order Confirmation Automation
- Loyalty Automation
- Stock Alert Automation
- Automation using Apex
- Apex Triggers
- Asynchronous Apex
- Batch Jobs
- Scheduled Processing
- Automation Testing
- Debugging and Monitoring
- Demo Video Evidence
- Deployment and Maintenance

## Evidence

The documentation uses screenshots from the completed Salesforce implementation. The evidence includes custom objects, tabs, App Manager, records, validation rules, profiles, roles, users, permission-set configuration, email templates, email alerts, Flow Builder, Apex/trigger code, batch/scheduled processing and Scheduled Jobs.

Each screenshot is placed beside the module it supports so the reviewer can connect the configuration to the corresponding Skills Wallet requirement.

## Testing

The documents include module-level test cases for:
- Data validation
- Object/UI configuration
- Security
- Email automation
- Record-Triggered Flows
- Apex
- Batch Jobs
- Scheduled Processing

Final test statuses should match the actual observed results in the completed Salesforce org.

## Demo Video

Recommended demonstration sequence:
1. Open the HandsMen Threads Lightning application.
2. Show the core objects and sample records.
3. Demonstrate data-quality/validation behavior.
4. Demonstrate order-confirmation automation.
5. Demonstrate loyalty automation.
6. Demonstrate the below-five stock alert.
7. Show Apex/trigger implementation.
8. Show batch/scheduled processing.
9. Summarize the major project outcomes.

**Demo Video:** _______________________________

## Skills Wallet Submission

**GitHub Repository:** _______________________________

**Skills Wallet Project:** _____________________________

**Demo Video:** _____________________________________

## Repository Structure

```text
HandsMen-Threads-Salesforce/
├── README.md
├── 01_Project_Overview_Data_Model_Configuration.docx
├── 02_Data_Security_Communication.docx
└── 03_Automation_Apex_Batch.docx
```

## Future Enhancements

- Personalized AI styling recommendations
- Customer self-service experience
- Advanced loyalty analytics
- Predictive inventory forecasting
- Automated personalized marketing journeys
- Lightning Web Components for a richer bespoke-tailoring interface
- Advanced sales, customer and inventory dashboards

## Conclusion

HandsMen Threads demonstrates how Salesforce can provide a centralized CRM for a premium fashion and bespoke tailoring business. The project combines data modelling, data quality, Lightning configuration, security, email communication, Flow automation, Apex and asynchronous processing. The three-document structure keeps the GitHub submission organized and makes individual Skills Wallet modules easier to verify.

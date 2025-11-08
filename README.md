Garage Management System (GMS) - Naan Mudhalvan Project
🌟 Project Overview
The Garage Management System (GMS) is a comprehensive, cloud-based application developed on the Salesforce Platform. Its primary goal is to optimize the end-to-end service lifecycle for automotive repair facilities, enhancing operational efficiency and improving customer relationship management.
The system manages key business processes, from initial customer and vehicle intake to service execution, final billing, and collecting customer feedback.
👥 Team
This project was developed by the following team under the Naan Mudhalvan Skilling Initiative:
Team Lead : Selvalakshmi.S
Team Member : Sarojini.M
Team Member : Ramadevi.G
Team Member : Monisha.M
🛠️ Key Technical Implementations
The GMS is built on a robust architecture utilizing both declarative and programmatic Salesforce capabilities:
Data Model & Integrity
Custom Objects: Customer Details, Appointment, Service records, and Billing details and feedback.
Auto-Numbering: Implemented unique, sequential identifiers (e.g., app-{000}, ser-{000}).
Validation Rules: Enforced data quality, including strict REGEX validation for the Vehicle number plate and numerical constraint checks for Service Ratings.
Lookup Filters: Applied a required filter on the Service records object for business logic enforcement.
Security and Access
Roles & Profiles: Defined a two-tiered hierarchy (Manager and Sales Person) with a custom Manager Profile.
Sharing Model: Used Private OWD for sensitive Service records and a specific Sharing Rule to grant managers Read/Write access over their sales team's records.
Automation
Record-Triggered Flows: Automated status updates (e.g., setting Service Status to 'Completed' upon quality check) and customer communication (sending a payment confirmation email).
Apex: Included placeholder logic for advanced cost distribution and calculation.
Analytics
Custom Report Type: Created a Service Information Report Type linking all four core objects.
Folder Sharing: Secured Reports and Dashboards by sharing folders exclusively with the Manager Role.
🚀 Getting Started
To replicate and explore the system, refer to the detailed Deployment Phase Document, which includes step-by-step setup instructions for recreating the custom objects, fields, and automation in a Salesforce Developer Org.# Garage-Management-System

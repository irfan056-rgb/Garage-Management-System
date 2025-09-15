# Garage-Management-System
🚗 Garage Management System for Salesforce

A Garage Management System built on Salesforce to streamline customer management, service bookings, vehicle tracking, and invoicing. This project helps garages and auto-service businesses improve efficiency by managing all operations within Salesforce.

📌 Features

🔑 Customer Management – Store and manage customer details.

🚙 Vehicle Records – Track vehicles linked to customers.

📅 Service Booking – Manage appointments and repair/service schedules.

🧾 Invoice & Billing – Auto-generate invoices and track payments.

🔔 Notifications & Reminders – Remind customers about upcoming services.

📊 Reports & Dashboards – Visualize garage performance and service history.

🛠️ Tech Stack

Platform: Salesforce (Lightning Experience)

Custom Objects: Customer, Vehicle, Service, Invoice

Automation: Flow, Validation Rules, Process Builder

UI Components: Lightning Web Components (LWC)

Reports: Salesforce Dashboards & Reports

📂 Project Structure
garage-management-salesforce/
│── force-app/
│   ├── main/
│   │   └── default/
│   │       ├── objects/       # Custom objects like Vehicle, Service, Invoice
│   │       ├── lwc/           # Lightning Web Components (UI)
│   │       ├── classes/       # Apex Classes
│   │       └── triggers/      # Triggers for automation
│── README.md                  # Project Documentation
│── sfdx-project.json          # Salesforce DX Project Config

🚀 Installation & Setup

Clone Repository

git clone https://github.com/your-username/garage-management-salesforce.git
cd garage-management-salesforce


Authorize Salesforce Org

sfdx force:auth:web:login -a GarageOrg


Push Source to Org

sfdx force:source:push -u GarageOrg


Assign Permission Set

sfdx force:user:permset:assign -n GarageManagementPermissions


Open Org

sfdx force:org:open -u GarageOrg

📖 Usage

Navigate to App Launcher → Garage Management.

Add Customer records and link their Vehicles.

Create a Service Booking and assign a technician.

Generate Invoices and track payments.

Use Dashboards to view reports like revenue, service count, and pending tasks.

🧪 Testing

Run Apex tests to ensure functionalities are working correctly:

sfdx force:apex:test:run -u GarageOrg --resultformat human --codecoverage

🤝 Contributing

Contributions are welcome! Please fork the repository and create a pull request.

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.

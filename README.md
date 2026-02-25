# 🧘 Zen-Flow Studio Manager

**Transforming administrative burdens into seamless, high-vibe business experiences.**

The **Zen-Flow Studio Manager** is a complete "Business Operating System" designed for boutique studios and service-based businesses. Originally inspired by enterprise-level ISP billing logic, this engine has been repurposed to respect the student-teacher relationship while ensuring the business remains financially healthy.

By replacing "cold" financial interactions with warm, community-focused touchpoints, this system allows owners and operators to focus on their craft rather than spreadsheets.

---

## 📋 Project Overview
* **Status**: V1.0 Build Complete
* **Last Updated**: February 25, 2026
* **Category**: Operations / Automation

---

## 🚀 The Four Pillars of the Engine
This repository contains the logic for four integrated workflows that manage the entire customer lifecycle:

1.  **Proactive Billing Scheduler**: Automatically scans the database and sends branded PayPal invoices 3 days before renewal.
2.  **Payment Reconciliation Receiver**: A real-time listener that updates membership status the second a payment is confirmed.
3.  **Frictionless Attendance Tracker**: A QR-code-based check-in system that automatically manages class/credit balances.
4.  **Executive Growth Reporter**: Monthly automated delivery of revenue vs. goal summaries to the business owner.

---

## 📁 Repository Structure
This project includes a complete suite of professional documentation to support the automation:

* **`/workflows`**: n8n JSON files for all core automation pillars.
* **`Pitch Deck.md`**: Strategy for selling the Zen-Flow system to new clients.
* **`Service Agreement & SOW.md`**: Formal contract and Scope of Work templates.
* **`Project Kickoff.md`**: Client onboarding protocols and data requirements.
* **`Final Handover Document.md`**: Comprehensive maintenance and support guides.

---

## 🛠️ Tech Stack
* **Core Logic**: n8n (Workflow Automation)
* **Database**: Google Sheets (The "Control Center")
* **Payment Gateway**: PayPal REST API
* **User Interface**: Google Forms & Dynamic QR Codes

---

## ⚙️ Installation & Setup
1.  **Database**: Create a Google Sheet using the headers defined in the `Master_Database_Template.csv`.
2.  **n8n Import**: Import the `.json` files from the `/workflows` folder into your n8n instance.
3.  **API Handshake**: Connect your Google Workspace and PayPal Developer credentials (Client ID and Secret).
4.  **Branding**: Update the HTML email templates in the n8n nodes with your specific studio logo and colors.

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---


## 📬 Contact
👩‍💻 Created by: **Charlote Araneta**

🔗 LinkedIn: https://www.linkedin.com/in/charlotearaneta

🌐 Portfolio: https://charlotearaneta.github.io

---
## ✍️ About the Consultant
This system was designed to minimize "Administrative Drag" and maximize community growth. For custom implementations or technical support, please reach out via the contact information in the **Final Handover Document**.

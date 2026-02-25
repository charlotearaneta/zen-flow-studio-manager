# 🧘 Zen-Flow Studio Manager

**Transforming administrative burdens into seamless, high-vibe business experiences.**

The **Zen-Flow Studio Manager** is a complete "Business Operating System" designed for boutique studios and service-based businesses. This engine transforms manual administrative burdens into a seamless, high-vibe experience by automating the entire customer lifecycle. 

---

## 📋 Overview
Managing a membership-based business often leads to "Admin Drag" from hours lost to manual billing, payment reconciliation, and attendance tracking. This project replaces those "cold" financial interactions with warm, community-focused touchpoints. 

It ensures a business remains financially healthy by repurposing logic derived from enterprise-level billing systems to fit a local, service-based context.

---

## 🚀 Workflow Architecture
The system is built on four integrated automation pillars that communicate in real-time:

1.  **The Scheduler**: A proactive engine that scans the database daily and triggers branded PayPal invoices 3 days before renewal.
2.  **The Receiver**: A webhook listener that reconcile payments instantly and updates membership status without human intervention.
3.  **The Attendance Tracker**: A QR-code-based check-in system that automatically manages class/credit balances in real-time.
4.  **The Reporter:**: Monthly automated delivery of revenue vs. goal summaries to the business owner.

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


## 📬 Contact
👩‍💻 Created by: **Charlote Araneta**

🔗 LinkedIn: https://www.linkedin.com/in/charlotearaneta

🌐 Portfolio: https://charlotearaneta.github.io

---

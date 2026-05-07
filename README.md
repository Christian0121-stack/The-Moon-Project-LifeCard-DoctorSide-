🩺 LifeCard: Doctor’s Interface
The LifeCard Doctor Side is a high-performance interface built for emergency response and clinical efficiency. It allows healthcare providers to access life-saving medical data in seconds through physical and digital triggers.

⚡ Core Features
1. Dual-Mode Emergency Scanning
QR Code Scanning: Instantly read medical data from physical LifeCard IDs.

NFC/RFID Tap: One-tap access via LifeCard+ wearables (bracelets/tags) for unconscious patients or rapid ER intake.

2. Offline-First Architecture (Critical Care)
Local Database Sync: Doctors can click "Sync Database Now" to store an encrypted local copy of patient records.

Zero-Signal Access: Ensures that in remote areas or "Golden Hour" emergencies where internet fails, patient data remains accessible.

🔐 Access & Security Protocols
Account Provisioning
To maintain medical integrity, doctors cannot self-register.

Registration: Accounts must be pre-authorized and created via the Admin Central Command.

Default Test Credentials:

christian0121 / christian0121

marielle0121 / marielle0121

cath123 / cath123

Device Integrity (Single Session Policy)
Single Sign-In: To prevent unauthorized remote access and credential sharing, only one active session is allowed per account.

Mandatory Logout: Users must sign out to release the session for another device.

Admin Reset: If a session is left active on a lost or inaccessible device, a system administrator must manually reset the session from the Central Command.

🏗 Setup Instructions
Clone the repository.

Run npm install and npm start.

Log in using the authorized credentials provided by the Admin.
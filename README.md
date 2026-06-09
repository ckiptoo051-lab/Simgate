SimGate Gateway

Android SMS Gateway for OTP Delivery, Verification Codes, Notifications, and Transactional SMS using your own carrier SIM card.

SimGate Gateway transforms any Android phone into a programmable SMS gateway. Developers can connect their Android device to the SimBridge platform and send SMS messages through a simple API using their own SIM card.

Perfect for:

- OTP SMS Verification
- Two-Factor Authentication (2FA)
- Login Verification Codes
- Password Reset Codes
- User Registration Verification
- Banking Alerts
- Transaction Notifications
- E-commerce Notifications
- Appointment Reminders
- SMS Automation
- Bulk Messaging
- SMS Bots
- Developer APIs

---

SimBridge Dashboard

Manage your devices and generate API credentials from:

https://simbridgesend.web.app

The dashboard allows you to:

- Create SMS Gateway Devices
- Generate Device IDs
- Generate Device Tokens
- Generate API Keys
- Monitor Device Status
- View SMS Logs
- Configure Webhooks
- Create Auto Reply Rules
- Manage Message Templates
- Monitor Device Health
- View Analytics

---

How It Works

Your Website/App
        │
        ▼
 SimBridge API
        │
        ▼
 Android Phone
        │
        ▼
 Your Carrier SIM Card
        │
        ▼
 Recipient Receives SMS

Instead of paying expensive SMS providers, SimGate Gateway allows you to use your own Android phone and carrier SIM card to deliver messages.

---

Features

SMS Gateway

- Send SMS through Android
- Receive Incoming SMS
- Delivery Reports
- Failed Message Reports
- SMS Queue Processing
- Multipart SMS Support
- Long SMS Support
- Background Operation

OTP & Authentication

- OTP Delivery
- Verification Codes
- Password Reset Codes
- Registration Verification
- Login Authentication
- Two-Factor Authentication (2FA)

Developer API

- REST API
- API Key Authentication
- Device-Based Routing
- JSON Responses
- Webhook Support
- Easy Integration

Compatible with:

- Laravel
- PHP
- Node.js
- React
- Next.js
- Flutter
- Android
- Python
- Java
- .NET

Android Features

- QR Code Pairing
- Device Token Authentication
- Device ID Authentication
- Auto Reconnect
- Auto Start on Boot
- Foreground Service
- Connection Monitoring
- Local SMS History
- Notification Controls
- SIM Management
- Dual SIM Support
- Multi SIM Support

Advanced Messaging

- Scheduled SMS
- SMS Drafts
- Message Templates
- Bulk SMS
- Resend Failed SMS
- SMS Queue Viewer

Auto Reply System

- Keyword Auto Reply
- Custom Rules
- Business Hours Reply
- Smart Responses
- Webhook-Based Automation

Examples:

HELP
→ How can we assist you?

PRICE
→ Visit our website for pricing information.

JOIN
→ Welcome to our service.

Device Monitoring

- Online Status
- Offline Detection
- Battery Monitoring
- Signal Monitoring
- Network Monitoring
- Device Health Tracking

---

Installation

1. Download APK

Download the latest APK from GitHub Releases.

2. Install

Install the APK on an Android device running Android 7.0 or newer.

3. Open SimGate Gateway

Launch the application.

4. Pair Device

Visit:

https://simbridgesend.web.app

Create a device and obtain:

- Device ID
- Device Token

Or scan the generated QR code.

5. Grant Permissions

Required:

- SEND_SMS
- RECEIVE_SMS
- READ_SMS
- READ_PHONE_STATE
- POST_NOTIFICATIONS

Recommended:

- Disable Battery Optimization
- Enable Auto Start

6. Start Gateway

Tap:

Start Gateway

The Android device will connect to the backend and begin processing SMS jobs.

---

API Example

Send SMS

POST /send-sms

Headers:

Authorization: Bearer YOUR_API_KEY

Request:

{
  "device_id":"dev_xxxxx",
  "recipient":"+254700000000",
  "message":"Your OTP is 123456"
}

Response:

{
  "success":true,
  "message_id":"msg_xxxxx",
  "status":"queued"
}

---

Android Dashboard

The Android application provides:

Home

- Gateway Status
- Battery Level
- Signal Strength
- SMS Statistics
- Device Health

History

- Sent Messages
- Failed Messages
- Incoming Messages

SIM Manager

- View Installed SIM Cards
- Select Default SIM
- Switch SIM for Sending

Auto Reply

- Create Auto Reply Rules
- Enable/Disable Automation
- Manage Templates

Settings

- Device Information
- API Configuration
- Restart Gateway
- Unpair Device
- Send Test SMS
- Notification Settings

---

Why SimGate Gateway?

- Use your own SIM card
- Reduce SMS costs
- Send OTPs from Android
- Full control of SMS infrastructure
- No expensive SMS provider required
- Easy API integration
- Reliable background operation
- Designed for developers

---

Requirements

- Android 7.0+
- Active SIM Card
- SMS Permissions
- Internet Connection

---

Keywords

Android SMS Gateway, SMS Gateway API, OTP SMS Gateway, SMS Verification, Verification Code SMS, Two-Factor Authentication, 2FA SMS, Transactional SMS, Bulk SMS, SMS Automation, Android SMS API, Programmable SMS, SMS Notifications, SIM Card SMS Gateway, Carrier SMS Gateway, Self Hosted SMS Gateway, SMS Infrastructure, OTP Delivery Platform, Android OTP Gateway.

---

License

MIT License

---

Built for developers who need affordable, programmable SMS infrastructure powered by their own Android devices and carrier SIM cards.

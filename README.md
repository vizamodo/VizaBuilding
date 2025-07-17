# Viza Application Project Proposal

## 1. Overview

**Viza** is an advanced mobile application designed to enhance resident experiences in modern apartment complexes. It improves convenience, security, and management efficiency through technologies like NFC, QR code, Bluetooth, and smart hardware (Viza Intercom & Viza Parking).

---

## 2. Key Features

### 2.1. Intercom Feature

- Android touchscreen devices at building entrances run Viza Intercom.
- Guests input apartment number to call residents directly via the app.
- Residents can:
  - Go down to welcome guests
  - Press “Open Door” remotely via the app

### 2.2. Door Opening Options

- **NFC Scan**: Tap phone to open door
- **QR Code**: Scan code or show dynamic QR from app
- **Touchless Bluetooth**: Rotate phone 90° near entrance to unlock

### 2.3. Billing & Notifications

- Receive monthly bills and debt reminders via push notification
- Pay bills through integrated gateways
- Get timely building announcements (e.g. meetings, maintenance, emergencies)

### 2.4. Monthly Parking Management

- Parking entry via:
  - **NFC Scan**
  - **QR Code Scan**
  - **Touchless Bluetooth** (for car users)
- Fee reminders and payments via app

### 2.5. Verified Visitor Parking (External Lots)

- Enter parking lots without paper tickets
- Receive e-ticket via app
- Exit with automatic fee deduction
- Search for all "Viza Verified" lots across the city

---

## 3. Benefits

### For Residents

- One app for guest entry, parking, bill management
- Transparent communication and payments
- Smart living with modern access control

### For Building Management

- Automate guest and vehicle access
- Real-time bill and fee collection
- Easier, faster notifications
- Optimize revenue

---

## 4. Proposed Technologies

- **Mobile App**: React Native  
- **Backend**: Node.js, GoLang, Express.js  
- **Database**: AWS DynamoDB  
- **GraphQL API**: Amplify AppSync  
- **Auth**: AWS Cognito  
- **Serverless**: AWS Lambda  
- **Hardware**: Android-based Viza Intercom & Viza Parking  
- **Payment Gateways**: VNPay, Momo, ZaloPay, bank integrations  
- **Communication Tech**: NFC, BLE (Bluetooth Low Energy), QR Code

---

## 5. Development Roadmap

### Phase 1: MVP

- Intercom feature
- NFC + QR door access
- Bill notifications
- Basic payment gateway

### Phase 2: Expansion

- Bluetooth touchless door access
- Monthly parking features
- Visitor parking module
- UI/UX improvements

### Phase 3: Optimization

- System performance, security
- Building management integration
- New value features (e.g. amenity booking, resident forum)
- City-wide expansion

---

## 6. Conclusion

**Viza** is a revolutionary solution for smart apartment living. It elevates resident convenience, empowers building managers, and transforms modern residential infrastructure through secure, digital interaction.

# HLF CampusCoin – Official Android APK Distribution

HLF CampusCoin is a blockchain-based campus digital currency system built on Hyperledger Fabric using ERC-20 chaincode.

This repository is used strictly for distributing official Android APK builds of the application.

No source code (Android, backend, or chaincode) is included in this repository.

---

## Purpose of This Repository

This repository exists only to:

- Publish official APK release files
- Provide installation instructions
- Share version information
- Allow users to download verified builds

If you are looking for source code, it is private and not available in this repository.

---

## How to Download the APK

Please follow these steps carefully:

1. Open this repository in your browser.
2. At the top of the repository page, click on the **"Releases"** section.
   - On GitHub, this is typically located on the right side panel or near the top navigation.
3. Click on the latest release version.
4. Under the **Assets** section of that release, you will see the APK file:
   
   Example:
   ```
   HLF-CampusCoin-v1.0.0.apk
   ```

5. Click on the APK file name to download it.
6. Wait for the download to complete.

Only download APK files from the official Releases section of this repository.

---

## How to Install the APK on Android

After downloading the APK file:

### Step 1: Locate the File
- Open your device's **File Manager**
- Go to the **Downloads** folder
- Tap on the downloaded APK file

### Step 2: Allow Installation (If Prompted)
If this is your first time installing an APK manually, Android may block the installation.

You will see a message such as:
"Installation blocked" or "Install unknown apps not allowed"

To fix this:

1. Tap **Settings** in the popup
2. Enable **Allow from this source**
3. Return to the APK file
4. Tap Install again

### Step 3: Install
- Tap **Install**
- Wait for the installation to complete
- Tap **Open** to launch the app

---

## Minimum Requirements

- Android 8.0 (Oreo) or higher recommended
- Internet connectivity
- Access to the configured backend server

---

## Important Note About Backend and Blockchain

This mobile application requires:

- A running Hyperledger Fabric network
- Backend API server connected to the Fabric network
- Proper user credentials

If the backend or blockchain network is not running, the application will not function.

---

## Application Roles

### Admin
- Mint tokens
- Burn tokens
- View transactions
- Manage users

### Student
- View token balance
- Transfer tokens
- View transaction history

All transactions are recorded on the Hyperledger Fabric ledger.

---

## Versioning

Each release follows this format:

```
HLF-CampusCoin-vX.X.X.apk
```

Always install the latest stable version unless instructed otherwise.

---

## Security and Authenticity

- Only download APK files from the official Releases section.
- Do not install files shared through unofficial channels.
- Verify release version before installation.

---

## What This Repository Does Not Contain

- Android source code
- Backend source code
- Chaincode source code
- Deployment scripts

This repository distributes compiled APK builds only.

---

## Reporting Issues

If you encounter problems, please open an issue and include:

- Device model
- Android version
- App version (from installed app)
- Steps to reproduce the issue
- Screenshots (if possible)

---

---

# Application Usage Guide

This section provides complete instructions for registering, securing, and using the CampusCoin mobile application after installation.

---

## 1. Account Registration

When opening the application for the first time, you must create a new account.

### Steps to Register

1. Select **Create Account**.
2. Enter your institutional email address.

   Examples:
   - B23CN082@kitsw.ac.in  
   - b23cn082@kitsw.ac.in  

3. Enter your **Student ID**.

   Example:
   - B23CN081  

4. Create a password that satisfies the following requirements:

   - Minimum 8 characters
   - At least one uppercase letter
   - At least one lowercase letter
   - At least one numeric digit
   - At least one special character

5. Select **Create Account** to complete registration.

If all information is valid and the backend system is accessible, your account will be created successfully.

---

## 2. Setting Up Your 6-Digit Security PIN

After successful registration, you are required to configure a 6-digit numeric PIN.

This PIN serves as an additional security layer for accessing your wallet.

### Important

- The PIN must contain exactly 6 digits.
- The PIN is required every time the application is closed and reopened.
- Without entering the correct PIN, access to the wallet will not be granted.

---

## 3. Home Dashboard Overview

After authentication via PIN, the dashboard displays:

- Your current CampusCoin balance
- Quick access options:
  - Send
  - My QR
  - History
- Recent transaction summary (if available)

This dashboard provides access to all primary wallet functions.

---

## 4. Sending CampusCoin Tokens

To transfer tokens to another registered user:

1. Select **Send** from the dashboard.
2. Enter the recipient’s Student ID  
   (The Student ID used during their account registration)

   OR

   Use the QR scan feature to scan the recipient’s QR code.

3. Enter the number of CampusCoin (CC) tokens to transfer.
4. Confirm the transaction.

### Transaction Conditions

The transaction will be successful if:

- The recipient account exists in the system.
- You have sufficient token balance.
- Backend and blockchain services are available.

The system will display an error if:

- The recipient does not exist.
- The token balance is insufficient.
- The backend or network is unavailable.

All successful transactions are recorded on the Hyperledger Fabric ledger.

---

## 5. My QR Code

The **My QR** section displays your unique QR code.

Other users can scan this QR code to automatically populate your Student ID when sending tokens.

This feature reduces manual entry errors during transfers.

---

## 6. Transaction History

The **History** section provides a complete record of your transactions, including:

- Sent transactions
- Received transactions
- Minted tokens (if applicable)
- Transaction status (Success or Failed)
- Date and time of each transaction

All records are retrieved from the blockchain ledger.

---

## 7. Profile Information

The Profile section allows you to view:

- Registered Student ID
- Email address
- Assigned role (Admin or Student)
- Account status

You may also log out from this section.

---

## 8. Security and Access Behavior

- A 6-digit PIN is required each time the application is reopened.
- Credentials and PIN must not be shared.
- Transactions require active backend and blockchain connectivity.
- If network services are unavailable, transactions cannot be processed.

---

This completes the operational guide for the CampusCoin mobile application.

## License and Usage

This application is distributed for educational and institutional use.

Unauthorized redistribution, reverse engineering, or modification is not permitted.
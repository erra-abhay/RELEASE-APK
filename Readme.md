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

## License and Usage

This application is distributed for educational and institutional use.

Unauthorized redistribution, reverse engineering, or modification is not permitted.
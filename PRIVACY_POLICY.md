# Privacy Policy for Focustown

**Last Updated: May 24, 2026**

Your privacy is of the absolute utmost importance to us. Focustown (referred to as "the App", "we", "us", or "our") was built from the ground up with a core philosophy: **your data belongs to you**. 

This Privacy Policy explains how we collect, store, and handle information when you use Focustown.

---

## 1. 🛡️ Summary: The Zero Data Policy
We do not run servers, we do not require accounts, and we do not track you.
* **No Accounts**: You do not need to sign up or sign in to use Focustown.
* **No Data Collection**: We do not collect, monitor, upload, or transmit any personal data, focus logs, session history, or configuration files.
* **No Trackers**: We do not use third-party analytics SDKs, advertising networks, or telemetry trackers.
* **100% Local**: All your data (including focus sessions, coins earned, town grids, and audio settings) is stored exclusively on your own device.

---

## 2. 💾 Where is Your Data Stored?
All configuration settings and logs are saved locally on your device in the App's secure private sandbox:
* **Storage Type**: We use standard platform local storage (`SharedPreferences` on Android, `NSUserDefaults` on iOS/macOS).
* **Saved Data Includes**:
  * Focus session history (timestamps, focus duration, state)
  * Town grid building placements and IDs
  * Your virtual currency balance (FT Coins)
  * User preferences (work/break durations, selected soundscapes, mute state, Zen mode status)
  * Local file paths for custom-imported sound tracks
* **Wiping Data**: If you wish to delete all your data, you can do so at any time by:
  1. Clearing the App's data/cache in your device's System Settings, or
  2. Uninstalling the App from your device.

---

## 3. 🔑 Device Permissions & Why They Are Needed
Focustown requests minimal local permissions to provide a seamless productivity experience. We never use these permissions to access your personal data for other purposes.

* **🔔 Local Notifications**:
  * *Purpose*: Used to alert you when your work session ends or your break is completed.
  * *Transmission*: Entirely local. We do not use push notification servers or cloud triggers.
* **📂 Storage / File Picker Access**:
  * *Purpose*: Used ONLY when you choose to use the "Import Music from Device" feature (Premium). This allows you to pick custom audio files (MP3, WAV, AAC) to use as ambient focus sounds.
  * *Transmission*: We only store the local file path on your device so the audio player can locate it. We never read, inspect, copy, or upload any other files on your storage.
* **📱 Keep Screen On (Wakelock)**:
  * *Purpose*: Prevents your phone screen from dimming or turning off during an active focus timer, allowing you to easily keep track of your progress.

---

## 4. 💳 In-App Purchases & Billing
Focustown offers a one-time "Premium Unlock" purchase.
* **Billing Handler**: All transactions are securely processed directly by the platform marketplaces (Apple App Store or Google Play Store) using their native in-app billing systems.
* **Developer Access**: We never see, collect, or store your payment details, billing address, or credit card information. The platform only returns a secure, encrypted token verifying that your account successfully purchased the unlock.

---

## 5. 🌐 Third-Party Services
* **Google Fonts**: The App uses the `google_fonts` package to deliver beautiful typography. Under standard usage in Flutter, font assets are bundled locally or fetched via standard Google API requests. Google does not collect any user tracking data through these font requests.

---

## 6. 👶 Children's Privacy (COPPA & GDPR-K Compliance)
Because Focustown does not collect, store, or share any personal information of any kind, it is fully compliant with the Children’s Online Privacy Protection Act (COPPA) and the General Data Protection Regulation (GDPR). The App is completely safe for use by individuals of all ages.

---

## 7. ⚖️ Compliance with Global Privacy Laws (GDPR & CCPA)
Although Focustown does not process personal data on external servers, we fully support your privacy rights under the European Union’s General Data Protection Regulation (GDPR) and the California Consumer Privacy Act (CCPA):
* **Right to Access & Portability**: You have full access to your data at all times. It is displayed directly inside your **Stats View** and **Town View**.
* **Right to Deletion**: You hold total control. Simply delete the App or clear your device storage to permanently destroy all records instantly.

---

## 8. 📧 Contact Information
If you have any questions or feedback regarding this Privacy Policy or Focustown's local data storage, please feel free to reach out:

* **GitHub Repository**: [https://github.com/your-username/focus_town](https://github.com/your-username/focus_town) 

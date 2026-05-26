# Privacy Policy — BGM Extractor

**Effective Date:** May 11, 2026

This Privacy Policy applies to **BGM Extractor** (the "App"), an iOS application developed by **Bie Qiutian (别秋田)**.

---

## 1. Summary

BGM Extractor is an iOS app that extracts background music and audio tracks from videos you select. The App is designed to process your files locally on your device.

- We do **not** collect, upload, or transmit your video or audio files.
- We do **not** use third-party analytics or advertising SDKs.
- We do **not** sell your personal information.
- All media processing happens on your device.

---

## 2. Information We Access

To provide its core functionality, the App may access the following on your device:

| Data | Purpose | Required? |
|------|---------|-----------|
| **Photo Library** | To let you select videos for audio extraction | Yes (core feature) |
| **Microphone** | To access audio tracks from video files for processing | Yes (core feature) |
| **Files (via UIDocumentPicker)** | To export audio files to your device when you choose | Optional (user-initiated) |

The App accesses these resources **only when you explicitly initiate an action** — selecting a video, exporting a file, or playing audio within the App.

---

## 3. How Your Data Is Used

The App uses data only to deliver its features:

- **Video files you select** are used solely to extract the audio track. No video data is uploaded or transmitted.
- **Extracted audio** is saved to the App's on-device library. You can play, trim, mix, or delete it at any time.
- **Export** — when you choose to export audio to the Files app, the file is copied to your chosen destination. The export is initiated by you and handled by iOS's system document picker.
- **In-app purchases** — Apple's StoreKit provides the App with transaction and entitlement information (e.g., whether you have an active subscription). The App stores this status locally to control premium feature access.

---

## 4. Local Processing

All audio extraction, trimming, mixing, and format conversion happens **entirely on your device**. 

- Video files are read locally to extract audio tracks.
- Temporary files may be created during processing and are deleted after the operation completes or when the system cleans temp files.
- The App's built-in audio library resides in the app's sandboxed document directory, which is not accessible to other apps.

No audio or video data is ever sent to our servers or any third party.

---

## 5. In-App Purchases and Subscriptions

The App offers optional premium features through Apple's in-app purchase system:

- A monthly auto-renewable subscription
- A one-time lifetime purchase

When you make a purchase, Apple (not the App) handles all payment processing. The App receives only the purchase confirmation and entitlement status from StoreKit.

The App may store limited local state on your device to remember your premium access status, including:

- A cache of your active entitlements
- A local flag indicating whether export features are unlocked

This data is stored locally and not transmitted.

---

## 6. Data Sharing

We do **not** share, sell, or transfer your personal information or your media files to any third party.

The only external communication the App makes is with Apple's services for:

- In-app purchase validation
- Subscription status checks
- Purchase restoration

These interactions are governed by Apple's own privacy practices and terms.

---

## 7. Tracking

The App does **not** track you. According to the App's privacy manifest:

- `NSPrivacyTracking` is `false`
- No tracking domains are declared
- No third-party analytics or advertising SDKs are used

---

## 8. Data Retention

Your media files remain under your control on your device for as long as you choose to keep them in the App's library. You can delete any audio file at any time from within the App.

Local app state (premium access cache, preferences) is retained until:

- you delete and reinstall the App, or
- the system removes the app's data.

---

## 9. Security

The App relies on Apple's platform security:

- App sandboxing isolates the App's data from other applications
- The iOS file system protects the App's on-device library
- StoreKit provides secure in-app purchase processing
- The App does not connect to any external servers or APIs beyond Apple's required services

---

## 10. Children's Privacy

The App is not directed to children under the age of 13. We do not knowingly collect any personal information from children.

---

## 11. International Users

The App is available globally through the App Store. When you use Apple services such as StoreKit, Apple may process data in accordance with its own privacy policy and infrastructure. The App itself does not transmit your data across borders.

---

## 12. Changes to This Policy

We may update this Privacy Policy from time to time. When updated, the revised version will be posted at this URL and the effective date will be updated. Continued use of the App after changes constitutes acceptance of the updated policy.

---

## 13. Contact

For questions or concerns about this Privacy Policy or the App's data practices, please contact:

**Bie Qiutian (别秋田)**  
长春市南关区君盈身份广场5栋518, Changchun, Jilin, China  
Email: bieqiutianios@163.com

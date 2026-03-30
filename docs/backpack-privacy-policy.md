# Privacy Policy

**Backpack — Document Vault**
Last updated: 30 March 2026

## The short version

Backpack is a privacy-first document vault. Your documents are stored on your device and never uploaded to any server. There is no account. There is no cloud storage. We never see your documents.

When you choose to connect your email, Backpack accesses your inbox with read-only permission to find documents. Attachments you select are downloaded directly to your device. Your email credentials are never seen or stored by Backpack — authentication is handled entirely by Google or Microsoft.

## What data Backpack processes

Backpack processes the following data entirely on your device:

**Documents you add** — photos, PDFs, and files you import via the camera, photo library, file picker, or share sheet. These are stored in your device's local storage and never leave your phone.

**Email inbox (optional)** — if you choose to connect your Gmail or Outlook account during onboarding or later in Settings, Backpack requests read-only access to your inbox via OAuth authentication provided by Google or Microsoft. Backpack uses this access to scan your emails for document attachments such as boarding passes, insurance policies, receipts, and similar files. Only attachments you explicitly select are downloaded and stored locally on your device. Backpack does not read, store, or process the body of your emails. Your email credentials (username and password) are never seen by Backpack — authentication is handled entirely by Google or Microsoft through their secure OAuth flows. The OAuth access token is stored securely on your device and is never transmitted to any server. You can disconnect your email account at any time in Settings, which revokes Backpack's access and deletes the stored token.

**Document text** — Backpack uses Apple's on-device OCR (Vision framework) and Apple's on-device AI (Foundation Models) to read, classify, and extract information from your documents. All text recognition and AI processing happens on your iPhone using Apple's built-in frameworks. No document content is ever sent to any server, cloud service, or third party.

**Location** — if you grant permission, Backpack checks your approximate location when you open the app to surface relevant documents (for example, showing your passport when you're near an airport). Your location is processed once, in memory, and immediately discarded. It is never stored, logged, or transmitted.

**Calendar events** — if you grant permission, Backpack reads your upcoming calendar events to surface relevant documents (for example, showing your boarding pass before a flight). Calendar data is read on-device and never stored or transmitted.

**Search queries and questions** — anything you type into Search or Ask Backpack is processed entirely on your device using local database queries and Apple's on-device AI. Your questions are never sent anywhere.

## What data Backpack does NOT collect

Backpack does not collect:

- Personal information (name, email address, phone number)
- Email content or message bodies
- Usage analytics or telemetry
- Crash reports
- Advertising identifiers
- Location history
- Document contents or metadata
- Search history
- Any data whatsoever

There are no tracking pixels and no third-party data collection of any kind.

## Data storage

All data is stored locally on your device in an encrypted application container protected by iOS. When you enable biometric lock (Face ID or Touch ID), the app requires authentication before displaying any content.

Your documents are included in your iCloud device backup if you have iCloud Backup enabled in iOS Settings. This is handled by Apple's backup system, not by Backpack. Backpack does not use iCloud Drive, CloudKit, or any cloud storage service.

## Third-party services

**Google and Microsoft (email access)** — if you connect your Gmail or Outlook account, authentication is handled by Google or Microsoft through their OAuth services. Backpack requests read-only access to your inbox. Your credentials are handled entirely by Google or Microsoft and are never seen by Backpack. You can revoke access at any time through Backpack's Settings or through your Google/Microsoft account security settings.

**Apple App Store and StoreKit** — if you purchase Backpack Pro, the transaction is processed by Apple through the App Store. Apple handles all payment information. Backpack never sees your payment details, Apple ID, or purchase receipt contents.

**RevenueCat** — Backpack uses RevenueCat to manage in-app purchase entitlements. RevenueCat receives anonymised transaction data from Apple (not from Backpack) to verify your purchase status. RevenueCat may collect anonymous, non-personal diagnostic data such as device type and OS version to ensure purchase functionality works correctly. RevenueCat does not receive any of your document data, email content, location, calendar events, or personal information. You can review RevenueCat's privacy policy at https://www.revenuecat.com/privacy.

No other third-party services, SDKs, or APIs are used.

## Notifications

Backpack schedules local notifications on your device for document expiry reminders and proactive insights. These notifications are created and triggered entirely by iOS on your device. They do not use push notification servers — there is no server to push from.

## Children's privacy

Backpack does not knowingly collect any data from anyone, including children under the age of 13. Since the app collects no data, no special provisions are necessary.

## Data deletion

Since all data is stored locally on your device, you have complete control:

- Delete individual documents within the app
- Delete all data by using the "Delete all documents" option in Settings
- Disconnect your email account in Settings to revoke access and delete the stored OAuth token
- Delete all data by uninstalling the app

There is no account to delete and no server-side data to request removal of.

## Changes to this policy

If this privacy policy changes, the updated version will be posted here with a new "Last updated" date.

## Contact

If you have questions about this privacy policy, contact:

**Email:** [your email address]
**Developer:** Usman Khan
